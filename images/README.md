# KEMIVAL - Screenshot Richiesti

Questa cartella contiene gli screenshot dell'applicazione KEMIVAL visualizzati nella landing page.

## 📸 Screenshot da Caricare

### 1. `screenshot-interface.png`
**Descrizione**: Screenshot dell'interfaccia principale di KEMIVAL

**Cosa mostrare**:
- Interfaccia principale con menu e pulsanti
- Parser SDS da PDF attivo
- Tabella con risultati KEMIVAL
- Classificazione del giudizio visibile
- Pulsanti "Esporta Excel", "Esporta Word"

**Dimensioni consigliate**: 1920x1080 o 1600x900 (16:9)

**Fonte**: Seconda immagine fornita (interfaccia con dark theme)

---

### 2. `screenshot-report.png`
**Descrizione**: Screenshot del report Word esportato

**Cosa mostrare**:
- Scheda riepilogo della valutazione
- Tabella completa con tutti i parametri:
  - File SDS, Nome commerciale, Stato fisico
  - Codici H, SCORE
  - Indici D, Q, U, C, T, I
  - Distanza operatore-sorgente
  - Valori E_inal, E_cut, R_inal, R_cut, R_tot
  - Giudizio SALUTE e SICUREZZA
  - Rischio complessivo
- Evidenziazione del risultato finale (es. "RISCHIO COMPLESSIVO: 8.62")
- Intestazione "SCHEDA RIEPILOGO DELLA VALUTAZIONE SOSTANZA/MISCELA/PREPARATO"

**Dimensioni consigliate**: 1200x800 o 1600x900

**Fonte**: Prima immagine fornita (report tabulare)

---

## 🔧 Come Caricare gli Screenshot

### Opzione 1: Manuale (GitHub Web)

1. Vai su: https://github.com/Giuseppe575/kemival/tree/main/images
2. Clicca "Add file" → "Upload files"
3. Trascina i due screenshot:
   - `screenshot-interface.png`
   - `screenshot-report.png`
4. Commit: "feat: Aggiunta screenshot applicazione"

### Opzione 2: Git Locale

```bash
cd C:\Users\atisgkemival-siteimages

# Copia i tuoi screenshot qui con questi nomi:
# - screenshot-interface.png
# - screenshot-report.png

cd ..
git add images/screenshot-interface.png images/screenshot-report.png
git commit -m "feat: Aggiunta screenshot applicazione"
git push origin main
```

---

## ✅ Verifica

Dopo il caricamento, verifica che le immagini siano visibili su:
https://giuseppe575.github.io/kemival/#caratteristiche

Gli screenshot appariranno nella sezione "L'applicazione in azione" con:
- 🖥️ Interfaccia Principale (screenshot-interface.png)
- 📊 Report Dettagliato (screenshot-report.png)

---

## 📐 Requisiti Tecnici

- **Formato**: PNG (preferito) o JPG
- **Dimensione file**: Max 2 MB ciascuno
- **Risoluzione**: Minimo 1280x720
- **Qualità**: Alta (per screenshot chiari e leggibili)

---

**Ultimo aggiornamento**: 30 Novembre 2025
