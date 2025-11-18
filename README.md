# Fundamentos del Lenguaje de Programación Java para Principiantes


## Resumen del Curso
Este curso tiene una duración de 1 hora y media, y tiene como objetivo introducir a estudiantes de secundaria a los fundamentos básicos de la programación con el lenguaje Java, incluyendo información básica del paradigma de la [Programación Orientada a Objetos (POO)](https://www.w3schools.com/java/java_oop.asp).

**Duración Total:** ~90 minutos
**Público Objetivo:** Estudiantes de 12 a 17 años sin experiencia en programación
**Pre-requisitos:** Ninguno
**Herramientas Necesarias:** Solo necesitas tu navegador web (Chrome, Brave, Firefox, Safari, Edge, etc).


## Secuencia de Lecciones

### Lección 1: Introducción a la Programación y al Lenguaje Java 
- **Descripción:** En esta lección, aprenderás qué es la programación y por qué Java es uno de los lenguajes más usados. Descubrirás cómo los programadores dan instrucciones a las computadoras, y cómo Java permite crear desde simples programas en consola hasta aplicaciones móviles y videojuegos.
- **Enlace del Video:** [¡Clic aquí!](https://youtu.be/uLt4VuX44PE)
### Bloques de Código: JAVA

- Introduccion programa "Hello World"

```Java

// Programa para imprimir "Hello world!"
public class Main {
  public static void main(String[] args) {
    System.out.println("Hello world!");
  }
}
```
- **Conclusiones:** Ahora comprendes que programar significa comunicarse con la computadora usando un lenguaje que esta entienda. Java es una puerta de entrada al mundo de la programación por su facilidad, potencia y gran comunidad. Ahora estás más que listo para escribir tu primer línea de código.
- **Empieza a Programar:** [¡Regístrate en Replit y comienza ahora!](https://replit.com/languages/java10)

### Lección 2: Sintaxis, Variables y Tipos de Datos 
- **Descripción:** Esta lección te enseña la estructura fundamental de un programa Java: clases, métodos y la función principal ```main```. También aprenderás a crear variables para guardar información y conocerás los tipos de datos básicos como enteros, decimales, texto y booleanos.
- **Enlace del Video:** [¡Clic aquí!](https://youtu.be/Os2uby36yKk)
### Bloques de Código: JAVA

- Variables y entidades

```Java

// Programa de Datos de estudiante
import java.util.Scanner;

public class Main {
  public static void main(String[] args) {

    // Crear un lector para datos
    Scanner input = new Scanner(System.in);

    // Pedir el nombre
    System.out.print("Escribe tu nombre: ");
    String nombre = input.nextLine();

    // Pedir la edad
    System.out.print("Escribe tu edad: ");
    int edad = input.nextInt();

    // Pedir la altura
    System.out.print("Escribe tu altura en metros (ejemplo 1.65): ");
    double altura = input.nextDouble();

    // Pedir si es estudiante
    System.out.print("¿Eres estudiante? (true/false): ");
    boolean estudiante = input.nextBoolean();

    // Mostrar datos guardados
    System.out.println("\n--- DATOS GUARDADOS ---");
    System.out.println("Nombre: " + nombre);
    System.out.println("Edad: " + edad);
    System.out.println("Altura: " + altura + " m");
    System.out.println("¿Es estudiante?: " + estudiante);

    input.close();
  }
}

```
- **Conclusiones:** Has aprendido cómo se organiza un programa en Java y cómo las variables te permiten almacenar distintos tipos de información. Ahora ya puedes crear pequeños programas que manipulen datos básicos y los muestren por pantalla.
- **Práctica:** Crea una tarjeta de presentación digital.

### Lección 3: Operadores y Expresiones 
- **Descripción:** En esta lección, aprenderás a cómo hacer que tus programas realicen cálculos y tomen decisiones simples. En esta lección aprenderás a usar operadores aritméticos, relacionales y lógicos, las herramientas que permiten que tu código “piense” y resuelva problemas.
- **Enlace del Video:** [¡Clic aquí!](https://youtu.be/biofxE3YZ00)
- **Conclusiones:** Comprendiste cómo combinar variables y operadores para crear expresiones matemáticas y lógicas. Con esto, tus programas ya pueden comparar, calcular y analizar condiciones de manera automática.

### Bloques de Código: JAVA

- Operadores Aritmeticos

```Java

public class Main {
  public static void main(String[] args) {

    int a = 10;
    int b = 5;

    System.out.println("Suma: " + (a + b));
    System.out.println("Resta: " + (a - b));
    System.out.println("Multiplicación: " + (a * b));
    System.out.println("División: " + (a / b));
    System.out.println("Módulo: " + (a % b));

    int resultado = (a + b) * 2;
    System.out.println("Resultado: " + resultado);
  }
}
```
- Operadores Relacionales
```Java

public class Main {
  public static void main(String[] args) {
    int x = 5;
    int y = 8;

    System.out.println(x > y);
    System.out.println(x < y);
    System.out.println(x == y);
    System.out.println(x != y);
    System.out.println(x >= y);
    System.out.println(x <= y);

  }
}
```
- Operadores Lógicos
```Java

public class Main {
  public static void main(String[] args) {

    int a = 10;
    int b = 5;
    int c = 8;

    System.out.println((a > b) && (b > c));
    System.out.println((a > b) || (b > c));
    System.out.println(!(a > b));

  }
}
```
- **Práctica:**

1. Declara dos números: `a = 15` y `b = 4`.  
Imprime la suma, resta, multiplicación, división y el módulo usando esos valores.

2. Declara dos variables: `x = 10` y `y = 12`.  
Imprime si `x` es mayor que `y`, si son iguales y si `x` es diferente de `y`.

3. Declara las siguientes variables:  
- `edad = 17`  
- `mayorDeEdad = 18`  
- `tienePermiso = true`

La persona puede entrar si:  

- es mayor o igual a 18 años, **o**  
- tiene un permiso.

Crea una condición lógica que verifique eso e imprime el resultado.

---
### Lección 4: Estructuras de Control Básicos 
- **Descripción:** En esta lección, verás cómo los programas pueden tomar decisiones (con las instrucciones: ```if``` y ```else```) y repetir acciones muchas veces (con: ```for``` y ```while```). Aprenderás a controlar el flujo del programa y crear comportamientos dinámicos y personalizados.
- **Enlace del Video:** [¡Clic aquí!](https://youtu.be/v3RVMqweLjU)
- **Conclusiones:** Has aprendido a controlar cómo y cuándo se ejecutan las instrucciones en tu programa. Gracias a las estructuras condicionales y los bucles, tus programas pueden reaccionar a distintas situaciones y automatizar tareas repetitivas.

### Bloques de Código: JAVA

- If y Else

```Java

public class Main {
  public static void main(String[] args) {

    int edad = 15;

    if (edad >= 18){
      System.out.println("Eres mayor de edad");
    } else {
      System.out.println("Eres menor de edad");
    }
      
  }
}
```

- If, Else if y Else

```Java

public class Main {
  public static void main(String[] args) {

    int nota = 14;

    if (nota >= 18){
      System.out.println("Excelente");
    } else if (nota >= 13) {
      System.out.println("Notable");
    } else {
      System.out.println("Desaprobado");
    }
      
  }
}
```

- Bucle for

```Java

public class Main {
  public static void main(String[] args) {

    for (int i = 1; i <= 5; i++){
      System.out.println("Iteración número: " + i);
    }
  }
}
```

- Bucle While

```Java

public class Main {
  public static void main(String[] args) {

    int contador = 1;

    while (contador <= 3) {
      System.out.println("Iteración número: " + contador);
      contador++;
    }
  }
}
```

- **Práctica:**

1. Declara una variable `temperatura = 30`

- Si la temperatura es mayor o igual a 25, imprime: "**Hace calor**"  
- De lo contrario, imprime: "**Hace frío**"


2. Declara una variable `puntos = 72` y evalúa el puntaje y muestra un mensaje:  

- Si es mayor o igual a 90 → "Nivel Alto"  
- Si es mayor o igual a 60 → "Nivel Medio"  
- Si es menor a 60 → "Nivel Bajo"


3. Usa un bucle `for` para imprimir los números del **1 al 30**.


4. Declara `contador = 5` y usa un `while` para imprimir el mensaje **"Cuenta regresiva"** hasta que llegue a 1.

---
### Lección 5: Métodos y Parámetros 
- **Descripción:** En esta lección, aprenderás a organizar tu código en bloques reutilizables llamados métodos. Entenderás cómo pasarles información (a través de parámetros) y cómo devolver resultados (con los llamados valores de retorno), haciendo tus programas más limpios, ordenados y eficientes.
- **Enlace del Video:** [¡Clic aquí!](https://www.youtube.com/watch?v=TpSX6KOj4Wc)
- **Conclusiones:** Ahora sabes cómo dividir un programa en partes más pequeñas y reutilizables. Las funciones te permiten escribir código más organizado y profesional, una habilidad esencial para cualquier programador.

### Bloques de Código: JAVA

- Método sin parametros (o `void`): Imprimir un mensaje en la consola.

```Java

import java.util.Scanner;

public class Main {
  public static void main(String[] args) {
    // Instanciando input
    Scanner input = new Scanner(System.in);

    // Llamando al metodo saludar
    saludar();
    
    input.close();
  }

  // Metodo saludar: Imprime un mensaje en consola
  public static void saludar() {
    System.out.println("Hola, Usuario");
  }
}
```

- Método con Parámetro: Deletreador de palabras

```Java

import java.util.Scanner;

public class Main {
  public static void main(String[] args) {
    // Instanciando input
    Scanner input = new Scanner(System.in);

    // Solicitando al usuario que ingrese una palabra
    System.out.print("Ingrese una palabra: ");
    // Guardando la palabra en una variable
    String palabra = input.nextLine();

    // Llamando al metodo deletrear
    // y pasandole la varable palabra como parametro
    deletrear(palabra);
    
    input.close();
  }

  public static void deletrear(String palabra) {
    for (int i = 0; i < palabra.length(); i++) {
      System.out.println("Letra " + (i + 1) + ": " + palabra.charAt(i));
    }
  }
}
```

- Métodos de Retorno con Parámetros: Operaciones matemáticas básicas

```Java

import java.util.Scanner;

public class Main {
  public static void main(String[] args) {
    // Instanciando input
    Scanner input = new Scanner(System.in);

    // Llamando e imprimiendo los valores
    // de las funciones de matematicas
    System.out.println("Suma: " + sumar(20, 30));
    System.out.println("Resta: " + restar(50, 20));
    System.out.println("Multiplicacion: " + multiplicar(15, 5));
    System.out.println("Division: " + dividir(105, 25));
    
    input.close();
  }

  // Funcion Sumar: Retorna Entero (int)
  public static int sumar(int a, int b) {
    return a + b;
  }

  // Funcion Restar: Retorna Entero (int)
  public static int restar(int a, int b) {
    return a - b;
  }

  // Funcion Multiplicar: Retorna Entero (int)
  public static int multiplicar(int a, int b) {
    return a * b;
  }

  // Funcion Dividir: Retorna Decimal (double)
  public static double dividir(int a, int b) {
    return a / b;
  }
}
```

- **Prácticas:**

1. Declara un método que devuelva el factorial de un número.
2. Declara un método que imprima los carácteres de una palabra al revéz.

---
### Lección 6: Introducción a la Programación Orientada a Objetos (POO) 
- **Descripción:** En esta lección, entrarás al mundo de la Programación Orientada a Objetos (POO), el paradigma que define al lenguaje Java. Aprenderás qué son las clases, los objetos y los constructores, y cómo representar personas, animales o cosas del mundo real dentro del código.
- **Enlace del Video:** [¡Clic aquí!](https://www.youtube.com/watch?v=-3r9lpholr4)
- **Conclusiones:** Ahora, ya entiendes el concepto clave de la POO: usar clases y objetos para modelar el mundo real. Has aprendido a crear tus propias clases y darles atributos y comportamientos, lo que te permitirá construir programas más organizados y potentes.
- **Práctica:**

```Java

import java.util.Scanner;

class Mascota {
  public String nombre;
  public String especie;
  public int edad;

  public Mascota(String nombre, String especie, int edad) {
    this.nombre = nombre;
    this.especie = especie;
    this.edad = edad;
  }

  public void dormir() {
    System.out.println(this.nombre + " esta durmiendo.");
  }

  public void comer() {
    System.out.println(this.nombre + " esta comiendo.");
  }

  public String informacion() {
    return "Nombre: " + this.nombre + ", Especie: " + this.especie + ", Edad: " + this.edad;
  }
}

public class Main {
  public static void main(String[] args) {
    // Instanciando input
    Scanner input = new Scanner(System.in);

    Mascota mascota1 = new Mascota("Firulais", "Perro", 2);
    Mascota mascota2 = new Mascota("Bojangles", "Gato", 3);

    mascota1.dormir();
    mascota1.comer();
    
    System.out.println("");
    
    mascota2.dormir();
    mascota2.comer();

    System.out.println("");

    String informacionMascota1 = mascota1.informacion();
    String informacionMascota2 = mascota2.informacion();

    System.out.println(informacionMascota1);
    System.out.println(informacionMascota2);
    
    input.close();
  }
}

```

---
### Lección 7: Encapsulación, Getters y Setters
- **Descripción:** En esta lección, aprenderás el principio de la encapsulación, que protege los datos dentro de las clases. Verás cómo usar modificadores de acceso (como ```private``` y ```public```) y métodos especiales (conocidos como _getters_ y _setters_) para acceder a la información de forma segura.
- **Enlace del Video:** [¡Clic aquí!](https://youtu.be/3BER3fadKis)
- **Conclusiones:** Ahora comprendes cómo proteger los datos de tus clases y controlar su acceso. La encapsulación te ayuda a mantener tu código más seguro, limpio y fácil de mantener, siguiendo buenas prácticas de la POO.
- **Práctica:**

```Java

class Persona {
    private int edad;      // Propiedad privada (encapsulada)
    private String nombre; // Propiedad privada

    // Constructor
    public Persona(String nombre, int edad) {
        this.nombre = nombre;
        this.edad = edad;
    }

    // Getter
    public int getEdad() {
        return edad;
    }

    // Setter con validación
    public void setEdad(int nuevaEdad) {
        if (nuevaEdad > 0) {
            this.edad = nuevaEdad;
        }
    }

    public String getNombre() {
        return nombre;
    }
}

```




---
### Lección 8: Arrays y Cadenas
- **Descripción:** En esta lección, aprenderás a trabajar con colecciones de datos mediante _arrays_, ideales para almacenar varios valores a la vez (como una lista de notas). Además, practicarás con métodos útiles de la clase _String_ para manipular texto.
- **Enlace del Video:** [¡Clic aquí!](https://youtu.be/q2-fReLv38I)
- **Conclusiones:** Ahora sabes cómo guardar y recorrer múltiples valores dentro de un arreglo, y cómo trabajar con cadenas de texto en Java. Este conocimiento será clave para crear cadenas más complejas y dinámicas.
- **Práctica:**

```Java


class Leccion8 {

    public static void ejecutar() {

        System.out.println("\n==============================");
        System.out.println("   LECCIÓN 8 - ARRAYS Y CADENAS");
        System.out.println("==============================\n");

        // ---- Arrays ----
        String[] frutas = {"Manzana", "Pera", "Plátano"};
        System.out.println("Primer elemento del array: " + frutas[0]);

        System.out.println("\nRecorriendo el array:");
        for (int i = 0; i < frutas.length; i++) {
            System.out.println("- " + frutas[i]);
        }

        // ---- Cadenas ----
        String nombre = "David";

        System.out.println("\nTrabajando con cadenas:");
        System.out.println("Longitud: " + nombre.length());
        System.out.println("Mayúsculas: " + nombre.toUpperCase());
        System.out.println("Incluye 'vi'? " + nombre.contains("vi"));

        // ---- Mezclando arrays + cadenas ----
        String[] nombres = {"Ana", "Carlos", "Diana"};
        System.out.println("\nSaludos:");
        for (String n : nombres) {
            System.out.println("Hola " + n);
        }
    }
}


```

---
### Lección 9: Buenas Prácticas y Errores Comunes 
- **Descripción:** En esta última lección verás las buenas prácticas de programación y los errores más frecuentes que cometen los principiantes. Aprenderás cómo escribir código más limpio, legible y fácil de mantener.
- **Enlace del Video:** [¡Clic aquí!](https://youtu.be/sHM_TkCFvBA)
- **Conclusiones:** Has llegado al final del curso con una base sólida en Java y pensamiento lógico. Ahora conoces las mejores formas de escribir, estructurar y depurar tu código. ¡Ya estás listo para seguir aprendiendo y crear tus propias aplicaciones!
- **Práctica:**
```Java


class Leccion9 {

    public static void ejecutar() {

        System.out.println("\n==============================");
        System.out.println("   LECCIÓN 9 - BUENAS PRÁCTICAS");
        System.out.println("==============================\n");

        // Nombres descriptivos
        int edadUsuario = 20;
        String nombreProducto = "Laptop";

        System.out.println("Edad usuario: " + edadUsuario);
        System.out.println("Producto: " + nombreProducto);

        // Indentación correcta
        if (edadUsuario > 18) {
            System.out.println("Eres mayor de edad.");
        }

        // Uso de funciones para evitar repetir código
        saludar("David");
        saludar("Ana");

        // Errores comunes
        System.out.println("\nERRORES COMUNES A EVITAR:");
        System.out.println("- Confundir '=' con '=='");
        System.out.println("- Olvidar llaves {}");
        System.out.println("- Nombres mal escritos");
        System.out.println("- Índices fuera del array");
        System.out.println("- No cerrar comillas");
    }

    public static void saludar(String nombre) {
        System.out.println("Hola " + nombre);
    }
}
```
## Main de las lecciones 7 a 9:

```Java
public class Main {
    public static void main(String[] args) {

        System.out.println("==============================");
        System.out.println("LECCIÓN 7 - ENCAPSULACIÓN");
        System.out.println("==============================\n");

        // Parte de la Lección 7
        Persona p = new Persona("María", 15);

        System.out.println("Edad inicial: " + p.getEdad());
        p.setEdad(16);
        System.out.println("Edad después del setter: " + p.getEdad());

        // Ejecutar Lección 8
        Leccion8.ejecutar();

        // Ejecutar Lección 9
        Leccion9.ejecutar();

        System.out.println("\n=== Fin de las lecciones 7-9 ===");
    }
}

```
## Recursos Adicionales
- **Código Fuente Completo:** [Github Link aquí](https://github.com)
- **Todas las actividades prácticas:**

| Nro. de Lección | Actividad | Empezar a Programar |
|-----------------|-----------|---------------------|
| 1 | Mi Primer Programa: ¡Hola, mundo! | [Replit \| ¡Clic aquí!](https://replit.com) |
| 2 | Sintaxis, Variables y Tipo de Datos | [Replit \| ¡Clic aquí!](https://replit.com) |
| 3 | Operaciones Lógicas y Matemáticas | [Replit \| ¡Clic aquí!](https://replit.com) |
| 4 | Condiciones y Bucles | [Replit \| ¡Clic aquí!](https://replit.com) |
| 5 | Funciones y Parámetros | [Replit \| ¡Clic aquí!](https://replit.com) |
| 6 | Implementación de POO | [Replit \| ¡Clic aquí!](https://replit.com) |
| 7 | Public, Private, Get y Set | [Replit \| ¡Clic aquí!](https://replit.com) |
| 8 | Arreglos y Cadenas | [Replit \| ¡Clic aquí!](https://replit.com) |


**¡Gracias por completar el curso!**

## Elaboración
Universidad Peruana de Ciencias Aplicadas (UPC)
Facultad de Ingeniería
Periodo 202520
1ASI0729 - Desarrollo de Aplicaciones Open Source
NRC 7327
**Desarrolado por:** RPG 2.0
**Líder:** Vivar Cesar, David Ignacio
**Integrantes del Equipo:**

| Apellidos y Nombres | Código |
|---------------------|--------|
| Céspedes Pillco, Jarod Jack | U202318588 |
| Guillen Giraldo, Myke Dylan | U202211881 |
| Howard Robles, Guillermo Arturo | U202222275 |
| Vivar Cesar, David Ignacio | U202414424 |

**Fecha de Entrega:** 14/11/2025
