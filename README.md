# Bezorgradar PhoneGap App 
after https://github.com/phonegap/phonegap-template-hello-world#hello-world-phonegap-template-

## Usage

#### Target users

Target users are independent package delivery workers registered at 

    https://citytransportservice.nl/bezorgradar/?start/onderweg

Register and download bezorgradar-app from

    https://build.phonegap.com/apps/3507341/install

Make sure the bezorgradar-app is granted access to location.

So far only for Android and Windows (not tested) devices

#### Instructions

##### Identify

Registered users may open the app and identify themselves with username and password.

##### Leave trail

After having hit the

    start - button

the registered user's location is sent to the server every six minutes. 
The trace between the latest five locations may be publicly displayed at

    https://citytransportservice.nl/bezorgradar/?address/positie

The personal trace between the latest five locations may be privately displayed at

    https://citytransportservice.nl/bezorgradar/?address/positie/u/[personal usercode]

which the registered user may share at will.

##### Stop tracing
After having hit the

    stop-button

the registered user's location is no longer sent, until the start-button is hit again or the app is restarted. 


