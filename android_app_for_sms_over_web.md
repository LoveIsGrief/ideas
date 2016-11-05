# Android APP for SMS over web

iPhone has a web-interface for their messaging (or so I've seen, I don't use Apple), WhatsApp allows you to connect to the app over the [web](https://web.whatsapp.com), and there are apps out there that allow you to send an SMS using your phone over the web.
It would be nice to have this on android as well, but without hosting any private data on the web.

## Existing apps

* [SMS from your PC](https://play.google.com/store/apps/details?id=com.texty.sms) - 
 Basically sends texts from a proprietary web interface
* [ShellMS](https://f-droid.org/repository/browse/?fdid=com.android.shellms) -
 This allows to send texts over ADB


## Expected flow

0. App is started (or is autostarted)
1. User enters URL
2. Authentication
3. Access granted --> all messages and contacts can be seen

... would it be better to access the SMS and contacts over XMPP?

## Possible solutions

### Webapp server on phone

Basically the phone would give HTTPS access to a web-interface and API.

#### Possible problems

**Security**

How would the webinterface and API be secured?

- Login and password
  - Randomly generated at each start
  - Manually configured username and password
- QR coded generated in the browser that has to be scanned by the phone  
  This would mean each computer generates a unique QR code each time the web-interface is accessed.
  One would therefore need physical access to the phone and the computer to authenticate

**Server address**

IP-addresses aren't very wieldy or beautiful for the average user. 

**Server access**

Do we really want the phone to be accessible over the web? Maybe making the app WiFi only could help.