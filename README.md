# AprendamosProgramacionBasica
## Introducción
Python es un lenguaje de programación poderoso y fácil de aprender. Cuenta con estructuras de datos
eficientes y de alto nivel y un enfoque simple pero efectivo a la programación orientada a objetos. La
elegante sintaxis de Python y su tipado dinámico, junto con su naturaleza interpretada, hacen de éste un
lenguaje ideal para scripting y desarrollo rápido de aplicaciones en diversas áreas y sobre la mayoría de
las plataformas.
El intérprete de Python y la extensa biblioteca estándar están a libre disposición en forma binaria y de
código fuente para las principales plataformas desde el sitio web de Python, http://www.python.org/, y
puede distribuirse libremente. El mismo sitio contiene también distribuciones y enlaces de muchos
módulos libres de Python de terceros, programas y herramientas, y documentación adicional.
El intérprete de Python puede extenderse fácilmente con nuevas funcionalidades y tipos de datos
implementados en C o C++ (u otros lenguajes accesibles desde C). Python también puede usarse como
un lenguaje de extensiones para aplicaciones personalizables.

## Lenguaje interpretado o de script
Lenguaje interpretado o de script es aquel que se ejecuta utilizando un programa intermediario , que se llama interprete en lugar de copilar el código al lenguaje maquina de lenguajes compilados.

La ventaja de los lenguajes compilados es que su se ejecución es mas rápida sin embargo los lenguajes interpretados son mas flexibles y portados.


Los ejercicios están diseñados para el desarrollo en el alumno la oportunidad de practicar problemas pequeños en pasos secuenciales adicionalmente se volverá familiar la sintaxis de python desarrollando los siguientes temas.
> * Generar una salida con asistencia "Print"
* Leer la entrada del usuario con el teclado usando raw_input.
* Reaizar cálculos sencillos con suma "+" y potencia "**".
* Realizar cálculos mas complejos con el modulo "math".

Para entrar a la terminal escribir el comando "Python" para salir de python usamos exit().

Existen dos formas de ejecutar código en Python, la cual puede ser mediante una sección, interactiva(linea a linea)con el interprete o bien de la forma habitual, escribiendo el código en un archivo de código fuente ejecutando en la primera parte de este curso lo haremos por el interprete.

El primer programa que vamos a escribir en Python es el clásico "Hola mundo" y en este lenguaje esta simple como **print('Hola mundo')**

Donde:

* Print = Comando
* ('Hola mundo') = Argumento(cadena de texto)

### Tipos de datos básicos
Los tipos de datos básicos se dividen en:

+ Números: como pueden ser:

3(Entero o integer)

1.75(punto flotante o float)

5+7j(complejos o complex)

En python los tipos de datos básicos se dividen en, números, como pueden ser 3 (*entero ó integer*) 1.75, (*punto flotante ó float*) 7+5j (*complejos ó complex*).

Para poder conocer el tipo de dato de una variable usaremos la instrucción **type()**.

Los números flotantes son los que tienen decimales. En python se expresan mediante el tipo **float**

Los números complejos son aquellos que tienen una parte imaginaria. Para definir una variable compleja se utiliza el termino **complex**.

Ejemplo:

 import math

 a = float(input("Ingresa un numero"9;))

 b = float(input("Ingresa un numero";))

 s = a+b

 r = b-a

 p = a\*a

 d = a/b

 m = a%b

 e = a\*\*b

 l = (math.log10(a))

 print("El resultado de la suma es;,s)

 print("El resultado de la resta es;,r)

 print("El resultado de la multiplicacion es;,p)

 print("El resultado de la division es;,d)

 print("El residuo de la division es;,m)

 print("El resultado de la potencia e;,e)

 print("El resultado de la logaritmo es:,l)
 
 
 ## variables
### Tipos de variables

**Salto de pagina**

'\n'
Ejemplo:

 print(nombre + ;\n; + calle;)


 ### Sentencias condicionales

Las sentencias condicionales nos permiten comprobar y hacer que nuestro programa se comparte de una forma u otra, que ejecute un fragmento de un código u otro, dependiendo esa condición.

**Condicional "if; else"**

La forma mas simple de una sentencia condicional es el **if** (del ingles "si") seguida de la condicion a evaluar, (:) y en la siguiente linea **in dentado** el código a ejecutar en caso de que se cumpla dicha condición.

Ejemplo:

 password\_user1 = input"Inserte su nuevo password: )

 password\_user2 = input("Confirme password: )

 if password\_user1 == &quot;password\_user2&quot;:

      print("Su password ha sido establecido";)

 else:

      print("Lo siento, intentelo de nuevo";)

 print("Gracias!")
 
 
 ### **Variable flotante**

Es una variable que puede guardar datos numéricos con punto decimal, para forzar a una variable a que sea flotante usaremos el comando 

**float()**

**float = numero decimal**

**int = numero entero**
 
 Ejemplo:

 a= int(input("Introduzca las millas por galón que da su carro"))

 b= 1.609344

 print ("los kilómetros por galón que da su automovil es:, a\*b)
 
 
 ### Funciones

Una función es un fragmento de código con un nombre asociado que realiza una serie de tareas y devuelve un valor. A demás de ayudarnos a programar y depurar dividiendo el programa en partes, las funciones también permiten reutilizar código.

Las Funciones ayudan al programador a dividir un problema en pequeñas piezas que pueden ser re usadas. También ayudan al programador a concentrarse en una pequeña parte del programa a la vez. Como resultado el escribir funciones es una parte importante del desarrollo del sofware.

En nuestro caso debemos aprender a:

*Definir una función para usarla después.

*Pasar uno o más valores a una función.

*Desarrollar un cálculo complejo en una función.

*Regresar uno o más resultados a una función.

*Llamar a una función que previamente hayamos definido.

Ejemplo:

 #definición de una función

  def tarifa(kilómetros):

      tarifa=7.00\*kilómetros+7.25

      if tarifa\&lt;40:

          return 40

      return tarifa

 km=float(input(&#39;Inserta los kilómetros

 recorridos:&#39;))

 precio =tarifa(km)

 print(&#39;Precio final:, precio)
 
 **Bucles**

Los bucles permiten ejecutar un mismo fragmento de código un cierto numero de veces mientras se cumpla una determinada acción condición

*While*

El bucle **while** ejecuta un fragmento de código mientras se cumpla la condición.

*Ciclo For*

En pyhton **for** se utiliza como una forma genérica de interés sobre una secuencia, es decir, recorrer una secuencia.



###Programación Orientada a Objetos

Al principio del curso comentamos que Python es un lenguaje multiparadigma en el que se podía trabajar con programación estructurada, como veníamos haciendo ahora o con programación orientada a objetos el cual es un paradigma de programación en el que los conceptos del mundo real relevantes para nuestro problema se modelan a través de clases y objetos, y en el que nuestro programa consiste en una serie de interacciones entre objetos.

**Objetos**

Un objetos es una entidad que agrupa un estado y una funcionalidad relacionada. El estado del objeto se define a través de variables llamadas atributos, mientras que la funcionalidad de modela a través de funciones a las que se les conoce con el nombre de métodos del objeto.

**Clases**

Una clase no es más que una plantilla genérica de la cual instancia los objetos; es la plantilla que define que atributos y métodos tendrán los objetos de esa clase.

Ejemplo:

 class Coche(object):

    def \_\_init\_\_(self,gasolina):

         self.gasolina = gasolina

    def arrancar(self):

         if self.gasolina \&gt; 0:

        print("Arranca")

         else:

             print(&#39;No Arranca&#39;)

     def conducir(self):

         if self.gasolina \&gt; 0:

             self.gasolina = self.gasolina - 1

             print(Quedan ;, self.gasolina, litros;)

         else:

             print(&#39;No se mueve&#39;)

 ferrari = Coche(5)

 prosche= Coche(3)

 ferrari.arrancar()

 ferrari.conducir()

 ferrari.conducir()

 ferrari.conducir()

 ferrari.conducir()

 ferrari.conducir()


### Modulo Turlte

Hay muchos módulos en python que proveen características poderosas que podemos usar en nuestros propios programas. Algunos de estos pueden enviar correos electrónicos y algunos de estos pueden extraer información de paginas de Internet. Para el manejo de gráficos usaremos un modulo que permite crear figuras y patrones. El modulo que se usara permiten desarrollar nuestro pensamiento computacional.

mport turtle

 def dibujar\_cuadro\_caracol(tur, d):

     for i in  [red, blue,green,yellow,orange]:

         tur.color(i)

         tur.forward(d)

         tur.left(90)

 ventana=turtle.Screen()

 ventana.bgcolor("yello")

 ventana.title("funciones")

 alex=turtle.Turtle()

 alex.pensize(2)

 alex.speed(100)

 d=100

## Gráficos.

Hay muchos módulos en Python que proveen caracterizaras poderosas que podemos usar en nuestros propios programas.

Algunos pueden enviar correos electrónicos y algunos de estos pueden extraer información de paginas de Internet. Para el manejo de gráficos usaremos en modulo que permite crear figuras y patrones. El modulo que se usara permite desarrollar nuestro pensamiento comunicacional.



## Orientación a objetos.

Al principio del curso comentábamos que python es un lenguaje multiparadigma en el que se podría trabajar con programación estructurada como veníamos trabajando hasta ahora o con programación orientada a objetos lo cual es un paradigma de programación en que los conceptos del mundo real relevantes para el problema se modelan atravez de clases y objetos, y que de nuestro programa consiste en una serie interacción entre objetos.

**Clases y objetos.

Un objeto es una identidad que agrupa un estado y una funcionalidad relacionada. El estado del objeto se define atravez de variables llamadas atributos, mientras que la funcionalidad se modela atravez de funciones a las que se les conoce con el nombre de métodos del objeto.

**Clases

Una clase no es mas que una plantilla genérica de la cual distancia los objetos; es la plantilla que define que atributos y métodos tendrán los objetos de esa clase.

En python las clases se definen mediante la palabra clave **class** seguido de nombre de la clase, seguido por dos puntos(;)y a continuación id entado el cuerpo de la clase.
