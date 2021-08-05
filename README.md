Este repositorio contiene una parte del flow 3 y 4 visto en clase , ejercicio de Introducción a NodeRed. Flow 4 permite enviar información al dash del profesor flow 3 permite recibirla.

# flow003-temperatura-grupal-01

-Muestra la información dash del profesor

-La información se tiene que enviar en formato JSON con las variables: `ID, Temp, mnsg` para poder ser visualizada correctamente

![prueba samsung 1](https://user-images.githubusercontent.com/71236850/128286405-6d6a29e1-e3fd-403e-9a25-4684839887e3.png)

![prueba samsung 3](https://user-images.githubusercontent.com/71236850/128286545-5832d27a-728e-4412-aa9f-010ce10b0650.png)

![image](https://user-images.githubusercontent.com/71236850/127755195-930992cb-d5d3-4418-8f13-37bc4ec3eb09.png)

# flow004-temperatura-grupal-01

-Envia un mensaje a `codigoIoT/SIC/flow3/temp`

-La información se envía en formato JSON con las variables: `ID, Temp, mnsg`

-La variable Temp se genera de forma aleatoria, el código se encuentra en `functionNodes/random-Temp-function.txt`

![prueba samsung 2](https://user-images.githubusercontent.com/71236850/128286435-2b5ff424-442e-4cd4-b86b-ad1e004f09c9.png)
