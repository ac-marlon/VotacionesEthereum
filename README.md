
# Election - DAPP
Decentralized application, or Dapp, on the Ethereum Network

Siga los pasos a continuación para descargar, instalar y ejecutar este proyecto.

## Dependencias
Instalar los siguientes programas:
- NPM: https://nodejs.org
- Truffle: https://github.com/trufflesuite/truffle
- Ganache: http://truffleframework.com/ganache/
- Metamask: https://metamask.io/

## Abrir una terminal en la carpeta raíz del proyecto
```
$ cd election-project
$ npm install
```
## Ejecutar Ganache
Abrir el cliente GUI de Ganache descargado previamente. Esto iniciará una blockchain local.

## Compilar e implementar el "Smart Contract"
`$ truffle migrate --reset`
Debe migrar el "smart contract" de elección cada vez que reinicie Ganache.

## Configurar Metamask
- Desbloquear Metamask
- Conectar Metamask a la blockchain local creada con Ganache.
- Importar una de las cuentas proporcionadas por Ganache.

## Ejecutar la interfaz gráfica de la aplicación
`$ npm run dev`
Si no se abre automaticament eel navegador, ir a: http://localhost:3000

## NOTA: Si no aparece la lista de los candidatos, es probable que deba conectar manualmente la cuenta de Metamask (desde el panel de configuración) al sitio
