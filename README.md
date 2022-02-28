# eos-client
EOS Client for PHP
## Install

composer.json

```json
{
    "require": {
        "masscult/eos-client": "dev-master"
    }
}
```

## Initialization

```php
use xtype\Eos\Client as EosClient;

$client = new EosClient( 'https://wax.greymass.com' );
```