# Actualización de WhatsApp: @username público + PIN anti-spam

![Mockup smartphone con candado luminoso representando seguridad en WhatsApp](assets/actualizacion-wa.jpg)

**Ciudad Autónoma de Buenos Aires, 1 de julio de 2026.** WhatsApp anunció hoy una actualización doble pensada para blindar la privacidad. Desde esta semana, la app permite configurar un **@username único** para compartir el perfil sin revelar el número de teléfono, y suma un **código PIN obligatorio** para autorizar nuevos contactos y proteger sesiones desde dispositivos no verificados.

### Guía express: @username + PIN
1. **Crear @username:** Configuración › Perfil › *Nombre de usuario* → escribí un alias (5-30 caracteres, letras/números/_), guardá cuando quede libre.
2. **Compartir:** Usá `https://wa.me/@tusuario` para invitar sin mostrar el número.
3. **Activar PIN:** Configuración › Privacidad › Código PIN. Elegí 6 dígitos únicos y confirmalos.
4. **Validación:** Cada nuevo dispositivo o contacto tendrá que ingresar ese PIN antes de abrir chat contigo.

## ¿Qué cambia para las marcas y comunidades?
- **Identidad controlada:** Los perfiles públicos podrán difundirse con un identificador corto, lo que simplifica campañas y activaciones sin exponer números personales del equipo.
- **Capa anti-spam:** El PIN funciona como llave de seguridad. Si alguien intenta iniciar un chat sin invitación, la app solicitará el código antes de entregar los mensajes.
- **Analíticas limpias:** Menos interacciones basura significa métricas más fiables para funnels conversacionales y chatbots.

## Claves técnicas
1. **Formato del nombre de usuario:** entre 5 y 30 caracteres, combina letras, números y guiones bajos. La reserva es por orden de llegada.
2. **Sincronización multi-dispositivo:** el PIN se solicita cuando un nuevo dispositivo intenta clonar una cuenta, reduciendo el secuestro de sesiones.
3. **Compatibilidad con catálogos y bots:** las API Cloud y On-Premise recibirán el campo `username` para identificar chats sin exponer MSISDN.

## Qué sigue
Meta confirmó que en agosto liberará la API para validar @username desde integraciones empresariales. Mientras tanto, recomienda activar el PIN desde Configuración > Privacidad > Código PIN de acceso.

> _"El objetivo es que cada conversación empiece con consentimiento explícito"_, explicó Aline Diniz, directora de producto de WhatsApp, en el evento virtual Craftdigit Connect.

La actualización ya se distribuye de forma gradual en iOS, Android y WhatsApp Web. Se espera que toda la base activa la reciba antes del 15 de julio.