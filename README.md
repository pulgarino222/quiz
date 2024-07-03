Quiz de Prerrequisitos para TypeScript y Node.
Objetivo

El objetivo de este quiz es evaluar tus conocimientos previos sobre JavaScript antes de comenzar con el curso de TypeScript y Node. Responde las preguntas a continuación y envía tus respuestas siguiendo las instrucciones. Este quiz no afectará tu calificación en el curso, pero te ayudará a identificar áreas en las que puedas necesitar repasar antes de comenzar.
Instrucciones de envío

    Crea un nuevo repositorio en tu cuenta de GitHub llamado quiz-prework-ts-node.
    Copia las preguntas a continuación y péguelas en el archivo README.md de tu repositorio.
    Responde cada pregunta en su respectiva sección.
    Realiza un commit y un push de tus respuestas a GitHub.
    Subir a moodle en el espacio habilitado de semana 1 el link del repositorio en GitHub. En caso de no estar habilitado el envío en moodle, enviar el link del repo a nicolas.picon@riwi.io.

Preguntas Abiertas (10)

    JavaScript Básico:
        1)Describe qué es una función en JavaScript y cómo se declara.
        una funcion en java script es un conjunto de acciones que nos permite llegar a un objetivo especifico y todas estas acciones se encapsulan en una funcion
        y se declara de dos formas la primera es: 
        *function nameOfFunction(parameter){
        content that have the function
        }
        *let saveFunction= ()=>{
        actions that have the functiion
        }

    

    Manipulación del DOM:
       2) Explica cómo seleccionar un elemento del DOM y cambiar su contenido.
        Respuesta:
        seleccionamos el elemento del doom que deseemos seleccionar se puede hacer de la siguiente forma 
        let elementThatChange=document.queryselector("nombre del elemento")
        y para editar el contenido que tiene este elemento lo podemos hacer de varias formas la mas sencilla en mi opinion seria 
        elementThatChange.innerHTML='<div>contenido nuevo modificado</div>'
        

    Programación Orientada a Objetos (OOP):
        ¿Qué es una clase en JavaScript y cómo se define una?
        una clase es simplemente una forma de agrupar metodos

    Eventos en JavaScript:
        ¿Cómo se agrega un evento de clic a un botón en JavaScript?

    Variables y Tipos de Datos:
        Explica las diferencias entre var, let, y const en JavaScript.

    Control de Flujo:
        ¿Qué son las estructuras de control de flujo y cuáles son algunas de las más comunes en JavaScript?

    Funciones de Flecha:
        Describe qué es una función de flecha en JavaScript y proporciona un ejemplo de cómo se usa.

    JSON:
        ¿Qué es JSON y cómo se utiliza en JavaScript?

    Promesas:
        Explica qué es una promesa en JavaScript y proporciona un ejemplo de su uso.

    Depuración:
        ¿Cuáles son algunas de las herramientas o métodos que se pueden usar para depurar código JavaScript?

Preguntas de Selección Múltiple (20)

    ¿Cuál de las siguientes es la forma correcta de declarar una variable en JavaScript?

    A) var myVariable;
    B) variable myVariable;
    C) let myVariable;
    D) A y C son correctas.

    ¿Qué método se utiliza para agregar un elemento al final de un array en JavaScript?

    A) push()
    B) pop()
    C) shift()
    D) unshift()

    ¿Cuál de los siguientes operadores se utiliza para comparar tanto el valor como el tipo de dos variables en JavaScript?

    A) ==
    B) ===
    C) !=
    D) !==

    ¿Cuál es la salida del siguiente código?

console.log(typeof null);

    A) null
    B) undefined
    C) object
    D) number

    ¿Cuál de los siguientes métodos se usa para recorrer todos los elementos de un array?

    A) forEach()
    B) map()
    C) filter()
    D) Todas las anteriores

    ¿Qué se entiende por “hoisting” en JavaScript?

    A) Declaraciones de variables y funciones se mueven al principio de su ámbito.
    B) Es un término para describir la eliminación de variables.
    C) Es un método para agrupar varias funciones.
    D) Ninguna de las anteriores.

    ¿Cuál es la diferencia entre null y undefined en JavaScript?

    A) null significa que una variable ha sido declarada pero no definida, undefined significa que no se ha declarado.
    B) null es un valor asignado intencionalmente, undefined significa que una variable no tiene valor.
    C) undefined es un valor asignado intencionalmente, null significa que una variable no tiene valor.
    D) No hay diferencia.

    ¿Cuál es el propósito del método Array.prototype.map()?

    A) Modificar el array original.
    B) Crear un nuevo array con los resultados de aplicar una función a cada elemento del array original.
    C) Filtrar los elementos de un array.
    D) Encontrar un elemento en un array.

    ¿Qué es el Event Loop en JavaScript?

    A) Un ciclo que controla las llamadas recursivas.
    B) Un proceso que permite a JavaScript realizar operaciones asincrónicas.
    C) Un método para iterar sobre arrays.
    D) Ninguna de las anteriores.

    ¿Cuál es la salida del siguiente código?

    console.log(0.1 + 0.2 === 0.3);

    A) true
    B) false
    C) undefined
    D) NaN

¿Qué se entiende por strict mode en JavaScript?

    A) Un modo que permite utilizar características experimentales.
    B) Un modo que cambia la forma en que se ejecuta JavaScript, haciéndolo más seguro.
    C) Un método para validar datos.
    D) Ninguna de las anteriores.

¿Cuál de las siguientes es una forma correcta de crear un objeto en JavaScript?

    A) let obj = {};
    B) let obj = Object.create();
    C) let obj = new Object();
    D) A y C son correctas.

¿Qué es un callback en JavaScript?

    A) Una función que se pasa como argumento a otra función.
    B) Un tipo de variable especial.
    C) Un método para declarar funciones.
    D) Ninguna de las anteriores.

¿Cuál es el propósito de async y await en JavaScript?

    A) Ejecutar funciones síncronas.
    B) Manejar operaciones asincrónicas de manera más simple y legible.
    C) Declarar variables globales.
    D) Ninguna de las anteriores.

¿Cuál de las siguientes es una estructura de datos inmutable en JavaScript?

    A) Arrays
    B) Strings
    C) Objetos
    D) Ninguna de las anteriores.

¿Cómo se puede convertir un objeto JSON en una cadena de texto en JavaScript?

    A) JSON.parse()
    B) JSON.stringify()
    C) toString()
    D) parseInt()

¿Qué es un Promise en JavaScript?

    A) Una función que se ejecuta inmediatamente.
    B) Un objeto que representa la eventual finalización (o falla) de una operación asincrónica.
    C) Un método para declarar variables.
    D) Ninguna de las anteriores.

¿Qué método se utiliza para agregar uno o más elementos al principio de un array y devolver la nueva longitud del array?

    A) push()
    B) pop()
    C) shift()
    D) unshift()

¿Cuál es la diferencia entre localStorage y sessionStorage en JavaScript?

    A) localStorage almacena datos solo durante la sesión del navegador, sessionStorage almacena datos de manera persistente.
    B) sessionStorage almacena datos solo durante la sesión del navegador, localStorage almacena datos de manera persistente.
    C) No hay diferencia entre ellos.
    D) Ambos almacenan datos solo durante la sesión del navegador.

¿Qué método se utiliza para detener la propagación de un evento en el DOM?

    A) event.stopPropagation()
    B) event.preventDefault()
    C) event.stop()
    D) event.cancel()


