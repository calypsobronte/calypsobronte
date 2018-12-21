My npm card inspired by [bitandbang](https://github.com/bnb/bitandbang)

Ejecutar 
Via npx

```
$ npx calypsobronte
```

Pasos

1. Puedes hacer fork en el repo de [bitandbang](https://github.com/bnb/bitandbang)
 o simplemente ir creando tus archivos.

* `mkdir calypsobronte`
* `cd calypsobronte`
* `npm init`
*Nota: iniciamos el package.json con tus datos*
despues:
* `npm i`
*Nota: instalamos el node_modules para que nos cargen algunas dependencias que necesitamos*
despues creamos:
* `mkdir bin`
* `touch card.js`

2. Ejecutas 
```
$ npm version major
```
asi miras que version tienes antes de darle publish debes de haber creado una cuenta en 
[npm.org](https://www.npmjs.com/)

3. ejecuta esto 

```
$ npm adduser 
```

3. y despues 
```
$ npm publish
```
 y ya al fin puedel ejecutar tu 
```
$ npx calypsobronte
```
