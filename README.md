# Hópverkefni 1

## Upplýsingar um keyrslu

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
1.  npm install --save-dev stylelint
2.  npm install --save-dev stylelint-config-primer
3.  "extends": "stylelint-config-primer" 
4.  "scripts": {
  "browser-sync": "browser-sync start --server --files index.html styles.css",
  "sass": "node-sass styles.scss styles.css -w",
  "dev": "npm-run-all --parallel sass browser-sync",
  "lint": "stylelint styles.scss --syntax scss" 
},
5.  npm run lint -s
```

## Lýsing verkefnis
Verkefnið er skipt í 5 möppur og nokkrar skrár á GitHubinu. <br>
Þar er index.html file og styles.scss file.  <br>
Það eru 3 möppur sem við notuðum <br>
Í img möppunni eru allar myndir sem unnar voru í verkefninu. <br>
Í pages möppunni eru cart.html, products.html og staff.html. Allar þessar skrár hafa link í index.html. <br>
Í scss möppunni eru styles á cart.scss, products.scss og staff.scss, öll þessi scss eru importuð í styles.scss sem er á forsíðunni.
Eina css skráin sem er notuð er grid.css, hún er importuð inn í allar scss skrárnar.

## Þeir sem unnu að verkefni

* Andri Jónasson 
* Brynjar Jónasson 
* Þorgeir Sigurðarson
