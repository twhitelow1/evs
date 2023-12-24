# evs

## Project setup
```
npm install
```
## Use the correct node version for the project
```
nvm use 17.9.1 (If using NVM)
```
### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production

npm run build

if you get a ERR_OSSL_EVP_UNSUPPORTED error then use:

$env:NODE_OPTIONS="--openssl-legacy-provider"
npm run build

```
## Deploy to production servers on firebase
```
npm run build
firebase deploy
```
### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
