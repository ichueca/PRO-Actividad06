# PRO-Actividad06
Uso de propiedades en clases JAVA

## Instrucciones
Se pide diseñar una clase `Email` para gestionar los envíos de correo electrónico de la empresa.


De cada correo se almacenará la siguiente información:

- `para` : Una cadena para almacenar el correo electrónico de la persona a la que se envía el correo
- `asunto` : Ídem para el tema del que trata el mensaje
- `texto` : El texto del correo propiamente dicho
 

Dichas propiedades **deberán ser accesibles desde cualquier clase que esté en el mismo paquete**.

Además, la clase contará con una **propiedad de clase** `de` que estará asignada a la dirección `noreply@zabalburu.org` y que deberá ser **accesible desde cualquier clase**. 

Asimismo se dispondrá de otra **propiedad de clase** llamada `numCorreos` de tipo **entero** e inicializada a `0`.
 

Diseñar, además, **una clase ejecutable** llamada `EnvioCorreos` que realizará las siguientes tareas en su método `main`:

- Declarará una variable emailde tipo Email (Email email;)
- Repetirá el siguiente proceso mientras el usuario quiera
  - Asignar a email un nuevo Email (email = new Email();). 
  - Pedir el destinatario, asunto y texto del mensaje y asignarlo a las propiedades correspondientes del objeto email
  - Incrementar la propiedad numCorreos de la clase Email en 1
  - Mostrar la información del email según el siguiente formato (los valores en cursiva deben sustituirse por las propiedades correspondientes)

`Mensaje : numCorreos

De : de

Para : para

Asunto : asunto

Texto

-----------------------------------`
