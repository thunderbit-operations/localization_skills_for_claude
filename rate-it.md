# Valutazione Qualità — Italiano

## Dimensioni di Valutazione (4 × 2.5 = 10 punti)

### D1: Naturalezza Linguistica (2.5 punti)

| Punteggio | Criterio |
|-----------|----------|
| 2.5 | Lettura completamente naturale, indistinguibile da contenuto scritto originalmente in italiano |
| 2.0 | Alcune frasi suonano leggermente tradotte, ma non compromettono la lettura |
| 1.5 | Strutture frasali visibilmente influenzate dall'inglese in più punti |
| 1.0 | Sembra traduzione automatica con editing superficiale |
| 0.5 | Traduzione letterale ovvia, lettura scomoda |

Verificare:
- Ordine delle parole naturale in italiano
- Uso corretto di preposizioni e congiunzioni
- Concordanza di genere e numero
- Uso naturale dei pronomi (evitare ripetizioni di soggetto come in inglese)
- Termini tech in inglese usati quando standard nel settore IT italiano

### D2: Adattamento Culturale (2.5 punti)

| Punteggio | Criterio |
|-----------|----------|
| 2.5 | Riferimenti, esempi e tono perfettamente adattati al pubblico italiano |
| 2.0 | La maggior parte dei riferimenti adattata, uno o due ancora americanizzati |
| 1.5 | Mix di riferimenti adattati e non adattati |
| 1.0 | Pochi adattamenti culturali, sembra ancora contenuto americano tradotto |
| 0.5 | Nessun adattamento culturale |

Verificare:
- Metafore e analogie rilevanti per il pubblico italiano
- Valuta in € quando applicabile
- Esempi di mercato/aziende italiane quando possibile
- Tono adeguato per professionisti italiani

### D3: Integrità Tecnica (2.5 punti)

| Punteggio | Criterio |
|-----------|----------|
| 2.5 | Tutti i componenti, link, immagini e formattazione perfettamente preservati |
| 2.0 | Un errore minore (spazio extra, formattazione inconsistente) |
| 1.5 | 2-3 errori tecnici minori |
| 1.0 | Componente rotto o link errato |
| 0.5 | Multipli componenti rotti |

Verificare:
- `<SideCard>`, `<TryButton>`, `<BottomCard>` intatti con title tradotto
- `<VideoPlayer>`, `<Table>` con content invariato
- URL delle immagini preservate
- Markdown valido (headers, liste, link, bold/italic)
- Link interni con prefisso `/it/`

### D4: Valore del Contenuto e SEO (2.5 punti)

| Punteggio | Criterio |
|-----------|----------|
| 2.5 | Contenuto aggiunge valore equivalente o superiore all'originale, keyword integrate naturalmente |
| 2.0 | Buon valore di contenuto, keyword presenti ma leggermente forzate |
| 1.5 | Contenuto adeguato ma con perdita parziale di sfumature o impatto |
| 1.0 | Informazione preservata ma senza engagement |
| 0.5 | Perdita significativa di valore informativo |

Verificare:
- Struttura H1 > H2 > H3 preservata
- Keyword adattate per termini di ricerca in italiano
- CTA efficaci e naturali
- Flusso logico mantenuto o migliorato

## Formato di Output del Report

```
## 📊 Report di Qualità — Italiano

| Dimensione | Punteggio | Dettagli |
|------------|-----------|----------|
| D1 Naturalezza | X.X/2.5 | ... |
| D2 Cultura | X.X/2.5 | ... |
| D3 Tecnica | X.X/2.5 | ... |
| D4 Contenuto/SEO | X.X/2.5 | ... |
| **Totale** | **X.X/10** | |

### Deduzioni dettagliate
- Riga XX: "testo problematico" → suggerimento (−0.X, DX)
...

### Riepilogo
[1-2 frasi sulla qualità generale e principali aree di miglioramento]
```
