[← Back to the organization page](README.md) · [中文](TEAM.zh-CN.md) · [Español](TEAM.es.md)

# EveryInfra team

EveryInfra was founded in Santa Clara, California in 2024. We are 26 people in Santa Clara and Singapore: three founders and 23 engineers and researchers.

## Founders

### Echo · Founder and CEO

- **Education:** Columbia University
- **Previously:** Databricks
- **At EveryInfra:** Started on the Delta Lake transaction log and later ran an enterprise data product line at Databricks. Founded EveryInfra in Santa Clara in early 2024 to give developers one key for platform data.

### Hacking · Lead Engineer, Data Platform

- **Education:** Columbia University
- **Previously:** Amazon → Stripe
- **At EveryInfra:** Built money-handling systems at AWS, then spent four years on idempotency and webhook reliability at Stripe. Owns the ledger, billing and every pipeline that touches money.

### keuury · Lead Engineer, Platform Coverage

- **Education:** Harvard University
- **Previously:** Oracle → ByteDance
- **At EveryInfra:** Two years of data integration at Oracle and four years on short-video content data at ByteDance. Owns every social and short-video platform integration at EveryInfra.

## Engineers and researchers

### Marcus Chen · Director of QA

- **Education:**
  - University of Washington, B.S. Computer Science (2008–2012)
- **Previously:**
  - Amazon (Seattle) — QAE → Senior QAE, Marketplace payments and refunds (2013–2019)
  - Expedia Group (Seattle) — QA Manager, settlement platform (2019–2024)
- **At EveryInfra:** Owns the billing regression gate: no pricing or billing change ships until it passes his reconciliation suite.

### Priya Raghavan · SDET, replay testing

- **Education:**
  - IIT Madras, B.Tech. Computer Science (2010–2014)
  - Carnegie Mellon University, M.S. Software Engineering (2014–2015)
- **Previously:**
  - Bloomberg (New York) — Software Engineer → Senior SDET, market data platform (2015–2021)
  - Two Sigma (New York) — SDET, trading data quality (2021–2024)
- **At EveryInfra:** Records anonymized production traffic and replays it across versions to catch billing differences between sync and async calls.

### Jake Morrison · SDET, contract testing

- **Education:**
  - University of Waterloo, B.A.Sc. Software Engineering (2009–2013)
- **Previously:**
  - Atlassian (Sydney / remote) — SDET → Principal, platform engineering (2014–2024)
- **At EveryInfra:** Keeps the catalog, OpenAPI, llms.txt, MCP server and SDKs in agreement; any drift between them fails CI.

### Vivian Zhang (张薇薇) · SDET, end-to-end testing and data masking

- **Education:**
  - UC Berkeley, B.S. Computer Science (2012–2016)
- **Previously:**
  - Meta (Menlo Park) — E2E Engineer → data masking infrastructure (2016–2024)
- **At EveryInfra:** Tests the field allowlists on social data, so that responses, logs, error messages and docs carry only public fields.

### Diego Ramírez · Scraping quality analyst

- **Education:**
  - Tecnológico de Monterrey, B.S. Computer Science (2011–2015)
- **Previously:**
  - Zyte (formerly Scrapinghub) (remote) — Scraping Quality Engineer → Senior (2016–2024)
- **At EveryInfra:** Publishes monthly field-coverage reports for every platform and catches site redesigns before they break results.

### Sam Okafor · SDET, proxies and account pools

- **Education:**
  - Imperial College London, MEng Computing (2013–2017)
- **Previously:**
  - Bright Data (London / Tel Aviv) — Proxy Quality Engineer → Senior (2018–2024)
- **At EveryInfra:** Validates account-pool health checks, quota scheduling and daily limits.

### Dr. Hannah Kessler · Head of Data Research

- **Education:**
  - TU Munich, M.S. Computer Science (2010–2012)
  - TU Munich, Ph.D., web mining (2012–2016)
- **Previously:**
  - Similarweb (Berlin / remote) — Data Scientist → Principal Researcher (2016–2024)
- **At EveryInfra:** Documents how each estimated field is computed and where its sampling bias comes from.

### Kenji Watanabe · Pricing and unit economics

- **Education:**
  - University of Tokyo, B.S. Mathematics (2006–2010)
  - University of Tokyo, M.S. Financial Engineering (2010–2012)
- **Previously:**
  - Nomura Securities (Tokyo) — Quantitative Analyst → VP (2012–2020)
  - Mercari (Tokyo) — Data Scientist, marketplace pricing (2020–2024)
- **At EveryInfra:** Owns the pricing model and risk reserves for every capability.

### Sofia Almeida · Field definitions researcher, e-commerce data

- **Education:**
  - Universidade de São Paulo, B.S. Statistics (2009–2013)
  - Universidade de São Paulo, M.S. Statistics, consumer panel methods (2013–2015)
- **Previously:**
  - Nielsen (São Paulo → global) — Panel Researcher → Senior Researcher (2015–2024)
- **At EveryInfra:** Defines the e-commerce fields for 1688, Taobao and Amazon, such as supplier ratings, price ranges, SKUs and variants, in plain language.

### Ravi Patel · E-commerce data researcher

- **Education:**
  - Georgia Institute of Technology, B.S. Industrial Engineering (2012–2016)
- **Previously:**
  - Jungle Scout (Austin) — Data Analyst → Head of Data Products (2016–2024)
- **At EveryInfra:** Shapes the e-commerce capabilities around the fields sellers actually use.

### Dr. Elena Petrova · Compliance and data ethics researcher

- **Education:**
  - Higher School of Economics (Moscow), B.S. and M.S. Applied Mathematics and Informatics (2007–2012)
  - Max Planck Institute for Software Systems, Ph.D., computational social science (2012–2018)
- **Previously:**
  - MPI-SWS (Kaiserslautern) — Postdoctoral Researcher (2018–2021)
  - A digital rights research institute (Berlin) — Research Scientist (2021–2024)
- **At EveryInfra:** Sets the compliance boundaries for each new platform: what data goes into the product, how it is stored and masked, and how the terms read.

### Alex Kim · Principal backend engineer, API reliability

- **Education:**
  - University of Illinois Urbana-Champaign, B.S. Computer Science (2011–2015)
- **Previously:**
  - Stripe (San Francisco) — Software Engineer → Staff (2015–2024)
- **At EveryInfra:** Designed the idempotent charge and refund flow: a retried request is charged once, and an unknown result is checked before any retry.

### Neha Gupta · Backend engineer, event pipelines

- **Education:**
  - BITS Pilani, B.E. Computer Science (2009–2013)
- **Previously:**
  - Flipkart (Bengaluru) — Data Infrastructure Engineer (2013–2016)
  - Uber (San Francisco) — Senior Software Engineer, data platform (2016–2024)
- **At EveryInfra:** Runs the usage and analytics event pipelines.

### Tom Bradley · Database architect

- **Education:**
  - University of Cambridge, B.A. Computer Science (2007–2011)
- **Previously:**
  - MongoDB (New York / London) — Solutions Architect → Principal Architect (2012–2024)
- **At EveryInfra:** Owns schema, index and data-migration changes; every step that touches customer data is rehearsed first.

### Lucas Ferreira · Principal scraping engineer, rendering and anti-detection

- **Education:**
  - Universidade Federal de Minas Gerais, B.S. Computer Science (2010–2014)
- **Previously:**
  - Oxylabs (Vilnius (remote)) — Scraping Engineer → Principal Engineer (2016–2024)
- **At EveryInfra:** Leads rendering for the web-based capabilities, so that fields come back clean even from heavily obfuscated pages.

### CT Tang (唐承泰) · Principal scraping engineer, scheduling and failover

- **Education:**
  - National Taiwan University, B.S. Computer Science (2011–2015)
- **Previously:**
  - A web automation platform (Prague (remote)) — Platform Engineer → Senior (2016–2024)
- **At EveryInfra:** Designed the multi-source failover scheduling: when one source degrades, requests move to a backup and switch back after recovery.

### Nadia Hassan · Anti-bot specialist

- **Education:**
  - EPFL, B.S. Computer Science (2010–2014)
  - EPFL, M.S. Computer Science, security (2014–2016)
- **Previously:**
  - DataDome (Paris) — ML Engineer → Fingerprinting team lead (2016–2024)
- **At EveryInfra:** Designs the challenge types for the CAPTCHA product line and the human-like behavior on the collection side.

### Grace Liu (刘佳宁) · Head of Frontend, developer console

- **Education:**
  - University of Toronto, B.S. Computer Science, minor in interaction design (2012–2016)
- **Previously:**
  - Shopify (Ottawa) — Frontend Engineer → Senior (2016–2024)
- **At EveryInfra:** Owns the customer console: API keys, usage, balance and invoices.

### Ollie Bennett · Developer experience (DX) engineer

- **Education:**
  - University of Bristol, B.S. Computer Science (2013–2017)
- **Previously:**
  - A YC-backed startup (London) — Full-stack Engineer (2017–2019)
  - Vercel (remote) — DX Engineer (2019–2024)
- **At EveryInfra:** Owns the docs and SDKs, with one goal: a first request that runs within five minutes.

### Marta Kowalska · Product manager, categories and marketplace

- **Education:**
  - Warsaw University of Technology, B.S. Computer Science, minor in economics (2010–2014)
- **Previously:**
  - Allegro (Warsaw) — Product Manager, marketplace categories (2014–2018)
  - RapidAPI (San Francisco) — Senior Product Manager, marketplace platform (2018–2024)
- **At EveryInfra:** Owns the catalog categories and pricing tiers.

### Ben Ortiz · Head of SRE

- **Education:**
  - Arizona State University, B.S. Computer Science (2007–2011)
- **Previously:**
  - AWS (Seattle) — SWE → Senior SRE, CloudFront and edge (2012–2024)
- **At EveryInfra:** Owns deployments, release gates and rollback drills.

### Felix Novak · Security engineer

- **Education:**
  - TU Wien, B.S. Computer Science (2008–2012)
  - TU Wien, M.S. Computer Science, security (2012–2014)
- **Previously:**
  - Cloudflare (Lisbon / remote) — Security Engineer → Senior (2015–2024)
- **At EveryInfra:** Owns host allowlists, edge cache rules and API key leak scanning.

### Jun-seo Park · ML engineer, AI gateway

- **Education:**
  - KAIST, B.S. Computer Science (2011–2015)
  - KAIST, M.S. Machine Learning (2015–2017)
- **Previously:**
  - ByteDance (Seoul / Beijing) — ML Engineer → Senior (2017–2024)
- **At EveryInfra:** Owns model routing and cost control in the AI gateway.
