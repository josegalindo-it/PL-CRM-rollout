<!--
PROPOSAL_TEMPLATE.md — v1.1 (homologación de variables, 22/09/2026)

Plantilla del brief LIGERO de una oportunidad. Para usarla: copia este fichero
a outputs/<repo>/src/PROPOSAL_<id>.md, rellena los campos y pega la oferta
en "Job Description" tal cual — sin reformatear, sin resumir.

Esto NO es el mismo formato que el PROPOSAL_<id>.md narrativo (MOTIVATION /
WHAT I BRING / PROJECT / CLOSING) que a veces llega ya redactado desde el
sistema TOS y que procesa `proposal_to_scheme.py`. Son dos rutas de entrada
distintas al mismo `SCHEME.md` — usa esta cuando partes de una oferta en
crudo (un job description, un mensaje de un reclutador, un enlace pegado como
texto) y no de una narrativa ya escrita:

  Ruta A (narrativa ya escrita, formato antiguo):
    PROPOSAL_<id>.md (narrativo) -> proposal_to_scheme.py -> SCHEME.md borrador

  Ruta B (brief en crudo, este fichero):
    PROPOSAL_<id>.md (este brief) + FACT_SHEETS.md -> Claude (ver CLAUDE.md
    en la raíz del repo) redacta SCHEME.md directamente -> tu revisión

En la Ruta B no hay script determinista intermedio: es Claude quien lee este
brief y FACT_SHEETS.md, selecciona qué logros/certificaciones/cifras de
FACT_SHEETS.md son relevantes para ESTA oferta concreta (nunca vuelca el
fichero entero) y redacta el `SCHEME.md` siguiendo MICROSITE_TEMPLATE.<idioma>.md
y las reglas de MICROSITE_SCHEME.md. Repite igual que la Ruta A: `SCHEME.md`
sigue siendo el único fichero que se revisa y aprueba a mano antes de construir
el sitio (build.py) — este brief no se toca después de escrito.

NOTA (22/09/2026) — este brief se redactó con los nombres de campo de v1.0
(Role Position/Customer/Language/Job Description/Type/Repo/Fecha) y se ha
migrado aquí a los de v1.1, homologados con SCHEME.md, tras completar el
caso real. cv_pdf se rellena en retrospectiva con el nombre de fichero
original que Jose adjuntó a mano ("Jose Galindo_SPM.pdf"); ya está renombrado
a la convención (assets/cv-pl-crm-rollout.pdf) y conectado en SCHEME.md.
-->
---
rol_u_oportunidad: "Senior Project Manager"
cliente_u_organizacion: ""
idioma: en                      # en | es — idioma en el que se redactará SCHEME.md
tipo: oferta-freelance           # candidatura-empleo | oferta-freelance | candidatura-formacion — mismo vocabulario que SCHEME.md
repo: "PL-CRM-rollout"           # nombre de la carpeta en outputs/<repo>/ y, más adelante, del repo
                                 # de GitHub publicado en proposals.josegalindo.net/<repo>/; el
                                 # slug de SCHEME.md se deriva de este en minúsculas y con guiones
fecha: "2026-09-22"
cv_pdf: "Jose Galindo_SPM.pdf"   # ya procesado — ver NOTA arriba
resumen_oferta: ""              # resumen de una línea; el texto completo va en la sección de abajo
---

## Job Description

Senior Project Manager, Global CRM Rollout and Vendor Management

We're looking for a Senior Project Manager for our client, which is a life sciences company operating across different markets.
It is rolling out new CRM capabilities to its commercial organisation, built on Veeva, Salesforce or a combination of both. The programme involves several vendors and implementation partners working in parallel, alongside global and local business teams.

📍Location: Remote
✍️ Engagement: Full-time, 6-12 month contract initially. Potential extension
✈️ Travel: Minimal, limited to occasional on-site workshops

We are looking for a Senior Project Manager to act as the CIO's delivery lead and the central point of coordination for everyone involved. You will supervise vendors and hold them to account, keep business and IT stakeholders aligned, and make sure the rollout lands well in every market. You will not be configuring the platforms yourself. Your job is to make sure the people who do deliver on time, on budget and to the standard the business needs.

This is a fully remote role and travel is only required on specific occasions when in-person workshops are needed.

Key responsibilities 🎯
Vendor management and supervision

- Act as the single point of contact between the client and all vendors, including platform providers, system integrators, data providers and content agencies
- Oversee statements of work, milestones, deliverables and service levels, and escalate when they are not met
- Coordinate work across vendors so that dependencies, handovers and integration points are actively managed
- Review vendor plans, estimates and change requests, and advise the CIO on commercial and contractual implications
- Run regular vendor performance reviews and keep a clear record of issues and decisions
- Serve as the bridge between IT, commercial, marketing, medical, compliance and country teams
- Translate business requirements into clear direction for vendors, and explain technical constraints back to the business in plain terms
- Own the integrated programme plan across all workstreams and vendors
- Set up and run steering committees, vendor boards and working groups, with clear decision rights
- Maintain the RAID log, budget tracking and status reporting for the CIO and executive sponsors
- Coordinate market readiness: data migration, local configuration, training, compliance sign-off and hypercare
- Balance the global template against genuine local requirements, and challenge unnecessary deviation

Experience and knowledge 👨🏻‍💻
Life sciences and commercial

- At least 8 years in life sciences, with substantial time in sales and marketing or commercial IT
- Solid understanding of field force operations, multichannel engagement, key account management and HCP data
- Working knowledge of pharma compliance, including GDPR, HCP transparency and promotional review
Platforms

- Strong knowledge of both Veeva (CRM or Vault CRM and related modules such as CLM, Approved Email, Events Management and OpenData) and Salesforce (Sales Cloud, Service Cloud or Life Sciences Cloud, and ideally Marketing Cloud)
Understanding of how the two platforms can coexist, integrate with each other and connect to MDM, marketing automation and data warehouse environments

Programme and vendor management

- At least 8 years leading complex, multi-country technology programmes
- Proven experience managing several vendors and implementation partners on the same programme
- Track record of enterprise CRM rollouts across multiple markets
- Experience with contract and SOW oversight, change control and vendor performance management

- Recognised certification such as PMP, PRINCE2 or MSP is desirable; agile delivery experience is a plus

✅ Let us know your related experience in your presentation message and please confirm your full-time remote availability
