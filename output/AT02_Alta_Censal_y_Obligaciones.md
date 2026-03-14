# AT02. Alta Censal (036/037) y Obligaciones Fiscales

Este documento contiene los procedimientos para el Director Financiero de una startup de hasta 10 empleados relativos al alta censal en la AEAT.

## 1. El Fichero Base: Los Modelos 036 y 037
Para que la startup inicie su actividad de forma legal, debe comunicar su "nacimiento" a nivel tributario.
*   **Modelo 036:** Es la declaración censal normal, obligatoria para Startups (S.L.), para solicitar el NIF (provisional y definitivo) y darse de alta.
*   *(Nota: El Modelo 037 es la versión simplificada, pero solo aplica a autónomos/personas físicas).*

Esta declaración funciona como un "menú" donde la empresa "marca" qué impuestos le van a aplicar en el futuro mensual/trimestralmente. Si no se marca en el 036, la empresa no está obligada a presentar el impuesto, pero si opera sin marcarlo comete una gran infracción.

## 2. Epígrafes IAE Comunes para Tecnológicas
El Impuesto de Actividades Económicas (IAE) define a qué se dedica la empresa. Es crucial elegir el correcto para efectos estadísticos, retenciones y futuras ayudas. Startups de Software / SaaS suelen emplear:
*   **Epígrafe 845.** *Explotación electrónica por cuenta de terceros (si el servidor/software sirve a terceros - común en proveedores en la nube).*
*   **Epígrafe 843.1 / 843.2.** *Servicios técnicos de ingeniería / Servicios técnicos de arquitectura e informática (si se hace consultoría o desarrollo a medida).*

*Importante: Las sociedades que facturen menos de 1 millón de euros están EXENTAS del **pago** del IAE, pero NO de la obligación de darse de alta en el epígrafe.*

## 3. El Registro de Operadores Intracomunitarios (ROI) / VIES
Fundamental para cualquier startup de base tecnológica que consuma servicios alojados en Europa (AWS, Google Cloud Ireland, proveedores SaaS europeos).
*   **Qué es:** Un censo europeo. Si la startup está ahí, obtiene un "NIF-IVA" (VAT Number, habitualmente "ES" + el CIF de la empresa, ej. ESB12345678).
*   **Utilidad crítica:** Al aportar el NIF-IVA a AWS o Google, estos proveedores emitirán la factura sin el IVA de Irlanda/Luxemburgo (inversión del sujeto pasivo). Esto evita tener que financiar IVAs extranjeros irrecuperables por ser un coste financiero inútil.
*   **Alta:** Se marca la casilla de alta en ROI en el modelo 036. La AEAT a veces tarda meses o hace visitas presenciales ("comprobación censal") o tele-inspecciones para verificar que no sea una empresa pantalla antes de conceder el ROI.

## 4. Obligación de Retener (Declaración Censal)
En el modelo 036 se debe declarar obligatoriamente que la empresa va a retener el IRPF de:
1.  **Trabajadores asalariados** (nóminas de la plantilla de los 10 empleados).
2.  **Profesionales independientes (Autónomos/Freelance)** (si se subcontratan desarrolladores, abogados, asesores).
3.  **Arrendadores** (si la startup tiene una oficina física cuyo propietario es una empresa/particular al que se le deba retener una parte del pago).
