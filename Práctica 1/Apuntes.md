# Ingeniería de requisitos: Lista inicial de requisitos

## Descripción general del problema 

- La aplicación debe gestionar los cobros de las rentas de alquiler de forma que el arrendador reciba periodicamente el cobro del arrendatario. En esta transferencia la agencia inmobiliaria recibe una comisión
- Para la creación de contratos de alquiler con clientes de la agencia la aplicación debe distinguir entre arrendador y arrendatario:
  - El arrendador debe tener un contrato con la agencia 
  - El arrendatario debe tener un contrato con la agencia y con el arrendador
- Control de la reclamación de deudas de inquilinos tanto para el arrendador como para la agencia. El arrendatario recibirá una penalización establecida en el contrato en base a la magnitud del impago
  - El arrendador podrá reclamar en cualquier momento pasado el plazo de pago del alquiler y el arrendatario recibirá una notificación
  - La agencia notificará al inquilino tras un periodo establecido en el contrato y si se requiere, se le deshauciará previo aviso
- El inquilino y el casero pueden notificar de las averías en las viviendas alquiladas. Dependiendo de la magnitud, la responsabilidad recaerá sobre el casero o la agencia. Si se determinara que la avería es provocada, el inquilino deberá responder con su fianza
  - Los contratos para locales comerciales incorporan un seguro sobre posibles desperfectos

- La aplicación debe poner en contacto arrendadores que deseen intercambiar sus viviendas
- La agencia debe tener integración con páginas de alquiler generalistas para listar los anuncios. La página web de la agencia se publicitará mediante anuncios en páginas web no relacionadas. También se publicarán anuncios de la localidad en periódicos de dicha zona.

### IMPLICADOS

- **Arrendador: **usuario sistema
  - Poner y retirar propiedades del mercado
  - Atender a los posibles arrendatarios
- **Arrendatario:** usuario sistema
  - Alquilar propiedades
  - Ponerse en contacto con arrendadores
- **Agente inmobiliario:** usuario producto
  - Poner en contacto arrendador y arrendatarios
  - Gestionar y diseñar el contrato
  - Verificar el correcto estado de las propiedades

### OBJETIVOS



## Lista estructurada de requisitos

### REQUISITOS DE INFORMACIÓN

- **RI-1.** Clientes

  Información del conjunto de todos los usuarios del sistema

  - Contenido: DNI, Datos personales, Restricciones de área (zona, localidad, provincia), Datos de pago
  
- **RI-2. ** Propiedades

  Información del conjunto de todas las propiedades en alquiler

  - Contenido:

  

### REQUISITOS FUNCIONALES

### REQUISITOS NO FUNCIONALES

## Glosario

- Arrendador: persona que pone en alquiler una propiedad de cualquier tipo 

- Arrendatario: persona que alquila una propiedad de cualquier tipo
- Propiedad: bien inmueble que se arrenda o es arrendado
  - Vivienda: propiedad habilitada para residencia (posee cedula de habitabilidad)
  - Local comercial: propiedad habilitada para actividades comerciales (no posee cedula de habitabilidad)
- Casero: arrendador de una vivienda
- Inquilino: arrendatario de una vivienda
- Fianza: importe extra al primer pago utilizado como aval para el inquilino y devuelto al final del contrato tras la resta de posibles penalizaciones

- Intercambio de viviendas/Intercambio: proceso mediante el cual dos propietarios arrendadores arrendan mutuamente sus respectivas viviendas durante un periodo no superior a tres meses
- 