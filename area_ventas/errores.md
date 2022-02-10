# ERRORES COMUNES
---
## <span style="color:nature"> Problema de Botón de Pánico Teltonika </span>

___
**DESCRIPCIÓN:**

No funciona el botón de alerta de pánico, modelo de dispotivo: 130fmb

**SOLUCIONES POSIBLES:**
~~~
1. Revisar que el dispositivo apunte al puerto 6903
2. Revisar que la entrada de ignición esté en 87A_12V
~~~
Luego de los 2 pasos anteriores sacar la batería, volver a armarlo y enviar el comando cpureset.

---
---

## <span style="color:nature"> Error en envío de comandos </span>

___
**DESCRIPCIÓN:**

Al enviar comandos al dispositivo no genera la acción correspondiente, al enviarlo un número determinada de veces logra funcionar.

**SOLUCIONES POSIBLES:**
~~~
1. Verificar la configuración del dispositivo. 
~~~
No es error de la plataforma, el inconveniente es que el dispositivo se desconecta cada tiempo determinado (depende de su 			configuración) y al enviar el comando no se ejecuta porque el dispositivo esta fuera de linea.

**NOTA:** Se implementará en un mediano plazo lo siguiente: Se detectará que el dispositivo esté fuera de línea y se mandará un error especificando la conectividad del dispositivo.

---
---

## <span style="color:nature"> Error al iniciar sesión </span>

___
**DESCRIPCIÓN:**

Al tratar de iniciar sesión la aplicación se reinicia y hay que volver a colocar los datos en en login.

**SOLUCIONES POSIBLES:**
~~~
1. Revisar que el usuario tenga acceso a la lista de conductores. 
2. Revisar que la cuenta pertenezca a la versión 2.
3. Revisar que tenga permisos del mapa, notificaciones y conductores. 
~~~
Esto sucede porque no tiene los permisos correspondientes para iniciar sesión.

---
---

## <span style="color:nature"> Error al asignar comandos, no aparecen </span>

___
**DESCRIPCIÓN:**

A la hora de enviar comandos no manda y si se revisa el listado de comandos no aparece ninguno.

**SOLUCIONES POSIBLES:**
~~~
1. Darle en el botón editar y guardar los cambios.
~~~
**NOTA: Esto error ya fue solucionado, pero los dispositivos que se crearon antes del 13 de Enero tendrán este inconveniente.**

---
---

## <span style="color:nature"> Problema de envío de comandos desde plataforma </span>

___
**DESCRIPCIÓN:**

Se selecciona el comando, se manda y no realiza la acción solicitada y de la misma manera funciona si se manda un comando personalizado.

**SOLUCIONES POSIBLES:**
~~~
1. Verificar si al enviar el comando realiza la acción contraria. Ejemplo: Si al enviar 
   Encendido de Motor apaga el dispositivo.
2. Si realiza la acción contraria cambiar la entrada de ignición de 87A_12V a 87_12V, en 
   caso de que esté configurado de forma contraria cambiar de 87_12V a 87A_12V.
~~~
Esto es un error de configuración, al cambiar la entrada de ignición funcionará correctamente.

---


