# Session_Keeper
Keep your session alive with low-impact requests.

Session Keeper is a quick and easy way to maintain a session in Burp while you perform other actions, step away for a coffee/dinner/shower, or finally go to sleep.

Usage is straight forward. Find a low-impact request. Something like requesting server time, a simple API request, or a ping/pong request if available. 

Right click the request and under Extensions -> Session Keeper -> Send to Session Keeper.

Go to the Session Keeper tab, select the interval you want for sending the low-impact request, set Max requests if you don't want to send till the end of time, and click start. 

Session Keeper will automatically send the request at the set interval.

Keep in mind that the request processing time is not considered in the countdown timer. 

The top windows shows the current request being sent, the middle window is the response, and the bottom window is a history of the requests.

You can reset the request history window with the "Clear Log" button at the top. 

Enjoy the ability to maintain your session for as long as you need (as long as a forever session is supported server-side).


## Features

- Automatically resend a low-impact request to keep sessions alive
- Supports custom intervals and max request limits
- Shows current request, response, and request history
- Clear log button to reset history view
- Easy UI inside Burp Suite

## Installation

1. Download the python file.
2. In Burp Suite, go to **Extensions > Installed**.
3. Click **Add**, select **PY** as extension type.
4. Load the python file.

## Development
This extension is written in Jython for Burp Suite.

## Requiremetns
- Jython 2.7.x
- Burp Extender API v1.7+

Pull requests welcome.

![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)
![Platform: Burp Suite](https://img.shields.io/badge/Burp%20Suite-Extension-orange)
![Language: Python](https://img.shields.io/badge/Language-Python%202.7-blue)

This project is licensed under the GNU General Public License v3.0 – see the [LICENSE](LICENSE) file for details.
