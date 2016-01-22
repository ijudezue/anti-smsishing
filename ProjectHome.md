# Android anti-SMSishing #

The anti-SMSishing project is an **android implementation of the GoogleSafeBrowsing project** in order to verify if a SMS contains a dangerous http link.

The Safe Browsing API is an experimental API that enables client applications to check URLs against Google's constantly updated blacklists of suspected phishing and malware pages. Your client application can use the API to download an encrypted table for local, client-side lookups of URLs that you would like to check. More informations here:
http://code.google.com/apis/safebrowsing/

The project is a modification of the jgooglesafebrowsing project, a Java implementation of the Safe Browsing API. More information here:
http://code.google.com/p/jgooglesafebrowsing/

**An interesting implementation of this project** is to check if a link received in a SMS is a fraudulent http link or not. When you receive a SMS with your Android phone, you can directly open it in a browser of the mobile phone and currently no check is done to know if the SMS wants to redirect you to a dangerous page or not. In this case, we do not speak about phishing, but **SMSishing**.
You will be able to find the download instructions under the 'wiki' tab.

_The project has been initiated at the Carnegie Mellon University supervised by Professor Benoit Morel and his grad student Adam Tagert_

_Deniz Binay_