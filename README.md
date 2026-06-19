# Challenge Amigo Secreto 🎁🎲

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)

Esta es una aplicación web interactiva desarrollada como parte del desafío (Challenge) del programa **ONE (Oracle Next Education)** en conjunto con **Alura Latam**. El objetivo del proyecto es poner en práctica conocimientos fundamentales de lógica de programación y manipulación del DOM mediante JavaScript.

La aplicación permite a los usuarios ingresar los nombres de sus amigos en una lista dinámica para posteriormente realizar un sorteo aleatorio y determinar quién es el **"Amigo Secreto"**.

## 🚀 Características del Proyecto

- **Añadir nombres de forma dinámica:** Permite capturar los nombres ingresados por el usuario mediante un campo de texto y un botón interactivo.
- **Validaciones de entrada:** El sistema valida que el campo de texto no esté vacío y previene la inserción de datos inválidos o espacios en blanco innecesarios.
- **Renderizado de lista en tiempo real:** Los nombres agregados se muestran inmediatamente en una lista en pantalla mediante la manipulación dinámica de nodos HTML.
- **Sorteo aleatorio transparente:** Utiliza algoritmos nativos de JavaScript (`Math.random()` y `Math.floor()`) para seleccionar de forma justa un único nombre de la lista de participantes.
- **Interfaz intuitiva y responsiva:** Diseño visual limpio, moderno y adaptable que asegura una excelente experiencia tanto en computadoras como en dispositivos móviles.

## 🛠️ Tecnologías Utilizadas

- **HTML5:** Estructura semántica del sitio web.
- **CSS3:** Estilos visuales personalizados, tipografías y maquetación adaptada.
- **JavaScript (Vanilla JS):** Lógica del negocio, captura de eventos, validaciones y actualización dinámica de la interfaz.

## ⚙️ Estructura del Repositorio

El repositorio está estructurado de la siguiente manera:
```bash
├── index.html        # Archivo principal de la estructura HTML.
├── style.css         # Archivo de estilos con el diseño visual del challenge.
├── app.js            # Archivo de lógica en JavaScript (controlador del DOM y sorteo).
└── assets/           # Carpeta con recursos gráficos (imágenes, iconos, etc.).



## Puntos clave del desarrollo en JAVASCRIPT

![image](https://github.com/user-attachments/assets/9338ec92-dfe6-40ee-a116-ce0d32404505)

Se creo una lista vacía llamada "amigos". Esta lista se utilizará para almacenar los nombres de las personas que participarán en el sorteo del amigo secreto.

![image](https://github.com/user-attachments/assets/911d2c22-ab0e-49f1-a97f-e31891ee6600)


Esta parte del codigo obtiene el nombre del amigo que el usuario ha escrito en un campo de texto en la página web y
verifica si el nombre está vacío. Si lo está, muestra una alerta pidiendo al usuario que ingrese un nombre.
Si el nombre no está vacío, lo añade al final de la lista "amigos" ademas borra el nombre del campo de texto
para que el usuario pueda ingresar otro nombre y tambien Llama a la función "actualizarListaAmigos" para
mostrar la lista de amigos actualizada en la página.

![image](https://github.com/user-attachments/assets/61d18d15-6db7-4744-abe1-59d1ddc05422)

Esto obtiene el elemento de la página web donde se mostrará la lista de amigos,
ademas que permite borrar todo el contenido anterior de esa lista,
recorre la lista "amigos", para cada nombre, crea un nuevo elemento de lista (un "li").
esto permite poner el nombre del amigo dentro del elemento de lista y
Añade el elemento de lista a la lista que se muestra en la página.

![image](https://github.com/user-attachments/assets/9277d005-490b-4b22-addc-3f99c3f8008f)

Por ultimo la parte de este codigo verifica si la lista "amigos" está vacía, si lo está,
muestra una alerta diciendo que no hay amigos para sortear. Si la lista no está vacía,
genera un número aleatorio que se utiliza para seleccionar un amigo al azar de la lista.
Obtiene el nombre del amigo seleccionado y muestra el nombre del amigo secreto.
