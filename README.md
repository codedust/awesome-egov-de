# awesome-egov-de

A curated list of resources on egovernment in Germany.

## Related awesome lists
- [awesome-opendata-german](https://github.com/codeforosnabrueck/awesome-opendata-german): articles and other resources about Open Data (by [Code-for-Germany](https://codefor.de/))
  - [opendata-antipatterns](https://github.com/transportkollektiv/opendata-antipatterns): list of open data anti-patterns that should be avoided
- [awesome-behoerden-floss](https://github.com/okfde/awesome-behoerden-floss): F/LOSS software that is used in German government organizations (by [Open Knowledge Foundation Deutschland](https://okfn.de/))
- [awesome-transit](https://github.com/CUTR-at-USF/awesome-transit): list of transit (public transport) APIs, apps, datasets, research, and software
- [awesome-deutschland](https://github.com/JonasGroeger/awesome-deutschland/): similar list but not restricted to government IT

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
- [EfA-Mindestanforderungen](https://www.onlinezugangsgesetz.de/SharedDocs/downloads/Webs/OZG/DE/EfA/efa-mindestanforderungen.pdf?__blob=publicationFile&v=3): minimal technical and legal requirements for the implementation of online services financed by the business activity support program (Konjunkturpaket)
- [Servicestandard für die OZG-Umsetzung](https://www.onlinezugangsgesetz.de/Webs/OZG/DE/umsetzung/servicestandard/servicestandard-node.html): standard quality priciples for online services, by BMI, including a [self audit](https://servicestandard.ozg-umsetzung.de/index.php/62918?lang=de)
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

### Literature
- [Better for Less: How to make Government IT deliver savings](https://ntouk.files.wordpress.com/2015/06/better-for-less-1.pdf) (2010) by Liam Maxwell and others: An absolute classic and must-read for decision makers in government organizations. The paper explains what has gone wrong in British egovernment and describes what strategic change is required. Considered to be the conceptual foundation of the [UK Government Digital Service](https://www.gov.uk/).
- [stk's blog](https://stefan.bloggt.es/): Blog by stk about open data, egovernment, and thoughts about the latest tech buzzwords.
- [Lilith Wittmann's blog](https://lilithwittmann.medium.com/)

### best practices OSS in der öffentlichen Verwaltung
- [Entwicklung einer Open Source Strategie beim Bundesamt für Strahlenschutz](https://media.ccc.de/v/fossgis2022-14146-die-open-source-strategie-des-bundesamtes-fr-strahlenschutz-bfs-bei-der-entwicklung-der-notfallschutzsysteme-ein-weg-fr-behrden-zu-mehr-digitaler-souvernitt-und-nachhaltigkeit)
- [Linux Arbeitsplatz Schleswig-Holstein (Studie)](https://www.schleswig-holstein.de/DE/landesregierung/themen/digitalisierung/linux-plus1/Downloads/_dateien/linux-studie.html)
- [Impulsvortrag für OSS auf kommunaler Ebene: pull request your government](https://pretalx.com/foss-backstage-2022/talk/RWUAZT/)

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
- [Open Source Code Repository](https://opencode.de): GitLab instance by BMI, NRW and BW
- [FIT-Connect](https://git.fitko.de/fit-connect): GitLab instance by Föderale IT-Koorperation (FITKO)
- [GitLab Land Schleswig-Holstein](https://code.schleswig-holstein.de/explore): GitLab instance by state Schleswig-Holstein
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

### Tooling for developers
- [Italian Open API Validation Checker](https://github.com/teamdigitale/api-oas-checker-action) by Team Digitale, [used by FITKO](https://git.fitko.de/fit-connect/api/-/blob/main/.spectral.yml)

## Open Source (FOSS) projects
- [ozg](https://github.com/LilithWittmann/ozg): parsers/generators for the standards related to "Onlinezugangsgesetz", esp. FIM (xDatenfelder/XZuFi/XÖV)
- [Formularium](https://github.com/formularium/formularium): a privacy-first and user-friendly toolkit for municipalities to support them in making their public services available online
- [leika-tool](https://github.com/codedust/leika-tool): simple tool to explore the [Leistungskatalog der öffentlichen Verwaltung (LeiKa)](https://de.wikipedia.org/wiki/LeiKa)
- [ars-tool](https://github.com/codedust/ars-tool): simple tool to explore German community identification numbers (Amtliche Regionalschlüssel, ARS)
- [libzufi](https://github.com/codedust/xzufi): library to parse XZuFi data
- [IRIS connect](https://www.iris-connect.de/): open api for health offices with focus on contract tracing
- [Bayerische Ehrenamtskarte](https://github.com/digitalfabrik/ehrenamtskarte): Fully open-source solution for entitlement cards
- [AusweisApp2](https://www.ausweisapp.bund.de/ausweisapp2/): app for the german identity card (*neuer Personalausweis*, nPA)
  - [GitHub](https://github.com/Governikus/AusweisApp2)
- [tldrlegal](https://tldrlegal.com/): tool to compare several OSS licences
- [bflow](http://bflow.org/): business process modelling, OSS based
