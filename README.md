### Steps to do after cloning/ forking

1. Run `npm i express body-parser web-push` in terminal
2. To generate Vapid keys run `./node_modules/.bin/web-push generate-vapid-keys`
3. Add the keys in `index.js` and `client.js`
4. To run the app in localhost `npm start`

![Push notification](https://github.com/sdkdeepa/pwa-push-notification/blob/main/notification.png)

### TO DO

1. Add webappmanifest
2. Fix Lighhouse errors to make sure this application is PWA compitible
