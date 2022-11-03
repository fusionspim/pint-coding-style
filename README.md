# Pint Coding Style

This repository provides configuration for [Laravel Pint](https://laravel.com/docs/9.x/pint), which we use to verify and enforce a single coding standard for PHP code within Fusions PIM.

## Installation

1. Run `composer require --dev laravel/pint fusionspim/pint-coding-style`

2. Add script to `composer.json`:

```
{
    ...
    "scripts": {
        ...
        "fix": "pint --config vendor/fusionspim/pint-coding-style/pint.json",
        ...
    }
    ...
}

```

3. Add to .gitignore:

```
.pint.cache
```

4. Add to continuous integration workflow:

`composer fix -- --test`

## Usage

Run `composer fix`
