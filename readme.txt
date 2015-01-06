payhub-zencart-plugin
=====================

PayHub plugin for ZenCart.

Tested up to Zen Cart Version: 1.5.4.

See commit history at https://github.com/payhubbuilder/payhub-zencart-plugin.


Installation
============

-Retrieve the plugin from http://developer.payhub.com or https://github.com/payhubbuilder/payhub-zencart-plugin.

-Download it and extract it if necessary.

-At this point you should have a directory structure as follows:

  --LICENSE
  --readme.txt
  --includes
    --languages
      --english
        --modules
          --payment
            --payhub.php
    --modules
      --payment
        --payhub.php

-Copy both of the "payhub.php" to their corresponding directories in your Zen Cart installation.

-Make sure the files are readable by your web server process.

-Now log into your Zen Cart admin page and go to Modules -> Payment.  You should see "PayHub" as an option there.

-Click on the PayHub row and you will see a box on the right where you can enable the module and put in your API credentials.

-To get your credentials, log into your VirtualHub account and go to Admin ->  3rd Party API and you will see the credentials you need.  If you do nnot have any credentails listed there then contact us to add that feature to your account.

-Once the module is configured and enabled, you should get the option to pay by credit card when checking out through your site.

**Note on testing: Currently there is no demo mode available on this plugin.  If you would like test credentials then please contact us.

PayHub Contact Information
==========================
Sales:
866-286-1300
sales@payhub.com

Support:
877-246-5133
wecare@payhub.com

www.payhub.com
