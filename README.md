# awesome-egov-de

A curated list of resources on egovernment in Germany.

> Pull requests and feedback via issues welcome! Get in touch via the [matrix](https://matrix.org/) chat at [#awesome-egov-de:tchncs.de](https://matrix.to/#/#awesome-egov-de:tchncs.de)

## Related awesome lists
- [awesome-opendata-german](https://github.com/codeforosnabrueck/awesome-opendata-german): articles and other resources about Open Data (by [Code-for-Germany](https://codefor.de/))
  - [opendata-antipatterns](https://github.com/transportkollektiv/opendata-antipatterns): list of open data anti-patterns that should be avoided
- [awesome-behoerden-floss](https://github.com/okfde/awesome-behoerden-floss): F/LOSS software that is used in German government organizations (by [Open Knowledge Foundation Deutschland](https://okfn.de/))
- [awesome-transit](https://github.com/CUTR-at-USF/awesome-transit): list of transit (public transport) APIs, apps, datasets, research, and software
- [awesome-deutschland](https://github.com/JonasGroeger/awesome-deutschland/): similar list but not restricted to government IT
- [foss-verwaltung](https://codeberg.org/opengovtech/foss-verwaltung): ressources on reuse and of free and open source software by governments (german)

## Community
Places to ask questions and find other community resources.

- [eGov AfterWork meetup](https://egovernment-podcast.com/events/): monthly meetup of the [eGovernment Podcast](https://egovernment-podcast.com/) community
  - [Matrix chat](https://matrix.to/#/#egov-afterwork:matrix.org)
  - [Twitter](https://twitter.com/eGovPod/)
- [N3GZ Nachwuchsnetzwerk Digitale Verwaltung](https://n3gz.org/): junior network for people working in public administration, industry and science
  - [eGov-Wiki](https://n3gz.org/egov-wiki/)
  - [mailing list](https://n3gz.org/n%c2%b3-mailingliste/)
  - [Twitter](https://twitter.com/N3GZ_org/)
- [Code for Germany](https://codefor.de/): civic tech open government network
  - [Twitter](https://twitter.com/codeforde/)
- [bund.dev](https://bund.dev/): civic tech community that documents government APIs
  - [GitHub](https://github.com/bundesAPI)
  - [Twitter](https://twitter.com/bund_dev/)
  - [Slack](https://join.slack.com/t/bunddev/shared_invite/zt-zvvyike8-39zn4X_xSw8JL0dqcIaFqA)
- [Formularium](https://formularium.verdrusssache.de/): a FOSS, privacy-first, and user-friendly toolkit for municipalities to support them in making their public services available online
  - [GitHub](https://github.com/formularium/formularium)
  - [Slack](https://join.slack.com/t/formularium/shared_invite/zt-ooxr8hzr-LMYSF93V~sLwqYaQwiEACg)
- [Zerforschung](https://zerforschung.org/): hacker collective focussing (i.a.) on the security of government infrastrucutre
  - [Twitter](https://twitter.com/zerforschung/)
- [Innovationsverbund Öffentliche Gesundheit (InÖG)](https://www.inoeg.de/): public healthcare tech network that builds open source tools for health offices
  - [GitHub](https://github.com/InOG-projects)
  - [Twitter](https://twitter.com/inoeg_de)
  - [Patreon](https://www.patreon.com/inoeg)

## Standardization Working Groups
- [EU Working Group "APIs for Innovative Public Services (API4IPS)"](https://ec.europa.eu/cefdigital/wiki/pages/viewpage.action?pageId=254313406)
  - [REST best practices](https://ec.europa.eu/cefdigital/wiki/pages/viewpage.action?pageId=335282435) by that working group

## Resources
### Policies
- [Gesetz zur Verbesserung des Onlinezugangs zu Verwaltungsleistungen (Onlinezugangsgesetz)](https://www.gesetze-im-internet.de/ozg/)
- [Verwaltungsabkommen zur Umsetzung des Onlinezugangsgesetzes](https://www.onlinezugangsgesetz.de/SharedDocs/downloads/Webs/OZG/DE/dachabkommen-vorabversion.pdf?__blob=publicationFile&v=1): administrative agreement on the implemenation of the Onlinezugangsgesetz (OZG)
  - Prescribes the use of open standards and open source software (SHOULD)
- [EfA-Mindestanforderungen](https://leitfaden.ozg-umsetzung.de/display/OZG/Arbeitshilfen?preview=/12583387/49316400/EfA_Mindestanforderungen.pdf): minimal technical and legal requirements for the implementation of online services financed by the business activity support program (Konjunkturpaket)
- [Servicestandard für die OZG-Umsetzung](https://www.onlinezugangsgesetz.de/Webs/OZG/DE/grundlagen/servicestandard/servicestandard-node.html): standard quality priciples for online services, by BMI, including a [self audit](https://servicestandard.ozg-umsetzung.de/index.php/62918?lang=de)
  - User centricity (assessment of user requirements, simple and intuitive use, accessibility, proximity to citizens and gender neutrality, once-only principle, data protection, promotion of digital use)
  - Approach (legal change requirements, agile approach, interconnected portals („Portalverbund“))
  - Collaboration (cross-level cooperation, implementation communities)
  - Openness (open standards, open source, software re-use)
  - IT operations (IT security and support, interoperability, technological evaluation)
  - Controlling (evaluation of user satisfaction, user-centered further development)
- [Föderale IT-Architekturrichtlinien](https://www.fitko.de/foederale-koordination/gremienarbeit/foederales-it-architekturboard): IT architecture policies by the federal IT architecture board of IT-Planungsrat
  - Stategic architecture guidelines SR1 and SR3 prescribe the use of open standards (MUST)
  - Stategic architecture guidelines SR2 and SR10 prescribe reusing existing software components and loose coupling (MUST)
  - Stategic architecture guideline SR4 prescribes security by default and privacy by default (MUST)
  - Stategic architecture guideline SR5 prescribes an API-first approach (MUST)
  - Stategic architecture guideline SR6 prescribes usability by design (MUST)
  - Stategic architecture guidelines SR7 and SR8 prescribes for open source licensing (dual-/multi-vendor strategie) (MUST)
  - Stategic architecture guideline SR9 prescribes interoperability between infrastrucutre components (MUST)
  - Stategic architecture guideline SR11 prescribes green IT (MUST)
  - Stategic architecture guideline SR12 prescribes the once-only principle (SHOULD)
  - Stategic architecture guideline SR13 prescribes open data by design (MUST)
- [Eckpunkte Umsetzung des OZG mit Mitteln des Konjunkturpakets](https://www.it-planungsrat.de/fileadmin/beschluesse/2020/Beschluss2020-39_Eckpunkte_Umsetzung_des_OZG.pdf)
  - Mandatory by [IT-PLR decision 2020/39](https://www.it-planungsrat.de/beschluss/beschluss-2020-39)
  - mandatory use of open standards
  - source code of custom software development must be released as open-source-software, if possible. Existing licensing models remain unaffected by this.  

### Literature
- [Better for Less: How to make Government IT deliver savings](https://ntouk.files.wordpress.com/2015/06/better-for-less-1.pdf) (2010) by Liam Maxwell and others: An absolute classic and must-read for decision makers in government organizations. The paper explains what has gone wrong in British egovernment and describes what strategic change is required. Considered to be the conceptual foundation of the [UK Government Digital Service](https://www.gov.uk/).
- [A civic technologist's practice guide](https://cydharrell.com/book/) (2020) by Cyd Harrell: onboarding guide and a survival manual for people interested in civic tech and government it

### Blogs
- [stk's blog](https://stefan.bloggt.es/): Blog by stk about open data, egovernment, and thoughts about the latest tech buzzwords.
- [Lilith Wittmann's blog](https://lilithwittmann.medium.com/)
- [Bianca Kastl's blog](https://bkastl.de/notes)
- [Blog by zerforschung](https://zerforschung.org/): hacker collective focussing on the security of public infrastrucutre

### Podcasts
- [eGovernment Podcast](https://egovernment-podcast.com/): podcast about german eGovernment topics
- eGovernment special by [Lage der Nation](https://lagedernation.org/)
  - [LdN301: „Keine weiteren Fragen“ – Digitalisierung der deutschen Verwaltung, Teil 1](https://lagedernation.org/podcast/ldn301-keine-weiteren-fragen-digitalisierung-der-deutschen-verwaltung-teil-1/)
  - [LdN302: Baustellen & Lösungen – Digitalisierung der deutschen Verwaltung, Teil 2](https://lagedernation.org/podcast/ldn302-baustellen-loesungen-digitalisierung-der-deutschen-verwaltung-teil-2/)

### OZG Progress tracking
- [OZG-Dashboard](https://www.onlinezugangsgesetz.de/Webs/OZG/DE/umsetzung/ozg-dashboard/ozg-dashboard-node.html) by BMI
- [OZG-Dashboard NRW](https://www.giscloud.nrw.de/ozg-dashboard.html) by MWIDE NRW
- [OZG-Monitoring](https://ozg.zfinder.de/) by Linie6Plus (BB, HE, MV, NI, RP, SH, ST, TH)
- [OZG-Dashboard](https://ozg.verdrusssache.de/) by Lilith Wittmann
- [OZG-Informationsplattform](https://informationsplattform.ozg-umsetzung.de/)

### Technical Documentation
- [Standards und Schnittstellen](https://docs.fitko.de/standards-und-schnittstellen/): overview over standards and APIs created by the Portalverbund project
- [Dokumentation der föderalen IT-Landschaft](https://www.fitko.de/foederale-koordination/gremienarbeit/foederales-it-architekturboard): documentation of it architecture with focus of OZG infrastructure by the federal IT architecture board of IT-Planungsrat
  - [archimate sources](https://git.fitko.de/foederale-it/it-landschaft)
- [FIT-Connect](https://docs.fitko.de/fit-connect/): developer resources on public service application submission APIs (project FIT-Connect)
- [Föderales Informationsmanagement (FIM)](https://ozg.nrw/das-ozg/foederales-informationsmanagement-fim) by MWIDE NRW
- [FIM-Haus](https://fimportal.de/fim-haus) at FIM-Portal
- [OZG in NRW - Dokumente](https://ozg.nrw/service/dokumente): Documentation and usage guides about federal IT-Infrastructure by MWIDE NRW

### UI/UX
- [Design-System.SH](https://www.design-system.sh/): design system developed in Schleswig-Holstein, inspired by [GOV.UK Design System](https://design-system.service.gov.uk/)

### Code Repositories
- [code.europa.eu](https://code.europa.eu): GitLab instance for open source projects shared
by the institutions of the European Union
  - [list of projects](https://code.europa.eu/explore)
- [OpenCoDE](https://opencode.de): GitLab instance for German government institutions by BMI, NRW and BW
  - [list of projects](https://gitlab.opencode.de/explore/groups)
- [git.fitko.de](https://git.fitko.de/fit-connect): GitLab instance by Föderale IT-Koorperation (FITKO)
  - [group "FIT-Connect"](https://git.fitko.de/fit-connect)
- [GitLab Land Schleswig-Holstein](https://code.schleswig-holstein.de): GitLab instance by state Schleswig-Holstein
  - [list of projects](https://code.schleswig-holstein.de/explore)
- [Stadt Treuchtlingen at Codeberg.org](https://codeberg.org/stadt_treuchtlingen)
- [GitHub and Government](https://government.github.com/community/): list of (not only) German government organizations using GitHub

### APIs
- [bund.dev](https://bund.dev/): list of public administration APIs, documented by civic tech community
  - [GitHub organization](https://github.com/bundesAPI)
  - [list of APIs as JSON](https://github.com/bundesAPI/apis/blob/main/index.json)
- [Verwaltungssuchmaschine NRW](https://ozg.kdn.de/verwaltungssuchmaschine): search for ARS/AGS, LeiKa-Services and Responsibilities (Zuständigkeiten)
  - [Serviceportal NRW](https://meineverwaltung.nrw/): frontend for end users

### Services
- [OpenPGP Schlüsselbeglaubigung](https://pgp.governikus.de/pgp/): PGP key signing service based on identity card (*neuer Personalausweis*, nPA) verification
- [Portalverbung Onlinegateway (PVOG)](https://servicesuche.bund.de/): search for public services throughout all federal levels
- [elektronischer Personalausweis (nPA / eID)](https://www.personalausweisportal.de/)
  - [blog post by ijonberlin about FIDO support](https://www.ijon.me/2020/04/16/versteckte-funktion-der-eid-fido) for two-factor authentication (2FA)
  - [WebAuthn-eID for Firefox extension](https://addons.mozilla.org/de/firefox/addon/webauthn-eid-for-firefox/)
- [leika-tool](https://github.com/codedust/leika-tool): simple tool to explore the [Leistungskatalog der öffentlichen Verwaltung (LeiKa)](https://de.wikipedia.org/wiki/LeiKa)
- [ars-tool](https://github.com/codedust/ars-tool): simple tool to explore German community identification numbers (Amtliche Regionalschlüssel, ARS)

### Tooling for developers
- [Italian Open API Validation Checker](https://github.com/teamdigitale/api-oas-checker-action) by Team Digitale, [used by FITKO](https://git.fitko.de/fit-connect/api/-/blob/main/.spectral.yml)
- [publiccode.yml](https://yml.publiccode.tools/): metadata standard for repositories containing software developed or acquired by the Public Administration, aimed at making them easily discoverable and thus reusable by other entities
  - [docs](https://yml.publiccode.tools/)
  - [editor](https://publiccode-editor.developers.italia.it/)
  - [GitHub](https://github.com/publiccodeyml/publiccode.yml)
- [ozg](https://github.com/LilithWittmann/ozg): parsers/generators for the standards related to "Onlinezugangsgesetz", esp. FIM (xDatenfelder/XZuFi/XÖV)
- [libzufi](https://github.com/codedust/xzufi): library to parse XZuFi data
- [Din91379-csharp](https://github.com/flxbe/Din91379-csharp): A C# implementation of DIN 91379 (String.Latin)
- [KoliBri](https://github.com/public-ui): an accessible component library by [ITZBund](https://www.itzbund.de).

## Open Source (FOSS) projects
- [Formularium](https://github.com/formularium/formularium): a privacy-first and user-friendly toolkit for municipalities to support them in making their public services available online
- [IRIS connect](https://www.iris-connect.de/): open api for health offices with focus on contract tracing
- [Bayerische Ehrenamtskarte](https://github.com/digitalfabrik/ehrenamtskarte): Fully open-source solution for entitlement cards
- [AusweisApp2](https://www.ausweisapp.bund.de/ausweisapp2/): app for the german identity card (*neuer Personalausweis*, nPA)
  - [GitHub](https://github.com/Governikus/AusweisApp2)
