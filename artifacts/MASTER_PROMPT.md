# MASTER PROMPT PARA REGENERACIÓN DE PROYECTO AI

**Rol de la IA:** Eres un experto Asesor Financiero, CFO (Chief Financial Officer), Gestor Administrativo y Consultor Legal especializado en el ecosistema de Startups tecnológicas radicadas en España (Comunidad de Madrid) con un equipo de hasta 10 empleados.

**Objetivo:** Regenerar desde cero de forma autónoma el repositorio "The CFO Playbook", consistente en 28 archivos Markdown detallados divididos en 4 Organismos del Estado, además de un README.md organizativo.

**Estructura a Generar (Todas las rutas deben comenzar en `output/` a excepción del README.md):**

## REGLAS DE FORMA Y GOBERNANZA
1. Todos los documentos deben estar en **español formal**.
2. Gran profundidad legal y práctica: Incluyendo artículos clave (ej: Ley Crea y Crece, LSC, LGT, RGPD), casos de uso (Venture Capital, rondas, servidores distribuidos, etc.) y plazos inamovibles.
3. El README principal debe listar los 28 ficheros como un índice y usar *badges* estilo Github (shields.io).
4. El alcance general del documento es "startup B2B/B2C, hasta 10 trabajadores, SL".

## PASO 1: ÁREA SEGURIDAD SOCIAL (SS) - 7 Ficheros en `output/`
Genera los siguientes ficheros con el prefijo `SS01_` a `SS07_`:
- `SS01_Intro_y_Sistema_RED.md`: Uso del certificado digital y Sistema RED / CASIA.
- `SS02_Inscripcion_y_Afiliacion.md`: Altas de trabajadores, modelos TA.6 y TA.2.
- `SS03_Cotizacion_y_SILTRA.md`: Uso de SILTRA, CRA, abonos salariales y seguros sociales.
- `SS04_IT_y_Accidentes.md`: Procedimiento ante Mutuas, sistema Delt@ para incapacidades y partes de baja médica.
- `SS05_Legislacion_BOE_BOCAM.md`: Estatuto de los Trabajadores y bonificaciones madrileñas.
- `SS06_Resumen_Formularios_y_Calendario.md`: Lista rápida y calendario mes a mes de vencimientos (días 20 y fin de mes).
- `SS07_Referencias_y_Guias_2026.md`: URLs oficiales, guías TGSS y subida de bases.

## PASO 2: ÁREA AGENCIA TRIBUTARIA (AT) - 7 Ficheros en `output/`
Genera los siguientes ficheros con el prefijo `AT01_` a `AT07_`:
- `AT01_Intro_y_Notificaciones_Electronicas.md`: DEHú, Apoderamientos, 30 días de cortesía.
- `AT02_Alta_Censal_y_Obligaciones.md`: Modelo 036, epígrafes y VIES/ROI intracomunitario.
- `AT03_Impuestos_Trimestrales_y_Anuales.md`: IVA (303), IRPF (111 y 115), e Impuesto de Sociedades (200/202).
- `AT04_Requerimientos_y_Sanciones.md`: Comprobaciones limitadas, moratorias, aplazamientos de IVA e infracciones formales.
- `AT05_Legislacion_LGT_IVA_IS.md`: LGT, LIS, Ley del IVA y Ley de Startups.
- `AT06_Resumen_Modelos_y_Calendario.md`: Calendario Fiscal Trimestral y Fechas NRC.
- `AT07_Referencias_y_Guias_AEAT.md`: Asistentes Virtuales (ADI), consultas vinculantes (DGT).

## PASO 3: ÁREA REGISTRO MERCANTIL Y JUSTICIA (RM) - 7 Ficheros en `output/`
Genera los siguientes ficheros con el prefijo `RM01_` a `RM07_`:
- `RM01_Intro_y_Sede_Registradores.md`: Certificados societarios y Sede CORPME.
- `RM02_Constitucion_y_Legalizacion_Libros.md`: Fundación con 1€ y legalización en abril de Libro de Socios y Actas.
- `RM03_Cuentas_Anuales_Depositadas.md`: Depósito formal en julio, titularidad real y riesgo de cierre registral por icac.
- `RM04_Modificaciones_Estatutarias.md`: Ampliaciones de capital (Seed/Series A), poderes y cese de directivos.
- `RM05_Legislacion_Mercantil.md`: Ley de Sociedades de Capital y RRM.
- `RM06_Resumen_Tramites_y_Calendario.md`: Ciclo anual a 31/12, formulación, juntas y publicación de hitos en BORME.
- `RM07_Referencias_y_Guias_RM.md`: Softwares como el D2, programa Legalia y Aranceles notariales.

## PASO 4: ÁREA PROTECCIÓN DE DATOS (PD / AEPD) - 7 Ficheros en `output/`
Genera los siguientes ficheros con el prefijo `PD01_` a `PD07_`:
- `PD01_Intro_y_Sede_AEPD.md`: Privacidad desde el diseño para startups, sede Notifica.
- `PD02_Registro_Actividades_Tratamiento.md`: RAT obligatorio, servidores AWS e infraestructura.
- `PD03_Gestion_Delegado_DPO.md`: Obligatoriedad y utilidad del DPO ante *Venture Capital*.
- `PD04_Brechas_Seguridad_y_Derechos.md`: Protocolos hackeo 72h (Ransomware), y derechos ARSULIPO.
- `PD05_Legislacion_RGPD_LOPDGDD.md`: Ley LSSI de cookies B2B y RGPD Europa.
- `PD06_Resumen_Tramites_y_Calendario.md`: Revisiones de cláusulas laborales NDA (anuales) y PIAs (Evaluaciones Impacto IA).
- `PD07_Referencias_y_Guias_AEPD.md`: Programa Facilita RGPD oficial de la AEPD y Guías de Tecnologías.

## PASO 5: EL README CENTRAL
Finalmente genera el archivo `README.md` resumiendo todo el alcance de los 28 módulos en 4 Organos de Cumplimiento. Agrega vínculos exactos en Markdown de cada título al path local `./output/Fichero_generado.md`.

*El cumplimiento de estas pautas regenerará de manera íntegra todo el repositorio original CFO Playbook.*
