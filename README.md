Open Source Android Market Ruby Library for parsing Android Market.

This project is under development.

Fell free to clone it and submit your changes to us.

INSTALL INSTRUCTIONS 

gem install android_market_api

For parsing an application on Android Market

Ex:

require 'rubygems'
require 'android_market_api'

$app=AndroidMarketApplication.new('com.zeptolab.ctr.paid')
$app.to_s


For getting Top Selling Paid Apps for a category

Ex:

require 'rubygems'
require 'android_market_api'

app_arr=AndroidMarket.get_top_selling_paid_apps('CASUAL')
app_arr[2].to_s


For getting Top Selling Free Apps for a category

Ex:

require 'rubygems'
require 'android_market_api'

app_arr=AndroidMarket.get_top_selling_free_apps('CASUAL')
app_arr[1].to_s

SOON MORE DOCUMENTATION 

How can i help ?

Contributions are welcome ! The project is mainly missing documentation and examples...

