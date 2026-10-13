# Estructura de Datos

## Práctica: Pilas Estáticas y Dinámicas en Java

### Descripción de la Estructura y Diferencias
* **Almacenamiento Estático (`PilaSimple.java`):** Utiliza un arreglo contiguo en memoria de tamaño fijo. Su principal limitación es que el tamaño máximo se define al crearse, lo que puede provocar desbordamiento (*overflow*) si se supera su capacidad.
* **Almacenamiento Dinámico (`PilaDinamica.java`):** Utiliza nodos enlazados mediante referencias. No requiere un tamaño máximo predefinido, por lo que su capacidad crece o decrece dinámicamente según la memoria RAM disponible.

---

### Pasos para Compilar y Ejecutar en la Terminal o IDE (IntelliJ IDEA)
1. Abrir el proyecto en **IntelliJ IDEA**.
2. Asegurarse de que todos los archivos (`PilaSimple.java`, `Nodo.java`, `PilaDinamica.java` y `Main.java`) estén dentro del directorio `src`.
3. Hacer clic derecho sobre la clase `Main.java` y seleccionar **Run 'Main.main()'** o compilar mediante la terminal con:

```bash
javac *.java
java Main
```
```text
=== PRUEBA DE PILA ESTÁTICA ===
Elemento 10 insertado en la pila estática.
Elemento 20 insertado en la pila estática.
Pila Estática (Tope -> Base): 20 10 
Elemento en el tope: 20
Elemento 20 extraído de la pila estática.
Pila Estática (Tope -> Base): 10 

=== PRUEBA DE PILA DINÁMICA ===
Elemento 100 insertado en la pila dinámica.
Elemento 200 insertado en la pila dinámica.
Pila Dinámica (Cima -> Base): 200 100 
Elemento en la cima: 200
Elemento 200 extraído de la pila dinámica.
Pila Dinámica (Cima -> Base): 100
