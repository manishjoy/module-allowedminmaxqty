# Mage2 Module ManishJoy AllowedMinMaxQty

    ``manishjoy/module-allowedminmaxqty``

 - [Main Functionalities](#markdown-header-main-functionalities)
 - [Installation](#markdown-header-installation)
 - [Configuration](#markdown-header-configuration)
 - [Specifications](#markdown-header-specifications)
 - [Attributes](#markdown-header-attributes)


## Main Functionalities


## Installation
\* = in production please use the `--keep-generated` option

### Type 1: Zip file

 - Unzip the zip file in `app/code/ManishJoy`
 - Enable the module by running `php bin/magento module:enable ManishJoy_AllowedMinMaxQty`
 - Apply database updates by running `php bin/magento setup:upgrade`\*
 - Flush the cache by running `php bin/magento cache:flush`

### Type 2: Composer

 - Make the module available in a composer repository for example:
    - private repository `repo.magento.com`
    - public repository `packagist.org`
    - public github repository as vcs
 - Add the composer repository to the configuration by running `composer config repositories.repo.magento.com composer https://repo.magento.com/`
 - Install the module composer by running `composer require manishjoy/module-allowedminmaxqty`
 - enable the module by running `php bin/magento module:enable ManishJoy_AllowedMinMaxQty`
 - apply database updates by running `php bin/magento setup:upgrade`\*
 - Flush the cache by running `php bin/magento cache:flush`


## Configuration

 - enable (allowedminmaxqty/general_settings/enable)

 - type (allowedminmaxqty/general_settings/type)

 - min_allowed_qty (allowedminmaxqty/general_settings/min_allowed_qty)

 - max_allowed_qty (allowedminmaxqty/general_settings/max_allowed_qty)


## Specifications




## Attributes



