# TiMe — Política de privacidad

**Última actualización:** 13 de noviembre de 2026
**En vigor:** 13 de noviembre de 2026

> Esta es una traducción. En caso de discrepancia, prevalece la versión
> inglesa o turca.

---

## En resumen

TiMe es una app para llevar el seguimiento del ciclo menstrual. Tus datos
se **guardan en tu dispositivo por defecto.** No necesitas cuenta. No
guardamos tus datos del ciclo en nuestros servidores. No compartimos
datos con redes publicitarias. La app no incluye software de analítica.

Tus datos solo salen de tu dispositivo en estos casos, y cada uno requiere
tu elección explícita:

1. **Comentarios de IA y chat** — cuando activas el modelo en línea para el chat o cuando el modelo del dispositivo no está
   disponible y has dado tu consentimiento
2. **Intercambio con Apple Salud (HealthKit)** — cuando das permiso
3. **Compras de suscripción**

Detalles a continuación.

---

## 1. Responsable del tratamiento

| | |
|---|---|
| Nombre | Batuhan Atabek |
| Dirección | Antalya, Turquía — las solicitudes pueden enviarse por correo electrónico |
| Correo | atabeksoft+privacy@gmail.com |

Esta política se aplica a la app TiMe para iOS.

---

## 2. Datos que tratamos

### 2.1 Datos que se quedan en tu dispositivo

Se guardan en la base de datos local de tu dispositivo y **nunca se envían
a nuestros servidores:**

- Fechas de inicio y fin de la regla, duración de los ciclos
- Intensidad del flujo
- Síntomas (físicos, ánimo, flujo vaginal, piel, digestión, sueño,
  energía)
- Registros de actividad sexual
- Temperatura basal, peso, resultados de pruebas de ovulación
- Tus notas de texto libre
- Preferencias de la app (idioma, unidades, horas de recordatorio)
- Tu historial de chat con la IA

Algunos de estos datos son **categorías especiales de datos** (datos de
salud y relativos a la vida sexual) según el artículo 9 del RGPD. Por eso
nuestra arquitectura por defecto es el almacenamiento en el dispositivo.

### 2.2 Datos que pueden salir de tu dispositivo

**a) Comentarios de IA y chat**

TiMe usa primero **el propio modelo de IA de tu dispositivo** para generar
comentarios. En ese caso, ningún dato sale de tu dispositivo.

Si diste tu consentimiento, también puedes activar "Chat más completo con el modelo en línea" en Ajustes. Si está activado, tus mensajes del chat van primero al modelo en línea según las reglas de abajo, aunque tu dispositivo admita el modelo del dispositivo. Está desactivado por defecto y no afecta a los comentarios puntuales.

Si tu dispositivo no admite ese modelo, se te pregunta una vez y **solo si
das tu consentimiento** se envía lo siguiente, mediante una conexión
cifrada, a un servidor proxy y de ahí a un proveedor de IA:

Se envía:
- La duración de tus ciclos (solo números)
- Tu fase actual del ciclo
- Las etiquetas de síntomas que elegiste
- Los mensajes **que escribes** en el chat
- El idioma de la interfaz

No se envía:
- Tu nombre, correo o fecha de nacimiento
- Ubicación
- Identificador del dispositivo o publicitario
- Fechas exactas
- Notas de texto libre de tus registros diarios

Puedes retirar este consentimiento cuando quieras en Ajustes. La app
vuelve entonces a los comentarios basados en reglas y sigue funcionando.

**Importante:** el texto que escribes en el chat se transmite al
proveedor tal como lo escribiste. Te recomendamos no escribir datos
identificativos en el chat.

**b) Apple Salud (HealthKit)**

Con tu permiso, el flujo menstrual, la temperatura basal y los registros
relacionados se intercambian con Apple Salud. Estos datos se quedan en tu
dispositivo y no se nos envían.

**No usamos los datos de HealthKit para publicidad, marketing ni minería
de datos, ni los compartimos con terceros.**

**c) Suscripciones**

Las compras las procesa Apple. **No tenemos acceso a tus datos de pago.**
Usamos RevenueCat para conocer el estado de la suscripción; solo se envían
un identificador de usuario anónimo y el estado de la suscripción, nunca
tus datos del ciclo.

**d) Prevención de abusos**

Para evitar abusos de las solicitudes de IA, se crea en tu dispositivo un
identificador aleatorio (UUID). No puede vincularse contigo, solo sirve
para contar las solicitudes diarias y se restablece al eliminar la app.

### 2.3 Datos que no recopilamos

- Nombre, correo, número de teléfono
- Ubicación
- Identificador publicitario (IDFA)
- Contactos, fotos, cámara, micrófono
- Analítica de uso (la app no incluye ningún SDK de analítica)

### 2.4 Funciones que no se ofrecen actualmente

La app **no** ofrece sincronización en la nube (iCloud). Tus datos no se
sincronizan entre dispositivos. Si se añade esta función, se actualizará
esta política y se pedirá tu consentimiento por separado.

---

## 3. Base jurídica (RGPD)

| Finalidad | Datos | Base jurídica |
|---|---|---|
| Predicción y seguimiento del ciclo | Datos del ciclo y síntomas | Consentimiento explícito, art. 9.2.a |
| Comentarios de IA (en el dispositivo) | Datos del ciclo y síntomas | Consentimiento explícito |
| Comentarios de IA (en línea) | Datos del §2.2(a) | Consentimiento explícito separado |
| Integración con Apple Salud | Registros de salud | Consentimiento explícito |
| Notificaciones | Fechas previstas, horas elegidas | Consentimiento |
| Gestión de la suscripción | ID anónimo, estado de la suscripción | Contrato, art. 6.1.b |
| Prevención de abusos | Identificador aleatorio del dispositivo | Interés legítimo, art. 6.1.f |

---

## 4. Transferencias internacionales

Si das tu consentimiento a los comentarios de IA en línea, los datos
indicados en el §2.2(a) se transfieren a servidores fuera de tu país.

| Destinatario | Función | País |
|---|---|---|
| Cloudflare, Inc. | Servidor proxy | EE. UU. |
| Google LLC | Proveedor de IA — comentario puntual (Gemini) | EE. UU. |
| Anthropic, PBC | Proveedor de IA — chat (Claude) | EE. UU. |

Esta transferencia se basa en tu **consentimiento explícito.** Si no lo
das, no se transfiere ningún dato y la app sigue funcionando en el
dispositivo.

Nuestro proxy **no registra** tus datos de salud.

Condiciones de datos de los proveedores:
- Google: https://ai.google.dev/gemini-api/terms
- Anthropic: https://www.anthropic.com/legal/commercial-terms

---

## 5. Conservación

- **Datos en el dispositivo:** hasta que los elimines. Eliminar la app los
  elimina.
- **Datos enviados al proveedor de IA:** no los conservamos después de
  generar la respuesta.
- **Identificador antiabuso:** 24 horas.
- **Registros de suscripción:** los que exija la ley, en poder de Apple y
  RevenueCat.

---

## 6. Tus derechos

Según el RGPD, tienes derecho de acceso, rectificación, supresión,
limitación del tratamiento, portabilidad, oposición y a retirar tu
consentimiento en cualquier momento. También puedes presentar una
reclamación ante tu autoridad de control (en España, la AEPD).

**En la práctica:** como la mayoría de tus datos solo están en tu
dispositivo, puedes ejercer varios de estos derechos directamente en la
app:

- **Acceso / portabilidad:** Ajustes → Exportar tus datos
- **Supresión:** Ajustes → Eliminar todos los datos
- **Retirar el consentimiento:** Ajustes → Consentimiento de IA

Para otras solicitudes: atabeksoft+privacy@gmail.com. Respondemos en un
plazo de 30 días.

---

## 7. Menores

TiMe no está dirigida a menores de 13 años y no recopilamos sus datos a
sabiendas. Si eres madre, padre o tutor y crees que tu hija o hijo usa la
app, escribe a atabeksoft+privacy@gmail.com.

---

## 8. Seguridad

- Los datos se guardan dentro del entorno aislado estándar de las apps de
  iOS.
- Bloqueo opcional de la app (Face ID / Touch ID).
- Todo el tráfico de red está cifrado con TLS.
- Nuestro proxy no registra datos de salud.
- Los datos enviados al proveedor de IA se minimizan.

Ningún sistema es completamente seguro. Te recomendamos mantener tu
dispositivo actualizado y usar un código de acceso.

---

## 9. Aviso médico

TiMe sirve para informarte y llevar un seguimiento personal. **No es un
diagnóstico médico, un tratamiento ni un método anticonceptivo.** Las
predicciones son estadísticas y pueden fallar. Consulta a un profesional
sanitario para tomar decisiones sobre tu salud.

---

## 10. Cambios

Si cambiamos esta política, mostraremos un aviso en la app y
actualizaremos la fecha de arriba. Si los cambios son importantes,
volveremos a pedir tu consentimiento.

---

## 11. Contacto

**Batuhan Atabek**
Antalya, Turquía — las solicitudes pueden enviarse por correo electrónico
atabeksoft+privacy@gmail.com
