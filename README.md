# ![Java](readme.png)

## **1. ¿Qué es Java?**

Java es un **lenguaje de programación de alto nivel y orientado a objetos**, diseñado para ser **portátil, seguro y robusto**.

### Características principales:

* **"Write Once, Run Anywhere" (WORA):**
  El código Java se compila a bytecode que se ejecuta en la Máquina Virtual de Java (JVM), permitiendo que el mismo programa corra en Windows, Linux, macOS o cualquier sistema con JVM.

* **Orientación a objetos:**
  Basado en objetos y clases, facilita la reutilización, modularidad y organización del código.

* **Gestión automática de memoria:**
  Su recolector de basura (garbage collector) libera memoria automáticamente, evitando fugas y errores comunes.

* **Seguridad:**
  Incluye mecanismos para prevenir accesos no autorizados y ataques, lo que lo hace ideal para aplicaciones críticas.

* **Amplia biblioteca estándar:**
  Proporciona APIs para redes, bases de datos, interfaces gráficas, entre otras funcionalidades.

---

## **2. Hola Mundo**

A continuación, un ejemplo básico que imprime “¡Hola Mundo!” en consola:

```java
public class HolaMundo {
    public static void main(String[] args) {
        System.out.println("¡Hola Mundo!");
    }
}
```

### ¿Cómo ejecutar este programa?

1. Instala el **JDK (Java Development Kit)** desde [Oracle](https://www.oracle.com/java/technologies/downloads/) o usa OpenJDK.

2. (Opcional) Usa un IDE como IntelliJ IDEA, Eclipse o NetBeans para facilitar la edición y ejecución.

3. Desde la terminal:

   * Guarda el código en un archivo llamado `HolaMundo.java`.

   * Navega en la terminal a la carpeta donde guardaste el archivo.

   * Compila con:

     ```
     javac HolaMundo.java
     ```

   * Ejecuta con:

     ```
     java HolaMundo
     ```

   * Verás en pantalla:

     ```
     ¡Hola Mundo!
     ```

---
