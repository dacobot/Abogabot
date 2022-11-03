# Abogabot
Práctica de introducción Launch X Latam
# Toma de Requerimientos

---

## Introducción

Un despacho de abogados requiere automatizar el primer paso para presentar una demanda, esto es un paso inicial (asesoría) en el que se pierdo mucho tiempo haciéndolo de forma manual (vía telefónica y/o mediante juntas con el cliente). Otro de los puntos donde el cliente (El despacho de abogados) identifico que se requiere de automatización es en el proceso de notificar a sus clientes los avances, cambios o retrasos en sus demandas, por lo que se tomo la decisión de automatizar el proceso, para que el cliente haga el primero contacto con el despacho de forma individual llenando un formulario a través de una página web (aplicación web), y posteriormente le pueda dar seguimiento a su demanda sin la necesidad de que un abogado lo atienda de manera personal.

### Objetivos

El objetivo principal del proyecto es el ahorro de tiempo mediante la automatización del proceso de iniciar una demanda ante un abogado y su posterior seguimiento. Para que esto sea posible, la página web deberá de contener los siguientes puntos:

- Cuentas de cliente y abogado/administrador.
- Formulario.
- Método de pago seguro.
- Seguimiento de las actualizaciones del proceso legal.
- Dashboard de pagos.
- Sistema de notificaciones para avance del proceso vía correo electrónico.
- El formulario ingresado crea un documento word con el formato legal para iniciar el proceso por parte del abogado.
- Dashboard para el administrador, donde se actualiza el proceso de demanda y puede agregar comentarios en cada caso del proceso, este dashboard puede ser visualizado por el cliente, pero solo el administrador puede entrar datos.

### Valor del producto

Los beneficios de este producto se verán reflejados en:

- Ahorro de tiempo
    - Los abogados ya no tendrán que entrevistarse personalmente con el cliente para el asesoramiento inicial y ver si la demanda es factible.
    - El cliente precisará desde un inicio los datos que son relevantes para la asesoría (mediante el formulario)
    - Los abogados tendrán un documento transcrito en automático donde puede empezar a trabajar de inmediato.
    - Ya no es necesario que los abogados se comuniquen personalmente con el cliente ante cualquier actualización de la demanda, el cliente lo podrá estar al tanto de las actualizaciones a través de su cuenta de usuario.
- Mejoramiento en la calidad de atención al cliente
    - Una vez que el cliente envía el formulario y hace el pago por la asesoramiento inicial, se inicia una relación cliente-proveedor de servicios.
    - Los clientes ya no tienen qué esperar a que un abogado este disponible (vía telefónica o personal) para conocer las actualizaciones de su caso.
- Ganar dinero
    - Al ahorrar tiempo y mejorar la calidad de atención al cliente se espera que sus servicios se requieran más.

### Especificaciones

- Página responsive, para poder visualizar desde el celular
- Preferencia de colores del buyer azul marino y blanco (acepta propuestas)
- Interfaz amigable.

### Buyer Persona

Cliente ideal del proyecto.
[Buyer Persona.pdf](https://github.com/dacobot/Practicas-Launch-X/files/9816451/Buyer.Persona.pdf)

### Público objetivo

Posibles usuarios del servicio
![Target Audience](https://user-images.githubusercontent.com/108957175/196586615-a83b9fec-ce22-41f7-9634-2cf12c1c7af5.jpg)

## Wireframe
![Flowchart (1)](https://user-images.githubusercontent.com/108957175/196587537-21190b63-095c-45cb-93bf-5a2ed7f5cf04.jpg)

### UX Cliente

1. Cliente entra a la página web
2. Visualiza tres menús
    1. Página Corporativa (misión, visión, valores, quien son, contacto)
    2. Asesoría (Consulta folio, Nueva Asesoría)
    3. Inicio de Sesión. (Cliente, Abogado, Nuevo usuario)
3. En el apartado de asesoría, el submenú “Nueva Asesoría”
4. Llena el formulario de toma de datos del caso
5. Realiza el pago de la asesoría
6. Se acepta el pago
7. Se genera un folio de seguimiento
8. Da opción a crear cuenta.

### UX Administrador

1. El administrador recibe la notificación de que se genero un pago, con los datos del formulario se genera automáticamente un documento en formato word para empezar el proceso.
2. El pago se recibe y visualiza en el Dashboard de Ingresos.
3. El formulario se recibe, se genera un docto en word que se visualiza en el Dashboard de Casos.
4. El administrador ingresa a la página de entrada
5. Visualiza tres menús
    1. Página Corporativa (misión, visión, valores, quien son, contacto)
    2. Asesoría (Consulta folio, Nueva Asesoría)
    3. Inicio de Sesión. (Cliente, Abogado, Nuevo usuario)
6. Inicia sesión como Abogado
7. Visualiza tres menús
    1. Notificaciones
    2. Dashboard Pagos
    3. Dashboard Casos
8. Accede al dashboard de casos dónde ya esta el documento de word con los datos de caso
9. Proceso de caso (indagaciones, solicitud de pruebas, investigación, requisitos documentales, etc)
10. Revisión avances
11. Agregar comentarios
12. Resolución de caso
13. Fin.
