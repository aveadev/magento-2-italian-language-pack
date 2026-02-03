## Magento 2 Italian Language Pack

**Install Italian pack**:

``` php
composer require aveadev/magento-2-italian-language-pack
php bin/magento setup:static-content:deploy sk_SK
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush
```
