# DevelopmentGame
VideoGame template for The Space Wealth

![image](./GitHubPhoto.png
)


**Los jugadores exploran galaxias pagando energía para descubrir planetas con recursos y rarezas únicas.
Encuentran planetas comunes, raros y legendarios con diferentes beneficios.**

Colonización y Gestión:

Los planetas se adquieren como _NFTs_ y generan recursos con el tiempo.
Pueden acelerar la producción de recursos pagando con Vara.
Comercio en Marketplace:

Intercambio de planetas, recursos y skins como NFTs.
Comisiones del _2-5%_ por cada transacción.
Eventos Temporales:

Participación en misiones o campañas como "La Nube de Oort," que desbloquean planetas raros y contenido exclusivo.
Sistema de Energía:

Explorar y acelerar procesos requiere energía, que puede recargarse lentamente o comprarse con Vara.
Recompensas y Staking:

Gastar Vara otorga beneficios como NFTs exclusivos, descuentos y acceso prioritario.
Los jugadores pueden hacer staking de Vara para reducir costos y obtener recompensas pasivas.
Personalización:

Mejoras y skins para naves adquiridas como NFTs, que aumentan la eficiencia y personalización.
Competencia:

Clasificación global basada en planetas, recursos y NFTs.
Fomentar rivalidades con clanes o rankings.



Dentro de https://polkadot.js.org/apps/ se llevará a cabo el registro de cuenta y deberás guardar las siguientes cosas:
1. Descargar Polkadot JS extensión para chrome o Firefox.
2. Hacer cuenta de Polkadot JS desde la extensión para Chrome/Firefox
3. Guardar el Seed Password Key
4. Guardar Usuario y contraseña.
5. Conectar Wallet a https://idea.gear-tech.io/programs?node=wss%3A%2F%2Ftestnet.vara.network para tramitar Gas
6. Dentro de la página de Gear Cambiar a Vara Testnet.
7. Dentro de la página de Gear conectar Wallet y hacer petición de gas.
8. El gas que viene incluido con la Vara testnet es de 100 transferable Balance
Para comenzar a crear contratos inteligentes se necesita de:


I. Instalación del compilador Rust o utilizar Gitpod e instalar el Compilador de Rust.
Para un entorno Windows se necesita utilizar powershell, es recomendable utilizar Powershell Core. Para instalar Powershell Core porfavor sigue los pasos en el siguiente link: https://youtu.be/sQm4zRvvX58?list=PLlVtbbG169nFq_hR7FcMYg32xsSAObuq8.


II. Una vez con powershell instalado se deberá instalar la herramienta chocolatey desde powershell. Utilizar el siguiente tutorial: https://chocolatey.org/install.


III. Para instalar Rust deberemos utilizar chocolatey. Los pasos para instalar Rust debemos hacer lo siguiente:
    III.0 Abrir la terminal Powershell.
    III.I ```choco install rust```


IV. Comprobaremos la installación de Rust con los siguientes comandos desde powershell.
    IV.0 ```rustc --version```
    IV.I ```cargo --version``` 


V. Los contratos inteligentes se pueden programar desde rust con la herramienta WebPack. Para instalar webpack desde un entorno de windows con powershell se deberá definir un compilador gcc y una herramienta cc.exe
    Para vincular Rust con GCC utilizaremos lo siguiente:
    V.0 Instalar mingw-w64-x86_64-toolchain con UCRT-64. 
           ```pacman -S --needed git base-devel mingw-w64-x86_64-toolchain.```
    V.I Vincular MSYS con "Git for Windows"
