# Guardaroba Case

PWA personale collegata a Supabase.

## Pubblicazione con GitHub Pages
1. Crea un repository GitHub.
2. Carica tutti i file di questa cartella nella radice del repository.
3. In GitHub: Settings → Pages.
4. Source: Deploy from a branch.
5. Branch: `main`, cartella `/ (root)`.
6. Salva e apri l'URL generato da GitHub Pages.

## Login
La prima volta premi “Crea account”. Supabase può richiedere la conferma dell'email.
Dopo la conferma, accedi con email e password.

## Sicurezza
Nel frontend è presente solo la chiave Supabase *publishable*, progettata per essere pubblica.
Le tabelle e le foto sono protette da Row Level Security (RLS) sul database.

## Aggiornamento quantità
Ogni capo ha ora un campo Quantità (minimo 1). L'import Excel accetta anche la colonna `Quantità` o `Quantita`.

## Versione 1.4
- Pulsanti separati per scattare una foto o sceglierla dalla libreria.
- Eliminazione casa consentita solo quando la casa è vuota.

## Versione 1.5
- Vista per categorie dentro ogni casa.
- Cartelle categoria con conteggio quantità.
- Possibilità di tornare a Tutti i capi in qualsiasi momento.

## Versione 1.6
- Correzione eliminazione case con storico trasferimenti.
- Toolbar mobile più compatta.
- 3 capi per riga sui telefoni piccoli.
- Icone automatiche per categorie.
- Emoji o foto personalizzata per le case.
