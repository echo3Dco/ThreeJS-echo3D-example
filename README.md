# ThreeJS-echo3D-example
Demo that loads 3D models and detects planes using ThreeJS, WebXR, and echo3D.

## Register
Don't have an API key? Make sure to register for FREE at [echo3D](https://console.echo3D.co/#/auth/register).

## Video
Watch on [Youtube here](https://youtu.be/t9c9wJPgNbk).

## Setup and Run
### Load Models into HTML Page without AR
* [Add 3D models](https://docs.echo3d.com/quickstart/add-a-3d-model) to the echo3D console.
* Download LoadModels.html, query-3.5.1.js, and three into the same directory.
* Host that directory on a [local server](https://threejs.org/docs/#manual/en/introduction/How-to-run-things-locally).
* Open LoadModels.html, enter your echo3D API Key, and press `Load Models`.
* [Modify the metadata](https://docs.echo3d.com/unity/transforming-content) with 'x' and 'scale'. You can modify it however else you like.
* To refer to models in the scene programmatically, use `models.get(id).hologram`, where id is the Entry ID in the echo3D console.

### Load Models into HTML Page with AR
* IMPORTANT: WebXR does not run on iPhones, so you must download Mozilla's [WebXR Viewer](https://apps.apple.com/us/app/webxr-viewer/id1295998056) to run any AR pages.
* We use [ngrok](https://ngrok.com/docs/secure-tunnels/ngrok-agent/reference/api/) to connect our local dev environment to mobile.
* [Add 3D models](https://docs.echo3d.com/quickstart/add-a-3d-model) to the echo3D console.
* Download HitTest.html, query-3.5.1.js, and three into the same directory.
* Host that directory on a [local server](https://threejs.org/docs/#manual/en/introduction/How-to-run-things-locally). We used VSCode.
* Open HitTest.html on your device and enter your echo3D API Key (it is case sensitive). Press `Start AR`.
* Move your camera to a flat surface until the white ring appears, and tap on the screen to download and place the models.
* [Modify the metadata](https://docs.echo3d.com/unity/transforming-content) with 'x' at 100 and 'scale' at 2. You can modify the values and add whatever metadata you like.
* To refer to models in the scene programmatically, use `models.get(id).hologram`, where id is the Entry ID in the echo3D console.

## Learn more
Refer to our [documentation](https://docs.echo3D.com) to learn more about how to use echo3D.

## Support
Feel free to reach out at [support@echo3D.com](mailto:support@echo3D.com) or join our [support channel on Slack](https://go.echo3D.co/join). 

## Screenshots
![Snapshot_48](https://github.com/echo3Dco/ThreeJS-echo3D-example/assets/99516371/1a90998d-6870-40db-9b28-99a6d49a13e1)<br>
![Snapshot_49](https://github.com/echo3Dco/ThreeJS-echo3D-example/assets/99516371/d9808cab-8018-497e-ba2d-252f88107950)<br>
![Snapshot_50](https://github.com/echo3Dco/ThreeJS-echo3D-example/assets/99516371/68f5310d-7d30-4769-bdab-042831ec4437)<br>
![Snapshot_51](https://github.com/echo3Dco/ThreeJS-echo3D-example/assets/99516371/86819a2c-2eb0-4f7d-b321-c86b80671741)

