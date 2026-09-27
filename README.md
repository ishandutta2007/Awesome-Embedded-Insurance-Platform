# Awesome-Embedded-Insurance-Platform

## Top Embedded Insurance Platforms Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on API-First Insurance Distribution, White-Label Coverage & Integration at Point of Sale*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Embedded Insurance**. These tools help platforms, marketplaces, fintechs, and carriers embed insurance products directly into customer journeys — travel booking, device purchase, car checkout, or mortgage closing — via API-first infrastructure and white-label distribution.



**Examples** include Cover Genius, Qover, Boost Insurance, Openly, Sure, Instanda, Setoo, Wrisk, Companjon, and Embedded Insurance Europe (the category leaders).



**Open-source emphasis**: Embedded insurance is one of the most commercially consolidated insurtech categories. Nearly all leading players are proprietary platforms. This section documents the small but growing set of **open-source foundations** for building insurance platforms — primarily core insurance platforms (policy administration, claims, embedded insurance modules) rather than turnkey embedded distribution APIs. Teams seeking fully open embedded insurance infrastructure must typically build on open core platforms or accept commercial APIs.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents



- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Cover Genius](https://covergenius.com/)**

  Global embedded insurance distribution platform. Enables e-commerce, travel, and fintech platforms to offer white-label insurance products via API. Processes claims in an average of 7 days with 60%+ automated adjudication. Partners include Booking.com, eBay, and Ryanair .



- **[Qover](https://qover.com/)**

  Brussels-based embedded insurance specialist operating across 32 EU/UK jurisdictions. API-first platform with built-in GDPR, DORA, and IDD compliance. Partners include Revolut (purchase protection, travel cover) and Deliveroo (rider accident cover) .



- **[Boost Insurance](https://boostinsurance.com/)**

  Embedded insurance infrastructure platform providing API-first distribution for partners. Enables platforms to offer insurance products without holding carrier licenses.



- **[Openly](https://openly.com/)**

  Homeowners insurance carrier with embedded distribution partnerships. Integrates into real estate and mortgage closing workflows for last-mile quotes.



- **[Sure](https://www.sure.com/)**

  Los Angeles-based MGA-as-a-Service platform with 50-state US license footprint. Pre-contracted carriers include Chubb, Munich Re, and Markel. No-code studio lets partners model product lines and pricing in a GUI, ship storefront via one-line web component (`<SurePolicy />`). Average go-live: 6 weeks. Partners include Carvana, AAA .



- **[INSTANDA](https://instanda.com/)**

  No-code insurance platform with embedded insurance modules. Enables insurers and MGAs to design, build, and launch products without traditional IT development cycles.



- **[Setoo](https://setoo.co/)**

  Embedded insurance platform focused on parametric and micro-duration coverage. Partners with travel, e-commerce, and mobility platforms.



- **[Wrisk](https://wrisk.com/)**

  Embedded insurance platform for automotive and mobility sectors. Provides white-label insurance products integrated into vehicle purchase and ownership journeys.



- **[Companjon](https://companjon.com/)**

  Dublin-based embedded insurance specialist. Provides API-first protection products for digital platforms including purchase protection, travel, and gadget insurance.



- **[Embedded Insurance Europe](https://embeddedinsurance.eu/)**

  European embedded insurance platform connecting carriers, MGAs, and distribution partners.



## Open-Source GitHub Projects



- **[Openkoda](https://github.com/openkoda/openkoda)**

  The most complete open-source insurance platform for building embedded insurance applications. MIT-licensed Core edition includes pre-built modules for **policy administration, claims management, and embedded insurance**. Stack: Java 17+, Spring Boot, Hibernate, PostgreSQL, Docker. Auto-generated REST/GraphQL APIs, visual dashboard builder, data model builder, document generation, multi-tenancy, role-based security, and audit trails. Enterprise edition adds AI reporting and advanced clustering. ~60% faster than building from scratch; users report 23% cross-sell lift and 65% faster custom feature delivery .



- **[Yosef](https://github.com/elyosemite/yosef)**

  Community-driven open-source microservices platform for the financial insurance industry. Includes full insurance lifecycle: identity management (Keycloak), project-based organization, quotation management, policy creation, notification service (SMS/gRPC), event processor, analytics service, and claims service. Stack: .NET C#, Python, Gleam, TypeScript, Golang. Observability via Grafana, Loki, Jaeger, Prometheus. Enterprise-grade security with HashiCorp Vault .



- **[InsuranceRAG](https://github.com/InsuranceRAG/InsuranceRAG)**

  Open-source implementation of multi-module Retrieval-Augmented Generation for health insurance applications. Three modules: Chatbot, Document Retrieval, and Policy Recommendation. Uses FAISS vector index, SentenceTransformer embeddings, and DeepSeek/LLaMA LLM backend. MIT licensed, published with peer-reviewed evaluation (Hit@5 scores 0.92–1.00, BERTScore F1 0.84) .



- **[Insurance Broker AI (Scalovate)](https://github.com/rulhaq/insurance-broker-ai)**

  Full-stack insurance broker platform with AI-powered workflow automation. Features automatic risk assessment, fraud detection, underwriting automation, policy management, claims processing, and customer communication sequences. Simulates integration with major carriers (State Farm, GEICO, Progressive, etc.) and AI services (Groq API, custom risk models). Firebase deployment .



### Additional Strong Open-Source Options



- **Core Insurance Platforms**: **Openkoda** (most complete, embedded insurance module), **Yosef** (microservices, full lifecycle) .

- **AI/Intelligence Layer**: **InsuranceRAG** (retrieval-augmented generation for policy Q&A and recommendations) .

- **Broker/Agent Platforms**: **Scalovate** (AI-powered broker platform with automation) .

- **Educational/Reference Projects**: Various insurance management systems on GitHub topics `insurance-project` and `insurance-management` .



**Frameworks for building custom systems**: Combine **Openkoda** for the core policy administration and embedded insurance module, **Yosef** for microservices orchestration and full lifecycle management, and **InsuranceRAG** for AI-powered policy Q&A and recommendation. Add **PostgreSQL** for persistence and **Docker** for deployment. Note that embedded distribution APIs (real-time quoting, binding, white-label widgets) must typically be built custom or sourced from commercial vendors.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Embedded insurance platforms handle sensitive financial and personal data; ensure compliance with insurance regulations (IDD, state licensing), data protection laws (GDPR, CCPA), and platform-specific requirements.

- **Open-source reality**: Fully open embedded insurance distribution infrastructure (real-time quoting APIs, white-label widgets, carrier capacity matching) is essentially non-existent. Openkoda provides the closest foundation but requires significant custom development for production embedded distribution. Most leading embedded insurance providers are proprietary platforms .



---



**Made for insurtech builders, platform product managers, MGA operators, and carrier innovation teams.**

Let's make embedded insurance infrastructure more open, transparent, and accessible.
