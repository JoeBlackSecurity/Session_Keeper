# Session_Keeper
Easily maintain your current session in Burp 

Session Keeper is a quick and easy way to maintain a session in Burp while you perform other actions, step away for a coffee/dinner/shower, or finally go to sleep.

Usage is straight forward. Find a low-impact request. Something like requesting server time, a simpel api request, or a ping/pong request if available. 

Right click the request and under Extensions -> Session Keeper -> Send to Session Keeper.  

Go to the Session Keeper tab, select the interval you want for sending the low-impact request, set Max requests if you dont want to send till the end of time, and click start.

Session Keeper will automatically send the request at the set interval. 

Keep in mind that the request processing time is not considered in the coundown timer.  

The top windows shows the current request being sent, the middle window is the response, and the bottom window is a history of the requests. 

You can reset the request history window witht he "Clear Log" button at the top.

Enjoy the ability to maintain your session for as long as you need (as long as a forever session is supported server-side).


![Burp Extension](https://img.shields.io/badge/Burp%20Suite-Extension-orange)
