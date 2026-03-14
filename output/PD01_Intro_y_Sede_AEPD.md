# PD01. Sede Electrónica AEPD, Principios Generales y "Privacy by Design"

Este documento introduce las pautas para que un Director Financiero o de Operaciones (DPO improvisado) implemente la cultura del dato impuesta por la AEPD a una startup tecnológica que trata datos de clientes y de hasta 10 trabajadores.

## 1. La Agencia Española de Protección de Datos (AEPD)
La AEPD es la máxima autoridad española (equivalente a sus homólogas europeas en el GDPR) centrada en defender los datos personales y sancionar ferozmente en caso de descuidos tecnológicos o abusos informáticos (como la cesión de correos o números a "terceros para marketing").
*   **Enfoque Startups (SaaS / B2C):** Una Tech Startup española suele basar su negocio (desde registro, analítica en firebase u optimización en nube) usando el dato del usuario final, haciendo que su cumplimiento normativo (GDPR compliance) deba ser revisado obsesivamente, o enfrentarse a multas que hunden el balance económico.

## 2. La Sede Electrónica de la AEPD (Notifica)
*   **Sitio Web:** [`sedeagpd.gob.es`](https://sedeagpd.gob.es/)
*   **Acceso Electrónico:** La empresa como S.L. usará el certificado digital FNMT.
*   **Comunica:** Herramienta usada para registrar el contacto del DPO (Delegado).
*   **Notifica:** Portal súper específico para alertar (en menos de 72 horas reales) de que a tu Startup "le han pirateado un servidor o se ha perdido un pendrive con copias de los sueldos en Madrid" (Brechas de seguridad / *Ransomwares*).

## 3. Principio Rector: "Privacidad desde el Diseño" (Privacy by Design)
Si la startup va a crear una App nueva o un portal B2B, este principio legal exige que desde la línea cero de código, la arquitectura sea ciega y minimizada para los programadores.
*   **Minimización de Datos:** No se pueden programar APIs de registro donde se solicite a un usuario "Edad y Género" si eres un SaaS de Facturación Empresarial (eso es un dato abusivo que la AEPD sanciona como sobre-extracción B2C con intención encubierta marketing/cookies).
*   **Transparencia de Capas:** El famoso "Doble check". Debajo del formulario de sign-up de las startups siempre se exigen **Primera Capa Básica** ("Quiénes somos, Qué usamos y Link a lo gordo") y **Segunda Capa (Política web completa de Privacidad)**. Un CFO Tech que no verifique que los Devs tienen el *Checkbox desmarcado* por defecto, provoca una sanción enorme casi instantánea por infracción flagrante o automatización ilegal no permitida por Europa.
