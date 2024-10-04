# pryAsanaHub
<h3> DESCRIPCIÓN </h3>
Repositorio que aloja la información sobre la gestion del proyecto de la app movil (tareas definidas en Asana &amp; codigo desarrollado). Trina 1 10B - TI (Alvaro, Josue, Jaime).


<h3> OBJETIVOS </h3>
- Mantener alojado el codigo del proyecto y en constante revision para minimizar errores de codificación.
- Comunicar los issues que se crean al gestionar las tareas nuevas para el desarrollo del proyecto desde la herramineta de gestion (Asana)


<h3> METODOLOGÍA </h3>
Se selecciono la metodologia XP debido a que se tienen requisitos cambiantes, entregas rápidas de valor, donde se valora la retroalimentación constante y se buscan prácticas que promuevan la mejora continua.


<h3> HERRAMIENTA DE CONTROL DE VERSIONES & FLUJO DE TRABAJO </h3>
Se elegio github como controlador de versiones con un flujo de trabajo de integracion continua, este garantiza que el código sea estable y sin errores a través de pruebas automatizadas.


<h3> ESTRATEGIA DE VERSIONAMIENTO Y GESTION DE RAMAS </h3>
Se utiliza el versionado continuo (Rolling Release), en el que el software se actualiza continuamente, por lo que siempre se tiene la versión más reciente sin grandes lanzamientos. Sera a través de la rama master o main donde alojaremos el código correspondiente a los avances del proyecto móvil, para que cada usuario sea capaz de acceder y modificar, siendo este notificado para su consulta.


<h3> CLONACION DEL REPOSITORIO </h3>
Para clonar este repositorio en su máquina local, siga estos pasos:
1. Abra su terminal o símbolo del sistema.
2. Navega hasta el directorio donde quieres clonar el proyecto.
3. Ejecute el siguiente comando:
   "git clone https://github.com/JaimeBC0646/pryAsanaHub"


<h3> INSTALACION DE DEPENDENCIAS </h3>
Si se descarga este repositorio se debe eliminar el archivo "package.json", y utilizar el comando "npm install", este se encargara de reinstalar las dependencias necesarias para poder correr el proyecto.


<h3> EJECUCION DEL PROYECTO </h3>
Para poder correr el proyecto en modo de desarrollador se utiliza el comando "npx expo start"
Para construirlo se debe seguir una serie de pasos:
- Instalar Expo CLI: npm install -g expo-cli
- Instalar EAS CLI: npm install -g eas-cli
- Iniciar sesión en tu cuenta Expo: eas login
- Configurar tu proyecto para EAS Build: eas build:configure
- Generar el APK (Android): eas build --platform android

