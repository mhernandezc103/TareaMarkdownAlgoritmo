# Marlon Hernandez - Documentación en Markdown
Tarea Markdown Algoritmos - 2do Semestre Ingenieria en Sistemas UMG - Boca Del Monte

## Cómo utilizar `if - else` y `switch`

![Imagen con el logo de C++ y Codigo de un While de fondo](https://msmk.university/wp-content/uploads/2025/05/programacionc.webp)

---

### **Que es If, else y Switch - Explicado como lo comprendi** 

#### `if - else`
La estructura `if - else` permite ejecutar diferentes bloques de código dependiendo de si una condición es verdadera o falsa.

En español, puede entenderse como:
> "Si se cumple esta condición, entonces haz esto; 
si no se cumple, entonces haz otra cosa."

**Ejemplo en pseudocódigo:**

```pseudo
Si (condición) {
    // Entonces realiza esto
} sino {
    // Entonces realiza esto otro
}
```

#### `if - else`

La estructura `Switch` permite evaluar múltiples condiciones (casos) y ejecutar un bloque de código según cuál se cumpla.

    Es como decir: 
    "Si es este caso, haz esto; 
    si es otro caso, haz aquello; 
    y si no es ninguno, haz otra cosa por defecto."

**Ejemplo en pseudocódigo:**

```pseudo
switch (valor) {
    caso 1:
        // Realiza acción 1
        romper;
    caso 2:
        // Realiza acción 2
        romper;
    caso 3:
        // Realiza acción 3
        romper;
    predeterminado:
        // Si no se cumple ningún caso, realiza esto
}
```

### Entonces Cuando uso If - Else o Switch?

En la programación, tanto if/else como switch son estructuras de control para tomar decisiones, pero se utilizan en contextos diferentes. if/else es más versátil para condiciones booleanas, mientras que switch es más eficiente y legible para múltiples casos basados en el valor de una sola variable. 
Cuándo usar if/else: 

    - Condiciones Booleanas Complejas:
        If - Else es ideal cuando se necesita evaluar condiciones que pueden ser 
        "Verdadero" o "Falso", 
        "1 > 2" o 
        "numero % 2 == 0"

Cuándo usar switch: 

    - Multiples Casos Basados en el Valor de una variable
        Por ejemplo:
            Ingresar un valor que puede tener muchos estados por ejemplo en las calculadoras, si ingresan: "+", "-", "*", "/" y en base a eso, seleccionar la operacion a realizar
