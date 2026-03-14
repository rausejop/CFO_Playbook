# PD06. Resumen de Trámites, Auditorías y Calendario de Cumplimiento

La Privacidad no es un "impuesto que se liquida a día 20", ni se hace una vez al año. Es un estado vivo de seguridad informática y jurídica operativa.

## 1. Calendario de Verificación del CFO/DPO
En una Startup de <10 empleados sin alta criticidad B2C médica, el calendario es de "baja periodicidad" formal hacia la AEPD pero alta hacia el interior. No hay vencimiento trimestral con Hacienda, pero si hitos recomendados.

*   **Hito 1 (Instantáneo al Constituir la Startup):** Elaboración y cierre del RAT (Registro de Actividades de Tratamiento).
*   **Hito 2 (Instantáneo pre-Lanzamiento SaaS/WEB):** Validación legal con abogados / revisión DPO de las 2 Capas web ("Privacy Policy, Cookies y T&C Terms and Conditions").
*   **Hito 3 (Cuando llega cada empleado):** Firma física de los anexos del contrato laboral ("Acuerdo de Confidencialidad NDA del Código" + "Consentimiento para el uso de su foto en Slack corporativo" + "Política de uso del Portátil de la SL").
*   **Hito 4 (Anual de Mantenimiento):** El DPO/CFO debe revisar que el RAT sigue coincidiendo con la realidad de código escrito. (Ejemplo: En el año 1, programaban B2B. En el Año 2 de repente los Developers enchufaron un SDK a TikTok y cogen métricas B2C sin decírselo a Finanzas. Ese año todo el ecosistema legal es diferente y debe rehacerse).

## 2. Evaluaciones de Impacto (EIPD / PIA)
Si la startup "va a sacar un Feature" hiperinvasivo:
*   *Ejemplo real:* La startup de repente quiere lanzar "Análisis de caras de los empleados de los clientes B2B con IA mediante fotos".
*   Antes de picar la primera línea de código de ese feature para vender, el CFO está OBLIGADO A AVISAR AL CTO de pedir un **estudio PIA** (Evaluación de Impacto en la Protección de Datos).
*   Un documento formal que sopesa "los riesgos vs garantías" y en muchas ocasiones debes enviarlo a la propia AEPD sede en Madrid a pedirles permiso para hacer o lanzar al mercado esa tecnología predictiva.

## 3. Las "Auditorías Bianuales" Recomendadas
Años atrás la auditoría física del fichero era obligatoria por un perito. Ahora el *Accountability* GDPR te dice que te audites libremente, pero recomienda **auditorías al menos cada dos (2) años** en Startups consolidadas con cierto nivel de riesgos B2B comerciales, ejecutada externamente para detectar desvíos técnicos (Bases de datos no cifradas TDE en el motor RDS o *Pass plain text*) vs los textos de privacidad.
