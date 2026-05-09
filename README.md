# Simulatore Pensione Complementare

**Dynamic (Raiffeisen) vs ActivITAS (ITAS)** — Strumento didattico interattivo per il confronto tra fondi pensione.

---

## 🎯 Cosa fa

Questo simulatore consente di confrontare due linee di fondi pensione — **Dynamic di Raiffeisen** e **ActivITAS di ITAS** — proiettando:

- **Accumulo** della posizione individuale nel tempo
- **Prestazioni al pensionamento** (capitale e rendita) con tassazione esplicita
- **Eredità** del capitale residuo, con diverse opzioni di rendita selezionabili:
  - Rendita vitalizia
  - Rendita certa 5, 10 o 15 anni
  - Rendita reversibile al 60%
- **RITA** (Rendita Integrativa Temporanea Anticipata) pre-pensionamento

---

## ⚙️ Parametri regolabili

| Parametro | Range |
|-----------|-------|
| Età attuale | 20–62 anni |
| Età pensionamento | 60–72 anni |
| TFR annuo | €500–€15.000 |
| Contributo volontario | €0–€10.000 |
| Montante pregresso | €0–€200.000 |
| Rendimento Dynamic | 1%–12% |
| Differenziale ActivITAS | −2% / +5% |
| Aliquota fiscale su capitale | 15%–43% |
| Rendimento post-pensionamento | 0%–6% |

---

## 🔢 Ipotesi di calcolo

- Rendimenti netti storici: **Dynamic +6,71%**, **ActivITAS +9,05%**, differenziale **+2,34%**
- Coefficiente di conversione in rendita: **5,75%**
- Caricamento sulla rendita: **−2,25%**
- Ripartizione: **60% capitale / 40% rendita** (salvo eccezione tutto-capitale sotto soglia INPS)
- Tassazione sul capitale: aliquota media simulabile (default **40%**)

---

## ⚠️ Avvertenze

> **Questo simulatore ha finalità esclusivamente didattiche.**
>
> Non costituisce consulenza finanziaria, previdenziale, fiscale o assicurativa.
> I rendimenti passati non sono garanzia di rendimenti futuri.
> Costi, fiscalità, coefficienti e regole successorie vanno verificati sulla documentazione ufficiale aggiornata di ciascun fondo.

---

## 🚀 Come usarlo

Il simulatore è pubblicato con GitHub Pages. Visita:

🔗 **https://MichelangeloGargiulo/pensione-complementare/**

*(sostituisci `tuo-username` con il tuo nome utente GitHub)*

In alternativa, puoi clonare la repository e aprire `index.html` localmente:

```bash
git clone https://github.com/tuo-username/pensione-complementare.git
cd pensione-complementare
open index.html
