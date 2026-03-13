# AMR Zorgnetwerk Noord-Nederland (AMRZNN)

Het **Antibioticaresistentie Netwerk Noord-Nederland (AMRZNN)** is een samenwerkingsverband van zorginstellingen, laboratoria, GGD's en ziekenhuizen in Noord-Nederland. Samen werken we aan het in kaart brengen, monitoren en beheersen van antibioticaresistentie en bijzonder resistente micro-organismen (BRMO's) in de regio.

---

## 🦠 Wat doen wij?

Antibioticaresistentie is een van de grootste uitdagingen voor de volksgezondheid. AMRZNN brengt de verspreiding van resistente bacteriën zoals **ESBL**, **MRSA**, **VRE** en **CPE** in Noord-Nederland systematisch in kaart, zodat zorgverleners en beleidsmakers tijdig kunnen handelen.

Onze activiteiten omvatten:

- **Surveillance** – regionaal volgen van BRMO-meldingen en resistentiecijfers
- **Gegevensuitwisseling** – samenwerken met Certe, Izore en UMCG om laboratoriumdata te combineren
- **Rapportage** – periodieke rapportages en dashboards voor aangesloten instellingen
- **Kennisdeling** – richtlijnen, protocollen en scholing voor zorgprofessionals

---

## 📊 Dashboard

We ontwikkelen een interactief **R Shiny-dashboard** ([`AMRZNN/dashboard`](https://github.com/AMRZNN/dashboard)) waarmee zorgprofessionals in Noord-Nederland in één oogopslag inzicht krijgen in de actuele stand van antibioticaresistentie.

### Functionaliteiten

| Functie | Omschrijving |
|---|---|
| **KPI-tegels** | Actuele incidentiecijfers voor BRMO-meldingen, ESBL, MRSA en CPE met sparklines en trendpijlen |
| **Incidentiegrafiek** | Interactieve tijdreeks van BRMO-meldingen per 100.000 inwoners (2015–heden) |
| **Microbiologisch profiel** | Gestapeld staafdiagram met de verdeling naar BRMO-type per jaar |
| **Regionale kaart** | BRMO-incidentie per regio in Noord-Nederland *(in ontwikkeling)* |
| **Meerdere doelgroepen** | Tabbladen voor GGD, laboratoria, verpleeghuizen, huisartsen en ziekenhuizen |

Het dashboard is gebouwd met [R Shiny](https://shiny.posit.co/) en [Plotly](https://plotly.com/r/) en leest data rechtstreeks uit CSV-bestanden, waardoor het eenvoudig te koppelen is aan bestaande rapportageprocessen.

---

## 🗂️ Repositories

| Repository | Omschrijving |
|---|---|
| [`dashboard`](https://github.com/AMRZNN/dashboard) | R Shiny AMR-dashboard voor Noord-Nederland |
| [`dashboard_data`](https://github.com/AMRZNN/dashboard_data) | Publieke data die in het dashboard staan |

---

## 📬 Contact

Voor vragen of samenwerking kunt u contact opnemen via <https://www.amrznn.nl>.

---

*© AMR Zorgnetwerk Noord-Nederland*
