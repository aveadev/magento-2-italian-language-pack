## Magento 2 Italian Language Pack

**Install Italian pack**:

``` php
composer require aveadev/magento-2-italian-language-pack:dev-main
php bin/magento setup:static-content:deploy it_IT
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush
```
