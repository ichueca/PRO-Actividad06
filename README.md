# PRO-Actividad06
Uso de propiedades en clases JAVA

## Instrucciones
Se pide diseñar una clase `Email` para gestionar los envíos de correo electrónico de la empresa.


De cada correo se almacenará la siguiente información:

*`para` : Una cadena para almacenar el correo electrónico de la persona a la que se envía el correo
*`asunto` : Ídem para el tema del que trata el mensaje
*`texto` : El texto del correo propiamente dicho
 

Dichas propiedades **deberán ser accesibles desde cualquier clase que esté en el mismo paquete**.

Además, la clase contará con una **propiedad de clase** `de` que estará asignada a la dirección `noreply@zabalburu.org` y que deberá ser **accesible desde cualquier clase**. 

Asimismo se dispondrá de otra **propiedad de clase** llamada `numCorreos` de tipo **entero** e inicializada a `0`.
 

Diseñar, además, **una clase ejecutable** llamada `EnvioCorreos` que realizará las siguientes tareas en su método `main`:

1. Declarará una variable `email` de tipo `Email` (`Email email;`)
2. Repetirá el siguiente proceso **mientras el usuario quiera**
  2.1 **Asignar** a `email` un nuevo `Email` (`email = new Email();`). 
  2.2 **Pedir** el `destinatario`, `asunto` y `texto` del mensaje y **asignarlo a las propiedades** correspondientes del objeto `email`
  2.3 **Incrementar** la propiedad `numCorreos` de la clase `Email` en `1`
  2.4 **Mostrar** la información del email según el siguiente formato (los valores entre corchetes deben sustituirse por las propiedades correspondientes)

``` console
Mensaje : [numCorreos]

De : [de]

Para : [para]

Asunto : [asunto]

Texto

-----------------------------------
```
