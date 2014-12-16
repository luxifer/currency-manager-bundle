# Luxifer/CurrencyManagerBundle

Symfony bundle to bridge `luxifer/currency-manager`

## Install

```
composer require luxifer/currency-manager-bundle
```

Add `LuxiferCurrencyManagerBundle` to `app/AppKernel.php`:

```php
<?php

use Symfony\Component\HttpKernel\Kernel;
use Symfony\Component\Config\Loader\LoaderInterface;

class AppKernel extends Kernel
{
    public function registerBundles()
    {
        $bundles = array(
            new Luxifer\CurrencyManagerBundle\LuxiferCurrencyManagerBundle(),
        );
    }
}
```

## Usage

```php
<?php

$currencyManager = $this->get('currency_manager');
```

## Doc

See https://github.com/luxifer/currency-manager
