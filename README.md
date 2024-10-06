<p align="center"> 
<a href="https://github.com/Ednut001"><img src="http://readme-typing-svg.herokuapp.com?font=mono&size=17&duration=4000&color=F7B11B&center=falso&vCenter=falso&lines=ARCH-+MD+by+Ednut+2024+best+repository.+%F0%9F%92%96" height="90px"></a> 
</p>
 
<p align="center">
<img src="https://files.catbox.moe/p2yazn.jpg" alt="ARCH-MD" width="800"/>

</p>

<p align="center">
<a href="#"><img title="ARCH-MD" src="https://img.shields.io/badge/DONT FORGET TO LEAVE A STAR 🌟 ¡THANKS! -red?colorA=%255ff0000&colorB=%23017e40&style=for-the-badge"></a> 
</p>

<p align="center">   
<a href="https://github.com/Ednut001/Arch-MD/watchers"><img title="Watchers" src="https://img.shields.io/github/watchers/Ednut001/Arch-Md?label=Watchers&color=green&style=flat-square"></a>
<a href="https://github.com/Ednut001/Arch-MD/stargazers"><img title="Stars" src="https://img.shields.io/github/stars/Ednut001/Arch-Md?label=Stars&color=yellow&style=flat-square"></a>
</p>

<div align="center">
 
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Ednutmail@gmail.com)
[![Support](https://img.shields.io/badge/Support-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/Ednut_x)
[![WhatsApp](https://img.shields.io/badge/STAFF-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/2348102487241)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@Ednuthimself)
[![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/Ednut001)
</div>

### 👇 `Todas las cuentas están aquí!!`
[![Enlaces](https://img.shields.io/badge/GataBot_Accounts-000000%7D?style=for-the-badge&logo=biolink&logoColor=white)](https://www.atom.bio/gatabot/)

### 🌟 (OPCIÓN 1) INSTALACIÓN AUTOMÁTICA 🫰
[![blog](https://img.shields.io/badge/Instalacion-Automatica-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/PESW8LXXlOI?feature=share)
> **Note** Comandos para instalar de forma automática en Termux  
```bash
termux-setup-storage
```
```bash
apt update -y && yes | apt upgrade && pkg install -y bash wget mpv && wget -O - https://raw.githubusercontent.com/GataNina-Li/GataBot-MD/master/gata.sh | bash
```
### Edita lo siguiente si deseas usar este método de instalación en tú repositorio previamente hecho un fork
```js
// PERSONALIZAR INSTALACIÓN AUTOMÁTICA (En caso de una Bifurcación)
// Parámetros editables

// REFERENCIA
"wget -O - https://raw.githubusercontent.com/GataNina-Li/GataBot-MD/master/gata.sh | bash"

// PARÁMETROS QUE PUEDE SER MODIFICADOS --> "[...]"
// Reemplace por su usuario de GitHub, y nombre del repositorio
"wget -O - https://raw.githubusercontent.com/[usuario]/[repositorio]/master/gata.sh | bash"
```
#### MODIFICAR ARCHIVO [`gata.sh`](https://github.com/GataNina-Li/GataBot-MD/blob/master/gata.sh)
```js
//LÍNEAS A MODIFICAR
205 --> "git clone https://github.com/[user]/[repositorio].git"
//Ejemplo: git clone https://github.com/GataNina-Li/GataBot-MD.git

209 --> "cd [repositorio]"
//Ejemplo: cd GataBot-MD

//Una vez hecho estos cambios ejecute los nuevos comandos en Termux
```
-----
### 🪄 (OPCIÓN 2) INSTALACIÓN MANUAL POR TERMUX - GITHUB 
> **Note** Comandos para instalar de forma manual
```bash
termux-setup-storage
```
```bash
apt update && apt upgrade && pkg install -y git nodejs ffmpeg imagemagick yarn
```
```bash
git clone https://github.com/GataNina-Li/GataBot-MD && cd GataBot-MD
```
```bash
yarn install && npm install
```
```bash
npm start
```
> **Warning** Si aparece (Y/I/N/O/D/Z) [default=N] ? use la letra "y" + "ENTER" para continuar con la instalación 
----
### 📁 (OPCIÓN 3) INSTALACIÓN POR TERMUX - ARCHIVOS
> **Note** Descargué y Descomprime
### [`GataBot-MD ~ Archivos`](https://github.com/GataNina-Li/GataBot-MD/archive/refs/heads/master.zip)
[![blog](https://img.shields.io/badge/Termux-GataBotMD-FF0000?style=for-the-badge&logo=youtube&logoColor=white)
](https://youtu.be/UcWlyQ8u5HE)
```bash
termux-setup-storage
```
```bash
apt update && apt upgrade && pkg install -y git nodejs ffmpeg imagemagick yarn
```
```bash
cd storage/downloads/GataBot-MD-master/GataBot-MD-master 
```
```bash
yarn install
```
```bash
npm install
```
```bash
npm start
```
* #### APLICACIÓN RECOMENDADA PARA [`DESCOMPRIMIR`](https://play.google.com/store/apps/details?id=com.rarlab.rar)
* #### APLICACIÓN RECOMENDADA PARA EDITAR [`NÚMERO DE OWNER`](https://play.google.com/store/apps/details?id=com.rhmsoft.code)
> **Note** Guardar los archivos en la ubicación: storage/downloads/GataBot-MD-master/GataBot-MD-master   
----
### 🚀 USAR GATABOT 24/7 EN TERMUX 
> Ejecutar estos comandos dentro de la carpeta GataBot-MD
```bash
termux-wake-lock && npm i -g pm2 && pm2 start index.js && pm2 save && pm2 logs 
``` 
#### ⬇️ Opciones Disponibles
> **Warning** Esto eliminará todo el historial que hayas establecido con PM2:
```bash 
pm2 delete index
``` 
> Si tienes cerrado Termux y quiere ver de nuevo la ejecución use:
```bash 
pm2 logs 
``` 
> Si desea detener la ejecución de Termux use:
```bash 
pm2 stop index
``` 
> Si desea iniciar de nuevo la ejecución de Termux use:
```bash 
pm2 start index
``` 
---- 
### 👉 ACTIVAR EN CASO DE DETENERSE EN TERMUX
> [!NOTE]
> Si despues que ya instalastes tu bot y termux te salta en blanco, se fue tu internet o reiniciaste tu celular, solo realizaras estos pasos:
```bash
cd && cd GataBot-MD && npm start
```
----
### ✳️ OBTENER OTRO CODIGO QR EN TERMUX
> **Warning** deten el bot, haz click en el símbolo (ctrl) [default=z] usar la letra "z" + "ENTER" hasta que salga algo verdes similar a: `GataBot-MD $`
> Escribe los siguientes comando uno x uno :
```bash 
cd && cd GataBot-MD && rm -rf GataBotSession && npm run qr
```
----
### ✳️ OBTENER NUEVO CÓDIGO DE 8 DÍGITOS 
```bash 
cd && cd GataBot-MD && rm -rf GataBotSession && npm run code
```
----
### 😼 ACTUALIZAR GATABOT
> **Note** Comandos para actualizar GataBot-MD de forma automática
```bash
grep -q 'bash\|wget' <(dpkg -l) || apt install -y bash wget && wget -O - https://raw.githubusercontent.com/GataNina-Li/GataBot-MD/master/update.sh | bash 
```
#### Para que no pierda su progreso en GataBot, estos comandos realizarán un respaldo de su `database.json` y se agregará a la versión más reciente.
> **Warning** Estos comandos solo funcionan para TERMUX, REPLIT, LINUX                           
-----
### ☁️ CORINPLUS HOTS 
<a href="https://dash.corinplus.com"><img src="https://qu.ax/ZycD.png" height="125px"></a>
### Información sobre CorinPlus

- **Dashboard:** [`Aquí`](https://dash.corinplus.com)
- **Panel:** [`Aquí`](https://ctrl.corinplus.com)
- **Estado de servicios:** [`Aquí`](https://status.corinplus.com)
- **Canal de WhatsApp:** [`Aquí`](https://whatsapp.com/channel/0029VakUvreFHWpyWUr4Jr0g)
- **Grupo - Soporte:** [`Aquí`](https://chat.whatsapp.com/K235lkvaGvlGRQKYm26xZP)
- **Contacto:** [`Gata Dios`](https://wa.me/message/B3KTM5XN2JMRD1)
- **Contacto:** [`elrebelde21`](https://facebook.com/elrebelde21)

- [x] **Configuración** <details><summary>**Ajustes del Servidor - GataBot-MD**</summary><img src="https://telegra.ph/file/5ba9167b88400845635df.jpg"></details>
----
### 📦⛏️ BOXMINE HOST 
[![YouTube](https://img.shields.io/badge/BoxMine_Host-GataBot-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtu.be/Ko019wvu2Tc)

### 🟣 ACTIVAR EN HEROKU 
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/GataNina-Li/GataBotMD-Heroku) 
### 👇 Añada lo siguente al Buildpack: 
```bash
heroku/nodejs
```
```bash
https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest.git
```
```bash
https://github.com/clhuang/heroku-buildpack-webp-binaries.git
```
- [x] Resultado <details><summary>Buildpack</summary><img src="https://i.imgur.com/t3Xzgnh.jpeg"></details>
-----

### ⚡ REPLIT - GATABOT
[![blog](https://img.shields.io/badge/Replit-GataBotMD-FF0000?style=for-the-badge&logo=youtube&logoColor=white)
](https://youtu.be/pQYkq4xv37o)

<a target="_blank" href="https://replit.com/github/GataNina-Li/GataBot-MD"><img alt="Run on Replit" src="https://binbashbanana.github.io/deploy-buttons/buttons/remade/replit.svg"></a> <a href="https://replit.com/github/GataNina-Li/GataBot-MD"> <img src="https://media0.giphy.com/media/lMwu8EJAnv9kmn51KQ/giphy.gif" height="29px"></a>

- [x] Configuración <details><summary>Importar Repositorio - GataBot-MD</summary><img src="https://i.imgur.com/GQyRnMf.jpg"></details>
----
### 🌌 **ACTIVAR EN CODESPACE**

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://github.com/codespaces/new?skip_quickstart=true&machine=basicLinux32gb&repo=GataNina-Li/GataBot-MD&ref=main&geo=UsEast)

----- 
### ⏏️ **ACTIVAR EN KOYEB**
[![Deploy to Koyeb](https://binbashbanana.github.io/deploy-buttons/buttons/remade/koyeb.svg)](https://app.koyeb.com/deploy?type=git&repository=github.com/GataNina-Li/GataBot-MD&branch=master&name=gatabot-md)

------------------
### ☁️ ACTIVAR EN RENDER 
[![Deploy to Render](https://binbashbanana.github.io/deploy-buttons/buttons/remade/render.svg)](https://dashboard.render.com/blueprint/new?repo=https%3A%2F%2Fgithub.com%2FGataNina-Li%2FGataBot-MD)

------------------
## 💻 PARA USUARIOS DE WINDOWS/VPS/RDP

* Descargar e instala Git [`Aquí`](https://git-scm.com/downloads)
* Descargar e instala NodeJS [`Aquí`](https://nodejs.org/en/download)
* Descargar e instala FFmpeg [`Aquí`](https://ffmpeg.org/download.html) (**No olvide agregar FFmpeg a la variable de entorno PATH**)
* Descargar e instala ImageMagick [`Aquí`](https://imagemagick.org/script/download.php)
* Descargar e instala Yarn [`Aquí`](https://classic.yarnpkg.com/en/docs/install#windows-stable)
```bash
git clone https://github.com/GataNina-Li/GataBot-MD && cd GataBot-MD && npm install && npm update && node .
```
## 💻 Instalación de FFmpeg para Windows 
* Descarga cualquiera de las versiones de FFmpeg disponibles haciendo clic en [FFmpeg](https://www.gyan.dev/ffmpeg/builds/).
* Extraer archivos a `C:\` path.
* Cambie el nombre de la carpeta extraída a `ffmpeg`.
* Ejecute el símbolo del sistema como administrador.
* Ejecute el siguiente comando:
```cmd
> setx /m PATH "C:\ffmpeg\bin;%PATH%"
```
Si tiene éxito, le dará un mensaje como: `SUCCESS: specified value was saved`.
* Ahora que tiene FFmpeg instalado, verifique que funcionó ejecutando este comando para ver la versión:
```cmd
> ffmpeg -version
```
----
### DISTRIBUIDORES AUTORIZADOS O RESELLERS - PREGUNTAS 
<details>
<summary><b>¿Te gustaría ser un Distribuidores Autorizados o reseller de GataBot?</b></summary>
  
- ¡Contáctanos **[correo electrónico](centergatabot@gmail.com)** o **[Telegram](https://t.me/SoporteGataBot)** para solicitar tu [**Licencia**](https://github.com/GataNina-Li/GataBot-MD/blob/master/terms.md)!
</details>

<details>
<summary><b>¿Qué significa ser un Distribuidor Autorizado o reseller en GataBot?</b></summary>
  
- Aquellos usuarios que adquieran la licencia de Distribuidores Autorizados o resellers obtienen el derecho legal de utilizar este repositorio para fines educativos, políticos o comerciales, sin poner en riesgo su reputación personal u organizacional.
</details>

<details>
<summary><b>¿Dónde puedes solicitar la licencia para ser Distribuidor Autorizado o reseller de GataBot?</b></summary>

  - Te ofrecemos opciones exclusivas: **[Instagram](https://www.instagram.com/gata_dios/)**, **[Telegram](https://t.me/SoporteGataBot)**, y **[correo electrónico](centergatabot@gmail.com)**.
</details>

<details>
<summary><b>¿Cómo puedo verificar quién es un distribuidor autorizado en GataBot?</b></summary>

  - Lo hemos simplificado para ti. Si deseas conocer la lista y contactar al reseller para verificar su autenticidad, simplemente visita este **[enlace](https://github.com/GataNina-Li/GataBot-MD/blob/master/dealers.md)**. La licencia debe estar disponible públicamente en el repositorio del distribuidor, y si tanto su nombre de usuario en GitHub como el código de la licencia coinciden con nuestra lista, significa que está **[verificado](https://github.com/GataNina-Li/GataBot-MD/blob/master/terms.md)** como parte de resellers de GataBot. **¡Estamos aquí para garantizar transparencia y calidad en nuestra red de distribución!**
</details>

> Recuerda leer la **[Política de GataBot. 😼](https://github.com/GataNina-Li/GataBot-MD/blob/master/terms.md)** antes de hacer algo con este repositorio. 
  
----
### 💠 [`IDIOMAS DISPONIBLES PARA GATABOT`](https://github.com/GataNina-Li/GataBot-MD/blob/master/config.js) 
#### 🌐 Español  
#### 🌐 Inglés (English) 
#### 🌐 Portugués (Português)
#### 🌐 Indonesio (Bahasa Indonesia) 
#### 🌐 Árabe (عرب)
#### 🌐 Hindi (Indian Language)
- [x] Ejemplo <details><summary>Idioma</summary><img src="https://i.imgur.com/ZTwOGkT.jpg"></details>
----

### 🌟 DESARROLLADORES
<a href="https://github.com/GataNina-Li/GataBot-MD/graphs/contributors">
<img src="https://contrib.rocks/image?repo=GataNina-Li/GataBot-MD" /> 
</a>

### 🌟 AGRADECIMIENTOS
[![TheShadowBrokers1](https://github.com/BrunoSobrino.png?size=60)](https://github.com/BrunoSobrino) 

### 🌟 CREADORA 
[![GataNina-Li](https://github.com/GataNina-Li.png?size=100)](https://github.com/GataNina-Li) 
> Copyright (c) 2024 **[GataNina-Li](https://github.com/GataNina-Li/GataBot-MD/blob/master/LICENSE)**.
