[← Volver a la página de la organización](README.es.md) · [English](TEAM.md) · [中文](TEAM.zh-CN.md)

# Equipo de EveryInfra

EveryInfra se fundó en Santa Clara, California, en 2024. Somos 26 personas en Santa Clara y Singapur: tres fundadores y 23 ingenieros e investigadores.

## Fundadores

### Echo · Fundador y CEO

- **Formación:** Universidad de Columbia
- **Antes:** Databricks
- **En EveryInfra:** Empezó en el registro de transacciones de Delta Lake y después dirigió una línea de producto de datos empresariales en Databricks. Fundó EveryInfra en Santa Clara a principios de 2024 para dar a los desarrolladores una sola clave para los datos de plataformas.

### Hacking · Ingeniero principal, plataforma de datos

- **Formación:** Universidad de Columbia
- **Antes:** Amazon → Stripe
- **En EveryInfra:** Construyó sistemas de pagos en AWS y pasó cuatro años en idempotencia y fiabilidad de webhooks en Stripe. Es responsable del libro contable, la facturación y todo flujo que toca dinero.

### keuury · Ingeniero principal, cobertura de plataformas

- **Formación:** Universidad de Harvard
- **Antes:** Oracle → ByteDance
- **En EveryInfra:** Dos años de integración de datos en Oracle y cuatro en datos de vídeo corto en ByteDance. Es responsable de todas las integraciones de redes sociales y vídeo corto en EveryInfra.

## Ingenieros e investigadores

### Marcus Chen · Director de QA

- **Formación:**
  - University of Washington, grado en Informática (2008–2012)
- **Antes:**
  - Amazon (Seattle) — QAE → Senior QAE, pagos y reembolsos de Marketplace (2013–2019)
  - Expedia Group (Seattle) — QA Manager, plataforma de liquidación (2019–2024)
- **En EveryInfra:** Es responsable de la puerta de regresión de facturación: ningún cambio de precios o cobros sale sin pasar su suite de conciliación.

### Priya Raghavan · SDET, pruebas de reproducción

- **Formación:**
  - IIT Madras, grado en Informática (2010–2014)
  - Carnegie Mellon University, máster en Ingeniería de Software (2014–2015)
- **Antes:**
  - Bloomberg (Nueva York) — Ingeniera de software → Senior SDET, plataforma de datos de mercado (2015–2021)
  - Two Sigma (Nueva York) — SDET, calidad de datos de trading (2021–2024)
- **En EveryInfra:** Graba tráfico de producción anonimizado y lo reproduce entre versiones para detectar diferencias de cobro entre llamadas síncronas y asíncronas.

### Jake Morrison · SDET, pruebas de contrato

- **Formación:**
  - University of Waterloo, grado en Ingeniería de Software (2009–2013)
- **Antes:**
  - Atlassian (Sídney / remoto) — SDET → Principal, ingeniería de plataforma (2014–2024)
- **En EveryInfra:** Mantiene de acuerdo el catálogo, OpenAPI, llms.txt, el servidor MCP y los SDK; cualquier diferencia entre ellos rompe la CI.

### Vivian Zhang (张薇薇) · SDET, pruebas de extremo a extremo y enmascaramiento de datos

- **Formación:**
  - UC Berkeley, grado en Informática (2012–2016)
- **Antes:**
  - Meta (Menlo Park) — Ingeniera E2E → infraestructura de enmascaramiento de datos (2016–2024)
- **En EveryInfra:** Prueba las listas de campos permitidos en los datos sociales para que respuestas, registros, errores y documentación solo lleven campos públicos.

### Diego Ramírez · Analista de calidad de extracción

- **Formación:**
  - Tecnológico de Monterrey, grado en Ciencias Computacionales (2011–2015)
- **Antes:**
  - Zyte (formerly Scrapinghub) (remoto) — Ingeniero de calidad de extracción → Senior (2016–2024)
- **En EveryInfra:** Publica informes mensuales de cobertura de campos de cada plataforma y detecta rediseños de sitios antes de que rompan los resultados.

### Sam Okafor · SDET, proxies y pools de cuentas

- **Formación:**
  - Imperial College London, MEng en Computación (2013–2017)
- **Antes:**
  - Bright Data (Londres / Tel Aviv) — Ingeniero de calidad de proxies → Senior (2018–2024)
- **En EveryInfra:** Valida los chequeos de salud del pool de cuentas, la planificación de cuotas y los límites diarios.

### Dr. Hannah Kessler · Directora de Investigación de Datos

- **Formación:**
  - TU Munich, máster en Informática (2010–2012)
  - TU Munich, doctorado en minería web (2012–2016)
- **Antes:**
  - Similarweb (Berlín / remoto) — Científica de datos → Investigadora principal (2016–2024)
- **En EveryInfra:** Documenta cómo se calcula cada campo estimado y de dónde viene su sesgo de muestreo.

### Kenji Watanabe · Precios y economía unitaria

- **Formación:**
  - Universidad de Tokio, grado en Matemáticas (2006–2010)
  - Universidad de Tokio, máster en Ingeniería Financiera (2010–2012)
- **Antes:**
  - Nomura Securities (Tokio) — Analista cuantitativo → VP (2012–2020)
  - Mercari (Tokio) — Científico de datos, precios del marketplace (2020–2024)
- **En EveryInfra:** Es responsable del modelo de precios y las reservas de riesgo de cada capacidad.

### Sofia Almeida · Investigadora de definiciones de campos, datos de comercio electrónico

- **Formación:**
  - Universidade de São Paulo, grado en Estadística (2009–2013)
  - Universidade de São Paulo, máster en Estadística, métodos de paneles de consumidores (2013–2015)
- **Antes:**
  - Nielsen (São Paulo → global) — Investigadora de paneles → Investigadora sénior (2015–2024)
- **En EveryInfra:** Define en lenguaje claro los campos de comercio electrónico de 1688, Taobao y Amazon, como valoraciones de proveedores, rangos de precio, SKU y variantes.

### Ravi Patel · Investigador de datos de comercio electrónico

- **Formación:**
  - Georgia Institute of Technology, grado en Ingeniería Industrial (2012–2016)
- **Antes:**
  - Jungle Scout (Austin) — Analista de datos → Responsable de productos de datos (2016–2024)
- **En EveryInfra:** Diseña las capacidades de comercio electrónico en torno a los campos que los vendedores usan de verdad.

### Dr. Elena Petrova · Investigadora de cumplimiento y ética de datos

- **Formación:**
  - Higher School of Economics (Moscú), grado y máster en Matemática Aplicada e Informática (2007–2012)
  - Max Planck Institute for Software Systems, doctorado en ciencias sociales computacionales (2012–2018)
- **Antes:**
  - MPI-SWS (Kaiserslautern) — Investigadora posdoctoral (2018–2021)
  - A digital rights research institute (Berlín) — Científica investigadora (2021–2024)
- **En EveryInfra:** Fija los límites de cumplimiento de cada nueva plataforma: qué datos entran en el producto, cómo se guardan y enmascaran, y cómo se redactan los términos.

### Alex Kim · Ingeniero principal de backend, fiabilidad de la API

- **Formación:**
  - University of Illinois Urbana-Champaign, grado en Informática (2011–2015)
- **Antes:**
  - Stripe (San Francisco) — Ingeniero de software → Staff (2015–2024)
- **En EveryInfra:** Diseñó el flujo idempotente de cobros y reembolsos: una solicitud reintentada se cobra una vez y un resultado desconocido se verifica antes de reintentar.

### Neha Gupta · Ingeniera de backend, pipelines de eventos

- **Formación:**
  - BITS Pilani, grado en Informática (2009–2013)
- **Antes:**
  - Flipkart (Bangalore) — Ingeniera de infraestructura de datos (2013–2016)
  - Uber (San Francisco) — Ingeniera de software sénior, plataforma de datos (2016–2024)
- **En EveryInfra:** Gestiona los pipelines de eventos de uso y analítica.

### Tom Bradley · Arquitecto de bases de datos

- **Formación:**
  - University of Cambridge, grado en Informática (2007–2011)
- **Antes:**
  - MongoDB (Nueva York / Londres) — Arquitecto de soluciones → Arquitecto principal (2012–2024)
- **En EveryInfra:** Es responsable de esquemas, índices y migraciones de datos; cada paso que toca datos de clientes se ensaya antes.

### Lucas Ferreira · Ingeniero principal de extracción, renderizado y antidetección

- **Formación:**
  - Universidade Federal de Minas Gerais, grado en Informática (2010–2014)
- **Antes:**
  - Oxylabs (Vilna (remoto)) — Ingeniero de extracción → Ingeniero principal (2016–2024)
- **En EveryInfra:** Dirige el renderizado de las capacidades web para que los campos vuelvan limpios incluso de páginas muy ofuscadas.

### CT Tang (唐承泰) · Ingeniero principal de extracción, planificación y conmutación

- **Formación:**
  - Universidad Nacional de Taiwán, grado en Informática (2011–2015)
- **Antes:**
  - A web automation platform (Praga (remoto)) — Ingeniero de plataforma → Senior (2016–2024)
- **En EveryInfra:** Diseñó la planificación con conmutación entre fuentes: si una fuente se degrada, las solicitudes pasan a otra de respaldo y vuelven al recuperarse.

### Nadia Hassan · Especialista antibots

- **Formación:**
  - EPFL, grado en Informática (2010–2014)
  - EPFL, máster en Informática, seguridad (2014–2016)
- **Antes:**
  - DataDome (París) — Ingeniera de ML → Líder del equipo de huellas digitales (2016–2024)
- **En EveryInfra:** Diseña los tipos de desafío de la línea CAPTCHA y el comportamiento humano en la recolección.

### Grace Liu (刘佳宁) · Responsable de Frontend, consola para desarrolladores

- **Formación:**
  - University of Toronto, grado en Informática con especialidad menor en diseño de interacción (2012–2016)
- **Antes:**
  - Shopify (Ottawa) — Ingeniera de frontend → Senior (2016–2024)
- **En EveryInfra:** Es responsable de la consola de clientes: claves API, uso, saldo y facturas.

### Ollie Bennett · Ingeniero de experiencia de desarrollador (DX)

- **Formación:**
  - University of Bristol, grado en Informática (2013–2017)
- **Antes:**
  - A YC-backed startup (Londres) — Ingeniero full stack (2017–2019)
  - Vercel (remoto) — Ingeniero DX (2019–2024)
- **En EveryInfra:** Es responsable de la documentación y los SDK, con un objetivo: que la primera solicitud funcione en cinco minutos.

### Marta Kowalska · Product manager, categorías y marketplace

- **Formación:**
  - Universidad Tecnológica de Varsovia, grado en Informática con especialidad menor en Economía (2010–2014)
- **Antes:**
  - Allegro (Varsovia) — Product manager, categorías del marketplace (2014–2018)
  - RapidAPI (San Francisco) — Product manager sénior, plataforma de marketplace (2018–2024)
- **En EveryInfra:** Es responsable de las categorías del catálogo y los niveles de precio.

### Ben Ortiz · Responsable de SRE

- **Formación:**
  - Arizona State University, grado en Informática (2007–2011)
- **Antes:**
  - AWS (Seattle) — SWE → Senior SRE, CloudFront y edge (2012–2024)
- **En EveryInfra:** Es responsable de los despliegues, los controles de publicación y los simulacros de reversión.

### Felix Novak · Ingeniero de seguridad

- **Formación:**
  - TU Wien, grado en Informática (2008–2012)
  - TU Wien, máster en Informática, seguridad (2012–2014)
- **Antes:**
  - Cloudflare (Lisboa / remoto) — Ingeniero de seguridad → Senior (2015–2024)
- **En EveryInfra:** Es responsable de las listas de hosts permitidos, las reglas de caché en el edge y el escaneo de fugas de claves API.

### Jun-seo Park · Ingeniero de ML, pasarela de IA

- **Formación:**
  - KAIST, grado en Informática (2011–2015)
  - KAIST, máster en Aprendizaje Automático (2015–2017)
- **Antes:**
  - ByteDance (Seúl / Pekín) — Ingeniero de ML → Senior (2017–2024)
- **En EveryInfra:** Es responsable del enrutamiento de modelos y el control de costes en la pasarela de IA.
