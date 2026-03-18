

# Movimiento del Jugador en Unity 2D

## Descripción del proyecto

Este proyecto consiste en la implementación del movimiento básico de un jugador en un videojuego 2D desarrollado con Unity. Se programaron mecánicas fundamentales como desplazamiento horizontal y salto, utilizando físicas del motor mediante Rigidbody2D.

## Objetivo

Desarrollar un sistema de control para el personaje que permita al usuario moverse de izquierda a derecha y realizar saltos, aplicando conceptos básicos de programación en C# dentro del entorno de Unity.

## Funcionalidades implementadas

* Movimiento horizontal (izquierda y derecha)
* Salto del jugador
* Detección de suelo (ground check)
* Uso de físicas mediante Rigidbody2D

## Tecnologías utilizadas

* Unity (motor de desarrollo)
* Lenguaje C#
* Física 2D de Unity (Rigidbody2D, Colliders)

## Estructura del código

El script principal utilizado es **PlayerMovement.cs**, el cual contiene:

* Variables públicas:

  * speed: controla la velocidad del jugador
  * jumpForce: define la fuerza del salto
* Variables privadas:

  * Rigidbody2D: controla la física del personaje
  * moveInput: almacena la entrada del usuario
  * isGrounded: verifica si el jugador está en el suelo
* Métodos principales:

  * Start(): inicializa componentes
  * Update(): detecta entradas del usuario
  * FixedUpdate(): aplica el movimiento físico

## Controles del jugador

* Movimiento:

  * Teclas A / D o flechas izquierda y derecha
* Salto:

  * Barra espaciadora

## Configuración en Unity

1. Crear un objeto jugador.
2. Agregar componentes:

   * Rigidbody2D
   * Collider2D (Box o Capsule)
   * Script PlayerMovement
3. Crear un objeto vacío llamado “GroundCheck” como hijo del jugador.
4. Colocar GroundCheck en la parte inferior del personaje.
5. Asignar la capa “Ground” al suelo del escenario.
6. Configurar el LayerMask en el script.

## Conclusión

Se logró implementar correctamente el movimiento básico de un personaje en un entorno 2D, comprendiendo el uso de físicas, entrada del usuario y detección de colisiones. Este sistema es la base para el desarrollo de mecánicas más avanzadas en videojuegos.
**Referencias**

Unity Technologies. (2021). Unity User Manual (2D Game Development). https://docs.unity3d.com/es/

Unity Technologies. (2021). Scripting API: Rigidbody2D. https://docs.unity3d.com/ScriptReference/Rigidbody2D.html

Unity. (2021). Manual de física 2D. https://docs.unity3d.com/es/Manual/Physics2D.html

YouTube. (2021). Tutorial COMPLETO Unity 2D desde Cero - 2021 [Video]. https://www.youtube.com/

Microsoft C# Documentation. (2021). Guía del lenguaje C#. https://learn.microsoft.com/es-es/dotnet/csharp/
## Autor

Brayan Raymundo Salas Rodríguez

