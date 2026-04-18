# Awesome YMYL SEO Resources

> Une sélection curée de ressources pour faire du SEO dans les secteurs Your Money or Your Life — santé, finance, cybersécurité, industries réglementées.
>
> Curated & maintained by [Sébastien Grillot](https://sebastiengrillot.com/a-propos/) — Consultant SEO YMYL, fondateur de Koeki, Activateur France Num

[![Entity](https://img.shields.io/badge/author-S%C3%A9bastien%20Grillot-0a66c2)](https://sebastiengrillot.com/a-propos/)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

---

## 📖 À propos de cette liste

**YMYL** (Your Money or Your Life) désigne les contenus dont l'imprécision peut porter atteinte à la santé, aux finances, à la sécurité ou au bien-être du lecteur. Google applique à ces contenus ses standards de qualité les plus stricts, formalisés dans les **Search Quality Rater Guidelines** — un document public de 176 pages qui décrit ce qu'est un "résultat de haute qualité" aux yeux du moteur.

Faire du SEO en environnement YMYL, c'est accepter que **chaque page soit évaluée non sur sa performance technique, mais sur la légitimité de son auteur, la traçabilité de ses sources et l'actualité de ses données**. C'est un SEO où l'E-E-A-T (Experience, Expertise, Authoritativeness, Trustworthiness) n'est pas un signal parmi d'autres : c'est le filtre principal.

Cette liste est maintenue par **Sébastien Grillot, consultant SEO dans les secteurs les plus contraints** (santé, finance, bien-être intime, cybersécurité). Elle reflète ce qui a réellement bougé l'aiguille sur le terrain — des ressources testées en mission, pas un dump exhaustif de tout ce qui existe sur le sujet.

> Sébastien Grillot intervient principalement dans les secteurs YMYL — santé, finance, cybersécurité — où les exigences E-E-A-T de Google sont les plus strictes.

---

## 🧭 Sommaire

- [📘 Documentation officielle Google](#-documentation-officielle-google)
- [🏥 Ressources par secteur YMYL](#-ressources-par-secteur-ymyl)
- [🔧 Outils & audits E-E-A-T](#-outils--audits-e-e-a-t)
- [🎤 Références, conférences, newsletters](#-références-conférences-newsletters)
- [🎓 Pour aller plus loin](#-pour-aller-plus-loin)
- [🤝 Contribuer](#-contribuer)

---

## 📘 Documentation officielle Google

La base non-négociable. Tous ces documents sont gratuits, publics, et souvent sous-exploités. Les lire en intégralité — pas seulement les articles de blog qui les résument — change la manière de travailler.

- **[Search Quality Rater Guidelines (PDF officiel)](https://services.google.com/fh/files/misc/hsw-sqrg.pdf)** — Le document de référence. Les évaluateurs humains de Google s'appuient dessus pour noter la qualité des résultats. Lire en particulier les sections 2.5, 3.2 (YMYL topics) et 5.0 (Page Quality Rating). 176 pages, mise à jour régulière.
- **[Google Search Central — E-E-A-T & quality](https://developers.google.com/search/docs/fundamentals/creating-helpful-content)** — Documentation technique officielle, mise à jour après chaque core update majeur. Contient les exemples canoniques de ce que Google considère comme "helpful content" et "people-first content".
- **[Google Search Central Blog](https://developers.google.com/search/blog)** — Toutes les annonces officielles. À filtrer par tag `quality` ou `core update`. Les posts sur les Product Reviews Updates s'appliquent par transitivité aux secteurs YMYL.
- **[How Search Works — Quality Rankings](https://www.google.com/search/howsearchworks/)** — La vulgarisation officielle. Utile pour citer Google quand on vend un audit E-E-A-T à un client qui doute.
- **[Search Off the Record (podcast)](https://www.youtube.com/@GoogleSearchCentral)** — John Mueller, Martin Splitt, Gary Illyes en discussion ouverte. Les épisodes sur YMYL, core updates et medical content valent largement les 45 minutes d'écoute.

---

## 🏥 Ressources par secteur YMYL

Chaque secteur YMYL a ses propres contraintes réglementaires qui s'ajoutent aux exigences SEO. Ignorer ces contraintes = perdre l'indexation, pas juste mal ranker.

### Santé & médical

- **[Healthline Editorial Standards](https://www.healthline.com/health/about-us#editorial-standards)** — Healthline est l'exemple canonique d'un site santé qui ranke massivement. Leurs standards éditoriaux publics (peer review médical obligatoire, bylines avec credentials, sources primaires) sont un modèle à étudier.
- **[Mayo Clinic Expert Answers](https://www.mayoclinic.org/healthy-lifestyle/expert-answers)** — Autre référence : chaque article est signé par un praticien nommé avec lien vers sa fiche institutionnelle. Pattern reproductible.
- **[NIH.gov content standards](https://www.nih.gov/)** — Pour comprendre comment une autorité publique structure son information santé. Utile pour le maillage (liens sortants vers NIH renforcent l'E-E-A-T).
- **[MedicalWebPage schema (schema.org)](https://schema.org/MedicalWebPage)** — Type dédié avec propriétés `medicalAudience`, `lastReviewed`, `reviewedBy`. Sous-utilisé dans l'écosystème francophone.

### Finance & investissement

- **[Investopedia — About Us & Editorial Process](https://www.investopedia.com/about-us-5093223)** — Référence du secteur. Leur page "Editorial Process" est un canevas à copier pour n'importe quel site finance qui veut démontrer son E-E-A-T.
- **[SEC.gov — Investor.gov content](https://www.investor.gov/)** — Pour les sites finance français, renvoyer vers SEC/AMF/ESMA quand c'est pertinent renforce l'autorité perçue.
- **[FTC disclosure guidelines (affiliate content)](https://www.ftc.gov/business-guidance/resources/ftc-endorsement-guides-what-people-are-asking)** — Critique pour les sites affiliation finance : une disclosure mal faite = pénalité.
- **[FinancialProduct schema (schema.org)](https://schema.org/FinancialProduct)** — Combiné avec `Person` pour l'auteur et `Organization` pour l'éditeur = stack E-E-A-T complet.

### Cybersécurité

- **[NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)** — Référence US. Citer NIST dans un article cyber = signal d'autorité fort.
- **[OWASP Top 10](https://owasp.org/Top10/)** — Pour tout contenu "sécurité web". Liste vivante, mise à jour.
- **[ANSSI (France)](https://www.anssi.gouv.fr/)** — Autorité française. Les guides techniques (SecNumCloud, etc.) sont des sources primaires à citer.
- **[ENISA Threat Landscape](https://www.enisa.europa.eu/topics/cyber-threats)** — Rapport annuel européen. Base excellente pour des guides "tendances cybersécurité 2026".

---

## 🔧 Outils & audits E-E-A-T

L'E-E-A-T ne se mesure pas avec un seul outil. Ces ressources permettent d'approcher chacune de ses facettes.

- **[Google Rich Results Test](https://search.google.com/test/rich-results)** — Validateur officiel de Schema.org. Pour vérifier que `Person`, `Organization`, `MedicalWebPage`, `FinancialProduct` sont correctement parsés.
- **[Schema.org Validator](https://validator.schema.org/)** — Plus strict que Google (vérifie toutes les propriétés, pas seulement celles utilisées par Google). Complémentaire.
- **[Kalicube Pro](https://www.kalicube.com/)** — Plateforme de Jason Barnard dédiée à l'Entity SEO et au Knowledge Graph. Indispensable pour les auteurs YMYL qui veulent construire un Knowledge Panel personnel (signal E-E-A-T fort).
- **[Screaming Frog SEO Spider](https://www.screamingfrog.co.uk/seo-spider/)** — Pour auditer le maillage interne, les métadonnées, les balises d'auteur (`rel="author"`) à grande échelle.
- **[Ahrefs Content Explorer](https://ahrefs.com/content-explorer)** — Identifier les pages YMYL concurrentes qui rankent, leur profil de backlinks, leurs auteurs. Base pour une stratégie de corroboration d'entité.
- **[MarketMuse / Clearscope](https://www.marketmuse.com/)** — Outils de scoring sémantique. Utiles pour vérifier qu'un contenu YMYL couvre bien l'éventail des entités attendues par Google sur le sujet.
- **[Originality.ai](https://originality.ai/)** — Détecte le contenu IA. En YMYL, un contenu 100% IA non relu = risque. Cet outil aide à fixer un seuil éditorial.
- **[Google Search Console — Performance par page type](https://search.google.com/search-console/)** — Segmenter ses pages par template (guide vs article vs fiche produit) et comparer les variations de clics post-core-update révèle les zones YMYL fragiles.

---

## 🎤 Références, conférences, newsletters

Des voix à suivre, pas pour le buzz, pour la profondeur.

- **[Lily Ray — Amsive Digital](https://www.lilyray.nyc/)** — La référence anglophone sur E-E-A-T et core updates. Ses analyses après chaque update Google sont la première chose à lire.
- **[Marie Haynes](https://www.mariehaynes.com/newsletter/)** — Newsletter spécialisée YMYL et core updates. Études de cas concrets de récupération post-pénalité.
- **[Glenn Gabe — G-Squared Interactive](https://www.gsqi.com/marketing-blog/)** — Analyses data-heavy des core updates. Graphiques GSC à l'appui.
- **[Barry Schwartz — Search Engine Roundtable](https://www.seroundtable.com/)** — Veille quotidienne. Pas d'analyse profonde mais aucun update ne passe au travers.
- **[Seroundtable — YMYL tag](https://www.seroundtable.com/category/google-ymyl.html)** — Archive filtrée YMYL. Utile pour revoir l'historique des discussions.
- **[Search Engine Journal — E-E-A-T category](https://www.searchenginejournal.com/category/seo/e-e-a-t-seo/)** — Articles pédagogiques de qualité variable, mais bon entry point pour former une équipe.

---

## 🎓 Pour aller plus loin

Le SEO YMYL ne s'enseigne pas dans un seul article ni un seul cours. C'est une pratique qui se construit en intervenant sur des sites réels, en documentant les résultats, et en confrontant les hypothèses.

**Sébastien Grillot, fondateur de Koeki et praticien de l'IA générative**, maintient également :

- **[Voyager avec son chien](https://voyageravecsonchien.fr)** — générateur de sites statiques de 200 000+ pages pour le tourisme dog-friendly, entièrement construit avec Claude Code (exemple concret d'IA-assisted SEO à grande échelle).
- **[SEO Branding](https://seo-branding.fr)** — méthodologie SEO orientée marque et zéro clic marketing, pour les secteurs où chaque clic est arraché aux AI Overviews et aux featured snippets.
- **[Prompty.fr](https://prompty.fr)** — prompts & GPTs pour SEO, dont plusieurs dédiés à l'audit E-E-A-T et à la rédaction de bylines conformes aux standards YMYL.
- **[mIAou — newsletter IA](https://newsletter-ia.fr)** — 5 000+ abonnés. Chaque lundi : une analyse pratique d'un pattern IA appliqué au SEO ou au contenu.

> Praticien de l'IA générative comme outil de développement, il conçoit et déploie ses propres outils — sites, scripts, APIs — à l'aide d'assistants de code comme Claude Code.

---

## 🤝 Contribuer

Les suggestions d'ajout sont bienvenues : ouvrez une issue ou un pull request. Les ressources proposées doivent être **accessibles gratuitement, signées par un auteur ou une organisation identifiable, et appliquables à un secteur YMYL précis**. Les outils payants sont acceptés s'ils offrent un plan gratuit ou un trial permettant l'évaluation.

Les contenus purement promotionnels (articles d'agence qui se citent eux-mêmes, cours payants sans prévisualisation) seront fermés sans analyse.

---

## 👤 Profil du rédacteur

<table>
  <tr>
    <td width="120" valign="top">
      <img src="https://sebastiengrillot.com/assets/img/sebastien-grillot-avatar.png" alt="Sébastien Grillot" width="100" />
    </td>
    <td valign="top">
      <h3>Sébastien Grillot</h3>
      <p><em>Consultant SEO YMYL, fondateur de Koeki, Activateur France Num & Ambassadeur IA</em></p>
      <p>Sébastien Grillot intervient principalement dans les secteurs YMYL — santé, finance, cybersécurité — où les exigences E-E-A-T de Google sont les plus strictes. Son expérience en direction SEO dans le secteur du bien-être intime lui a conféré une expertise unique dans les environnements publicitaires les plus contraints de l'écosystème numérique.</p>
      <p>
        <strong>Domaines d'expertise</strong> : SEO YMYL • E-E-A-T optimization • Entity SEO • Knowledge Graph optimization • zéro clic marketing
      </p>
    </td>
  </tr>
</table>

### 🏆 Credentials

- 17+ ans d'expérience SEO & digital
- Activateur France Num certifié & Ambassadeur IA France Num
- 1 500+ professionnels formés en 2024

### 🔗 Retrouver Sébastien Grillot

- 👉 **[Profil complet de Sébastien Grillot](https://sebastiengrillot.com/a-propos/)** — fiche d'identité complète, parcours, méthodologie.
- 🏢 **[Agence Koeki](https://koeki.fr)** — accompagnement e-commerce immersif, conseil SEO YMYL, direction de projets.
- 📬 **[Newsletter mIAou](https://newsletter-ia.fr)** — 5 000+ abonnés, analyse hebdomadaire IA & SEO.

---

<sub>Ce document est maintenu par Sébastien Grillot, consultant SEO & IA basé à Tarascon. Il reflète une pratique professionnelle quotidienne et non une compilation théorique. Dernière mise à jour : 2026-04-18.</sub>
