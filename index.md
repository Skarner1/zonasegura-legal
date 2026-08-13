---
layout: default
title: "Política de Privacidad — Zona Segura"
permalink: /
---

# Política de Privacidad — Zona Segura

**Última actualización:** 13 de agosto de 2026
**Versión de la aplicación:** 2.3.1

**Español** · [English version](privacy/) · [Cómo eliminar tus datos](eliminar-datos/)

## 1. Quién es responsable de tus datos

Zona Segura (la «app») es desarrollada y operada por Ivan Santiago Torres, con domicilio en Colombia.

Para cualquier asunto relacionado con esta política o con tus datos personales, escribe a **[ivantr158@gmail.com](mailto:ivantr158@gmail.com)**.

## 2. Resumen en tres líneas

La app comparte tu ubicación en tiempo real con las personas de tu sala para que puedan cuidarse
entre ellas. Para eso necesitamos tu ubicación GPS, y sí la almacenamos mientras la sala esté
activa. Todo se borra automáticamente a las 24 horas, y no pedimos tu correo, tu teléfono ni tu
nombre real.

## 3. Qué datos recopilamos

Estos datos se envían a nuestros servidores (Google Firebase) y son visibles para los demás
miembros de tu sala mientras estés dentro de ella:

| Dato | Detalle | Por qué lo necesitamos |
|---|---|---|
| **Ubicación precisa** | Latitud, longitud y velocidad de desplazamiento | Es la función principal: mostrar tu posición a tu grupo y detectar si sales de la zona segura |
| **Ubicación en segundo plano** | La misma ubicación, también con la app cerrada o minimizada | Las alarmas de zona y el SOS no servirían si dejaran de funcionar al bloquear el teléfono |
| **Apodo** | El nombre que tú escribes al entrar; puede ser inventado | Para que tu grupo sepa qué punto del mapa eres tú |
| **Estado** | Una de estas etiquetas: bien, baño, comida, transporte o SOS | Para avisar a tu grupo qué estás haciendo sin escribir mensajes |
| **Nivel de batería** | Porcentaje de carga de tu dispositivo | Para que tu grupo sepa si estás por quedarte sin teléfono |
| **Ruta activa** | Destino, trayecto trazado, distancia y duración estimada | Para que tu grupo vea hacia dónde te diriges y detectar desvíos |
| **Estado de conexión** | Si estás conectado y la hora de tu última señal | Para avisar a tu grupo si pierdes internet o señal |
| **Identificador anónimo** | Un código aleatorio que Firebase genera para tu dispositivo | Para distinguir a un miembro de otro dentro de la sala |
| **Datos de la sala** | Código de sala, zonas seguras definidas (centro y radio) y quién es administrador | Para que el grupo comparta el mismo mapa y las mismas alarmas |

### Datos que se quedan solo en tu teléfono

Estos **nunca** salen de tu dispositivo y no llegan a nuestros servidores:

- **Tu PIN de 4 dígitos.** Se guarda únicamente en el almacenamiento local de la app.
- Tu idioma, el tema de color y el registro de que aceptaste los términos.
- Los mapas descargados para uso sin conexión.

### Qué NO recopilamos

No pedimos ni almacenamos: correo electrónico, número de teléfono, nombre real, documento de
identidad, contactos, fotos, micrófono, cámara ni historial de navegación. No existe registro de
cuenta. No usamos publicidad ni rastreadores publicitarios, y no elaboramos perfiles comerciales
sobre ti.

## 4. Para qué usamos tus datos

Usamos los datos descritos arriba **exclusivamente** para hacer funcionar la app: mostrar
posiciones en el mapa de tu sala, disparar alarmas cuando alguien sale de una zona segura,
transmitir señales de SOS, trazar rutas y mostrar lugares cercanos.

No vendemos tus datos. No los cedemos a anunciantes, aseguradoras, empleadores ni intermediarios
de datos. No los usamos para entrenar modelos de inteligencia artificial.

### Base legal (si estás en la Unión Europea o el Reino Unido)

Tratamos tu ubicación sobre la base de tu **consentimiento explícito** (art. 6.1.a del RGPD), que
otorgas al aceptar el aviso inicial y al conceder el permiso de ubicación del sistema. Puedes
retirar ese consentimiento en cualquier momento saliendo de la sala o revocando el permiso desde
los ajustes de Android; la app dejará de funcionar, pero no habrá ninguna otra consecuencia.

## 5. Ubicación en segundo plano

La app solicita el permiso de **ubicación en segundo plano** de Android. Necesitamos explicártelo
con claridad porque es el permiso más sensible que pedimos:

- Se usa **únicamente** para seguir compartiendo tu posición con tu sala cuando la pantalla está
  apagada o la app está minimizada, y para que las alarmas de zona y el SOS sigan funcionando.
- Solo está activo **mientras perteneces a una sala**. Al salir de la sala, la app deja de
  recopilar tu ubicación.
- Puedes negar este permiso: la app seguirá funcionando, pero tu grupo dejará de verte cuando
  cierres la pantalla y las alarmas podrían no dispararse.
- Puedes revocarlo cuando quieras en Ajustes → Aplicaciones → Zona Segura → Permisos.

## 6. Con quién se comparten tus datos

### Con los miembros de tu sala

Tu ubicación, apodo, estado, batería y ruta son visibles para **todas las personas que tengan el
código de tu sala**. Comparte ese código solo con gente en la que confíes: cualquiera que lo tenga
puede entrar y ver dónde estás.

### Con proveedores de servicios

| Proveedor | Qué recibe | Para qué |
|---|---|---|
| **Google (Firebase Authentication y Cloud Firestore)** | Todos los datos de la sección 3 | Alojar la base de datos en tiempo real y generar el identificador anónimo |
| **Mapbox** | Tus coordenadas cuando trazas una ruta o buscas lugares cercanos, y de forma implícita la zona del mapa que estás viendo | Dibujar el mapa, calcular rutas y encontrar bares, tiendas, policía y hospitales cercanos |

Estos proveedores tratan los datos por cuenta nuestra y bajo sus propias políticas de privacidad:
[Google](https://policies.google.com/privacy) y [Mapbox](https://www.mapbox.com/legal/privacy).
No autorizamos a ninguno de los dos a usar tus datos para sus propios fines comerciales.

Los mapas incluyen datos de [OpenStreetMap](https://www.openstreetmap.org/copyright), a los que no
se envía información sobre ti.

### Por obligación legal

Podríamos entregar datos si una autoridad competente nos lo exige mediante una orden válida.
Dado que los datos se borran a las 24 horas, en la práctica casi nunca habrá algo que entregar.

## 7. Transferencias internacionales

Los servidores de Google y Mapbox están ubicados fuera de Colombia, principalmente en Estados
Unidos y la Unión Europea. Al usar la app, tus datos se transfieren a esos países. Ambos
proveedores ofrecen garantías contractuales para estas transferencias, incluidas las Cláusulas
Contractuales Tipo aprobadas por la Comisión Europea.

## 8. Cuánto tiempo conservamos tus datos

- **Al salir de una sala**, tus datos de miembro se eliminan de inmediato.
- **Cada sala se borra automáticamente 24 horas después de su creación**, junto con todos los
  datos de sus miembros y zonas. Esto es automático y no requiere que hagas nada.
- El administrador de una sala puede eliminarla antes, borrando los datos de todos sus miembros.

No conservamos historiales de ubicación. No existe un archivo de por dónde has estado: la
ubicación anterior se sobrescribe con la nueva.

## 9. Tus derechos

Tienes derecho a acceder a tus datos, rectificarlos, eliminarlos, limitar u oponerte a su
tratamiento, y a solicitar una copia portable. Si estás en la Unión Europea o el Reino Unido estos
derechos provienen del RGPD; en Colombia, de la Ley 1581 de 2012 (Habeas Data); en California, de
la CCPA/CPRA.

En la práctica, **la forma más rápida de ejercer tu derecho de supresión es salir de la sala**:
eso borra tus datos al instante, sin trámite ni espera.

Si prefieres una solicitud formal, escribe a [ivantr158@gmail.com](mailto:ivantr158@gmail.com). Responderemos en un plazo máximo de 30
días. Ten en cuenta que, como no recopilamos datos identificativos, es posible que necesitemos el
código de sala y tu apodo para localizar tu registro, y que si ya pasaron 24 horas no quedará nada
que borrar.

Si consideras que tratamos mal tus datos, puedes reclamar ante la autoridad de protección de datos
de tu país. En Colombia es la Superintendencia de Industria y Comercio; en la Unión Europea, la
autoridad de tu Estado miembro.

## 10. Menores de edad

La app no está dirigida a menores de 13 años y no recopilamos deliberadamente sus datos. Si eres
madre, padre o tutor y crees que un menor a tu cargo está usando la app, retíralo de la sala o
escríbenos a [ivantr158@gmail.com](mailto:ivantr158@gmail.com).

Si un menor de edad usa la app con supervisión familiar, quien ejerza la patria potestad es
responsable de dar el consentimiento para el tratamiento de su ubicación.

## 11. Seguridad

Las comunicaciones con nuestros servidores viajan cifradas mediante HTTPS/TLS. El acceso a los
datos de una sala está limitado a quienes conozcan su código, y las salas se destruyen a las 24
horas, lo que reduce mucho la cantidad de información expuesta ante un eventual incidente.

Aun así, ningún sistema es completamente seguro. Recuerda que **cualquiera que tenga el código de
tu sala puede ver tu ubicación**: esa es la principal vía por la que tus datos pueden llegar a
alguien no deseado, y depende de con quién compartas el código.

## 12. Uso responsable

No uses esta app para rastrear a nadie sin su conocimiento y consentimiento. Hacerlo puede ser
delito en tu país. Zona Segura está pensada para grupos que acuerdan cuidarse mutuamente, no para
la vigilancia de una persona sobre otra.

La app tampoco sustituye a los servicios oficiales de emergencia. Ante una emergencia real, llama
al número de emergencias de tu país.

## 13. Cambios en esta política

Si modificamos esta política, actualizaremos la fecha del encabezado y publicaremos la nueva
versión en https://skarner1.github.io/zonasegura-legal/. Si el cambio afecta de forma significativa a cómo tratamos tus datos, te lo
avisaremos dentro de la app y te pediremos que aceptes de nuevo antes de continuar.

## 14. Contacto

**Ivan Santiago Torres**
Correo: [ivantr158@gmail.com](mailto:ivantr158@gmail.com)
País: Colombia
