# CONSTRUFURGO



## INTRODUCCION

Este proyecto se centra en la optimización y automatización de procesos clave para impulsar el crecimiento de nuestra empresa, específicamente en las áreas de ventas, generación de leads y oportunidades de negocio. Reconociendo el valor estratégico de la información, implementaremos soluciones para centralizar y facilitar el acceso a datos relevantes, permitiendo un análisis más preciso y la mejora continua de nuestras métricas de desempeño.

Además, hemos desarrollado un sistema de alertas proactivas con el objetivo de elevar la satisfacción del cliente, asegurando una atención oportuna y personalizada que no solo responda a sus necesidades expresas, sino que también anticipe y satisfaga sus requerimientos futuros.

![![Image](https://media.discordapp.net/attachments/1218023015510577187/1352321232715907143/Gemini_Generated_Image_dckiscdckiscdcki.jpg?ex=67dd96ca&is=67dc454a&hm=71b37097115ae378dae62a17364a356b9a647d167f19b0b6c423a757eb7987ea&=&format=webp&width=549&height=549)



# Configuración General

## Información Legal de la Empresa

``````
Se realiza la creacion de la cuenta ConstruFurgo.
``````

1. **Razón Social**: ConstruFurgo S.A.S.

2. **Número de Identificación Tributaria (NIT)**: 901456789-2.

3. **Domicilio Principal**: Av. Boyacá #12-33, Bogotá, Colombia.

4. **Capital Social**: $5,000,000 USD.

5. **Tipo de Empresa**: Sociedad por Acciones Simplificada (S.A.S.).

6. **Objeto Social**: Diseño, fabricación, comercialización y mantenimiento de furgones industriales.

7. **Representante Legal**: Juan Pérez López.

8. **Registro Mercantil**: Matrícula 456789 en la Cámara de Comercio de Bogotá.

9. **Correo Oficial**: contacto@construfurgo.com

   

   ​	***Especificaciones:***

   1.  Se realizo la creacion de la empresa con los datos solicitados.
   2.  Dentro de la cuenta se agrego como contacto al representante legal: Juan Pérez López

   

   ​	***Datos faltantes:***

   1. Numero de contacto
   2. Cantidad de empleados
   3. Ingresos anuales
   4. Pagina de la empresa

   ![image](https://media.discordapp.net/attachments/1218023015510577187/1352311915996774451/image.png?ex=67dd8e1d&is=67dc3c9d&hm=711afe233959d72a3bde8ea8e4254d0c85eddecc77d24e98eab2d8800f298676&=&format=webp&quality=lossless&width=763&height=432)



## CREACION Y MODIFICACION DE OBJETOS

**leads:**

Se agrega el campo Contador interacciones el cual tiene un valor por default para que no hayan furutos problemas al momento de interaccionar dentro de un flow con este campo.

![Image](https://media.discordapp.net/attachments/1218023015510577187/1352344785674834000/image.png?ex=67ddacba&is=67dc5b3a&hm=b6ac8d725434dc196e890fcf00d9236c44ef88f07e56601c8f10d9d174064809&=&format=webp&quality=lossless&width=926&height=432)



**Productos:** 

Se agregaron los campos de Stock, Category y Price, los cuales almacenaran la informacion adicional de los productos.

![Image](https://media.discordapp.net/attachments/1218023015510577187/1352371425557741578/image.png?ex=67ddc589&is=67dc7409&hm=02e4fd8dd211ab0659debe660e75a4e8fbcb756eb0102016e125c1feed4af648&=&format=webp&quality=lossless)



**Facturas:**

Se crea el objeto factura donde se tomara toda la informacion de las opportunidades cerradas.

![Image](https://media.discordapp.net/attachments/1218023015510577187/1352344522708746250/image.png?ex=67ddac7b&is=67dc5afb&hm=916bfcc1918a05f5f985b3a0b7dae1831788d061a639b9f609e29bd7f3369591&=&format=webp&quality=lossless&width=1075&height=432)



**Facturas Pagadas:** Se crea el objeto donde se guardaran todas las facturas que su estado sea pagado

![Image](https://media.discordapp.net/attachments/1218023015510577187/1352345041762385940/image.png?ex=67ddacf7&is=67dc5b77&hm=8cdde033a611d08a3efe1697e65fdbf325a0b8ed64cfbb41b365abc6853f1d6a&=&format=webp&quality=lossless&width=1090&height=432)



**Cuentas por Cobrar**: se crea el objeto donde se guardara todas las facturas que su estado sea pendiente

![Image](https://media.discordapp.net/attachments/1218023015510577187/1352345465076584540/image.png?ex=67ddad5c&is=67dc5bdc&hm=08c8a3f77e52d57d2148a2127d7cd4f19ba02f49408ae831e0c8de7a9aaf0434&=&format=webp&quality=lossless&width=1046&height=432)



## JERARQUIA

    ConstruFurgo se estructura jerárquicamente de la siguiente manera:

1.  **Gerencia General (CEO)**: Responsable de la estrategia global de la empresa.
2.  **Gerencia de Ventas**: Administración de clientes, oportunidades de negocio y crecimiento del mercado.
3.  **Gerencia de Producción**: Gestión de fabricación de furgones y control de calidad.
4.  **Gerencia de Soporte Técnico**: Atención a clientes post-venta y resolución de problemas.
5.  **Gerencia de Compras y Logística**: Manejo de proveedores y optimización de entregas.

![](![Image](https://media.discordapp.net/attachments/1218023015510577187/1352314703157919776/image.png?ex=67dd90b6&is=67dc3f36&hm=92e490a8f363567f673647c7cf08adde328cd7cf58770952e7ab1c9a68c16f86&=&format=webp&quality=lossless&width=381&height=449)



## PERFILES

    El organigrama de ConstruFurgo se ha implementado en Salesforce, reflejando la estructura jerárquica de la empresa.Los permisos de objetos se han configurado de la siguiente manera:		



### PERFILES DE VENTAS

* #### Cuentas (Accounts):

  - **Acceso**: Lectura y escritura.
  - **Justificación**: Proporcionar visibilidad completa de las cuentas objetivo de ventas para acceder a información crucial y preparación previa al contacto.
  - **Permisos específicos**:
    - Lectura de los campos "Activo", "Descripción de la empresa", "Industria" e "Idioma preferido" para facilitar la comprensión del perfil de cada cuenta y anticipar las necesidades de comunicación.
    - Edición del campo "Teléfono" para permitir la actualización de la información de contacto.
    - Se le dieron permisos únicamente para la aplicación Sales Aplication



* #### Contactos (Contacts):

  - **Acceso:** Lectura y escritura.

  - **Justificación**: Permitir la gestión y mantenimiento de la información de los contactos objetivo de ventas, facilitando el seguimiento, la comunicación y la construcción de relaciones.

  - **Permisos** **específicos**: No se requieren modificaciones de campos específicos.

    

* #### Oportunidades (Opportunities):

  - **Acceso:** Lectura y escritura.

  - **Justificación**: Gestionar el seguimiento de clientes y el progreso de ventas, visualizando y actualizando información crucial.

  - **Permisos específicos:**

    - Edición de los campos "Precio", "Origen del lead" y "Siguiente paso" para permitir la actualización de datos necesarios para el avance de las oportunidades.

    - Implementación de una notificación al CEO (a través de flujo) por cada cambio en una oportunidad.

      

* #### Clientes Potenciales (Leads):

  - **Acceso**: Lectura y escritura.

  - **Justificación**: Gestionar eficazmente la información de clientes potenciales, facilitando la captura, el acceso y la actualización de datos.

  - **Permisos específicos**: No se requieren modificaciones de campos específicos.

    

* #### Campañas (Campaigns):

  - **Acceso**: Lectura y escritura.

  - **Justificación**: Permitir el seguimiento de iniciativas de marketing y ventas, asociando leads y oportunidades, y mejorando las interacciones con clientes potenciales.

  - **Permisos específicos:** Habilitación de los campos "Nombre de la campaña", "Estado de la campaña", "Tipo de campaña", "Fecha de inicio", "Fecha de fin" y "Miembros de la campaña"

  - **Acceso**: Lectura y modificación.

  ![](https://media.discordapp.net/attachments/1218023015510577187/1352319121295151196/image.png?ex=67dd94d3&is=67dc4353&hm=2a30636a486866676662a060c41d6f1c82102d71479d01aab325902f4ddf283d&=&format=webp&quality=lossless&width=921&height=432)

  

  ![Image](https://media.discordapp.net/attachments/1218023015510577187/1352317777850925097/image.png?ex=67dd9393&is=67dc4213&hm=ed4f475ba472de81bb5f086a92fb870ffecb2cf975e5967f6d34e1dbc97b681c&=&format=webp&quality=lossless&width=980&height=432)


### **Perfil: Production Manager**

**Productos (Products):**

- **Acceso**: Lectura.

- **Justificación**: Proporcionar una visión clara y actualizada del catálogo de productos para la planificación y gestión de la producción.

- **Permisos específicos**: Habilitación de los campos "Nombre del producto", "Proveedor", "Stock", "Precio".

  

**Inventario (Inventory):**

- **Acceso**: Lectura y escritura (permiso por defecto).

- **Justificación**: Permitir al Production Manager gestionar y mantener registros precisos del inventario, asegurando la disponibilidad de materiales y productos para la producción. Esto es crucial para evitar retrasos y optimizar el flujo de trabajo.

  

**Recursos (Resources):**

- **Acceso**: Lectura y escritura (permiso por defecto).

- **Justificación**: Facilitar la gestión de recursos necesarios para la producción, incluyendo maquinaria, herramientas y personal. Esto permite al Production Manager asignar recursos de manera eficiente y garantizar la disponibilidad de los mismos.

  

**Órdenes de trabajo (Work Order):**

- **Acceso**: Lectura y escritura (permiso por defecto).

- **Justificación**: Permitir al Production Manager crear, gestionar y supervisar las órdenes de trabajo, asegurando que la producción se realice de acuerdo con las especificaciones y plazos establecidos. Esto facilita el seguimiento del progreso de la producción y la identificación de posibles problemas.

  

**Informes y Paneles (Reports & Dashboards):**

- **Acceso**: Lectura.

- **Justificación**: Proporcionar al Production Manager acceso a informes y paneles relevantes para el seguimiento del rendimiento de la producción, la identificación de áreas de mejora y la toma de decisiones informadas. Esto permite una gestión basada en datos y una mejora continua de los procesos de producción.

  

  ![Image](https://media.discordapp.net/attachments/1218023015510577187/1352319376962883644/image.png?ex=67dd9510&is=67dc4390&hm=9cf6d6a0628b64be1ff412eded373f8ec2ed80785d01b2668afb8f3af2018ec0&=&format=webp&quality=lossless&width=925&height=432)

  

# PROCESOS DE NEGOCIO

### VALIDACION DE DATOS LEADS:

- Para los Leads hemos creado 3 tipos diferentes de validacion sobre el telefono y el email:

  #### Telefono:

- Se realizan validation rules para que este campo no quede vacio.

![](https://media.discordapp.net/attachments/1218023015510577187/1352323484210036788/image.png?ex=67dd98e3&is=67dc4763&hm=0acd93e37d7c23da84099bfbf0dbc2e880835f1ca8c625257cdd8c605747bb35&=&format=webp&quality=lossless&width=790&height=429)

- Se valida que el telefono tenga el indicador correcto, en este caso solo se modifico para el de colombia por lo que no aceptara telefonos extranjeros, se usa el not regex para que no salten los 2 errores al mismo tiempo.

![Image](https://media.discordapp.net/attachments/1218023015510577187/1352324704056250509/image.png?ex=67dd9a06&is=67dc4886&hm=8b9852ed6341fbd1da27caee44aafa5dab772845cfcd9dbcc6d00f877016f676&=&format=webp&quality=lossless&width=765&height=432))



- Se verifica que el numero después de el indicador tenga un valor exacto de 10 dígitos, se realiza una omisión de campos en blanco para que no los tome como si llegasen a ser un numero y no tome letras.



[![Image](https://media.discordapp.net/attachments/1218023015510577187/1352324320168247469/image.png?ex=67dd99aa&is=67dc482a&hm=eadb5078a55aba7fca13bba3c7bd42344b6954a41b3260e58f85ce3479f1eacd&=&format=webp&quality=lossless&width=757&height=478)]()





#### EMAIL:

- Se verifica que el email contenta @:

![](https://media.discordapp.net/attachments/1218023015510577187/1352327452411691029/image.png?ex=67dd9c95&is=67dc4b15&hm=e63f4a2721cd50f74029e5ef216bf70c994f0b62ab15e811b2c45c12ca629c87&=&format=webp&quality=lossless&width=757&height=454)

- Se verifica que tenga terminacion en un dominio conocido, se validan unicamente .com y .es

  ![Image](https://media.discordapp.net/attachments/1218023015510577187/1352327348048892036/image.png?ex=67dd9c7c&is=67dc4afc&hm=0580360e35dd0f5ed14f41d4d3f676aebb791f28f1467ff1b5c7e6b0a73e3955&=&format=webp&quality=lossless&width=759&height=432)



### FLOWS

- Antes de mostrar los flows, vamos a ver el paso a paso detras de las alertas que se usan en estos flows, como la creación de templates y los email alerts.

  #### Templates y Alertas

- **Paso 1:** Se crea una carpeta de templates para tener mas organizada la información, en este caso la llamamos ConstruFurgo

​		![](https://media.discordapp.net/attachments/1218023015510577187/1352328927124787210/image.png?ex=67dd9df5&is=67dc4c75&hm=141500f5aaa2a14cd504c56eaa7781fcb37bbe2568b143cbcc59ccdfc89cbe71&=&format=webp&quality=lossless&width=1278&height=295)

- Se modifica el contenido sobre que es lo que se va a informar en el email alert.

![Image](https://media.discordapp.net/attachments/1218023015510577187/1352329973641252894/image.png?ex=67dd9eee&is=67dc4d6e&hm=af61bf71a25138f35520f4c85ab929e76d91df75eeaa2000473f175221fbc944&=&format=webp&quality=lossless&width=815&height=432)

- **Paso 2:** Ahora vamos a asignarle este template a un email alert para poder usarlo en los futuros flows, 	en este punto es donde configuramos a quien se le va a enviar el email, En este punto en la parte	inferior podremos agregar correos adicionales si fuese necesario el envio de correo externo.

![](https://media.discordapp.net/attachments/1218023015510577187/1352330723956363305/image.png?ex=67dd9fa1&is=67dc4e21&hm=41c79aa935c1e17d33870e61ed0b144d794820391cc9200df6dd8d1cb8ca1366&=&format=webp&quality=lossless&width=757&height=475)

​	Realizamos los mismos pasos con los demas templates y alertas.



### 	FLOWS

##### 	Alerta nuevos leads

- Vamos a revisar el paso a paso de la creacion del flow de alerta de leads, donde se enviara una notificacion a el gerente de ventas una vez se haya creado un lead, para esto creamos el flow tipo triggering verificamos que el iniciador sea cuando se crea el objeto y vamos a seleccionar el objeto de leads que s nuestro iniciador.
- Creamos un email alert, seleccionamos el email alert anteriormente creado y nombramos la alerta, en la parte de abajo debemos coincidir el lead con el id.

​	![](https://media.discordapp.net/attachments/1218023015510577187/1352333191943557152/image.png?ex=67dda1ee&is=67dc506e&hm=c7a2b8840511a13b660aa09322d2dddcee89157f9d020ff389e5ff1afb877e2d&=&format=webp&quality=lossless&width=1204&height=432)

​	



##### 	Cambio de lead a opportunidad

- En este proceso veremos como crear una nueva opportunidad a traves de los leads, para esto creamos un flow con iniciador en task, donde se verifica el id de cada task creada para ir aumentando el contador de interacciones de el cliente.

  Explicacion: 

  En el get records se toman todos los datos de el objeto lead

  En el update records se verifica que el id registrado en la tarea sea el mismo del lead

  A este lead se tomara el campo contador de interacciones y se le ira sumando de a 1

  

  ![Image](https://media.discordapp.net/attachments/1218023015510577187/1352337109934936135/image.png?ex=67dda594&is=67dc5414&hm=90612aad3c636eb80c597fcc8f5a3d3fc4233f0f8a02f1ccb19feb80ecc29966&=&format=webp&quality=lossless&width=926&height=432)

  

  

- Para mas claridad de como se realiza debido a que no se puede poner directamente el campo de contador de interacciones se deja una imagen de como se realizo el aumentador, este es un campo tipo formula, el cual toma el campo de contador de interacciones y lo suma en 1:

![](https://media.discordapp.net/attachments/1218023015510577187/1352338106379927613/image.png?ex=67dda681&is=67dc5501&hm=bd41d45f902c40d4090ce03246e69dde3948924890199d7dc3c41f904275e356&=&format=webp&quality=lossless&width=841&height=432)

- Se toma un accion y se busca la opcion new opportunity, seguido mappeamos los datos que queremos que queden dentro de el nuevo opportunity.

  ![Image](https://media.discordapp.net/attachments/1218023015510577187/1352565786794786836/image-20250320125104935.png?ex=67de7a8d&is=67dd290d&hm=1c211fde021c1f2602a6cdc7460f97a8102fbd99911fe056715303c88c055538&=&format=webp&quality=lossless&width=982&height=432)

  

- Ahora tenemos una desicion donde se podra modificar el envio de correo a los clientes por si se desea realizar algun cambio futuro sobre el envio hacia los clientes, si desean que se envie el correo o no en este caso seguimos el flujo de trabajo y lo dejamos con la condicion de que tuviera 3 interacciones

- si la desicion fue si se ejecutara el comando de apex que tiene la informacion de la creacion de correos donde tomara el lead verificara el correo que tenga asociado y armara un correo de prueba segun el stage de cada cliente, este proceso se realizo directamente con apex, debido a la flexibilidad que tiene para el envio de correos a externos.

- Para esto tenemos que usar un metodo invocable, para que nuestro flow pueda reconocer esta accion, y realizamos lo siguiente:

  - Mapeamos los objetos que vamos a usar en este caso los leads y los leads convertidos
  - Se verifica el email que no este en blanco para el envio del correo
  - Se asocia el campo company con account para evidenciar si hay alguna compañia dentro de nuestro datos y tomar este email para el envio.
  - Si no se encuentra la cuenta se creara una account nueva
  - Por ultimo se realiza una pequeña verificacion por si llegase a fallar la convercion de leads

  ![Image](https://media.discordapp.net/attachments/1218023015510577187/1352341443091370054/image.png?ex=67dda99d&is=67dc581d&hm=9dd338d7ef988567bf9be2f959e19fa8883774862c15874445b1d34465c15849&=&format=webp&quality=lossless&width=768&height=432)



##### 	Crear Factura

- Para este flow dispusimos de la herramienta de apex nuevamente para mapear los campos necesarios dentro del objeto factura, el iniciador de este evento es cuando una opportunidad cambia a estado closed win, donde el cliente si va a realizar la compra, para esto tenemos 2 procesos invocables, uno donde mapeamos toda la informacion de la factura:

  ![Image](https://media.discordapp.net/attachments/1218023015510577187/1352347095083913258/image.png?ex=67ddaee0&is=67dc5d60&hm=90fed7f00fe7f82e0f67844f64b1aca46c685d76abab44ab7caf039450f67820&=&format=webp&quality=lossless&width=768&height=432)

- Y otro donde tomamos todos los datos de la cuenta, los comparamos con la factura, tomamos el correo de la cuenta y el nombre, y generamos un correo de manera automatica al correo guardado, con el monto total de la factura.

  ![Image](https://media.discordapp.net/attachments/1218023015510577187/1352347260805054524/image.png?ex=67ddaf08&is=67dc5d88&hm=fc74f680e2868106945053c33ee0749dffc90e98c53d480a1e4b3ac0ad65ff57&=&format=webp&quality=lossless&width=768&height=432)



##### **Asignacion de facturas**:

Debido a que acabamos de generar la factura aun se encuentra en estado de pendiente, debemos organizar las facturas debido al estado que queramos, para ello creamos un flow, donde verifica el estado de la factura, y si el estado es igual a pendiente, crea una factura en el objeto de facturas pendientes o pagadas,



## SEGURIDAD Y ACCESOS

- Para la seguridad se han tomado varias medidas, como los ajustes de campos que puede visualizar cada perfil, se realizo un schedule para que envie toda la data los primeros dias de cada mes: 

  ![Image](https://media.discordapp.net/attachments/1218023015510577187/1352383898188910712/image.png?ex=67ddd127&is=67dc7fa7&hm=0096658e003b4eb0736608f6be70e8bca0d39f71887955777c0463074ca4fb24&=&format=webp&quality=lossless)



- Se realizo la creacion de un reporte el cual nos indica los loggins fallidos, junto con sus datos.

  ![Image](https://media.discordapp.net/attachments/1218023015510577187/1352384752975609876/image.png?ex=67ddd1f3&is=67dc8073&hm=91698a89f4f63a5417ab9cb7788b1c75504a05120e84c8e6ba9b2b8c19d47701&=&format=webp&quality=lossless)



- Se realizaron permission sets para verificar que solo puedan tener acceso a los campos especificados segun el perfil que tenga cada usuario.campos mencionados anteriormente desde el apartado de perfiles, adicional para la informacion sensible de la parte de accounts, se aumento la seguridad de algunos campos para que solo los puedan verificar el CEO y el sistem administrator.

  - Account number

  - Annual revenue

  - Employees



- Se verifico que la configuracion se el inicio de sesion de los ususarios cumplieran con los estandares, se deja desactivado el multi factor

![Image](https://media.discordapp.net/attachments/1156413197931249765/1352387684328411187/image.png?ex=67ddd4ae&is=67dc832e&hm=e383d93fe96d7c20c8a23e717cd61c64a7c16947133c6a9a914ce6f13110fde8&=&format=webp&quality=lossless&width=1433&height=790)



## REPORTES

- En la aplicacion principal se crean 4 carpetas que nos serviran para el uso compartido con los perfiles que vayamos a utilizar, de esta manera solo podran ver los reportes los usuarios que nosotros queramos y no podran ver los informes de otras ramas.

### Reportes de ventas

- Para los reportes de ventas tenemos los siguientes 4 reportes, los cuales nos daran toda la informacion acerca de como van las ventas, cuales fueron las oportunidades que ganamos y cuantas oportunidades hemos perdido hasta el momento, esto para realizar la comparativa entre ellas y verificar en que podemos seguir mejorando, para esto nos vamos a fijar principalmente en las empresas, que empresa tiene mayor indice de ganadas (se desactivo la informacion como subtotal y grantotal):

![Image](https://media.discordapp.net/attachments/1218023015510577187/1352568753493250059/image.png?ex=67de7d50&is=67dd2bd0&hm=5c5f872d8814b37ec1745cbab3043299b3460d630b135aec159a288dc78f7166&=&format=webp&quality=lossless&width=916&height=432)

- Y cual tiene mayor indice de perdidas:

![Image](https://media.discordapp.net/attachments/1218023015510577187/1352568070366822440/image.png?ex=67de7cad&is=67dd2b2d&hm=533c5e4de1ce51e4a64284f02f5db7f2c14204999e411bcd8f31eeec5208e4e0&=&format=webp&quality=lossless&width=1245&height=432)

- Tambien hemos creado el reporte del historial de ventas donde verificaremos todas las facturas con el nombre de la empresa a la cual se han realizado dichas facturas, lo que queremos tomar con este dato es la fiabilidad de cada empresa y seguir el curso de ventas:

![image](https://github.com/user-attachments/assets/49a0ff96-8ce0-4bbd-8e4c-6300d7b9b125)


Por ultimo el reporte de importe proyectado y alcanzado; Este reporte constituye una herramienta esencial para el área de ventas, ya que proporciona una visión clara del desempeño en relación con los objetivos establecidos. Al comparar el importe de ventas proyectado con el importe real alcanzado, se facilita el seguimiento del progreso y la identificación de áreas de mejora.

![Image](https://media.discordapp.net/attachments/1218023015510577187/1352571404272533614/image.png?ex=67de7fc8&is=67dd2e48&hm=7a728589aeca415f6c77921d6ef7a04fea94f636004038f5e0d800eea07a8e65&=&format=webp&quality=lossless&width=1113&height=432)



## APLICACIONES

### ConstruFurgo

- Para facilitar la toma de decisiones estratégicas, se ha creado una aplicación central que ofrece al CEO una visión panorámica y detallada de la información generada por todas las aplicaciones de la empresa.

![Image](https://media.discordapp.net/attachments/1218023015510577187/1352373216332742876/image.png?ex=67ddc734&is=67dc75b4&hm=b12bdb790980f8e50859ddfd56e14931089e7e7eb482269586c6069b4c60c068&=&format=webp&quality=lossless)

- La configuracion de la aplicacion es la siguiente: 

  ![Image](https://media.discordapp.net/attachments/1218023015510577187/1352374327710060666/image.png?ex=67ddc83d&is=67dc76bd&hm=3bfdc4009d801a6b3695010c4f0c8abb563c21435b5094c75759cb6d14bdbbdf&=&format=webp&quality=lossless)

- Esta aplicacion la va a manejar el CEO por lo tanto tiene acceso a todas las tabs:

  ![Image](https://media.discordapp.net/attachments/1218023015510577187/1352374960559099955/image.png?ex=67ddc8d4&is=67dc7754&hm=e5efa4b287d4c79d5884d3a51c152771e76e384376acc85f79188ac1751a9db4&=&format=webp&quality=lossless)

### Sales Aplication

- Se realiza una aplicacion de ventas la cual tendran acceso solo el sales manager y el procurement specialist

  ![Image](https://media.discordapp.net/attachments/1218023015510577187/1352375544167268513/image.png?ex=67ddc95f&is=67dc77df&hm=89540636b8d5046c6d89702fbb46b158a8be557d90d3a5f3436a20397552fa82&=&format=webp&quality=lossless)

  

  

- En la configuracion de sales manager desactivamos la personalizacion de nav items para que no puedan modificar la informacion de otras areas

  ![Image](https://media.discordapp.net/attachments/1218023015510577187/1352376087484567742/image.png?ex=67ddc9e1&is=67dc7861&hm=b6f94eaf766547ae1fbd28f785daf7d1ce8031dca8f95f364899d7772630522c&=&format=webp&quality=lossless)

- Seleccionamos las tabs asociadas a ventas, que es donde tendra la informacion de ventas.

![Image](https://media.discordapp.net/attachments/1218023015510577187/1352376785769201734/image.png?ex=67ddca87&is=67dc7907&hm=8c75fbbbbc41e0152096b61c09e434685b75d776cc230228430e973d7479427e&=&format=webp&quality=lossless)



### Technical support

- Se realiza la creacion de la aplicacion para soporte tecnico: 

![Image](https://media.discordapp.net/attachments/1218023015510577187/1352378649957105745/image.png?ex=67ddcc44&is=67dc7ac4&hm=f411fd06cb5bfe31bdc30fe9a48bfd7c8edbbcde06845577ef94f7726e1dd04d&=&format=webp&quality=lossless)



- Se ajusta para uqe no pueda cambiar las tabs y se ajustan los nav de soporte:

  ![Image](https://media.discordapp.net/attachments/1218023015510577187/1352573215825985556/image.png?ex=67de8178&is=67dd2ff8&hm=f7cdd9a675dbb340181b03d92741bc45075c1f6f4b22bc9b72b1e48924a5f2e4&=&format=webp&quality=lossless&width=883&height=340)



## CONCLUSIONES

### **Implementación Exitosa de Salesforce:**

- Se ha logrado configurar y personalizar Salesforce para reflejar la estructura y los procesos de negocio de ConstruFurgo.
- Se han creado objetos personalizados, flujos de trabajo automatizados y reportes para optimizar la gestión de ventas, leads, oportunidades y facturación.

### **Mejora en la Gestión de Ventas:**

- Se han implementado flujos para la conversión de leads a oportunidades, automatizando el seguimiento y la interacción con clientes potenciales.
- Se han creado reportes de ventas que proporcionan información valiosa sobre el desempeño, incluyendo oportunidades ganadas y perdidas, y el historial de ventas por empresa.
- Se ha implementado el reporte de importe proyectado vs alcanzado lo cual es una herramienta valiosa para el area de ventas.

### **Automatización de Procesos Clave:**

- Se han automatizado las alertas de nuevos leads y la creación de facturas, mejorando la eficiencia y la respuesta a los clientes.
- Se ha automatizado la asignación de facturas a estados pendientes o pagadas, facilitando la gestión financiera.

### **Aplicaciones Personalizadas para Diferentes Roles:**

- Se han creado aplicaciones personalizadas para el CEO, el equipo de ventas y el equipo de soporte técnico, facilitando el acceso a la información relevante para cada rol.

### **Mejora en la Seguridad y el Control de Acceso:**

- Se han configurado perfiles y permisos para asegurar que los usuarios tengan acceso solo a la información necesaria para sus roles.
- Se han creado permission sets para aumentar la seguridad de los datos.
- Se han creado reportes de loggins fallidos, para mejorar la seguridad de la información.
- Se ha configurado un schedule para el envio de la data de manera automatica.
- Se ha aumentado la seguridad en campos sensibles de la información de accounts.

### **Optimización de la Gestión de Leads:**

- Se han implementado validaciones de datos para asegurar la calidad de la información de los leads.
- Se ha automatizado el aumento de interacciones de los leads, para tener un mejor control del seguimiento.










pedroandresortega0410@gmail.com

​	Pedrito2025
