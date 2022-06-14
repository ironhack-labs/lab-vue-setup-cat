![logo_ironhack_blau 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# LAB | Configuració de Vue.js

## Introducció

En aquest laboratori, començareu a explorar com funciona Vue.js i com crear un projecte amb aquest marc de desenvolupament web.

Els vostres objectius per a aquest laboratori seran els següents:

- Instal·lació de la CLI de Vue.js al vostre ordinador
- Creació d'un nou projecte Vue amb un conjunt específic de configuracions
- Crear un nou component Vue dins del projecte i mostrar-lo a la pantalla d'inici
- Mostrant dades del vostre JavaScript dins del vostre HTML
- (Bo) Creació d'una funció "Hola món" que s'activa quan premeu un botó
- (Bonus) Crear dues rutes diferents i navegar entre elles

Seguirem la guia oficial de Vue.js durant la major part d'aquest laboratori.

## Configuració

- Bifurca aquest repo
- Clona aquest repo
- Obriu el LAB i comenceu:

  ```bash
   $ cd lab-vue-setup-cat
   $ yarn install
   $ yarn dev
  ```

## Submissió

- En finalitzar, executeu les ordres següents:

  ```bash
  $ git add .
  $ git commit -m "done"
  $ git push origin main # or master if you are working from a master
  ```

- Creeu una sol·licitud d'extracció perquè els vostres TA puguin comprovar el vostre treball.

## Començant

<!-- Installing the CLI -->

1. El primer pas abans de crear el vostre primer projecte Vue serà **instal·lar la CLI** . Només heu de fer aquest pas una vegada a l'ordinador.

Podeu trobar les instruccions [en aquest enllaç](https://cli.vuejs.org/guide/installation.html) . Recordeu afegir l'ordre `-g` per instal·lar Vue al vostre ordinador en lloc de només dins d'una carpeta específica.

Si esteu treballant al Mac, recordeu que haureu d'afegir la paraula clau "sudo" abans de l'ordre perquè funcioni.

<!-- ## Create a new Vue project -->

2. A continuació, procedirà a crear un nou projecte. Crear un projecte nou a Vue és tan senzill com inserir una ordre a la vostra consola un cop hàgiu instal·lat la CLI globalment. Podeu veure els passos exactes a seguir [en aquest enllaç](https://cli.vuejs.org/guide/installation.html) .

Un cop hàgiu creat un projecte nou, podreu triar quines funcions voleu. En aquest cas, volem que escolliu algunes funcions manualment:

- Babel
- Encaminador
- Linter / Formatador

També volem que creeu un projecte Vue 2 en lloc d'un de Vue 3. Si tens qualsevol dubte, la documentació és el teu millor amic!

## Instruccions

### Iteració 1 | Creeu un nou component Vue dins del vostre projecte i mostreu-lo a la pantalla d'inici

Ja has creat el teu primer projecte? Genial! Ara començareu a navegar per l'estructura del projecte.

Per facilitar-vos la vida, us recomanem que instal·leu l'extensió [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur) . Us ajudarà a crear nous components i afegir funcionalitats d'una manera més fàcil.

Un cop hàgiu creat el vostre nou projecte i hàgiu navegat per la carpeta que ha creat la CLI, ara podeu crear el vostre primer component Vue!

Aquí teniu una guia útil per si us trobeu encallat: [Com crear un component Vue](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Client-side_JavaScript_frameworks/Vue_first_component) .

Consell professional: si utilitzeu l'extensió Vetur, només heu d'escriure "vue" dins del vostre fitxer .vue i triar la plantilla adequada per obtenir una estructura bàsica.

Un cop hàgiu creat el vostre nou component, volem mostrar-lo dins del fitxer App.vue. Ja hem vist a classe com fer-ho, però [aquí teniu una guia pas a pas](https://flaviocopes.com/vue-import-component/) que us ajudarà amb aquesta tasca.

### Iteració 2 | Mostrant dades del vostre JavaScript dins del vostre HTML

Ara que teniu el vostre nou component, practicarem com enllaçar els elements dins del `<script>` amb la nostra `<template>`.

Per a això, haureu d'entendre la `Text Interpolation` . Si necessiteu una actualització al respecte, [aquí teniu l'enllaç a la documentació oficial](https://vuejs.org/guide/essentials/template-syntax.html#text-interpolation) .

### Iteració 3 | Bonificació | Creeu una funció "Hola món" que s'activa quan feu clic a un botó

Aquest repte és una mica més avançat; però us mostrarà com de fàcil és crear i activar funcions (o mètodes, com s'anomenen a Vue) quan treballeu amb un mètode JavaScript.

Aquí teniu el que heu de fer:

- Creeu un mètode nou anomenat `helloWorld()` que mostri la frase "hola món" a la consola.
- Creeu un botó nou dins del vostre component i mostreu-lo a la pàgina d'inici.
- Truqueu al mètode `helloWorld()` quan feu clic al botó que acabeu de crear.

Si necessiteu ajuda, [aquí teniu l'enllaç a la documentació oficial](https://vuejs.org/guide/essentials/event-handling.html#inline-handlers) .

### Iteració 4 | Bonificació | Creant dues rutes diferents i navegant entre elles

Aprofundirem molt més en el mòdul Vue Router en futures lliçons; però si voleu un nou repte, aquí teniu la vostra última tasca per a aquest laboratori:

- Si no l'heu inclòs durant la configuració inicial, descarregueu i configureu el mòdul Router. [Aquí teniu un enllaç a la guia oficial](https://github.com/vuejs/router) .

Recordeu que només l'haureu de tornar a instal·lar si no heu decidit incloure-lo al vostre projecte quan el vau crear amb la CLI.

- Creeu un component nou i registreu-lo com a ruta. Un cop més, [la documentació](https://router.vuejs.org/) és el teu millor amic aquí.

- Creeu una barra de navegació (pot ser tan senzill com dos enllaços a la secció superior del lloc web) que us permeti navegar entre els vostres components.

<br/>

Això és!

<br/>

Feliç codificació! :heart: