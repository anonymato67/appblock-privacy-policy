# Política de privacidad de BloqPriv

**Última actualización:** 14 de octubre de 2026

## 1. Responsable de la aplicación

**BloqPriv** es una aplicación para dispositivos Android desarrollada por **Langosta.dev**. Su finalidad es ayudar a los usuarios a proteger la privacidad de sus aplicaciones mediante funciones como el bloqueo con patrón, PIN, contraseña o huella dactilar, la ocultación de aplicaciones y la protección del contenido de las notificaciones.

Para consultas relacionadas con esta política o con el tratamiento de datos, puedes contactar con el desarrollador:

- **Desarrollador:** Langosta.dev
- **Correo electrónico:** [langostaProton@proton.me](mailto:langostaProton@proton.me)

## 2. Información y permisos utilizados

BloqPriv utiliza determinados permisos de Android para proporcionar sus funciones de bloqueo y privacidad. Estos permisos se utilizan con las finalidades descritas a continuación.

### 2.1. Servicio de accesibilidad

El servicio de accesibilidad permite detectar qué aplicación se encuentra en primer plano para mostrar la pantalla de bloqueo cuando el usuario intenta abrir una aplicación protegida.

Según el funcionamiento previsto de BloqPriv, este servicio se utiliza para identificar la aplicación abierta y activar el bloqueo correspondiente. No está destinado a leer ni registrar el contenido de lo que el usuario escribe, ve o realiza dentro de otras aplicaciones.

### 2.2. Acceso al uso de aplicaciones

Este permiso permite consultar el tiempo de uso de las aplicaciones para proporcionar estadísticas, como el tiempo de uso, los intentos de acceso bloqueados y el tiempo ahorrado.

La información de uso consultada por BloqPriv se procesa y almacena localmente en el dispositivo.

### 2.3. Acceso a notificaciones

Este permiso permite proteger el contenido de las notificaciones de aplicaciones bloqueadas, sustituyéndolo por avisos genéricos, como «Notificación nueva · contenido oculto».

Esta función está diseñada para ocultar el contenido de las notificaciones y evitar que se muestre en la interfaz de BloqPriv. No está destinada a almacenar ni transmitir dicho contenido.

### 2.4. Permiso para mostrar notificaciones

En Android 13 y versiones posteriores, este permiso permite que BloqPriv muestre sus propias notificaciones, incluidos los avisos genéricos relacionados con las funciones de privacidad.

### 2.5. Excepción de optimización de batería

Esta configuración ayuda a que Android no interrumpa el servicio de bloqueo cuando se ejecuta en segundo plano. Su disponibilidad y funcionamiento dependen de la versión de Android y del fabricante del dispositivo.

### 2.6. Administrador del dispositivo (opcional)

Si el usuario activa esta función, BloqPriv puede utilizar los permisos de administrador del dispositivo disponibles en Android para añadir protección frente a la desinstalación no autorizada, según la implementación de la aplicación.

### Tratamiento de la información obtenida mediante estos permisos

La información obtenida mediante los permisos descritos anteriormente se procesa y almacena localmente en el dispositivo, según las funciones habilitadas por el usuario.

BloqPriv no transmite a sus propios servidores el contenido de otras aplicaciones, el contenido de las notificaciones, las estadísticas de uso ni los métodos de bloqueo. Los servicios de terceros integrados en la aplicación pueden tratar determinados datos conforme a lo indicado en la sección 5.

## 3. Información almacenada en el dispositivo

BloqPriv almacena localmente la información necesaria para ofrecer sus funciones. Según las características utilizadas, esta información puede incluir:

- **Preferencias de bloqueo:** aplicaciones bloqueadas, aplicaciones ocultas, horarios programados, método de bloqueo seleccionado y configuración de la pantalla de bloqueo, incluidos el fondo, los colores y las opciones del patrón.
- **Método de bloqueo:** el patrón, PIN o contraseña se representa mediante un hash criptográfico PBKDF2 con una sal aleatoria. El método de bloqueo en texto claro no se almacena.
- **Estadísticas de uso:** tiempo de uso de aplicaciones, intentos de acceso bloqueados y tiempo ahorrado, calculados a partir de la información disponible en Android.
- **Imagen de fondo personalizada:** si el usuario selecciona una imagen de su galería, BloqPriv guarda una copia reducida dentro del almacenamiento de la aplicación.
- **Estado de BloqPriv Premium:** información local necesaria para gestionar o reflejar el estado de la compra y las pruebas relacionadas con anuncios, según corresponda.

Esta información se almacena en el dispositivo mediante las preferencias y los archivos internos de la aplicación.

BloqPriv no envía estos datos a sus propios servidores. Los servicios de terceros pueden procesar los datos necesarios para sus respectivas funciones, conforme a la sección 5.

## 4. Recopilación y transmisión de datos

BloqPriv no dispone de cuentas de usuario ni de servidores propios para almacenar información personal en la nube.

La información utilizada por las funciones locales de bloqueo, configuración y estadísticas se procesa en el dispositivo, de acuerdo con el funcionamiento descrito en esta política.

No obstante, BloqPriv integra servicios de terceros para mostrar anuncios, gestionar el consentimiento publicitario y procesar compras. Estos proveedores pueden recopilar o recibir determinada información desde el dispositivo, conforme a sus propias políticas y a la configuración aplicable.

Los detalles de dichos servicios se describen en la siguiente sección.

## 5. Servicios de terceros

BloqPriv integra servicios de Google para determinadas funciones.

### 5.1. Google AdMob

**Proveedor:** Google LLC  
**Finalidad:** mostrar anuncios publicitarios, incluidos anuncios de banner y anuncios recompensados.

AdMob puede recopilar o procesar identificadores del dispositivo, información de interacción con anuncios, datos de uso e información relacionada con la publicidad. La información utilizada y la personalización de los anuncios pueden depender de la configuración del dispositivo, las opciones de consentimiento y las políticas aplicables.

Consulta la [Política de privacidad de Google](https://policies.google.com/privacy).

### 5.2. Google User Messaging Platform (UMP)

**Proveedor:** Google LLC  
**Finalidad:** gestionar los avisos y las opciones de consentimiento relacionados con la publicidad, cuando corresponda.

Este servicio permite presentar y gestionar las preferencias de consentimiento publicitario. El tratamiento de información asociado al servicio se rige por las políticas aplicables de Google.

Consulta la [Política de privacidad de Google](https://policies.google.com/privacy).

### 5.3. Google Play Billing

**Proveedor:** Google LLC  
**Finalidad:** gestionar las compras de BloqPriv Premium realizadas mediante Google Play.

Google procesa la información necesaria para gestionar las transacciones. BloqPriv recibe la información de compra necesaria para reconocer el estado de la adquisición y habilitar las funciones correspondientes; la aplicación no accede directamente a los datos completos de pago del usuario, como los datos de su tarjeta.

Consulta la [Política de privacidad de Google](https://policies.google.com/privacy).

### Otros servicios

Según la configuración descrita para BloqPriv, la aplicación no utiliza servicios adicionales de analítica ni de informes de fallos. Esta declaración debe revisarse si se incorporan nuevas bibliotecas o servicios en futuras versiones.

## 6. Seguridad de la información

BloqPriv aplica medidas destinadas a proteger la información almacenada y utilizada por la aplicación.

Entre las medidas implementadas, según la versión de la aplicación, se incluyen:

- **Protección del método de bloqueo:** el patrón, PIN o contraseña se almacena como un hash criptográfico PBKDF2 con una sal aleatoria de 128 bits y 10 000 iteraciones, según la implementación descrita. El método de bloqueo en texto claro no se guarda ni se transmite.
- **Protección frente a intentos fallidos:** después de tres intentos fallidos consecutivos, el acceso se bloquea durante 30 segundos.
- **Almacenamiento privado:** la configuración y las preferencias se guardan en el almacenamiento interno privado de la aplicación, que normalmente está aislado de otras aplicaciones mediante los mecanismos de seguridad de Android.
- **Ofuscación del código:** la versión publicada utiliza R8 para dificultar el análisis y la ingeniería inversa del código.

BloqPriv no utiliza servidores propios para almacenar la información local descrita en esta política. Estas medidas reducen determinados riesgos de exposición, aunque ningún sistema de seguridad puede garantizar una protección absoluta.

## 7. Conservación y eliminación de los datos

Los datos locales de BloqPriv se conservan en el dispositivo mientras sean necesarios para sus funciones y hasta que el usuario los elimine o desinstale la aplicación, según el tipo de información.

El usuario puede eliminar los datos locales mediante cualquiera de los siguientes métodos:

### 7.1. Borrar los datos desde Android

En los dispositivos compatibles, abre:

**Ajustes → Aplicaciones → BloqPriv → Almacenamiento → Borrar datos**

Esta acción elimina los datos locales de la aplicación, que pueden incluir las preferencias, las aplicaciones configuradas, los horarios, el método de bloqueo y la imagen de fondo personalizada.

Los nombres y la ubicación de estas opciones pueden variar según el fabricante y la versión de Android.

### 7.2. Desinstalar la aplicación

Al desinstalar BloqPriv, Android elimina normalmente los datos locales asociados a la aplicación. Los datos gestionados por proveedores externos no se eliminan necesariamente mediante esta acción.

### 7.3. Datos gestionados por terceros

Los datos que puedan recopilar o procesar Google AdMob, Google UMP o Google Play Billing se conservan y eliminan conforme a las políticas, los procedimientos y los plazos aplicables de cada proveedor.

Para obtener información adicional sobre esos datos, consulta la [Política de privacidad de Google](https://policies.google.com/privacy).

## 8. Cambios en esta política

Esta política puede actualizarse cuando cambien las funciones de BloqPriv, los permisos utilizados, los servicios integrados o los requisitos legales aplicables.

Las versiones actualizadas se publicarán en esta misma página junto con la fecha de la última actualización.

Se recomienda revisar periódicamente esta página para conocer las prácticas de privacidad vigentes.

## 9. Contacto

Para realizar consultas sobre esta política de privacidad, las funciones de BloqPriv o el tratamiento de información, puedes contactar con el desarrollador:

- **Desarrollador:** Langosta.dev
- **Correo electrónico:** [langostaProton@proton.me](mailto:langostaProton@proton.me)

