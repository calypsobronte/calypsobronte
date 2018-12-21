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
cuando ya creas el .js
vas a copias este codigo
```js
#!/usr/bin/env node
// 👆 Used to tell Node.js that this is a CLI tool

// Pull in our modules
const chalk = require('chalk')
const boxen = require('boxen')

// Define options for Boxen
const options = {
  padding: 1,
  margin: 1,
  borderStyle: 'round'
}

// Text + chalk definitions
const data = {
  name: chalk.white('Tu nombre / '),
  handle: chalk.cyan('tuname'),
  work: chalk.white('donde trabajas'),
  twitter: chalk.cyan('tu cuenta de twitter'),
  github: chalk.cyan('tu cuenta de github'),
  linkedin: chalk.cyan('tu cuenta de linkedin'),
  web: chalk.cyan('tu pagina web (opcional)'),
  npx: chalk.white('npx tuejecutable'),
  labelWork: chalk.white.bold('      Work:'),
  labelTwitter: chalk.white.bold('   Twitter:'),
  labelGitHub: chalk.white.bold('    GitHub:'),
  labelLinkedIn: chalk.white.bold('  LinkedIn:'),
  labelWeb: chalk.white.bold('       Web:'),
  labelCard: chalk.white.bold('      Card:')
}

// Actual strings we're going to output
const newline = '\n'
const heading = `${data.name} ${data.handle}`
const working = `${data.labelWork}  ${data.work}`
const twittering = `${data.labelTwitter}  ${data.twitter}`
const githubing = `${data.labelGitHub}  ${data.github}`
const linkedining = `${data.labelLinkedIn}  ${data.linkedin}`
const webing = `${data.labelWeb}  ${data.web}`
const carding = `${data.labelCard}  ${data.npx}`

// Put all our output together into a single variable so we can use boxen effectively
const output = heading + newline + newline + working + newline + twittering + newline + githubing + newline + linkedining + newline + webing + newline + newline + carding

console.log(chalk.green(boxen(output, options)))
```
despues:

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

4. y despues 
```
$ npm publish
```
 y ya al fin puedel ejecutar tu 
```
$ npx calypsobronte
```
