<p align="center">
  <a href="https://www.canva.com/design/DAGTCoR8DKg/jIBVABBvNQb8lKqWIJOLIA/edit?utm_content=DAGTCoR8DKg&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton" target="blank"><img src="https://www.canva.com/design/DAGTCoR8DKg/jIBVABBvNQb8lKqWIJOLIA/edit?utm_content=DAGTCoR8DKg&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton" width="120" alt="Glamping Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/tu-usuario/tu-repo/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/tu-usuario/tu-repo

<p align="center">Una plataforma innovadora que utiliza <a href="http://nodejs.org" target="_blank">Node.js</a> y blockchain para promover el turismo sostenible a través de glampings y recompensas tokenizadas.</p>
<p align="center">
  <a href="https://www.npmjs.com/~tu-usuario" target="_blank"><img src="https://img.shields.io/npm/v/@tu-paquete/core.svg" alt="NPM Version" /></a>
  <a href="https://www.npmjs.com/~tu-usuario" target="_blank"><img src="https://img.shields.io/npm/l/@tu-paquete/core.svg" alt="Package License" /></a>
  <a href="https://www.npmjs.com/~tu-usuario" target="_blank"><img src="https://img.shields.io/npm/dm/@tu-paquete/common.svg" alt="NPM Downloads" /></a>
  <a href="https://circleci.com/gh/tu-usuario/tu-repo" target="_blank"><img src="https://img.shields.io/circleci/build/github/tu-usuario/tu-repo/master" alt="CircleCI" /></a>
  <a href="https://coveralls.io/github/tu-usuario/tu-repo?branch=master" target="_blank"><img src="https://coveralls.io/repos/github/tu-usuario/tu-repo/badge.svg?branch=master" alt="Coverage" /></a>
  <a href="https://discord.gg/tu-enlace" target="_blank"><img src="https://img.shields.io/badge/discord-online-brightgreen.svg" alt="Discord"/></a>
  <a href="https://opencollective.com/tu-repo#backer" target="_blank"><img src="https://opencollective.com/tu-repo/backers/badge.svg" alt="Backers on Open Collective" /></a>
  <a href="https://opencollective.com/tu-repo#sponsor" target="_blank"><img src="https://opencollective.com/tu-repo/sponsors/badge.svg" alt="Sponsors on Open Collective" /></a>
  <a href="https://paypal.me/tu-usuario" target="_blank"><img src="https://img.shields.io/badge/Donate-PayPal-ff3f59.svg" alt="Donate us"/></a>
  <a href="https://opencollective.com/tu-repo#sponsor" target="_blank"><img src="https://img.shields.io/badge/Support%20us-Open%20Collective-41B883.svg" alt="Support us"></a>
  <a href="https://twitter.com/tu-usuario" target="_blank"><img src="https://img.shields.io/twitter/follow/tu-usuario.svg?style=social&label=Follow" alt="Follow us on Twitter"></a>
</p>

## Descripción

Este proyecto utiliza tecnología blockchain y airdrop para fomentar la participación en turismo sostenible mediante glampings. Los usuarios pueden ganar tokens por participar en actividades ecológicas, promocionar destinos turísticos y contribuir al crecimiento de la plataforma.

## Configuración del proyecto

1. **Descargar el proyecto de GitHub con el siguiente comando:**

   ```bash
   git clone https://github.com/andres2017/airdrop_back.git

2. CREAMOS BASE DE DATOS CON EL NOMBRE DE " airdrop " EN EL PROGRAMA POSTGRES

3. LUEGO CONFIGURAMOS EN VISUAL CODE EL ARCHIVO " Typeorm.config.ts "  CON LOS SIGUIENTES DATOS:

	username: process.env.DB_USERNAME || 'postgres',
  	password: process.env.DB_PASSWORD || '123456',
  	database: process.env.DB_DATABASE || 'airdrop',

5.CONFIGURAMOS EL ARCHIVO " env.development " Y GUARDAMOS :

	PORT=5001
	DB_HOST=localhost
	DB_USERNAME=postgres
	DB_PASSWORD=123456
	DB_DATABASE=airdrop
	DB_PORT=5432

	DATABASE_URL=
	JWT_SECRET=1234567890


5. INSTALAMOS 
npm install
npm run mig-run
npm start
npm run dev

http://localhost:5001/api

Contribuciones
Las contribuciones son bienvenidas. Si deseas colaborar, por favor abre un problema o envía un pull request.

Licencia
Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.

Contacto
Para más información, por favor contáctame en andres9304v@gmail.com




