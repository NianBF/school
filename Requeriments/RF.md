# Requerimientos Funcionales
###### RF = Requerimiento Funcional
##### REQUERIMIENTOS DE USUARIO: Son declaraciones, en lenguaje natural y en diagramas, de los servicios que se espera que el sistema proporcione y de las restricciones bajo las cuales debe funcionar.
##### REQUERIMIENTOS DE SISTEMA: Estos requerimientos establecen con detalle las funciones, servicios y restricciones operativas del sistema. El documento de requerimientos del sistema deberá ser preciso, y definir exactamente lo que se va a
#### REQUERIMIENTOS FUNCIONALES: Son declaraciones de los servicios que debe proporcionar el sistema, de la manera en que éste debe reaccionar a entradas particulares. O también pueden declarar explícitamente lo que el sistema no debe hacer.
#### REQUERIMIENTOS DE PRODUCTO: Estos requerimientos especifican el comportamiento del producto.  Dentro de estos encontramos lo referente a Rendimiento del sistema (memoria, rapidez, etc.) Y Fiabilidad (tasa de fallos aceptable).
#### REQUERIMIENTOS ORGANIZACIONALES: Estos requerimientos se derivan de políticas y procedimientos existentes en la organización del cliente y en la del desarrollador. Un ejemplo de este tipo de requerimientos podría ser el tiempo solicitado de entrega a la empresa.
#### REQUERIMIENTOS EXTERNOS: Estos requerimientos se derivan de políticas y procedimientos existentes en la organización del cliente y en la del desarrollador. En esta clasificación de requerimientos encontramos los que tienen que ver con Requerimientos Legislativos, Requerimientos Éticos, etc.
##### REQUERIMIENTOS DE DOMINIO: Son requerimientos que provienen del dominio de aplicación del sistema y que reflejan las características y restricciones de ese dominio. Pueden ser funcionales o no funcionales.
___
___
## Roles

* Rector/Administrador
* Coordinador/Líder
* Profesor
    * Director de Curso
    * Asignado
* Estudiante
    * Representante -*[Cargo de estancia de Gobierno Estudiantil]*-
    * Normal/Estudiante
* Padre/Madre/Acudiente
---

0. **RF 0:** _Registro de Usuarios_ ->
El usuario administrador/origen vendrá por defecto en el sistema y sus credenciales permitirán crear a los usuarios que utilizarán el sistema; Los demás usuarios podrán ser creador por un usuario administrador.

2. **RF 1:** _Inicio de Sesión_ ->
El usuario podrá ingresar al sistema iniciando sesión con usuario y contraseña asignados.

4. **RF 2:** _Registro de Notas_ ->
EL sistema tendrá espacios para asignar una nota a cada temática registrada por el rol «Profesor» y dejar registro de las actividades realizadas, no realizadas, aprobadas y no aprobadas por los usuarios de rol «Estudiante».

3. **RF 3:** _Cálculo de Notas_ ->
El sistema permitirá escoger al rol «Profesor» la forma en que se cálcula la nota y el sistema calculará de forma automática la nota definitiva de los usuarios con rol «Estudiante».

