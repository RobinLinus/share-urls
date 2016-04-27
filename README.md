# share-urls
Collection of share urls and documentations of various share urls


## Android Intents
[Official Documentation](https://developer.chrome.com/multidevice/android/intents)

## whatsapp 
[Official Documentation](https://www.whatsapp.com/faq/en/iphone/23559013)
### Sending a message to a specific contact:
[Stack Overflow](http://stackoverflow.com/questions/21500570/start-whatsapp-from-url-href-with-custom-text-content)
```
<a href="intent://send/<<number here>>#Intent;scheme=smsto;package=com.whatsapp;action=android.intent.action.SENDTO;end">
```

[Whatsapp Manifest](https://gist.github.com/kimenye/eef321a2a182bd4544af) (Look for `BROWSABLE`)

## Twitter Web Intents
https://dev.twitter.com/web/intents


## Paypal Payment Links
[Stack Overflow](http://stackoverflow.com/questions/9956081/how-can-i-create-a-paypal-link-that-will-send-money-to-a-specific-e-mail-address)
Assuming you are logged in:
[POC](https://www.paypal.com/us/cgi-bin/webscr?cmd=_send-money&nav=1&email=FOO@BAR.com)
