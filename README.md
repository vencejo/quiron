# quiron
Gestor educativo basado en la Blockchain de Ethereum

## Ideas

Partiendo de un sistema de formación en el que la red de alumnos sea autosuficiente , y se corrijan los ejercicios entre los alumnos , por ejemplo, con anillos de corrección tal y como hemos hecho en el taller de Python básico.

Hacer un framework que automatice la propuesta ,la recepción y la corrección de los ejercicios, así como la asignación de títulos según la consecución de los objetivos (achievement traking) .

El gestor podría también incluir el pago de tasas a la organización del curso por la realización de los distintos temas, así el alumno solo pagaría por las lecciones que haya dado.

El framework estaría basado en la red ethereum , 

con un acceso al público mediante una web hecha con javascript, o con un acceso desde programas de python si el curso está basado en esta tecnología.

Hacer el desarrollo del proyecto transparente y continuamente respaldado por github.

Dar de alta el proyecto en dapps ( https://www.stateofthedapps.com )



## Supuesto de trabajo en el que funcionaría el gestor

Un curso/taller/hackaton al que asistan alumnos presenciales y/o virtuales tutorizados por un profesor que les va poniendo ejercicios y/o retos.

La resolución de estos ejercicios será entregada por los alumnos al gestor que se encargará de comprobar que la fecha de entrega está dentro de los plazos marcados por el tutor.

Una vez recepcionados los ejercicios la plataforma se encargaría de asignar los correctores de los mismos entre los propios alumnos y/o el profesor.

El tiempo de corrección y la entrega de las correcciones también serían controlados por la plataforma.

Los alumnos tendrán la oportunidad de quejarse un número limitado de veces de las correcciones malas que consideren que están sufriendo. Entonces la aplicación activará el proceso de corrección por parte del profesor.

Así como los correctores puntuarán a los alumnos, los alumnos puntuarán a sus correctores en la aplicación.

El proceso de corrección es anónimo y los correctores y alumnos no saben quienes les ha tocado.

La aplicación guardará el registro de las puntuaciones de los alumnos tanto de sus ejercicios como de sus correcciones.

La aplicación , si se ha superado el umbral mímimo exigido y el alumno paga las tasas del curso, hará público el “diploma” o grado de consecución del taller que quedará registrado en la blockchain.  




## Funcionalidades básicas

1. Dar de alta a los alumnos y profesores

2. El profesor da de alta el ejercicio/reto con los correspondientes tiempos de entrega y corrección 

3. La aplicación  se encargará de comprobar que la fecha de entrega está dentro de los plazos marcados por el tutor

4. La plataforma se encargaría de asignar de manera aleatoria los correctores de los mismos entre los propios alumnos y/o el profesor.

5. El tiempo de corrección y la entrega de las correcciones también serían controlados por la plataforma.

6. En la primera versión del taller los ejercicios tendrán el formato de texto plano , y podrán ser explicaciones mas o menos literarias o programas de python, etc ...

7. Los alumnos tendrán la oportunidad de quejarse un número limitado de veces de las correcciones malas que consideren que están sufriendo. Entonces la aplicación activará el proceso de corrección por parte del profesor.

8. Los alumnos puntuarán a sus correctores en la aplicación.

9. El proceso de corrección es anónimo y los correctores y alumnos no saben quienes les ha tocado.

10. La aplicación guardará el registro de las puntuaciones de los alumnos tanto de sus ejercicios como de sus correcciones.

11. La aplicación podrá controlar el pago de tasas por parte de los alumnos

12. Si se ha superado el umbral mínimo exigido y el alumno paga las tasas del curso, la dapp hará público el “diploma” o grado de consecución del taller que quedará registrado en la blockchain.
