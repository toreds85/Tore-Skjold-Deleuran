# Delegerede roller — Padel Performance

*Udkast, 5. sep 2026*

## 0. Kilden — og hvad jeg faktisk kan bekræfte om den

Dan Harrisons pointe fra opslaget: han udfylder rollerne (EA, video editor, social media manager, media buyer, tech officer, chief of staff) med AI-agenter — men det kan han **kun**, fordi han i tyve år har lært at beskrive en rolle så præcist, at den kan overdrages uden ham. "You can't hand a job to AI if you can't describe the job."

Jeg har undersøgt, hvad der offentligt er kendt om hans konkrete system (kaldet "Claude for Coaches") — hans faktiske SOP'er ligger bag login, så det her er research om *rammen*, ikke en kopi af hans interne materiale:

- **The Chat Closer** — en AI-konversationsramme, der overtager DM'en fra første besked: kvalificerer (høj-intent vs. spild af tid) og booker et kald direkte i kalenderen, uden at han selv er i samtalen.
- **AI Powered Delivery** — leverer hans egne rammer/IP til klienter automatisk, i stedet for at han manuelt sender det.
- **Micro Offer Builder** — lead magnets + AI-drevne annoncer, der fylder toppen af tragten.

Pointen for os er ikke at kopiere navnene, men mekanikken: **en rolle skal beskrives som en SOP med triggere, input, beslutningsregler og output** — ikke kun som formål og ansvar. Det er det, der gør den udførbar af en AI (eller en ny medarbejder, uden at du skal forklare det).

Jeg har også undersøgt, hvad der faktisk findes af værktøjer til at automatisere en Skool-baseret forretning som din, fordi det er der, det bliver konkret:

- **Skool selv** har ingen indbygget automatisering ud over det basale (medlem tilmelder sig, betaler).
- **Zapier's native Skool-integration er tynd** — kun medlems-events som trigger (ny tilmelding, opsigelse), ingen mulighed for at sende opslag eller DM-sekvenser derfra.
- **StickyHive** (fra ca. 29 USD/md) er tredjepartslaget, der reelt gør det, Harrison beskriver, muligt på Skool: DM-sekvenser med forgrening, churn-detektion (opdager medlemmer der er ved at falde fra og sender automatisk retention-beskeder), AI-moderation, indholds-planlægning og et lille CRM. Det er den mest realistiske vej til at automatisere store dele af Community Manager- og dele af Salg-rollen på Skool specifikt.
- Derudover har du allerede adgang til (i dette workspace): **Calendly** (booking), **MailerLite** (e-mail-sekvenser), **Fireflies** (optager/transskriberer samtaler), **Gamma** og **Canva** (indholdsproduktion), **Notion** (videnbase/SOP'er), **Gmail/Google Calendar**, **Stripe**. Det er byggeklodserne — ikke Skool-specifikke, men de dækker alt det, der foregår udenom Skool (salgsopfølgning, forløbslogistik, indhold, cases).

---

## 1. Sådan skrives en rolle, så den kan overdrages (til menneske eller AI)

For hver opgave i rollen, ikke kun rollen som helhed:

1. **Trigger** — hvad sætter opgaven i gang (en ny tilmelding, et modtaget DM, en session er afholdt, en betaling er 3 dage forsinket)
2. **Input** — hvilken information skal bruges (medlemsdata, samtalehistorik, transskription, produktinfo)
3. **Beslutningsregel** — hvad skal der ske i de forskellige scenarier, og hvornår skal det eskaleres til dig i stedet for at blive afgjort selv
4. **Output** — det konkrete resultat (en besked sendt, et opslag udgivet, en note i et system)
5. **Værktøj** — hvad opgaven rent faktisk udføres i (Skool, StickyHive, MailerLite, Calendly, Notion …)

De to prioriterede roller herunder (Community Manager og Salg/Onboarding) er brudt helt ned på dette niveau. De øvrige er skitseret på samme måde, men mindre udfoldet — de kræver mere af din faglighed og er derfor sværere at give fuldt væk endnu.

---

## 2. Padel Skool

### Rolle: Community Manager
**Formål:** Medlemmerne bliver, engagerer sig og oplever fremdrift — uden din daglige tilstedeværelse.

| Opgave | Trigger | Beslutningsregel | Output/værktøj |
|---|---|---|---|
| Velkomstsekvens til nye medlemmer | Nyt medlem tilmelder sig i Skool | Altid samme flow, personaliseret med navn/niveau fra tilmeldingsformular | 3-4 DM'er over første uge — **StickyHive** DM-sekvens |
| Churn-forebyggelse | Medlem holder op med at logge ind/deltage i X dage, eller signalerer opsigelse | Automatisk retention-besked først; hvis medlemmet svarer negativt/frustreret → eskaler til dig | **StickyHive** churn-trigger + DM |
| Moderation af opslag/kommentarer | Nyt opslag/kommentar postes | Spam/støj fjernes automatisk; alt fagligt/personligt sendes videre til dig eller Indholdsansvarlig | **StickyHive** AI-moderation |
| Ugentlig rytme (opslag, Q&A) | Fast ugentlig trigger (fx mandag kl. 8) | Skabelon findes for hver faste post-type; nyt fagligt indhold kræver din godkendelse først | Planlagt i **StickyHive**/Skool-kalender |
| Statusrapport til dig | Fast månedlig trigger | — | Aktivitetsniveau, churn-rate, svartid samlet i **Notion**-dashboard |

**Hvad kræver stadig dig:** Godkendelse af nyt fagligt indhold, håndtering af medlemmer der eskaleres, beslutninger om pris/produkt/struktur.

### Rolle: Salg/Onboarding
**Formål:** Kvalificerede spillere finder vej ind i Padel Skool og forstår, hvad de får — uden salgssamtaler.

| Opgave | Trigger | Beslutningsregel | Output/værktøj |
|---|---|---|---|
| Kvalificering af henvendelse | Nyt DM/lead via Skool eller landingsside | Skelner høj-intent (klar til at melde sig ind) fra "bare kigger" ud fra svar på 2-3 kvalificerende spørgsmål | AI-drevet DM-flow (StickyHive eller tilsvarende) |
| Nurture af ikke-klar-endnu leads | Lead svarer "ikke nu"/tøver | Automatisk sekvens med social proof/cases over 1-2 uger, herefter stop hvis ingen respons | **MailerLite**-sekvens |
| Direkte optag/betaling | Lead er kvalificeret og klar | Sender betalingslink, bekræfter medlemskab | **Stripe**-link + Skool-optag |
| Personlig samtale (kun ved behov) | Lead beder specifikt om at tale med dig, eller AI'en vurderer det som en high-value case | Booking uden om dig indtil kaldet skal afholdes | **Calendly** |
| Rapportering | Fast ugentlig trigger | — | Antal leads, konverteringsrate, kilder — **Notion**-dashboard |

**Hvad kræver stadig dig:** Særaftaler/rabatter, high-value samtaler AI'en selv eskalerer, den oprindelige kvalificeringslogik (skal skrives af dig, ikke gættes).

### Rolle: Indholdsansvarlig
**Formål:** Der er altid næste stykke indhold klar — uden at du selv producerer det i sidste øjeblik.

- **Opgave:** Omsætte rå kilder (dine sessions optaget via **Fireflies**, egne noter) til strukturerede lektioner.
- **Sådan i dag:** Foregår formentlig ad hoc, når du har tid.
- **Automatiseringsvej:** Fireflies-transskription → udkast til lektion/opslag skrevet i din tone → lægges i **Notion** som kladde → du godkender → publiceres via **Gamma/Canva** (visuelt materiale) og planlægges i **StickyHive**/Skool.
- **Hvad kræver stadig dig:** Fagligt indhold skal godkendes, før det udgives — det er ikke til forhandling givet din positionering (ingen udvanding af metoden).

---

## 3. The Performance Mind

Tættere på din kernefaglighed og samarbejdet med Andreas Johansson. Automatiseringen her handler om at fjerne logistik, ikke det faglige indhold.

### Rolle: Forløbsansvarlig / Program Manager
- **Opgaver:** Booking af sessions (**Calendly**), automatisk opfølgning mellem sessions (**MailerLite**/Gmail), overblik over hvor hver spiller er i forløbet (**Notion**-tracker).
- **Beslutningsregel:** Hvis en spiller ikke booker næste session inden for X dage → automatisk påmindelse, herefter eskalering til dig/Andreas.
- **Hvad kræver stadig dig:** Selve det faglige indhold i forløbet.

### Rolle: Case- og materialeansvarlig
- **Opgaver:** Hver session optages/transskriberes (**Fireflies**), og mønstre/cases udtrækkes til et voksende bibliotek i **Notion**.
- **Beslutningsregel:** Et udkast til case/ramme genereres automatisk efter hver session — men bruges først bredt, når du/Andreas har valideret det.
- **Hvad kræver stadig dig:** Validering — det mentale kan ikke forsimples til floskler, og det er her kvaliteten typisk går tabt, hvis AI'en får lov at generalisere selv.

---

## 4. Rækkefølge og hvad det kræver at komme i gang

1. **Community Manager** — kræver: StickyHive-opsætning (~5-15 min/uge vedligehold), skrevne skabeloner til velkomst/churn/moderation-regler. Det tungeste forarbejde er at skrive kvalificerings- og eskaleringsreglerne én gang.
2. **Salg/Onboarding** — kræver: samme DM-lag (StickyHive) + kvalificeringsspørgsmål defineret af dig + MailerLite-sekvens skrevet.
3. **Indholdsansvarlig** — kræver: at Fireflies bruges konsekvent til dine sessions, og en Notion-struktur til kladder/godkendelse.
4. **Forløbsansvarlig (Performance Mind)** — kræver: Calendly-opsætning pr. forløbstype, Notion-tracker pr. spiller.
5. **Case- og materialeansvarlig** — kræver: nok volumen af transskriberede sessions til at mønstrene giver mening at systematisere.

---

## 5. Hvor jeg kan gå videre nu

Jeg har allerede adgang til Zapier, MailerLite, Calendly, Fireflies, Gamma, Canva, Notion, Gmail, Google Calendar og Stripe i dette workspace. StickyHive er ikke en integration jeg har adgang til her — det kræver din egen konto og opsætning på stickyhive.ai.

Sig til, hvis du vil have mig til at:
- Sætte en konkret Notion-struktur op til rolle-SOP'er og case-bibliotek
- Skrive de faktiske kvalificerings- og eskaleringsregler til Salg/Onboarding (det kræver din faglige stemme, men jeg kan lave et udkast baseret på hvad Padel Skool faktisk sælger)
- Bygge en MailerLite-nurture-sekvens til leads, der ikke er klar endnu

---

## Kilder

- [Claude for Coaches — Skool](https://www.skool.com/claudeforcoaches/about)
- [Claude for Coaches: Full Review 2026 — Skoolmakers](https://skoolmakers.com/communities/claude-for-coaches/)
- [Dan Harrison – Claude for Coaches — Skillocourses](https://skillocourses.com/products/dan-harrison-claude-for-coaches)
- [StickyHive — Run Your Community Like a Business](https://stickyhive.ai/)
- [StickyHive Features: AI Moderation, Scheduling & Automation](https://stickyhive.ai/features/)
- [Best Skool Automation Tools 2026 — StickyHive](https://stickyhive.ai/skool/automation-tools/)
- [Skool Zapier Alternative: 28 Triggers & 60+ Actions vs Zapier's 4 — StickyHive](https://stickyhive.ai/skool/zapier-alternative/)
