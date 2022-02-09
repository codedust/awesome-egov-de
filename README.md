# awesome-egov-de

A curated list of resources on egovernment in Germany.

## Related awesome lists
- [awesome-opendata-german](https://github.com/codeforosnabrueck/awesome-opendata-german): articles and other resources about Open Data (by [Code-for-Germany](https://codefor.de/))
- [awesome-behoerden-floss](https://github.com/okfde/awesome-behoerden-floss): F/LOSS software that is used in German government organizations (by [Open Knowledge Foundation Deutschland](https://okfn.de/))
- [awesome-transit](https://github.com/CUTR-at-USF/awesome-transit): list of transit (public transport) APIs, apps, datasets, research, and software

## Community
Places to ask questions and find other community resources.

- [eGov AfterWork meetup](https://egovernment-podcast.com/events/): monthly meetup of the [eGovernment Podcast](https://egovernment-podcast.com/) community
  - [matrix chat](https://matrix.to/#/#egov-afterwork:matrix.org)
  - [Twitter](https://twitter.com/eGovPod/)
- [N3GZ Nachwuchsnetzwerk Digitale Verwaltung](https://n3gz.org/): junior network for people working in public administration, industry and science
  - [eGov-Wiki](https://n3gz.org/egov-wiki/)
  - [mailing list](https://n3gz.org/n%c2%b3-mailingliste/)
  - [Twitter](https://twitter.com/N3GZ_org/)
- [Code for Germany](https://codefor.de/): civic tech open government network
  - [Twitter](https://twitter.com/codeforde/)
- [Zerforschung](https://zerforschung.org/): hacker collective focussing (i.a.) on the security of government infrastrucutre
  - [Twitter](https://twitter.com/zerforschung/)

## Standardization Working Groups
- [EU Working Group "APIs for Innovative Public Services (API4IPS)"](https://ec.europa.eu/cefdigital/wiki/pages/viewpage.action?pageId=254313406)
  - [REST best practices](https://ec.europa.eu/cefdigital/wiki/pages/viewpage.action?pageId=335282435) by that working group

## Resources
### Policies
- [Gesetz zur Verbesserung des Onlinezugangs zu Verwaltungsleistungen (Onlinezugangsgesetz)](https://www.gesetze-im-internet.de/ozg/)
- [Verwaltungsabkommen zur Umsetzung des Onlinezugangsgesetzes](https://www.onlinezugangsgesetz.de/SharedDocs/downloads/Webs/OZG/DE/dachabkommen-vorabversion.pdf?__blob=publicationFile&v=1): administrative agreement on the implemenation of the Onlinezugangsgesetz (OZG)
- [EfA-Mindestanforderungen](https://www.onlinezugangsgesetz.de/SharedDocs/downloads/Webs/OZG/DE/EfA/efa-mindestanforderungen.pdf?__blob=publicationFile&v=3): minimal requirements for the implementation of online services financed by the business activity support program (Konjunkturpaket)
- [Servicestandard für die OZG-Umsetzung](https://www.onlinezugangsgesetz.de/Webs/OZG/DE/umsetzung/servicestandard/servicestandard-node.html): standard quality priciples for online services by BMI
- [Föderale IT-Architekturrichtlinien](https://www.fitko.de/foederale-koordination/gremienarbeit/foederales-it-architekturboard): IT architecture policies by the federal IT architecture board of IT-Planungsrat

### Progress tracking
- [OZG-Dashboard](https://www.onlinezugangsgesetz.de/Webs/OZG/DE/umsetzung/ozg-dashboard/ozg-dashboard-node.html) by BMI
- [OZG-Dashboard NRW](https://www.giscloud.nrw.de/ozg-dashboard.html) by MWIDE NRW
- [OZG-Monitoring](https://ozg.zfinder.de/) by Linie6Plus (BB, HE, MV, NI, RP, SH, ST, TH)
- [OZG-Dashboard](https://ozg.verdrusssache.de/) by Lilith Wittmann
- [OZG-Informationsplattform](https://informationsplattform.ozg-umsetzung.de/)

### Existing, reusable solutions
- [FIT-Store](https://www.fitko.de/produktmanagement/fit-store): Ready to use solutions for governments (including a section on open-source solutions)
- [Bayerische Ehrenamtskarte](https://github.com/digitalfabrik/ehrenamtskarte): Fully open-source solution for entitlement cards

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
- [Open Source Code Repository](https://gitlab.o4oe.de/explore) by BMI, NRW and BW
- [FIT-Connect](https://git.fitko.de/fit-connect) at FITKO-GitLab
- [GitHub and Government](https://government.github.com/community/): list of (not only) German government organizations using GitHub

### APIs
- [bund.dev](https://bund.dev/): a list of public administration APIs, collected by civic tech community
  - [GitHub organization](https://github.com/bundesAPI)
  - [list of APIs as JSON](https://github.com/bundesAPI/apis/blob/main/index.json)
- [Verwaltungssuchmaschine NRW](https://ozg.kdn.de/verwaltungssuchmaschine): search for ARS/AGS, LeiKa-Services and Responsibilities (Zuständigkeiten)
  - [Serviceportal NRW](https://meineverwaltung.nrw/): frontend for end users

### Tooling for developers
- [Italian Open API Validation Checker](https://github.com/teamdigitale/api-oas-checker-action) by Team Digitale, [used by FITKO](https://git.fitko.de/fit-connect/api/-/blob/main/.spectral.yml)

## FOSS projects
- [ozg](https://github.com/LilithWittmann/ozg): parsers/generators for the standards related to "Onlinezugangsgesetz", esp. FIM (xDatenfelder/XZuFi/XÖV)
- [leika-tool](https://github.com/codedust/leika-tool): simple tool to explore the [Leistungskatalog der öffentlichen Verwaltung (LeiKa)](https://de.wikipedia.org/wiki/LeiKa)
- [ars-tool](https://github.com/codedust/ars-tool): simple tool to explore German community identification numbers (Amtliche Regionalschlüssel, ARS)
