## Herramientas de desarrollo

**1.** Ejecuta el programa "Hola mundo" en los siguientes lenguajes:

- bash

  ```bash
  #!/bin/bash
  echo` `Hola Mundo!
  ```

- python

  ```py
  print("¡Hola, mundo!")
  ```

- php

  ```php+HTML
  <html> 
  	<head> 
  		<title>Prueba de PHP</title> 
  	</head> 
  	<body> 
  		<?php echo '<p>Hola Mundo</p>'; ?> 
  	</body>
  </html>
  ```

- javascript (nodejs)

  ```js
  <html>
  	<head>
  		<title>Mi primer codigo JavaScript</title>
   	</head>
      <body>
      	<h1>Mi primer código JavaScript</h1>
      	<script>
        	document.write("Hola Mundo");
      	</script>
    	</body>
  </html>
  ```

  

- C

  ```c
  /* Programa: Hola mundo */ 
  #include <conio.h> 
  #include <stdio.h> 
  int main() 
  {    
  printf( "Hola mundo." );     
  getch();     
  return 0; }
  ```

- C++

  ```c++
  #include <iostream>
   
  int main () 
  {
      std::cout << "Hola, mundo";
      return 0;
  }
  ```

- java

  ```java
  class holaMundo
  {
      public static void main(String args[])
      {
          System.out.println("Hola Mundo");
      }
  }
  ```
  
- ruby

  ```ruby
  ruby -e 'print "Hola Mundo\n"'
  ```

- go

  ```go
  package main
  
  import "fmt"
  
  func main() {
  
    fmt.Println("Hola Mundo")
  
  }
  ```

  

- rust

  ```rust
  fn main() {
      println!("¡Hola, mundo!");
  }
  ```

- lisp

  ```lisp
  (print "Hola Mundo!")
  ```

**2.** Para cada uno de los lenguajes anteriores,  indica el proceso realizado para conseguir ejecutar el código:  ¿compilación o interpretación?

- bash  >  interpretación 
- python  >  interpretación 
- php  >  interpretación 
- javascript (nodejs)  >  interpretación 
- C  >  compilación 
- C++  >  compilación 
- java  >  compilación 
- ruby  >  interpretación 
- go  >  compilación 
- rust  >  compilación 
- lisp  >  interpretación 
- ensamblador (nasm)  >  compilador cruzado 

**3.** Para cada uno de los lenguajes anteriores, indica el nombre del compilador o interprete utilizado en GNU/Linux.

- bash  >  SCRIPTS
- python  >  CPYTHON 
- php  >  NETBEANS 
- javascript (nodejs)  >  GCC 
- C  >  GCC 
- C++  >  GCC 
- java  >  JAVAC
- ruby  >  compilador JIT 
- go  >  GO BUILD 
- rust  >  RUSTC
- lisp  >  CAR/ CDR
- ensamblador (nasm)  >  GCC 

**4.** Investiga y averigua que extensión tienen los archivos de código fuente de los siguientes lenguajes:

- bash = .sh
- python = .py
- php = .php
- javascript = .js
- C = .c
- C++ = .cpp
- java = .java
- ensamblador (nasm) = .asm
- ruby = .rb
- go = .go
- rust = .rs
- lisp= .lisp

**5.** Scripts ejecutables para los lenguajes interpretados. Edita los scripts para los siguientes lenguajes:

- bash

```
#!/bin/bash
echo` `Hola Mundo!
```

- python

```
print("¡Hola, mundo!")
```

- php

  ```
  <html> 
  	<head> 
  		<title>Prueba de PHP</title> 
  	</head> 
  	<body> 
  		<?php echo '<p>Hola Mundo</p>'; ?> 
  	</body>
  </html>
  ```

- javascript

  ```
  <html>
  	<head>
  		<title>Mi primer codigo JavaScript</title>
   	</head>
      <body>
      	<h1>Mi primer código JavaScript</h1>
      	<script>
        	document.write("Hola Mundo");
      	</script>
    	</body>
  </html>
  ```

- java

  ```
  class holaMundo
  {
      public static void main(String args[])
      {
          System.out.println("Hola Mundo");
      }
  }
  ```

- ruby

  ```
  ruby -e 'print "Hola Mundo\n"'
  ```

- go

  ```
  package main
  
  import "fmt"
  
  func main() {
  
    fmt.Println("Hola Mundo")
  
  }
  ```

- rust

  ```
  fn main() {
      println!("¡Hola, mundo!");
  }
  ```

- lisp

  ```
  (print "Hola Mundo!")
  ```

**6.** ¿Qué extensión tienen los archivos de código objeto?

- Los archivo la de código objeto tiene extensión `.obj` 

**7.** Lenguaje C. Código en varios archivos. Obtener el código objeto a partir del código fuente de los 3 archivos siguientes:

```lang-c
//-------------
// datos.c
//-------------

char *mensaje="Hola a todos y todas";
int  num1 = 8;
int  num2 = 10; 
```

```lang-c
//-------------
// suma.c
//-------------

int suma (int a, int b) {
  return a + b;
}
```

```lang-c
//-------------
// main.c
//-------------

/#include <stdio.h>

int suma (int a, int b);

extern char *mensaje;
extern int  num1, num2;

int main(){
  printf("%s\n", mensaje);
  printf("%d\n", suma (num1, num2) );
  return 0;
}
```

**8.** Lenguaje C. Código en varios archivos. Obtener  el código binario ejecutable a partir del código objeto de los 3  archivos anteriores:

- Debemos obtener un archivo `programa` binario ejecutable. Si lo ejecutamos obtenemos el siguiente resultado:

```lang-c
./programa
Hola a todos y todos
20
```

## Bibliotecas

**11.** Bibliotecas. Define que se entiende por biblioteca o librería y los tipos que existen.

- En este sentido, una biblioteca o librería es un conjunto de archivos que se utiliza para desarrollar software. Suele estar compuesta de  código y datos, y su fin es ser utilizada por otros programas de forma  totalmente autónoma.  
- Biblioteca estática. 
- Bibliotecas dinámica.

**12.** Bibliotecas. ¿Qué tipo es el más utilizado actualmente? ¿Por qué?

- La más utilizada son las bibliotecas dinámicas (.DLL o .so) (.jar en  Java). Ejemplos de librerías más usados: JavaScript, C++ y Python. Porque facilitan la gestión y aprovechamiento de la memoria del sistema. Permite al sistema operativo aplicar algoritmos que mejoren el  rendimiento del sistema cuando se carguen estas bibliotecas. Además, al  estar compartidas, basta con mantener una copia en memoria para todos  los programas que la utilicen.

**13.** Bibliotecas. Crea una biblioteca dinámica en C  que proporcione  las funciones para sumar, restar, multiplicar y dividir 2 números  enteros. Crea un programa que haga uso de ella y comprueba  que se ejecuta  correctamente.

```
int suma (int sumando1, int sumando2);

int resta  (int minuendo, int sustraendo);

int multiplicacion (int  numero1, int numero2);

float division (int dividendo, int divisor);
```

**14.** Bibliotecas. Crea una biblioteca dinámica en  Java que proporcione las funciones para sumar, restar, multiplicar y  dividir 2 números  enteros. Crea un programa que haga uso de ella y  comprueba que se ejecuta  correctamente.

```
int suma (int sumando1, int sumando2) {
	return (sumando1+sumando2);
}


int resta  (int minuendo, int sustraendo) {
	return (minuendo-sustraendo);
}


int multiplicacion (int  numero1, int numero2) {
	return (numero1*numero2);
}


float division (int dividendo, int divisor) {
	return (dividendo/(float)divisor);
}
```

**15.** Bibliotecas. Busca información y explica las ventajas y desventajas de usar bibliotecas estáticas.

- *Ventaja*: - No es necesario proporcionar las bibliotecas correspondientes al publicar el programa. - Biblioteca de carga rápida.

- *Desventaja*:  - La biblioteca está empaquetada en la aplicación, lo que resulta en una gran biblioteca. - La biblioteca ha cambiado y es necesario volver a compilar el programa.

**16.** Bibliotecas. Busca información y explica las ventajas y desventajas de usar bibliotecas dinámicas.

- *Ventajas*: 1. La programación se centra completamente en la esencia del diseño del  programa, se mejora la simplicidad del código y la eficiencia del  desarrollo. 2. Debido a que la escala del programa se reduce, la inteligibilidad del programa también se mejora.

- *Desventajas*: 1. La velocidad de ejecución del programa es lenta debido al lenguaje de tipo dinámico, la verificación de tipo se realiza en tiempo de  ejecución.  2. No se pueden detectar errores sin ejecución. 

