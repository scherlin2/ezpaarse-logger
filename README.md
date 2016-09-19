ezPAARSE Logger
===

ezPAARSE logger is a web application that captures the traffic from the browser and send it to [ezPAARSE](https://github.com/ezpaarse-project/ezpaarse) to analyze it.

**NB:** works with ezPAARSE **v2.9.0** or greater.

Installation
===

Get the companion extension for either [Google Chrome](https://chrome.google.com/webstore/detail/ezpaarse-logger-extension/cpjllnfdfhkmbkplldfndmfdbabcbidc) or [Mozilla Firefox](https://addons.mozilla.org/fr/firefox/addon/ezpaarse-logger-extension/).

Usage
===

- Ensure that the extension is active.
- Navigate to the [WebApp page](http://analogist.couperin.org/ezlogger/) or click the extension icon.
- Once opened, the app will capture your web traffic as you browse the internet.
- Click 'Analyze' to send the captured traffic to ezPAARSE.

Note
===

You can :
- use any ezPAARSE instance by changing the URL in the settings of the app (defaults to http://127.0.0.1:59599).
- customize the headers sent to ezPAARSE.
- export the captured traffic in a standard EZproxy format.
- filter out the traffic caused by loading CSS, JS and image files.
