# PD02. Registro de Actividades de Tratamiento (RAT)

El antiguo modelo burocrático de declarar unos "ficheros informáticos masivos a Madrid" ha mutado a que la empresa autogestione y audite su interior mediante un documento interno exigible instantáneamente ante una inspección.

## 1. Qué es el Registro de Actividades de Tratamiento (RAT)
El RAT es un "mapa escrito y exhaustivo de todos los usos que da la Startup a los datos personales de las personas y sus flujos/procesos desde que entran por pantalla hasta que terminan almacenados o eliminados al años de la ley".

Se exige en Excel (o plataformas SaaS como Facilita RGPD oficial o terceras legales SaaS), pero es el "core de operaciones Privacy de toda PYME". Se divide normalmente en varios capítulos o flujos que se ejecutan en las startups comunes (10 empleados):

### A. Tratamiento de Empleados Locales
*   **Origen:** Currículums por email B2B, info del TA.2/S (Seguridad Social).
*   **Finalidad:** Elaborar la nómina, el M111 de la AEAT, o los certificados médicos básicos para la Ley de Prevención de riesgos de una Mutua.
*   **Almacenamiento (Dónde residen):** Computadoras Mac portátiles Windows en *Drive o MS OneDrive / AWS S3*. (Aquí reside la legalidad, los servidores físicos *DEBEN ESTAR EN EUROPA* no importados a China -o tener cláusulas europeas tipo CCT para los SaaS EE.UU.- o el CFO tiene multas graves al subir datos a fuera).

### B. Tratamiento CRM B2C / Clientes
*   **Origen:** Formularios Web de landing en la APP de la Startup (Firebase de Google/AWS base).
*   **Finalidad:** Ofrecer servicio de la App B2C, cobros pasarelas financieras (ej. Stripe o Redsys en Europa).
*   **Bajas (Derecho Supresión):** A diferencia de Hacienda que pides 4 años para investigar el modelo 303 (Facturas B2C guardadas en Base SQL). Los datos de CRM marketing directo si un usuario se borra de las listas de email de una "Mailchimp campaña" debes purificarlos sin excusas a cero o "bloquearlos" en el disco de la S.L. durante tiempo preventivo por si tienes demandas pasadas en Europa (Bases en cuarentena).

### C. Tratamiento de Proveedores (Freelances de B2B)
*   **Datos:** DNI, Nombres y cuentas IBAN de pago a los asesores/desarrolladores de soporte.

## 2. Contratos Encargados de Tratamiento (El "Bypass" AEPD)
Para que el RAT de la Startup sea válido y se "escude" si pasa un hackeo masivo a "Mailchimp" o a "Microsoft", la Startup de 10 trabajadores debió firmar con sus proveedores tecnológicos un contrato ciego: "Yo le dejo los datos a EE.UU./MicroSoft en Dublín, solo para que corra el programa, ustedes jamás cederán mi correo/los míos del RAT y ustedes, Microsoft garantizan mis ISO 27001".
*   Las startups firman un **Contrato de Encargado de Tratamiento (Artículo 28 GDPR)** o anexo *Data Processing Agreement (DPA)* antes de que los desarrolladores pongan en producción el software para terceros sobre AWS en Amazon nube externa ("La startup -Tú SL- eres el Responsable; Amazon / AWS es solo el Encargado de que funcionen los discos ciegamente").
