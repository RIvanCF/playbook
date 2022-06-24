# Weekly Mission 1
## Primeros codigos en JS 👨🏻‍💻

<details>
  <summary> 0. Hola mundo ✅ </summary>
  
  ![Hola mundo](https://user-images.githubusercontent.com/99302791/170813868-1a5d2658-2ba2-4c79-9244-faccc0724f85.png)
  
  ### Ejercicio 💻
  > En esta practica de introducción, creé un documento js cuyo contenido es el siguiente. 
  
  ``` js
  console.log("Hola LaunchX desde Node JS")
  ```
  
  ### Resultado 📑
  A la hora de ejecutar el codigo, la consola imprime lo siguiente
  ![Hola mundo_1](https://user-images.githubusercontent.com/99302791/170814378-bbc2e331-8d0a-403f-9dd7-9daf3badd0a9.png)
  
  ### Evidencia 🔗
  <a href="https://github.com/RIvanCF/playbook/blob/main/weekly_mission_1/hello.js"><img src="https://img.shields.io/badge/Practica%200-Hola-green"></a>
  
  ### Video 🎥
  
  ![test](https://user-images.githubusercontent.com/99302791/170816459-960dd58c-b7cb-4e9f-8de3-2c046988c291.gif)

</details>

<details>
  <summary> 1. 🪐 Codigo 1: Objetos de JS</summary>
  
  ### Ejercicio 💻
  > 1. Crea una carpeta llamada "example1" dentro de la carpeta "weekly_mission_1".
  > 2. Copia el contenido y crea una archivo llamado "main. js" dentro de esta carpeta. 
  > 3. Ejecuta el siguiente comando: `node main.js`
  > 4. Este código tambien puede ser probado desde la consola de JavaScript del navegador. 
  
`main.js`
  ```javascript
// 1. Creación de un objeto con propiedades
  
let myCar = new Object(); // Creación de un objeto
myCar.make = 'Ford'; // Guardando un valor dentro del objeto creado
myCar.model = 'Mustang';
myCar.year = 1969;
  
console.log(myCar) // Imprimiendo objeto
  
// 2. Declaración de un objeto con variables locales y públicas
const myModule = (() => {
  
// Variables de contexto local
  const privateFoo = "Soy un valor privado, solo me usan dentro de este objeto"
  const privateBar = [1,2,3,4]
  const baz = "Soy un valor que va a ser expuesto"
  
// Variable para guardar las variables locales
  const exported = {
    publicFoo: "Valor público, pueden verme desde donde me llamen",
    publicBar: "Otro valor público",
		publicBaz: baz
  }
  
// Exposición de variables locales
  return exported
})()
  
console.log(myModule)
 ```

### Código 
  
  ![Codigo_1 1_LaunchX](https://user-images.githubusercontent.com/99302791/175697987-26c0fc5f-358b-406e-b2b6-b882f1da53a9.png)
  
### Resultados 
  
![Codigo_1 1_LaunchX_1](https://user-images.githubusercontent.com/99302791/175698657-fe68ab89-282e-4ea8-adca-91fe19d23dc1.png)

  
  
