# 📊 **Voluntary Disclosure & Personalized Pricing**
**Theoretische Analyse von Ali et al. (2022) – Market Design & Verhaltensökonomie**
*Theo Osterhaus | Universität zu Köln | WiSe 2025/26*

---

## 🎯 **Ziel der Arbeit**
Analyse des **bahnbrechenden Papers von Ali, Lewis & Vasserman (2022)** (*Review of Economic Studies*) mit Fokus auf:
- **Wie beeinflusst freiwillige Datenoffenlegung** die Preisgestaltung in digitalen Märkten?
- **Können Konsumenten von personalisierten Preisen profitieren**, wenn sie die Kontrolle über ihre Daten haben?
- **Welche Implikationen hat das für Unternehmen, Regulierer und die Gesellschaft?**

**🔗 [Vollständige Präsentation (PDF)](output/Information_and_Strategie.pdf)**

---

---

## 📚 **Zusammenfassung der Kern-Ergebnisse**
| **Frage** | **Antwort aus Ali et al. (2022)** | **Meine Analyse** | **Business-Relevanz** |
|-----------|------------------------------------|-------------------|-----------------------|
| **Können Konsumenten von personalisierten Preisen profitieren?** | ✅ **Ja!** Bei **Rich Evidence** (selektive Offenlegung) steigt die Konsumentenrente (CS) um bis zu **~20%**. | Bestätigt durch **PBE-Analyse** (Seite 12–14 der Präsentation). | **E-Commerce:** Amazon/Zalando könnten durch **Gruppendiscounts** (z. B. Studentenrabatt) CS erhöhen. |
| **Was passiert bei einfacher Offenlegung (Simple Evidence)?** | ❌ **CS sinkt!** Monopolist extrahiert gesamte Rente (Perfekte Preisdiskriminierung). | Mathematische Herleitung in **Anhang (Seite 26–28)**. | **Regulierung:** Datenschutzgesetze (z. B. GDPR) müssen **selektive Offenlegung** ermöglichen. |
| **Wie wirkt sich Offenlegung auf Bertrand-Wettbewerb aus?** | 🔄 **Strategische Offenlegung:** Konsumenten teilen Daten mit **Rivalen**, um Preiskämpfe auszulösen. | **Hotelling-Modell** (Seite 16–17, 30–32) zeigt: **Extreme Typen** offenbaren nur dem Konkurrenten. | **Tech-Firmen:** Google/Apple müssen **Datenportabilität** (z. B. via APIs) ermöglichen. |
| **Was sind die Wohlfahrtsgewinne?** | 📈 **Pareto-Verbesserung:** Sowohl Konsumenten als auch Unternehmen profitieren (kein Deadweight Loss). | Berechnung der **CS- und PR-Gewinne** (Seite 13). | **Policy:** Bundeskartellamt könnte **Offenlegungsstandards** einführen. |

---

---

## 🏢 **Real-World Anwendungen & Beispiele**
### 1️⃣ **Museum Ludwig (Köln) – Praktisches Beispiel für Rich Evidence**
- **Standardpreis:** 11,00 €
- **Ermäßigt (mit Nachweis):** 7,50 €
- **Mechanismus:** Konsumenten **beweisen** ihre Zugehörigkeit zu einer Gruppe (z. B. Studenten) und erhalten einen Rabatt.
- **Theoretische Grundlage:** **Zeno’s Partition** (Seite 14) – Konsumenten zwingen den Monopolisten zu **Gruppendiscounts**.

### 2️⃣ **Smartphone Switcher Paradox (Apple vs. Samsung)**
- **Setup:** Hotelling-Modell mit **Apple (a = -1000)** und **Samsung (s = 1000)**.
- **Konsumentenstrategie:**
  - **Extreme Typen** (l ∈ [500, 1000]) offenbaren **nur Samsung** ihre Position → **Preiskampf** mit Apple.
  - **Zentrale Typen** (l ≈ 0) offenbaren **beiden** Firmen ihre Position → **Uniform Pricing**.
- **Ergebnis:** **Preise sinken** durch strategische Offenlegung (Seite 17, 32).


### 3️⃣ **Equilibrium Prices & Consumer Surplus**
- **Monopol mit Rich Evidence:** Konsumenten erzwingen **gestufte Preise** (Seite 12).
- **Wohlfahrtsgewinne:**
  - **Konsumentenrente (CS):** +1,19 (normalisiert)
  - **Produzentenrente (PR):** +2,37 (normalisiert)
  - **Gesamtwohlfahrt:** **Pareto-optimal** (kein Deadweight Loss).

![Equilibrium Prices & CS](output/eqpricesandcs.png)
*Quelle: Ali et al. (2022), Abb. 3 – in der Präsentation auf Seite 12*

---

---

## 📊 **Mathematische Modelle & Herleitungen**
### 1️⃣ **Monopol mit Simple Evidence**
- **Benchmark:** Uniform Pricing (p* = 20, CS = 5).
- **Problem:** Bei **vollständiger Offenlegung** (m = v) extrahiert der Monopolist **alle Rente** (CS = 0).
- **Lösung:** Konsumenten **verweigern Offenlegung** → Monopolist setzt **p_ND = 10** (Default-Preis).
- **Ergebnis:** **CS ≤ Uniform Pricing** (Proposition 1, Seite 9).

**Formel (Discrete Example, Seite 26):**


### 2️⃣ **Monopol mit Rich Evidence (Zeno’s Partition)**
- **Mechanismus:** Konsumenten beweisen **Zugehörigkeit zu einer Gruppe** (z. B. v ∈ [a, b]), ohne **exakten Wert** preiszugeben.
- **Ergebnis:**
  - **Preisfunktion:** Gestufte Preise (Seite 12).
  - **CS steigt für fast alle Typen** (Seite 14).
  - **Pareto-Verbesserung:** Win-Win für Konsumenten und Unternehmen.

**Berechnung der Wohlfahrtsgewinne (Seite 13):**


---

---

## 💡 **Policy Implications & Business Cases**
### **Für Regulierer (Bundeskartellamt, EU, GDPR)**
| **Problem** | **Lösung aus dem Paper** | **Umsetzung** |
|-------------|--------------------------|---------------|
| **Perfekte Preisdiskriminierung** | **Rich Evidence** (selektive Offenlegung) ermöglicht CS-Gewinne. | **Datenschutzgesetze** müssen **selektive Offenlegung** (z. B. via APIs) erzwingen. |
| **Datenmonopole (Google, Meta)** | Konsumenten können **Daten an Rivalen** weitergeben, um Wettbewerb zu fördern. | **Datenportabilität** (Art. 20 GDPR) stärken. |
| **Forced Revelation** | Monopolisten können Konsumenten **zur Offenlegung zwingen** (sceptical beliefs). | **Transparenzpflichten** für Algorithmen einführen. |

### **Für Unternehmen (Amazon, Zalando, Apple, Samsung)**
| **Branche** | **Anwendung** | **Beispiel** |
|-------------|---------------|--------------|
| **E-Commerce** | **Gruppendiscounts** (z. B. Studentenrabatt) erhöhen CS und Umsatz. | **Amazon Prime:** Rabatte für nachgewiesene Gruppen (z. B. Senioren). |
| **Tech (FAANG)** | **Selektive Datenfreigabe** für personalisierte Werbung. | **Google Ads:** Nutzer entscheiden, welche Daten sie teilen. |
| **Telekommunikation** | **Preisdifferenzierung** basierend auf **freiwilliger Offenlegung**. | **Vodafone:** Günstigere Tarife für Nutzer, die ihre Nutzungsdaten teilen. |
| **Banken/FinTech** | **Kredit-Scoring** mit **selektiver Offenlegung**. | **N26:** Bessere Zinsen für Nutzer, die Einkommensdaten teilen. |
