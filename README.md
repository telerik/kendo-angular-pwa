# KendoAngularPwa

This repository demonstrates a PWA application based on the <a href="https://angular.io/guide/service-worker-getting-started">official Angular implementation of a service worker</a>.

## Get Started

1. Clone this repository by using your favorite Git client or by executing git clone https://github.com/telerik/kendo-angular-pwa.git.
2. Enter the project directory by running cd kendo-angular-pwa.
3. Install the node modules by running npm install.
4. Install a web server by running npm install -g http-server. 

## Running the Application

1. We need to build the application in production mode so that we have the service worker available by running ng build --prod.
2. Enter the newly created dist folder by running cd dist.
3. Run the server in a disabled cache mode by runnig http-server -c-1.

## Further help

Once the application is up an running in prod mode, we can check its functionality by inspecting the Application tab of the browser's console.

![Service Worker](https://github.com/telerik/kendo-angular-pwa/blob/master/src/assets/help_images/sw.png)

We can then check the "Offline" option in order to check the offline functionality of the app.
![Offline](https://github.com/telerik/kendo-angular-pwa/blob/master/src/assets/help_images/offline.png)

We can inspect the cached local assets:
![Local assets](https://github.com/telerik/kendo-angular-pwa/blob/master/src/assets/help_images/cached_local.png)

And the cached remote assets:
![Remote assets](https://github.com/telerik/kendo-angular-pwa/blob/master/src/assets/help_images/cached_remote.png)
