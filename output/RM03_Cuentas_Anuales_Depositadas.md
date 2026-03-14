# RM03. Formulación y Depósito de Cuentas Anuales (CCAA)

Las Cuentas Anuales son "la foto financiera oficial" de la salud de un año natural de una PYME, y representan el cumplimiento del principio de transparencia que exige la Ley de Sociedades de Capital frente al Registro Mercantil, inversores (*Venture Capital*), bancos y otros terceros de buena fe. 

En este documento se detalla la operativa para formular, aprobar y depositar las CCAA en el seno de una startup tecnológica de hasta 10 empleados.

## 1. El Embudón Contable: Tiempos Legales y Aprobación

El legislador impone un calendario inflexible para garantizar que la información mercantil fluya al mercado de forma veraz y puntual (asumiendo un ejercicio fiscal estándar que coincida con el año natural, del 1 de enero al 31 de diciembre):

1. **Cierre Contable y Regularización (Diciembre Año X - Enero Año X+1):** El CFO / Gestoría cuadra bancos, contabiliza las amortizaciones de desarrollos de software activados, provisiona nóminas y ajusta el IVA y el Impuesto de Sociedades del ejercicio.
2. **Formulación de las Cuentas Anuales (Máximo 3 meses - Hasta 31 de Marzo):** La Ley exige que el Órgano de Administración (CEO, Consejo) elabore físicamente el documento. El CFO es quien materialmente las expide y consolida. Deben estar firmadas (digital o físicamentemente) por todos los administradores vigentes a fecha de formulación.
3. **Junta General Ordinaria de Socios (Máximo 6 meses - Hasta 30 de Junio):** Reunión obligatoria de los *Founders* e Inversores dueños del capital. Los socios:
    * Reúnen el quórum necesario.
    * Votan y aprueban (o rechazan) la gestión del órgano de administración.
    * Aprueban el contenido de las Cuentas Anuales.
    * Votan la aplicación de resultados (ej., destinar las pérdidas a bases negativas a compensar, o los escasos beneficios a Reservas Legales/Voluntarias, ya que las startups no suelen repartir dividendos en fases iniciales).
4. **Depósito Oficial en Sede Mercantil (Máximo 1 mes desde JGA - Hasta 30 de Julio):** Una vez celebrada la asamblea, el CFO u Órgano de Administración dispone de un mes para empaquetar todo telemáticamente y enviarlo al Registro Mercantil central.

## 2. Contenido Documental Obligatorio del Modelo Oficial

Para pymes tecnológicas españolas con 10 empleados (que no superan los topes de Activo > 4M€, Facturación > 8M€ y > 50 empelados), se aplica el modelo de **"PYME" o "Abreviado"**, el cual exime a la startup del Estado de Cambios en el Patrimonio Neto o del Estado de Flujos de Efectivo obligatorios.

El envío telemático mediante el programa D2 del Colegio de Registradores debe contener en su estructura `.ZIP`:

### A. Documentos Contables
1. **Balance de Situación:** Refleja la estructura patrimonial. Mostrará los Derechos de Cobro (Caja/Bancos, Subvenciones concebidas pero no cobradas de ENISA) frente a las Obligaciones (Préstamos convertibles, préstamos participativos, deudas con AEAT/SS).
2. **Cuenta de Pérdidas y Ganancias (PYG):** Resultado del ejercicio. Reflejará como ingresos las cuotas de SaaS/Servicios B2B vendidos, contra el elevado coste salarial del talento técnico (los 10 desarrolladores) y el *burn rate* en servidores e infraestructura.
3. **La Memoria Abreviada:** El documento esencial para los inversores. Una explicación ("letra pequeña") en texto de todo lo sucedido: reglas de inmovilización de software o I+D, pactos con fundadores, operaciones vinculadas (sueldos prestados a administradores), o desglose pormenorizado del cálculo del gasto del IS.

### B. Certificados Complementarios Obligatorios (Firmados por el CEO)
1. **Certificado del Acta de Aprobación de Cuentas:** Documento (PDF generado por el CFO) que indica lugar, fecha, socios presentes y la votación a favor de los balances y distribución del resultado.
2. **Documento sobre la Titularidad Real (TR):** Normativa estricta Anti-Blanqueo de Capitales (Ley 10/2010). El Registro exige rellenar unas casillas donde se informe, con nombre, apellidos y DNI, de quién o quiénes son las personas físicas (*Humanos*) que controlan la startup por encima del **25%** del capital o por acuerdos directivos de pacto de socios. Si se oculta, la falta es gravísima.
3. **Declaración Covid/Medioambiental (y anexos anuales transitorios):** Ciertos formularios extra donde a veces se informan si han recibido moratorias públicas.

## 3. Consecuencias Críticas y Sanciones por Infracción (El "Cierre de Ventanilla")

Depositar las cuentas a tiempo no es un mero "formularismo". Si la startup entra en la "zona zombie" en su *Runway* (falta de dinero) y el CFO despista las cuentas al año siguiente, el impacto legal es fulminante:

1. **Paralización Registral ("Hoja de Cierre" – Art. 378 RRM):** Un año después de vencer el plazo legal del depósito, el Registro *clausurará* la hoja de la empresa de forma digital. La S.L. se vuelve un "cadáver burocrático":
    * No podrá inscribir ampliaciones de capital, ni nombrar nuevos CEOs, ni cambiar domicilios.
    * No podrá otorgar poderes formales a nuevos responsables o abrir sucursales.
2. **Alarma y Bloqueo Bancario:** Inmediatamente las entidades de crédito (Sabadell BStartups, BBVA Spark) verán la infracción societaria por sus APIs automáticas de Compliance. Suspenderán la firma digital del CEO en la entidad y bloquearán líneas de crédito por blanqueo de capitales (*KYC Compliance*).
3. **Sanciones del propio ICAC (Instituto de Contabilidad y Auditoría de Cuentas):** El Gobierno cruza la información entre la AEAT (si pasaste el Impuesto de Sociedades) y los Registradores, notificando automáticamente multas por falta de depósito que varían entre los **1.200 a 60.000 euros**, calculables sobre el volumen de negocio si eras una PYME con tracción y facturación.
4. **Derivación de Responsabilidad (El "Velo Societario"):** Ante un juzgado, los acreedores y proveedores que no cobraron, usarán la falta de depósito de CCAA como dolo agravado para intentar imputar la quiebra al bolsillo personal y viviendas del Administrador/Equipo Director de la Startup, alegando que "ocultó el estado ruinoso de la tech intencionadamente al mercado".

*Acción Preventiva D2/CORPME:* El propio CFO será el artífice de entrar con su firma electrónica corporativa autorizada a la página de Registradores, subir la memoria, importar el XML contable de las sumas saldos, cruzar el D2 sin errores y abonar la tasa obligatoria BORM final de ~60€ euros aprox.
