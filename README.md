# Numeros-Primos..

### - Que voy a hacer 
En este reto (número 3), voy a hacer un pseudocódigo y un diagrama de flujo en el cual se indentifiquen todos los números primos que sean menores a un número natural N.

![image](https://github.com/user-attachments/assets/b581f5ae-92bb-46ff-95b9-249ba92b4aa6)


## Pseudocódigo 

```
Inicio
    Escribir "Ingresa un número:"
    Leer n

    Para i desde 2 hasta n hacer

        esPrimo ← Verdadero

        Para j desde 2 hasta i - 1 hacer
            Si i mod j = 0 entonces
                esPrimo ← Falso
                Salir del Para
            Fin Si
        Fin Para

        Si esPrimo entonces
            Escribir i
        Fin Si

    Fin Para
Fin
```

## Diagrama de Flujo

```mermaid
flowchart TD
    A[Inicio] --> B[Leer número n]
    B --> C[Para i desde 2 hasta n]
    C --> D[es primo = Verdadero]
    D --> E[Para j desde 2 hasta i - 1]
    E --> F{i % j == 0 ?}
    F -- Sí --> G[es primo = Falso]
    G --> H[Salir del ciclo j]
    F -- No --> E
    H --> I{es primo es Verdadero?}
    E --> I
    I -- Sí --> J[Imprimir i]
    I -- No --> K[No hacer nada]
    J --> L[¿Hay más i?]
    K --> L
    L -- Sí --> C
    L -- No --> M[Fin]
```

## Muchas Gracias X La Atencion Prestada 

![image](https://github.com/user-attachments/assets/9d2e5a15-3b66-4ca9-bb4b-453abb64b979)
