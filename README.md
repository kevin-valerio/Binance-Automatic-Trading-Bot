# Binance-Automatic-Trading-Bot
Automatic Binance trading bot. Create your own algorithm for better improvement

I didn't write the all code. Just use this repo for my own using.
This code use Ta4j library, which is a Java-based Technical Analysis framework.

To create your own strategy, go to util/BinanceTa4jUtils.java and edit buildMacdStrategy() method.

Also, you'll have to create two files
One will be /resources/config.properties (https://pastebin.com/raw/GeS5D2Xd) (read the code to understand)
And /resources/logback.xml (https://pastebin.com/raw/WXMRTmRk=

Put your binance API key in the properties file.

Start the main class, then it'll scan all the pairs and check for those that have an valid entry posotion matching with the algorithm.
The code automatically fetch the price of BTC pairs, in realtime

If you have any questions, contact valerio.kevin83@gmail.com 
