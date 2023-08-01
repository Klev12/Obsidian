<p>Python es un lenguaje de alto nivel de programación interpretado cuya filosofía hace hincapié en la legibilidad de su código, se utiliza para desarrollar aplicaciones de todo tipo, ejemplos: Instagram, Netflix, Spotify, Panda3D, entre otros.​</p>
<h2>Booleans y Condicionales</h2>

<p>Phyton usa usa bool con valores True/False. Se usan con operadores booleanos, comparaciones y condicionales. Permiten controlar la ejecucion del codigo.</p>
<h2>Listas</h2>
<p>Son secuencias ordenadas de valores que pueden ser modificadas e indexadas, también ofrecen funciones útiles para manipular</p>
![[Pasted image 20230727113215.png]]
![[Pasted image 20230727114701.png]]
![[Pasted image 20230727114718.png]]


<h2>Bucles y comprensión de listas</h2>
<p>Los bucles en phyton (for, while) repiten código determinado. Las comprensiones de listas permiten condensar bucles y condicionales en una sola línea.</p>
>bucles for
>![[Pasted image 20230727113319.png]]
>bules while![[Pasted image 20230727113356.png]]
>
<h2>Trabajos con librerías externas</h2>
<p>Phyton permite la importación de librerías, ya sea estándar o personalizada, a través de importaciones. Las librerías contienen módulos que son colecciones de funciones y valores.</p>

<h2>Ejercicio 1</h2>
def multiply_by_two(x):

    """This funcion multiplies

          an imput number by 2"""

    return x * 2

help(multiply_by_two)


<h2>Ejercicio 2</h2>
def greet(person):

    return f"Hello,{person}!"

  

def repeat(func, times, arg):

    for _ in range(times):

        print (func(arg))

  

repeat(greet, 3, 'OpenAI')

<h2>Ejercicio 3</h2>

fruits = ['apple','banana','cherry','date','elderberry']

print(fruits[1:-1])

  

fruits[0] = 'apricot'

  

print(fruits)

<h2>Ejercicio de signos</h2>
nos = ["aries", "tauro", "geminis", "cancer", "leo", "virgo", "libra", "escorpio", "sagitario", "capricornio", "acuario", "piscis"]

predicciones = ["Hoy será un pesimo dia.", "Deberías evitar tomar decisiones apresuradas.", "La suerte está de tu lado hoy.", "Podrías enfrentarte a un desafío hoy.", "Es un buen momento para intentar algo nuevo.", "Hoy recibirás buenas noticias.", "Deberías centrarte en tus relaciones hoy.", "Tómate un tiempo para relajarte hoy.", "Deberías seguir tus instintos hoy.", "Hoy puede ser un día de cambios.", "Hoy podría ser un día emocionalmente cargado.", "Hoy es un día de aprendizaje."]

  

signo = input("Por favor, ingresa tu signo del zodiaco: ")

signo = signo.lower()

  

if signo in signos:

    print(predicciones[signos.index(signo)])

else:

    print("Lo siento, no tengo predicciones para ese signo.")


