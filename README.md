# ayudantia1810
# Ejercicios de Programación Avanzada en Python

A continuación, se presentan dos ejercicios de programación avanzada en Python que se centran en el uso de excepciones y otros conceptos fundamentales del lenguaje.

## Validador de Expresiones Matemáticas

**Enunciado:**

Desarrolla un programa que valide si una expresión matemática ingresada por el usuario tiene paréntesis, corchetes y llaves balanceados. Por ejemplo, la expresión `3 + (4 - [2 * {6/3}])` es válida, mientras que `3 + (4 - [2 * {6/3]}` no lo es.

**Requisitos:**

- El programa debe solicitar al usuario que ingrese una expresión matemática.
- Utiliza una estructura de pila para validar el balanceo de los paréntesis, corchetes y llaves.
- Si la expresión no está balanceada, lanza una excepción personalizada llamada `ExpresionNoValidaError` indicando la posición y el carácter no balanceado.

## Sistema de Reservas

**Enunciado:**

Desarrolla un sistema de reservas para un teatro. El teatro tiene 3 filas de asientos y cada fila tiene 5 asientos. El usuario puede:

1. Reservar un asiento.
2. Cancelar una reserva.
3. Ver los asientos disponibles.
4. Ver los asientos reservados.

**Requisitos:**

- Los asientos deben ser representados utilizando una lista de listas.
- Si el usuario intenta reservar un asiento ya reservado, el programa debe lanzar una excepción personalizada llamada `AsientoYaReservadoError`.
- Si el usuario intenta cancelar una reserva de un asiento no reservado, el programa debe lanzar una excepción personalizada llamada `ReservaNoExistenteError`.

---
## Ejercicio: Registro de Estudiantes

**Enunciado:**

Se te ha encargado desarrollar un sistema de registro para estudiantes de una universidad. Los estudiantes tienen un nombre, una edad y una carrera. El sistema debe ser capaz de realizar las siguientes operaciones:

1. Registrar un nuevo estudiante.
2. Buscar un estudiante por nombre.
3. Modificar la información de un estudiante.
4. Eliminar un estudiante del registro.
5. Listar todos los estudiantes registrados.

Toda la información de los estudiantes debe ser almacenada en un archivo llamado `estudiantes.txt`. Cada línea del archivo representa a un estudiante y sus datos están separados por comas, por ejemplo: `Juan Pérez,23,Ingeniería Informática`.

**Requisitos:**

- El programa debe leer y escribir en el archivo `estudiantes.txt`.
- Si el usuario intenta registrar un estudiante con un nombre que ya existe en el registro, el programa debe lanzar una excepción personalizada llamada `EstudianteExistenteError`.
- Si el usuario busca o intenta modificar/eliminar un estudiante que no existe en el registro, el programa debe lanzar una excepción personalizada llamada `EstudianteNoEncontradoError`.
- Debes utilizar excepciones para manejar cualquier error que pueda surgir al abrir el archivo o al leer/escribir en él.


