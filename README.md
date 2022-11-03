# Pint Coding Style

This repository provides configuration for [Laravel Pint](https://laravel.com/docs/9.x/pint), which we use to verify and enforce a single coding standard for PHP code within Fusions PIM.

## Installation

1. Run `composer require --dev fusionspim/pint-coding-style`

2. Add script to the projects `composer.json`:

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

3. Add to projects .gitignore:

* .pint.cache

## Usage

Run `composer fix`
