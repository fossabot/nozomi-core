# nozomi-core
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fafroraydude%2Fnozomi-core.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fafroraydude%2Fnozomi-core?ref=badge_shield)



## What is `nozomi-core`?
`nozomi-core` is the core libraries for Nozomi. It was made for ease and organizational purposes related to the Nozomi project.
It is built on top the original Slim Framework.

## Installation

### Via Composer
Include `nozomi-core` repository into Composer:

```json
    "repositories": [{
        "type": "vcs",
        "url": "https://github.com/afroraydude/nozomi-core"
    }],
    "require": {
        "afroraydude/nozomi-core": "dev-master",
        ...
    }
```

Then run: 
```
composer update
```

### Via `nozomi`

Clone the `nozomi` repository:
```
git clone https://github.com/afroraydude/nozomi.git
```

Enter the directory and install requirements:
```
cd nozomi

composer install
```

## Usage
Adding Nozomi to your Slim application is very simple. In your public `index.php` file after you define your app, dependencies, and settings:
```php
$nozomi = new \Nozomi\Core\Nozomi($app);
```


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fafroraydude%2Fnozomi-core.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fafroraydude%2Fnozomi-core?ref=badge_large)