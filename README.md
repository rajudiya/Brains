# Magento Brains

Magento Brains Payment Module 

`Magento Brains Payment Module`

## Composer install

- `composer config repositories.brains vcs https://github.com/rajudiya/brains`

- `composer require magento/brains:dev-main`

## Composer uninstall

- `composer remove magento/brains`

## Known issues

- **Issues will be here**
  Compartible with magento 2.4.6

## Developer informations
- Developer Name - Rohan Ajudiya
- Inkdin url     - https://www.linkedin.com/in/ajudiya-rohan-9a9ab81b3/
- Contect us     - +91 6353856107

### Install module

1. Run `php bin/magento setup:upgrade`
2. Run `php bin/magento setup:di:compile`
3. Run `php rm -rf generated/`
3. Run `php bin/magento s:s:d`
4. Run `php bin/magento c:c`
6. Run `php bin/magento indexer:reindex`
7. run `php bin/magento setup:static-content:deploy -f`

### Uninstall module
1. Run `php bin/magento setup:di:compile`
2. Run `php bin/magento s:s:d`
3. Run `php bin/magento c:c`
4. Run `php bin/magento indexer:reindex`
5. run `php bin/magento setup:static-content:deploy -f`

### Additional developer notes
Reference URL `References will be added.`
