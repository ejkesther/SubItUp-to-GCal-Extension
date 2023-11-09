# SubItUp-to-GCal-Extension
Desciption: Chrome extension that turns posted shift schedule on SubItUp into Google Calendar events.

Project Structure:
Manifest.json -> allows recognition of program as a Chrome extension; houses basic app info and sets up API
subitup.png -> image of app icon
window.html -> popup display of app, main web screen visuals
index.html -> initializes and maintains the web server localhost:8000 that allows app to make requests to GCal API
background.js -> where actual operation of GCal event-making and processing of SubItUp meta data occurs


might need more JavaScript files?

Useful Links/Resources Used:
https://developer.chrome.com/docs/extensions/reference/scripting/
https://developer.chrome.com/docs/extensions/migrating/checklist/

https://developer.chrome.com/docs/extensions/reference/pageCapture/
https://developer.chrome.com/docs/extensions/reference/declarativeContent/
https://developer.chrome.com/docs/extensions/mv3/manifest/activeTab/
https://developer.chrome.com/docs/extensions/mv3/content_scripts/#programmatic 
https://developer.chrome.com/docs/extensions/reference/contentSettings/

IDs for Google Calendar API JavaScript Application: 
ClientID -> 936996695558-cjdnq0abhvhuvnddr8njpcja7gc0o71c.apps.googleusercontent.com
API Key -> AIzaSyB0kmXkWhbomenkDLfJjA-ljGx4LPpchSE