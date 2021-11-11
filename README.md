# Stock Alert

![phpcs](https://github.com/DominicWatts/StockAlert/workflows/phpcs/badge.svg)

![PHPCompatibility](https://github.com/DominicWatts/StockAlert/workflows/PHPCompatibility/badge.svg)

![PHPStan](https://github.com/DominicWatts/StockAlert/workflows/PHPStan/badge.svg)

![php-cs-fixer](https://github.com/DominicWatts/StockAlert/workflows/php-cs-fixer/badge.svg)

Allow stock alerts to be added via email on product page instead of requiring login

# Install instructions #

`composer require dominicwatts/stockalert`

`php bin/magento setup:upgrade`

`php bin/magento setup:di:compile`

# Frontend behaviour

Before (requires customer login)

![Before](https://gcdn.pbrd.co/images/v9Ilz3WnSvbq.png)

After

![After](https://gcdn.pbrd.co/images/pU2lPP1mnOGM.png)