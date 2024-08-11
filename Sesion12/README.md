# Sesion 12

## Enunciado

El objetivo de esta práctica es el diseño de un sistema secuencial sencillo y su implementación empleando distintas estrategias. 

Diseñar un circuito (Subcircuito1) que genere una secuencia de los 5 primeros números que sean diferentes en su “Número de ID” (que será el DNI en el caso de estudiantes españoles) del estudiante en Moodle (ir a Perfil->Preferencias->Editar perfil->Opcional). 

Si existen menos de 5 números diferentes, añadir entonces los números no repetidos subsiguientes al último hasta tener la secuencia de 5 números. Esta secuencia debe repetirse tres veces (implementado en el Subcircuito2). Acabada la última repetición de la secuencia, el contador tomará el valor del primer digito de la secuencia indefinidamente. Tomar la frecuencia de 2 Hz para el reloj.

El circuito main incluirá dos botones para inicializar Subcircuito1 y Subcircuito2.

**NOTA: Primero de todo, incluir el ID y la secuencia en el circuito main usando el editor de texto de Logisim.**

### Parte 1. Implementación del subcircuito 1.

Implementar en el Subcircuito 1 el circuito que genere de forma cíclica la secuencia de los 5 primeros números que sean diferentes en su “Número de ID” con biestables T3, T2, D1 y J0 K0, y tomando:

- Decodificadores 2x4 para para entradas T3 y T2.

- Puertas para la entrada D1.

- Multiplexores 8x1 para las entradas J0 y K0.

### Parte 2. Implementación del subcircuito 2.

Implementar en el Subcircuito 2 el circuito que cuenta en número de repeticiones de la secuencia anterior, usando cualquier tipo de biestables y puertas lógicas.

### Parte 3. Implementación del circuito main.

Implementar el circuito main que resuelve el problema planteado utilizando: el Subcircuito1, Subcircuito2, dos Hex Digit Displays (para ver las cuentas de ambos subcircuitos), dos botones (para inicializar cada uno de los subcircuitos) y otros componentes lógicos que el alumno considere necesarios. Notar que el estado inicial de Subcircuito1 es el primer digito de la secuencia y el estado inicial del Subcircuito2 es 0.

## Entrega

Descargar de Moodle los archivos examenlabo.xlsx, examenlabo.docx y examenlabo.circ. y cambiar el nombre de todos estos archivos acorde con sus datos personales, poniendo  apellido1apellido2_nombre-sesion12.xslx, apellido1apellido2_nombre-sesion12.docx y apellido1apellido2_nombre-sesion12.circ.

Después de terminar el ejercicio, el estudiante debe subir a Moodle el citado archivo apellido1apellido2_nombre-sesion12.circ que incluirá los diseños correspondientes a los circuitos de las Partes 1, 2 y 3. También se deberá subir el archivo .xlsx y/o .docx para documentar el proceso de implementación de los diferentes apartados. Al final, en la entrega debe haber un solo archivo .zip o .rar que contenga los archivos mencionados anteriormente, nombrado de la siguiente manera apellido1apellido2_nombre-sesion12.zip

Todos los diagramas lógicos de circuitos entregados emplearán señales de entrada y salida de 1 bit de anchura (no multibit) y dichas señales estarán etiquetadas de modo coherente con la especificación dada. En dichos circuitos las señales constantes (0, 1) deben emplear elementos constantes (contenidos en librería wiring), no señales con valor variable (modificable).

[CastillejoBravo_Paula-sesion12.zip](CastillejoBravo_Paula-sesion12.zip).

[CastillejoBravo_Paula-sesion12](CastillejoBravo_Paula-sesion12).