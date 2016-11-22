# umons-latex-rapport-de-stage-template

Template LaTeX pour un rapport de stage pour les étudiants de la faculté des
sciences l'UMons.

Pour générer le PDF, utilisez
```
make
```

Le PDF généré est disponible dans le dossier `_build` sous le nom `rapport.pdf`.

Vous pouvez changer le dossier de sortie en changeant la variable `BUILD_DIRECTORY` dans le fichier de configuration du Makefile `Makefile.config`.

Si vous utilisez `bibtex` pour générer la bibliographie (ce qui est recommandé), ajoutez le fichier `bib` dans le dossier `src` et changez la variable `USE_BIB` dans le fichier de configuration du Makefile `Makefile.config` à `true`.


