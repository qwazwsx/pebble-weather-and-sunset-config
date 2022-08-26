# pebble-weather-and-sunset-config
temporary fix for the settings page for Yusuke Saitoh's Pebble watch face "weather &amp; sunset"


ALL code is property of Yusuke Saitoh, you can find the watch face [here](https://apps.rebble.io/en_US/application/5745db904b7068898e000013?dev_settings=true) on Rebble, the revived Pebble appstore. The original settngs page is located [here](https://yusukesaitoh.com/sketch/pebble/weather-sunrise-sunset.html).


```
Mixed Content: The page at 'https://yusukesaitoh.com/sketch/pebble/weather-sunrise-sunset.html' was loaded over HTTPS, but requested an insecure script 'http://code.jquery.com/jquery-1.11.3.min.js'. This request has been blocked; the content must be served over HTTPS.
segment.js:25 Uncaught ReferenceError: jQuery is not defined
    at segment.js:25:4
(anonymous) @ segment.js:25
weather-sunrise-sunset.html:107 Uncaught ReferenceError: $ is not defined
    at weather-sunrise-sunset.html:107:1
(anonymous) @ weather-sunrise-sunset.html:107
weather-sunrise-sunset.html:120 Uncaught ReferenceError: jQuery is not defined
    at weather-sunrise-sunset.html:120:5
```
