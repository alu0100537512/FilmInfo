Proyecto final - Asignatura PL
=========
Creador de Exámenes
=========

En este proyecto se ha creado una sintaxis un poco particular para hacer exámenes en la web. Se dispondrá a redactar en este README las siguientes cuestiones:

  - Propósito
  - Gramática
  - Generación del HTML

El lenguaje propuesto para este proyecto es uno de tantos existentes se espera que les sea familiar y lo disfruten y que no pase lo que dijo un día Alan J. Perlis:

> Cuando alguien dice: 'quiero un lenguaje de programación en el que sólo tengo que decir lo que quiero hacer ", le dan un chupetin

Propósito
----

    El objetivo de este proyecto se resume en facilitar la labor a una persona que no esté familiarizada 
    con el lenguaje de etiquetado de HTML y desee obtener un código en dicho lenguaje con el objetivo de 
    crear un examen y aquí encontrará una forma de atacarlo de una forma sencilla.

Gramática
-----------

- Preguntas de desarrollo

        ?? pregunta ; [].
        
- Preguntas Test

        ?T pregunta ;
            * opcion;
            * opcion;.
            
- Preguntas MultiTest 

        ?M preguntas ;
              <> opcion;
              <> opcion;.

Generador de HTML
--------------
        Cuando  escriba  su programa se y le  dé  al boton  de parsear  
        se generará el código HTML expecífico al lado y usted tendrá que copiar ese 
        HTML y ya tendrá el index de su Examen/Formulario. 
