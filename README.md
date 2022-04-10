# LazerPay WHMCS Module
LazerPay payment gateway module for WHMCS.

## How to use
#### 1. Download with Composer:
```shell
cd your_whmcs_installation_path/modules/gateways
```
Then pull from packagist registry with composer
```shell
composer require cloudinos/whmcs-lazerpay
```

#### 2. Download from GitHub:
 - Locate the `Code` button with green color, click on it and select `Download ZIP`
 - Unzip the downloaded file to `modules/gateways` folder.

#### 3. Create initiator:
Move the file `lazerpay.php` into this folder `modules/gateways`. You can also do this by executing the command below:
```shell
cd your_whmcs_installation_path/modules/gateways & mv lazperay/lazerpay.php ./lazerpay.php
```

### Things To Note
The `verify-payment.php` file handles payment verification just as callbacks works on WHMCS. 

## How To Contribute
We love working together. Notice something very important, fork the repo, create a Pull Request, and we'd be happy to merge.
