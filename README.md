# 📘 Documentación — Clase `Aprendiz` (POO en Java)

## 1) Propósito de la clase
La clase `Aprendiz` representa un **modelo de datos** (o *entidad*) para almacenar y gestionar la información básica de un aprendiz del SENA.  
Aplica conceptos de **Programación Orientada a Objetos (POO)** como:

- **Encapsulamiento** (atributos privados)
- **Constructores** (vacío y con parámetros)
- **Getters/Setters** (acceso controlado)
- **Validación de datos** (correo y edad)
- **Comportamiento** (método `presentarse()`)

---

## 2) Paquete y declaración de clase
```java
package com.sena;

public class Aprendiz {
    ...
}

private String nombre;
private String documento;
private String correo;
private int edad;

public Aprendiz() {
}