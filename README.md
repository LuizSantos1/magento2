Moip_Magento2
-------------
  README
-------------

===== 1.0.1 =====
 * Initial stable M2 release
 Following Feature contain
 => place order using Moip Payment
 => update order status based on trigger
 => From backend not update order status on payment side
===============================

How to install module
you need to add Moip Library using below command from root folder of magento
=> composer require moip/moip-sdk-php

=============
How to register your controller as trigger of payment method for update order status
=> copy trigger.php file from module to root folder of magento
=> then run yourdomain.com/trigger.php
