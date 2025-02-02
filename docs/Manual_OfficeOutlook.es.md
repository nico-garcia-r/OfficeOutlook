# OfficeOutlook
  
Connect to Outlook Desktop application.  

*Read this in other languages: [English](Manual_OfficeOutlook.md), [Portugues](Manual_OfficeOutlook.pr.md), [Español](Manual_OfficeOutlook.es.md).*
  
![banner](/docs/imgs/Banner_OfficeOutlook.png)
## Como instalar este módulo
  
__Descarga__ e __instala__ el contenido en la carpeta 'modules' en la ruta de Rocketbot.  




## Como usar este módulo
Para usar este módulo, tienes que agregar una cuenta a Outlook y luego podras conectarte correctamente.


## Descripción de los comandos

### Conectar a Outlook
  
Conectar a una insancia de la aplicación de Outlook
|Parámetros|Descripción|ejemplo|
| --- | --- | --- |
|Variable donde guardar el resultado|Guardar el resultado de la conexión.|result|

### Crear carpeta
  
Crea una carpeta en Outlook
|Parámetros|Descripción|ejemplo|
| --- | --- | --- |
|Nombre carpeta|Nombre de la carpeta que se desea crear.|Nueva carpeta|
|Carpeta destino|Carpeta donde se quiere crear la nueva (opcional).|EF000000B8EE7A4C31BD6441BF6B59D0B56B93BEE4E12200|
|Asignar a variable|Guardar el resultado de la creación de la carpeta.|Variable|

### Buscar por filtro
  
Buscar correos por filtros
|Parámetros|Descripción|ejemplo|
| --- | --- | --- |
|Filtro|Filtro que se desea utilizar.|(domain 'rocketbot.com' or domain 'gmail.com') and subject 'Aviso de compra'|
|Buscar en|Filtro para emails leidos y no leidos.|Todos|
|Carpeta|Carpeta en la que se desea buscar.|Inbox|
|Asignar a variable|Guardar el resultado de la búsqueda.|Variable|

### Leer email por EntryID
  
Lea la información del correo electrónico por EntryID
|Parámetros|Descripción|ejemplo|
| --- | --- | --- |
|EntryID|ID del email que se desea obtener.|EF000000B8EE7A4C31BD6441BF6B59D0B56B93BEC40C2000|
|Asignar a variable|Guardar la lectura del email.|Variable|
|Descargar adjuntos|Carpeta donde guardar los documentos adjuntos.|C:\User\|

### Mover email a una carpeta
  
Mueve un email hacia una carpeta por EntryID
|Parámetros|Descripción|ejemplo|
| --- | --- | --- |
|EntryID|ID del email que se desea mover.|EF000000B8EE7A4C31BD6441BF6B59D0B56B93BEC40C2000|
|Carpeta de destino|Carpeta donde se desea mover.|0014182A9615CE201001B40B98EB45D6B4A70D3F4F050000D5955FDE0000|

### Mover email a una carpeta por nombre
  
Mueve un email hacia una carpeta por Nombre (Solo carpetas dentro de la bandeja de entrada)
|Parámetros|Descripción|ejemplo|
| --- | --- | --- |
|EntryID|ID del email que se desea mover.|EF000000B8EE7A4C31BD6441BF6B59D0B56B93BEC40C2000|
|Carpeta de destino|Carpeta donde se desea mover.|mi_carpeta|

### Marcar email como no leído
  
Marca un email como no leído por EntryID
|Parámetros|Descripción|ejemplo|
| --- | --- | --- |
|EntryID|ID del email que se desea marker como no leído.|EF000000B8EE7A4C31BD6441BF6B59D0B56B93BEC40C2000|

### Enviar Email
  
Envia un email, previamente debe configurar el servidor
|Parámetros|Descripción|ejemplo|
| --- | --- | --- |
|Para|Email de los destinatarios.|to@mail.com, to2@mail.com|
|Copia|Email de los destinatarios.|cc@mail.com, cc2@mail.com|
|Asunto|Asunto que se desea dar.|Nuevo mail|
|Mensaje|Mesaje del mail.|Esto es un mensaje de prueba|
|Archivo Adjunto|Archivo adjunto que se desea enviar.|C:\User\Desktop\test.txt|
|Carpeta (Varios archivos)|Carpeta que contiene archivos adjuntos que se desea enviar.|C:\User\Desktop\Files|
|Confirmación de lectura||True|

### Responder Email
  
Responde un email usando el Entry ID
|Parámetros|Descripción|ejemplo|
| --- | --- | --- |
|EntryID|ID del email que se desea responder.|EF000000B8EE7A4C31BD6441BF6B59D0B56B93BEC40C2000|
|Mensaje|Mesaje del mail.|Esto es una prueba|
|Archivo Adjunto|Archivo adjunto que se desea enviar.|C:\User\Desktop\test.txt|
|Carpeta (Varios archivos)|Carpeta que contiene archivos adjuntos que se desea enviar.|C:\User\Desktop\Files|

### Reenviar Email
  
Reenvia un email usando el Entry ID
|Parámetros|Descripción|ejemplo|
| --- | --- | --- |
|EntryID|ID del email que se desea reenviar.|EF000000B8EE7A4C31BD6441BF6B59D0B56B93BEC40C2000|
|Para|Email de los destinatarios.|to@mail.com, to2@mail.com|

### Guardar Email
  
Guarda un email usando el Entry ID
|Parámetros|Descripción|ejemplo|
| --- | --- | --- |
|EntryID|ID del email que se desea guardar.|EF000000B8EE7A4C31BD6441BF6B59D0B56B93BEC40C2000|
|Ruta donde guardar|Ruta en la cual se desea guardar el archivo.|C:/Users/Documents/mail.msg|

### Extraer tabla por EntryID
  
Extrae una table del correo electrónico por EntryID
|Parámetros|Descripción|ejemplo|
| --- | --- | --- |
|EntryID|ID del email que se desea extraer la tabla.|EF000000B8EE7A4C31BD6441BF6B59D0B56B93BEC40C2000|
|Asignar a variable|Guardar el resultado de la lectura de la tabla.|Variable|

### Descargar adjuntos por EntryID
  
Descargar adjuntos por EntryID en una carpeta
|Parámetros|Descripción|ejemplo|
| --- | --- | --- |
|EntryID|ID del email que se desea obtener.|EF000000B8EE7A4C31BD6441BF6B59D0B56B93BEC40C2000|
|Descargar adjuntos|Carpeta donde guardar los documentos adjuntos.|C:\User\|
