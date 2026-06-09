# 👋 Hey, nice to see you!

I'm **Lina María Montaño Ramírez** (calypsobronte)  
**Backend Developer** with +5 years of experience | **Google Women Techmakers Ambassador**

Passionate about building scalable backend systems, clean architecture, and creating impact through technology and community.

---

### 🚀 What I do

- Backend Developer with experience at **MercadoLibre** and **Sinapsis**
- Strong background in **Go, Python, Node.js, TypeScript** and Cloud (AWS, Azure, GCP)
- Love clean code, Domain-Driven Design (DDD), and building secure, maintainable systems
- Currently studying **Software Development Technology** at SENA (Remote or Colombia)

---

### 🛠️ Tech Stack

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

---

### 🌍 Leadership & Community

- **Google Women Techmakers Ambassador**
- Organizer & Leader at **NodeCo** and **Pioneras Devs**
- Mentor at **Coderise**
- Co-founder & Podcaster at **CaminoDev**

---

### 📺 Content Creation

- 🎥 YouTube: [RyukPlay](https://www.youtube.com/@ryukdeathnotetv)
- 🎮 Twitch: [ryukdeathnotetv](https://www.twitch.tv/ryukdeathnotetv)
- 🎙️ Podcast: [CaminoDev](https://www.youtube.com/@CaminoDev)

---

### 📍 Find me online

- 💼 [LinkedIn](https://www.linkedin.com/in/calypsobronte/)
- 🐙 [GitHub](https://github.com/calypsobronte)
- 🐦 [X / Twitter](https://x.com/calypsobronte)
- 🌐 [Personal Website / Portfolio](https://calypsobronte.github.io/)

---

### 📊 GitHub Stats

![Lina's GitHub stats](https://github-readme-stats.vercel.app/api?username=calypsobronte&show_icons=true&theme=radical&hide=contribs)

---

> 💬 *Open to opportunities in Backend Development, Cloud, and tech communities.  
> Currently looking for SENA paid internships and junior/mid-level positions.*


---

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
