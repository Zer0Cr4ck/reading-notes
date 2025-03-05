### 1️⃣ ¿Qué es "Control Flow" (Control de Flujo)?
El **Control de Flujo** en JavaScript se refiere a la forma en que se ejecutan las instrucciones en un programa, de arriba hacia abajo, a menos que se modifique con estructuras como:

- **Condicionales (`if`, `else if`, `else`, `switch`)** → Permiten tomar decisiones.  
- **Bucles (`for`, `while`, `do while`)** → Ejecutan código repetidamente.  
- **Funciones (`function`)** → Organizan el código en bloques reutilizables.  

✅ **Ejemplo:**
```javascript
let edad = 18;

if (edad >= 18) {
    console.log("Eres mayor de edad");
} else {
    console.log("Eres menor de edad");
}
🔹 Si edad es 18 o más, se ejecuta el primer console.log().
🔹 Si edad es menor a 18, se ejecuta el segundo console.log().

2️⃣ ¿Qué es una "function" (Función) de JavaScript?
Una función en JavaScript es un bloque de código reutilizable que realiza una tarea específica. Se puede definir con la palabra clave function y se ejecuta cuando se la llama.

✅ Ejemplo de una función simple:

javascript
Copiar
Editar
function saludar(nombre) {
    return "Hola, " + nombre + "!";
}

console.log(saludar("Juan")); // Output: "Hola, Juan!"
🔹 saludar("Juan") llama a la función con el argumento "Juan", devolviendo "Hola, Juan!".

3️⃣ ¿Cuántas veces se ejecutará un bucle "while"?
Un bucle while se ejecutará mientras la condición especificada sea true.

✅ Ejemplo:

javascript
Copiar
Editar
let contador = 0;

while (contador < 3) {
    console.log("Iteración " + contador);
    contador++;
}
🔹 Salida:

Copiar
Editar
Iteración 0
Iteración 1
Iteración 2
✔ Se ejecuta 3 veces porque contador comienza en 0 y se incrementa hasta que contador < 3 sea falso.
⚠ ¡Cuidado con los bucles infinitos! Si la condición nunca se vuelve false, el bucle seguirá ejecutándose para siempre.

4️⃣ ¿Qué método usarías para agregar un elemento al final de un array y cómo se utiliza?
Para agregar un elemento al final de un array en JavaScript, usamos el método push().

✅ Ejemplo:

javascript
Copiar
Editar
let frutas = ["Manzana", "Plátano", "Uva"];
frutas.push("Naranja"); 

console.log(frutas); // Output: ["Manzana", "Plátano", "Uva", "Naranja"]
🔹 push("Naranja") añade "Naranja" al final del array frutas.

