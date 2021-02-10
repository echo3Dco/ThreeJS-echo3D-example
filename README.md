# ThreeJS-echoAR-demo
Demo that loads 3D models and detects planes using ThreeJS, WebXR, and echoAR.

## Register
Don't have an API key? Make sure to register for FREE at [echoAR](https://console.echoar.xyz/#/auth/register).

## Setup and Run
### Load Models into HTML Page without AR
* Place 3D models into the echoAR console.
* Download LoadModels.html, query-3.5.1.js, and three into the same directory.
* Host that directory on a [local server](https://threejs.org/docs/#manual/en/introduction/How-to-run-things-locally).
* Open LoadModels.html, enter your echoAR API Key, and press `Load Models`.
* Enter the metadata from Arctic Fox Metadata.csv to see how the models change!
* To refer to models in the scene programmatically, use `models.get(id).hologram`, where id is the Entry ID in the echoAR console.

### Load Models into HTML Page with AR
* IMPORTANT: WebXR does not run on iPhones, so you must download Mozilla's [WebXR Viewer](https://apps.apple.com/us/app/webxr-viewer/id1295998056) to run any AR pages.
* Place 3D models into the echoAR console.
* Download HitTest.html, query-3.5.1.js, and three into the same directory.
* Host that directory on a [local server](https://threejs.org/docs/#manual/en/introduction/How-to-run-things-locally).
* Open HitTest.html, enter your echoAR API Key, and press `Start AR`.
* Move your camera to a flat surface until the white ring appears, and tap on the screen to download and place the models.
* Enter the metadata from Arctic Fox Metadata.csv to see how the models change!
* To refer to models in the scene programmatically, use `models.get(id).hologram`, where id is the Entry ID in the echoAR console.


## Learn more
Refer to our [documentation](https://docs.echoar.xyz/unity/) to learn more about how to use echoAR.

## Support
Feel free to reach out at [support@echoAR.xyz](mailto:support@echoAR.xyz) or join our [support channel on Slack](https://join.slack.com/t/echoar/shared_invite/enQtNTg4NjI5NjM3OTc1LWU1M2M2MTNlNTM3NGY1YTUxYmY3ZDNjNTc3YjA5M2QyNGZiOTgzMjVmZWZmZmFjNGJjYTcxZjhhNzk3YjNhNjE). 

## Screenshots
