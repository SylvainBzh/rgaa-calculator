# Calculateur RGAA

Le calculateur RGAA permet de calculer la conformité d'une page avec les règles RGAA 3.

Vous pouvez accéder au calculateur directement depuis cette page: [Calculateur RGAA.html](http://sylvainbzh.github.io/Calculateur%20RGAA.html)

Deux modes sont disponibles:
- Le mode "check-list" qui permet de marquer chaque règle comme valide ou invalide.
- Le mode "pourcentage" qui permet de saisir un pourcentage de conformité pour chaque règle.

# Nouveautés de la version 2
- 2 modes au choix "check-list" ou "pourcentage"
- Fonctionnalités d'import / export.
- Bouton enregistrer-sous.
- Message concernant le label e-accessible lorsque le score est suffisant.

# Fonctionnement
* Ouvrir la page avec Firefox (doit aussi fonctionner avec Chrome).
* Modifier le titre
* Choisir le niveau (A, AA, AAA)
* Choisir le mode "check-list" (mode par défaut), ou pourcentage disponible à partir du menu (en haut à gauche).
* Cliquer sur une règle pour changer son état ou son pourcentage de conformité. En mode pourcentage, il est également possible de cliquer dans la colonne score pour saisir une valeur pour chaque règle.
* Le score total s'affiche en bas de page.

A noter que le calculateur peut être utilisé à l'aide du clavier (touches classiques).

A tous moments:
 - Vous pouvez changer de mode (passer du mode pourcentage au mode check-list)
 - Enregistrer la page en cours de travail soit à partir du menu, soit depuis votre navigateur (fichier -> enregistrer) pour continuer plus tard.

Vous pouvez également saisir un commentaire libre dans le champ situé en bas de page.

Le bouton reset comme son nom l'indique permet de réinitialiser toutes les modifications apportées.

**Raccourcis:** si vous cliquez sur le titre "Calculateur RGAA" ou le titre d'un chapitre vous atterrissez directement au score. Si vous cliquez sur un chapitre dans la liste des scores, vous atterrissez directement sur les règles correspondantes.

# Import / export
La version 2 introduit des fonctionnalités d'import/export au format JSON (disponible à partir du menu principal).

# Label e-accessible
Lorsque le score est suffisant un message est indiqué à l'utilisateur que la page peut techniquement bénéficier du label e-accessible version x.

# Générer le calculateur

Si vous souhaitez générer la page Calculateur RGAA.html:
* cloner le dépot
* lancer la commande `npm install --dev`
* puis `grunt`

La liste des règles au format JSON est obtenue à l'aide de mon autre projet : [rgaa-scrapper](https://github.com/SylvainBzh/rgaa-scraper)
