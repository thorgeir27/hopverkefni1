# Hópverkefni 1

## Upplýsingar um keyrslu
Til þess að keyra vefsíðuna þarf

Til þess að sækja alla pakka

```bash
npm install
```

Til þess að keyra browser sync og sass saman

```bash
npm run dev
```

Til þess að keyra stylelint 

```bash
1. npm install --save-dev stylelint
2. "extends": "stylelint-config-primer" 
3. "scripts": {
  "browser-sync": "browser-sync start --server --files index.html styles.css",
  "sass": "node-sass styles.scss styles.css -w",
  "dev": "npm-run-all --parallel sass browser-sync",
  "lint": "stylelint styles.scss --syntax scss" 
},
4. npm run lint -s
```

## Lýsing verkefnis

Verkefnið er skipt í 5 möppur með efni sem við notuðum til þess að skapa síðuna. 
Í img möppunni eru allar myndir sem unnar voru í verkefninu. 
Í pages möppunni eru cart, products og staff sem eru allt tengdir linkar við index file á forsíðunni. 
Í SCSS möppunni eru styles á cart, product og staff. öll þessi SCSS eru importuð í styles.scss sem er á forsíðunni.
Eina css skráin sem er notuð er grid.css, hún er importuð inn í allar SCSS skrárnar. 

## Þeir sem unnu að verkefni

* Andri Jónasson 
* Brynjar Jónasson 
* Þorgeir Sigurðarson
