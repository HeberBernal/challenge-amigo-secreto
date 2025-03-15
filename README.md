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
Obtiene el nombre del amigo seleccionado y muestra el nombre del amigo secreto en la página web.
