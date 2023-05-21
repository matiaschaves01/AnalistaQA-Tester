---------------------------------------------------------------------------------------------------------------------
/////////////////////////////////--------<Los fundamentos de la norma ISO 25010>------//////////////////////////////

<La norma ISO 25010 >
Se enfoca en la calidad del producto de software y establece fundamentos clave para evaluar y medir esa calidad.>

<Fundamentos :/>

<Enfoque en la calidad del producto:>
Se centra en evaluar y medir la calidad del producto de software en términos de características específicas y atributos de calidad.

<Características de calidad:> 
Define un conjunto de características de calidad fundamentales para evaluar un producto de software, como la funcionalidad, usabilidad, eficiencia, fiabilidad, seguridad, mantenibilidad y portabilidad.

<Atributos de calidad:>
Cada característica de calidad se desglosa en atributos más específicos que se utilizan para medir y evaluar el nivel de calidad, como la idoneidad, exactitud e interoperabilidad.

<Evaluación y métricas:> 
Establece criterios para evaluar cada atributo de calidad mediante la definición de métricas y métodos de evaluación. Esto permite medir objetivamente el nivel de calidad y compararlo con requisitos y estándares establecidos.

<Orientación al usuario:> 
Considera las necesidades y expectativas de los usuarios finales del software, centrándose en la satisfacción del usuario y la usabilidad como aspectos clave de la calidad

<Adaptabilidad y mejora continua>: 
Promueve la adaptabilidad del software a diferentes contextos y la mejora continua de la calidad a lo largo del ciclo de vida del producto.

Estos fundamentos proporcionan una base sólida para evaluar, medir y mejorar la calidad del software, asegurando que cumpla con los requisitos y expectativas de los usuarios finales.
--
<Pensar las cosas de otra forma. En un producto, pagina, software hay que analizar multiples cosas.
Abtraerse cuando le dan un problema, entender y plasmar los datos y la situacion.>
--
<Casos de uso y Escenarios:>
Entendimiento  de los usuarios y o publico (A quien esta apuntado)
Sistema Operativo, Deskstops , Mobile
Roles cumplen los usuario, para que cantidad de usuarios
En que idioma esta
Con que Finalidad
Si es de uso interno o Externo
Si consume Apis publicas o privadas
Para que ubicacion es, si es nacional , internacional etc. (Geolocalizacion)
Disponibiliad de dias y horarios especificos

<Utilizar Plataformas para modelar, diseñar Problemas y Soluciones.
En Draw.io , Visio(Microsoft)>

<Keywords>

<Eje>                               <Tecnico>             
-Cliente                            -Gravedad/Prioridad
-Proceso                            -Caja Blanca, Caja Negra
-Calidad                            -Para que probamos
-Analisis                       
-Entender los Requerimientos

<Diferencias entre Tester y Analista QA>
<Tester:>
Ejecuta casos de prueba para identidificar errores, registra los problemas haciendo tickets en Jira o Trello, valida el funcionamiento
<Analista QA:>
Diseña, Analiza y Planifica los casos de prueba, los requerimientos, las historias de usuario para el Tester.

<Gravedad>: Esta relacionado a lo Funcional.

<Prioridad>: Esta relacionado con la Urgencia.


Ejemplo de una Tostadora: Que probarias?
<Datos de prueba>
Primordialmente si cumple la funcion para la que fue hecha
Celentar Tostadora
Si tiene algun indicador de prendido
Probar un Pan
Verificar si tiene detalles esteticos(bug)
Probar enchufada varias horas para saber si resiste enchufada
Si tiene algun problema electrico

La tostadora tiene distintos tipos de fallas pero tiene que salir a producion:
Determinar las gravedades y Prioridades

1- A las 5hs de enchufada explota
2- El nombre de la marca esta mal escrito
3- No hace pan caliente
4- Tiene un raspon en la parte superior derecha

Escalas de gravedades:
1- No hace pan caliente
2- El nombre de la marca esta mal escrito
3- A las 5hs de enchufada explota
4- Tiene un raspon en la parte superior derecha

Reportar Bugs y/o Error
Informacion relevante
Datos: Modelo, Lote, Codigo, Color
Falla: Reproduccion de falla paso por paso para llegar a la falla, Adjuntar fotos
Como Deberia Funcionar:
En este caso se refiere a la Gravedad y Prioridad, debemos listarlas. La Prioridad es si es que se puede sacar a produccion. 
Por ejemplo si la tostadora explota a las 5hs, pero todo lo demas cumple la funcion de Tostadora , se le envia un carta al usuario con una advertencia que no debe dejarla enchufada mas de 5hs, y ademas tambien verificar si se puede hacer un cambio de producto en el lugar donde lo compro, si tiene que ir a un deposito , o a la fabrica directamente.

<Los 7 principios del Testing:>

<1 .-La prueba muestra la presencia de defectos:> 
La finalidad de las pruebas es revelar la presencia de defectos y errores en el software.
<2 .-La exhaustividad de las pruebas es imposible:>
Es imposible probar todas las combinaciones posibles de un sistema debido a limitaciones de tiempo y recursos.
<3 .-La detección temprana de defectos:> Cuanto antes se detecten y corrijan los defectos, más efectivo y menos costoso será el proceso de prueba.
<4 Agrupación de defectos:> Los defectos suelen agruparse en determinadas áreas o módulos del software, lo que ayuda a enfocar los esfuerzos de prueba.
<5 .-El parado de defectos:> 
Se ha observado que la distribución de los defectos sigue una curva de Pareto, es decir, un pequeño número de módulos concentra la mayoría de los defectos.
<6 .-La dependencia del contexto:> 
La estrategia de prueba debe adaptarse al contexto del proyecto, teniendo en cuenta factores como los objetivos, los riesgos y los recursos disponibles.
<7 .-La inexistencia de pruebas exhaustivas:> 
A pesar de los esfuerzos, las pruebas no pueden garantizar la ausencia de defectos en el software.


<Caja Negra:> / <Caja Blanca:>

<La caja negra>
Se enfoca en probar el software desde una perspectiva externa, evaluando las entradas y salidas sin conocer su estructura interna.
<Caja blanca>
implica conocer el código y la estructura interna del software para evaluar su funcionamiento interno. Ambos enfoques son importantes y se utilizan para diferentes propósitos en el aseguramiento de la calidad del software.
