# ThreeJS-echo3D-example
Demo that loads 3D models and detects planes using ThreeJS, WebXR, and echo3D.

## Register
Don't have an API key? Make sure to register for FREE at [echo3D](https://console.echo3D.co/#/auth/register).

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
* [Add 3D models](https://docs.echo3d.com/quickstart/add-a-3d-model) to the echo3D console.
* Download HitTest.html, query-3.5.1.js, and three into the same directory.
* Host that directory on a [local server](https://threejs.org/docs/#manual/en/introduction/How-to-run-things-locally). We used VSCode.
* Use ngrok to connect your phone to your browser to view in AR. Set up an account at ngrok.com and download the MacOSX ARM64 or Windows(32-Bit) file. Follow the ngrok setup instructions [here](https://dashboard.ngrok.com/get-started/setup).
* Start an HTTP tunnel. In the terminal within the ngrok directory, type in ./ngrok http (port number). Fill in the port number with the port from your Live Server.
* Next to 'Forwarding', copy and paste the given forwarding link (for example [https://8418-168-122-7-164.ngrok.io]https://8418-168-122-7-164.ngrok.io/) and send to your phone.
* Open the link on your phone.
* Open HitTest.html on your device and enter your echo3D API Key. Press `Start AR`.
* Move your camera to a flat surface until the white ring appears, and tap on the screen to download and place the models.
* [Modify the metadata](https://docs.echo3d.com/unity/transforming-content) with 'x' and 'scale'. You can modify it however else you like.
* To refer to models in the scene programmatically, use `models.get(id).hologram`, where id is the Entry ID in the echo3D console.


## Learn more
Refer to our [documentation](https://docs.echo3D.com) to learn more about how to use echo3D.

## Support
Feel free to reach out at [support@echo3D.com](mailto:support@echo3D.com) or join our [support channel on Slack](https://go.echo3D.co/join). 

## Screenshots
