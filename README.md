# A2 Deutsch-Trainer

A small practice app for A2 German: der/die/das, grammar, and word order.

**Live site:** https://simaykucukkolbasi.github.io/deutsch-trainer/

Everyone's progress is saved in their own browser.

## Adding a new week

Everything is in `index.html`. Open it on GitHub, click the pencil (Edit), and change the `DATA` section near the top of the `<script>`:

1. **New chapter:** add a line to `CHAPTERS`, e.g. `3:"Gesund leben"`. A chip for it shows up automatically, and it is switched on for returning learners too.
2. **Words:** add to `NOUNS` as `["die","Apotheke","die Apotheken","pharmacy",3],`
3. **Grammar:** add to `GRAM`, either multiple choice
   `{ch:3,topic:"Reflexiv",type:"mc",q:"Ich freue ___ .",opts:["mich","mir"],a:"mich",why:"sich freuen → Akkusativ."},`
   or typed
   `{ch:3,topic:"Reflexiv",type:"type",q:"Wir treffen ___ morgen. (sich)",a:"uns",why:"wir → uns."},`
4. **Word order:** add to `ORDER` as `{ch:3,de:"Ich gehe zum Arzt, weil ich krank bin.",en:"I'm going to the doctor because I'm ill."},`

Commit the change. The site updates in about a minute.
