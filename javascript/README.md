# Esqueleto para JavaScript

## Opciones para el esqueleto
A continuación se describen tres opciones diferentes para tener un entorno en el que realizar una kata en JavaScript:
1. Realizarla **online, a través de Codepen**. Para ello, sigue los siguientes pasos:
   * Ir a https://codepen.io/islomar/details/PKLbzx/
   * Haz click sobre "Fork"
   * Si ya tienes una cuenta, lógate. Si no, puedes clicar sobre "Save anonymously"
   * Enhorabuena: ¡ya tienes una copia del fichero base sobre la que puedes trabajar!
2. Si no quieres instalar nada en tu PC o tienes problemas de compatibilidad con el OS, puedes usar **Docker** de la siguiente manera (siempre y cuando lo tengas instalado):
   * Clónate/forkea este repo
   * Desde dentro del repo, ejecuta `docker run -v "$PWD":/root/workspace -t -i node:6.10 bash`
   * Ve al directorio `/root/workspace`
   * Desde ahí, puedes ejecutar el resto de pasos de este README
3. Realizarla en un **entorno local**. Para ello, tu entorno debe tener **node** y **npm** instalados.


## Instrucciones para las opciones 2 o 3 anteriores
1. Instalar todas las dependencias, ejecutando `npm install`
2. Ejecutar los tests:
   * Los tests deben guardarse bajo la carpeta /test, con sufijo **Spec.js**
   * `npm run test:watch`: ejecuta los tests en fondo, refrescándose automáticamente ante cambios
   * `npm run test`: ejecuta los tests una única vez
   * `npm run mocha`: ejecuta los tests y el feedback te lo da un gatete ^___^
