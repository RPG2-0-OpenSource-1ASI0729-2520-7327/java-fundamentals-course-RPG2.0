# Fundamentos del Lenguaje de Programación Java para Principiantes

---

## Resumen del Curso
Este curso tiene una duración de 1 hora y media, y tiene como objetivo introducir a estudiantes de secundaria a los fundamentos básicos de la programación con el lenguaje Java, incluyendo información básica del paradigma de la [Programación Orientada a Objetos (POO)](https://www.w3schools.com/java/java_oop.asp).

**Duración Total:** ~90 minutos
**Público Objetivo:** Estudiantes de 12 a 17 años sin experiencia en programación
**Pre-requisitos:** Ninguno
**Herramientas Necesarias:** Solo necesitas tu navegador web (Chrome, Brave, Firefox, Safari, Edge, etc).

**Repositorio de Código Fuente:** [Link aquí](GETOUT)

## Secuencia de Lecciones

### Lección 1: Introducción a la Programación y al Lenguaje Java ( 5 minutos )
- **Descripción:** En esta lección, aprenderás qué es la programación y por qué Java es uno de los lenguajes más usados. Descubrirás cómo los programadores dan instrucciones a las computadoras, y cómo Java permite crear desde simples programas en consola hasta aplicaciones móviles y videojuegos.
- **Enlace del Video:** [¡Clic aquí!](https://www.youtube.com)
- **Conclusiones:** Ahora comprendes que programar significa comunicarse con la computadora usando un lenguaje que esta entienda. Java es una puerta de entrada al mundo de la programación por su facilidad, potencia y gran comunidad. Ahora estás más que listo para escribir tu primer línea de código.
- **Empieza a Programar:** [¡Regístrate en Replit y comienza ahora!](https://replit.com/languages/java10)

### Lección 2: Sintaxis, Variables y Tipos de Datos ( 7 minutos )
- **Descripción:** Esta lección te enseña la estructura fundamental de un programa Java: clases, métodos y la función principal ```main```. También aprenderás a crear variables para guardar información y conocerás los tipos de datos básicos como enteros, decimales, texto y booleanos.
- **Enlace del Video:** [¡Clic aquí!](https://www.youtube.com)
- **Conclusiones:** Has aprendido cómo se organiza un programa en Java y cómo las variables te permiten almacenar distintos tipos de información. Ahora ya puedes crear pequeños programas que manipulen datos básicos y los muestren por pantalla.
- **Práctica:** 

### Lección 3: Operadores y Expresiones ( 9 minutos )
- **Descripción:** En esta lección, aprenderás a cómo hacer que tus programas realicen cálculos y tomen decisiones simples. En esta lección aprenderás a usar operadores aritméticos, relacionales y lógicos, las herramientas que permiten que tu código “piense” y resuelva problemas.
- **Enlace del Video:** [¡Clic aquí!](https://youtu.be/biofxE3YZ00)
- **Conclusiones:** Comprendiste cómo combinar variables y operadores para crear expresiones matemáticas y lógicas. Con esto, tus programas ya pueden comparar, calcular y analizar condiciones de manera automática.
---
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
### Lección 4: Estructuras de Control Básicos ( 8 minutos )
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

---

2. Declara una variable `puntos = 72` y evalúa el puntaje y muestra un mensaje:  

- Si es mayor o igual a 90 → "Nivel Alto"  
- Si es mayor o igual a 60 → "Nivel Medio"  
- Si es menor a 60 → "Nivel Bajo"

---

3. Usa un bucle `for` para imprimir los números del **1 al 30**.

---

4. Declara `contador = 5` y usa un `while` para imprimir el mensaje **"Cuenta regresiva"** hasta que llegue a 1.

---
### Lección 5: Funciones y Parámetros ( 7 minutos )
- **Descripción:** En esta lección, aprenderás a organizar tu código en bloques reutilizables llamados funciones. Entenderás cómo pasarles información (a través de parámetros) y cómo devolver resultados (con los llamados valores de retorno), haciendo tus programas más limpios, ordenados y eficientes.
- **Enlace del Video:** [¡Clic aquí!](https://www.youtube.com)
- **Conclusiones:** Ahora sabes cómo dividir un programa en partes más pequeñas y reutilizables. Las funciones te permiten escribir código más organizado y profesional, una habilidad esencial para cualquier programador.
- **Práctica:**

### Lección 6: Introducción a la Programación Orientada a Objetos (POO) ( 8 minutos)
- **Descripción:** En esta lección, entrarás al mundo de la Programación Orientada a Objetos (POO), el paradigma que define al lenguaje Java. Aprenderás qué son las clases, los objetos y los constructores, y cómo representar personas, animales o cosas del mundo real dentro del código.
- **Enlace del Video:** [¡Clic aquí!](https://www.youtube.com)
- **Conclusiones:** Ahora, ya entiendes el concepto clave de la POO: usar clases y objetos para modelar el mundo real. Has aprendido a crear tus propias clases y darles atributos y comportamientos, lo que te permitirá construir programas más organizados y potentes.
- **Práctica:**

### Lección 7: Encapsulación, Getters y Setters (6 minutos ) 
- **Descripción:** En esta lección, aprenderás el principio de la encapsulación, que protege los datos dentro de las clases. Verás cómo usar modificadores de acceso (como ```private``` y ```public```) y métodos especiales (conocidos como _getters_ y _setters_) para acceder a la información de forma segura.
- **Enlace del Video:** [¡Clic aquí!](https://www.youtube.com)
- **Conclusiones:** Ahora comprendes cómo proteger los datos de tus clases y controlar su acceso. La encapsulación te ayuda a mantener tu código más seguro, limpio y fácil de mantener, siguiendo buenas prácticas de la POO.
- **Práctica:**

### Lección 8: Arrays y Cadenas ( 7 minutos )
- **Descripción:** En esta lección, aprenderás a trabajar con colecciones de datos mediante _arrays_, ideales para almacenar varios valores a la vez (como una lista de notas). Además, practicarás con métodos útiles de la clase _String_ para manipular texto.
- **Enlace del Video:** [¡Clic aquí!](https://www.youtube.com)
- **Conclusiones:** Ahora sabes cómo guardar y recorrer múltiples valores dentro de un arreglo, y cómo trabajar con cadenas de texto en Java. Este conocimiento será clave para crear cadenas más complejas y dinámicas.
- **Práctica:**

### Lección 9: Buenas Prácticas y Errores Comunes ( 6 minutos )
- **Descripción:** En esta última lección verás las buenas prácticas de programación y los errores más frecuentes que cometen los principiantes. Aprenderás cómo escribir código más limpio, legible y fácil de mantener.
- **Enlace del Video:** [¡Clic aquí!](https://www.youtube.com)
- **Conclusiones:** Has llegado al final del curso con una base sólida en Java y pensamiento lógico. Ahora conoces las mejores formas de escribir, estructurar y depurar tu código. ¡Ya estás listo para seguir aprendiendo y crear tus propias aplicaciones!
- **Práctica:**

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

- **Cuestionario:** [Prueba de Conocimientos](https://forme.gle/the-test)

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

**Fecha de Entrega:** XX/11/2025
