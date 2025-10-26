# Tarea 19
En esta tarea tuvimos que hacer un programa que contara la cantidad de vocales que tenía un texto o frase.

Lo primero que tenemos que hacer es declarar la variable compartida, que en este caso es `private static int total = 0;`, y el lock, `private static final Object locked = new Object();`

Después, tenemos que crear la clase donde creamos las variables texto, ` private String texto;` y vocal, `private char voca;`. Ahora, dentro de esta misma clase, podemos introducir el código para el hilo en donde tendremos que crear otra variable, contador, para que el programa pueda contar las vocales.

Por último, en el main, ya podremos instanciar la función `Scanner sc = new Scanner(System.in);` para poder introducir el texto que queramos y, también, definir los hilos.

El programa final quedaría así:

<img width="597" height="1328" alt="Captura de pantalla 2025-10-26 163515" src="https://github.com/user-attachments/assets/886e737c-e2b3-4a12-9df6-d955c7ab6db7" />

Y estos son los resultados, uno con el texto en minúsculas y el otro con el texto en mayúsculas:

<img width="338" height="310" alt="Captura de pantalla 2025-10-26 163550" src="https://github.com/user-attachments/assets/276a389e-53f3-4e55-8b6c-7f71cdaf7aa5" /> <img width="289" height="309" alt="Captura de pantalla 2025-10-26 163611" src="https://github.com/user-attachments/assets/f93edc8a-dae7-4ea6-998f-96aaac6221f1" />

