# Quasar App (quasar-project)

A Quasar Project

## Install the dependencies
```bash
yarn
# or
npm install
```

### Start the app in development mode (hot-code reloading, error reporting, etc.)
```bash
quasar dev
```


### Lint the files
```bash
yarn lint
# or
npm run lint
```


### Format the files
```bash
yarn format
# or
npm run format
```



### Build the app for production
```bash
quasar build
```

### Customize the configuration
See [Configuring quasar.config.js](https://v2.quasar.dev/quasar-cli-vite/quasar-config-js).


### SQL UPIT
SELECT s.id, s.artikl, s.kolicina
FROM stavke s
JOIN racuni r ON s.racun = r.id
WHERE r.id = "id neki";

zavrsni upit

### link
https://github.com/svalinai/test-is.git


