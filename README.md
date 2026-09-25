# 📊 Dashboard Interactiv - Analiză Vânzări & Încasări

O aplicație web modernă, rapidă și securizată pentru analiza financiară din fișiere Excel sau CSV. Proiectul rulează 100% în browser (*client-side*), fără a trimite datele către un server extern.

![Interfață Dashboard](Screenshot%202026-09-25%20interfata_dasb.png)
![Preview Dashboard](Screenshot%202026-09-25%20dashb_datefictive.png)


🚀 **[Accesează Dashboard-ul Live Aici](https://madalinacalota-ghub.github.io/analiza-incasari-dashboard/)**

---

## ✨ Caracteristici Principale

* 🔒 **Confidențialitate Maximă (100% Client-Side):** Fișierele încărcate sunt procesate local în browserul tău. Nicio informație confidențială nu părăsește calculatorul.
* 📁 **Suport Multi-Format:** Încarcă fișiere `.xlsx`, `.xls` sau `.csv` prin funcția Drag & Drop sau selectare directă.
* 🎯 **Filtrare Dinamică & Flexibilitate:**
  * Slicer dedicat după **Județ CP**.
  * Selector pentru dimensiunea graficelor (*Compartiment, Tip activitate, Natura, OGC*).
* 📈 **Vizualizări Financiare:**
  * Carduri KPI pentru **Total Încasat (fără TVA)** și **Clienți Unici**.
  * **Top 10 Performeri** (Grafic orizontal de bare).
  * **Distribuție Procentuală** Top 5 + Altele (Grafic Donut).
  * **Top 5 Clienți** după valoarea încasată.
* 📄 **Export Raport:** Funcție integrată pentru export PDF/Printare optimizată.

---

## 🛠️ Tehnologii Utilizate

* **HTML5 & Vanilla JavaScript (ES6+)**
* **Tailwind CSS** (via CDN) — Interfață modernă și responsive
* **Chart.js** — Grafice dinamice interactive
* **SheetJS (XLSX) & PapaParse** — Parcurgere fișiere structurate
* **FontAwesome** — Iconografie

---

## 🚀 Cum îl folosești local

1. Clonează depozitul:
```bash
git clone https://github.com/MadalinaCalota-ghub/analiza-incasari-dashboard.git 
