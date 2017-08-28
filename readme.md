# Google Payment API Reference

#### Getting Started
* Android Phone w/ [Android Pay](https://play.google.com/store/apps/details?id=com.google.android.apps.walletnfcrel) set up
* Make sure you have 11.4+ of [Google Play Services](https://play.google.com/store/apps/details?id=com.google.android.gms&hl=en)
* [Chrome M61](https://play.google.com/store/apps/details?id=com.chrome.beta) for Android
* Enable the following flag: chrome://flags/#pay-with-google-v1

The following examples show how to use the Google Payment API with PaymentRequest.

# Sample Implementations

## pwg-main  
hosted on androidpayweb.firebaseapp.com

### simple.html [Demo](https://androidpayweb.firebaseapp.com/simple.html)

* Sample checkout page that supports Pay with Google and other payment methods
* Returns either a gateway tokenized form of payment from user's Google Account or a card stored in Chrome

### button.html [Demo](https://androidpayweb.firebaseapp.com/button.html)

* Sample checkout page that shows a Pay with Google button
* Google is the only supported payment method
* Returns a gateway tokenized form of payment from the user's Google Account

### button-direct.html [Demo](https://androidpayweb.firebaseapp.com/button-direct.html)

* Sample checkout page that shows a Pay with Google button
* Google is the only supported payment method
* Returns a card or token details directly (not a gateway token) from the user's Google Account

### iframe.html

* Reference iframe hosted androidpayweb.firebaseapp.com used by iframe examples (below)
* Returns a gateway tokenized form of payment from the user's Google Account


## pwg-iframe
hosted on androidpayiframe.firebaseapp.com


### Platform.html [Demo](https://androidpayiframe.firebaseapp.com/platform.html)

* Shows how a 1:many platform can use a hosted iframe to call the Google Payment API from multiple domains
* Calls iframe.html (above) which returns a gateway tokenized form of payment from the user's Google Account

### AMP.html [Demo](https://androidpayiframe.firebaseapp.com/amp.html)

* Call Pay with Google from within an AMP page
* Calls iframe.html (above) which returns a gateway tokenized form of payment from the user's Google Account



