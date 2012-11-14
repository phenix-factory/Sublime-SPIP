#INSTALLATION !



Ce plugin s’installe via [package control](http://wbond.net/sublime_packages/package_control).
La procédure d’installation de package control se trouve [ici](http://wbond.net/sublime_packages/package_control/installation).

Une fois l’installation terminée, ouvrer la console de Sublime text 2 ( *Tools => Command palette* ), et sélectionnez la commande **« Add repository »**.
Il suffit maintenant d’ajouter le dépôt GitHub, dans la console en bas qui vient de s’ouvrir.

	https://github.com/phenix-factory/Sublime-SPIP

Une fois cela fait, rouvrez la console Sublime Texte ( *Tools => Command palette* ) et cherchez **« Install package »**. Ensuite, cherchez Sublime-SPIP.

Enjoy !


##SUBLIME-SPIP 0.7

* Ajout des filtres SPIP
* Ajout de la fonction PHP get_session()
* Correction de <INCLURE>
* Correction de #NOTES
* Correction de #PS
* Correction de #SOUSTITRE et #SURTITRE
* Ajoute de #URL_PAGE
* Correction des bug des snippets LANG et formulaires

##SUBLIME-SPIP 0.6

* Ajout d'un scope pour n'afficher les balise SPIP que dans des fichier html
* Ajout de la balise #TEXTE
* Correction du snippet **spip_formCVT_php**
* Ajout de l'option redirect dans le snippet **spip_formCVT_php**

##SUBLIME-SPIP 0.5

* Ajout de sql_get_select
* Ajout de sql_fetsel
* Ajout de sql_getfetsel
* Ajout de sql_countsel
* Ajout d'un snipet "template" pour les fichiers de langue de spip: **SPIP_lang**
* Ajout de de snippet pour les formulaire CVT de spip: **spip_formCVT_html** et **spip_formCVT_php**

* Correction de sql_quote
* Correction des complétions pour les critières

##SUBLIME-SPIP 0.4

Ajout des fonction PHP

* debut_grand_cadre
* fin_grand_cadre
* recuperer_fond

* Correction du bug de debut_cadre_relief

##SUBLIME-SPIP 0.3

Correction de include_spip.
Correction de #PAGINATION

Ajout d'un snippet pour sql_fetch

Ajout de: 
* gros_titre
* debut_cadre_relief
* debut_cadre_relief
* generer_url_ecrire
* _request
* sql_select
* sql_update
* sql_updateq
* sql_quote
* \#URL_ECRIRE
* {transitteration}

##SUBLIME-SPIP 0.2

Debut du fichier pour l'auto-complétion PHP avec inclde_spip (Oui une seule fonction, j'ai la flemme)

* Ajout de la balise #COMPTEUR_BOUCLE
* Ajout des critères SPIP:
* {par }
* {inverse}
* {tout}

##SUBLIME-SPIP 0.1

* Ajoute les balises des squelettes SPIP à Sublime Text 2.
* Utiliser BOUCLE pour obtenir un squelette de boucle basique.