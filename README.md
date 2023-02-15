# altinn-dev-extension
WebExtension to redirect Altinn 3 app-frontend to local development server. Redirects all environments (prod, tt02++) to use [app-frontend-react](https://github.com/Altinn/app-frontend-react) from `localhost:8080`. Only keep this enabled when you need to test out a local version in a staging/production environment, as it _will_ overwrite functionality to switch app-frontend versions in [LocalTest](https://github.com/Altinn/app-localtest).

Clone the repo and add the folder to Chrome as an
[unpacked extension](https://developer.chrome.com/docs/extensions/mv3/getstarted/development-basics/#load-unpacked).
This might not work on Firefox, as it is using Manifest v3.
