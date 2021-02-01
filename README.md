***
### Note d'intention au lecteur
Ces datavisualisations ont été conçues au cours du mois de janvier 2021 selon des questions/besoins que j'ai rencontrés dans mon quotidien. Le rendu de ce devoir prend donc la forme d'un journal/blog illustré, avec le parti pris d'un storytelling personnel. En espérant que cela vous diverstisse ! 

### Données et outils utilisés
Les jeux de données utilisés sont en langue française et dépeignent des situations centré autour de la france/du monde francophone (média francophone, paysage, donnée SNCF). Les outils utilisés sont Openrefine (pour remodelage et vérification des données), l'interface Wikidata query service, Palladio, Opendatasoft, et Flourish.

***

### Sommaire
Thème 1 : [La radio, la télévision et le genre : Taux d'expression homme-femme : radio et télévision](#Theme1)
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1.1. [Visuel Opendatasoft : Taux d'expression homme femme selon type de média](#visuel_1_1)
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1.2. [Visuel Opendatasoft : Taux d'expression homme femme par chaine](#visuel_1_2)
<br/>
<br/>
Thème 2 : [La peinture : représentation la seine et origine de leur auteur](#Theme2)
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.1. [Visuel : Palladio : grille d'image](#visuel_2_1)
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.2. [Visuel : Map des lieux de naissance et mort des peintres](#visuel_2_2)
 <br/> 
 <br/>
Thème 3 : [Les voyages en train : évolution de la performance du réseaux féré au du XXe a aujourd'hui](#Theme3)
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; > [Visuel Flourish : race sur Flourish ](#visuel_3_1)
 <br/>
 <br/>
Thème 4 : [Les objets perdus : gares françaises et objets perdus](#Theme4)
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; > [Visuel Flourish : story treemap sur Flourish ](#visuel_4_1)
<br/>
<br/>

![separation](https://www.inharmonydentalcare.com/wp-content/uploads/2019/08/divider-line-png.png)
# Cher Journal : 
***

#### Note du lundi 1er février 2021.

> *Le mois de janvier peut parfois être un peu difficile : c'est à la fois une nouvelle année qui s'annonce, avec tout ce que cela apporte d'espoir et de mélancolie, mais également le milieu de l'hiver, et bien souvent une période d'examen et de reprise pour tout le monde. D'autant plus qu'en ce moment, les loisirs sont restreint, et la chaleur humaine se cristallisée de plus en plus dans des écrans froid. Je voulais donc profiter de la fin de ce mois pour établir un premier bilan, et partager 4 choses que je juge importante, et qu'il faut travailler tout au long de l'année, surtout quand les temps sont diffuciles.*
<br/>
<br/>
## 1/ L'importance des rituels : se tenir informer. (13/01/2021) <a name="Theme1"></a>
***

> *La routine n'est pas toujours synonyme d'ennuie. Elle peut être bénéfique. Tous les matins, j'écoute la radio. Il arrive parfois que j'entende des femmes se faire couper la parole. Je me suis souvent demandé si je le remarquais plus que les hommes se faisant couper, par identification. Au delà de ce phénomène, j'ai voulu comparé le temps de parole entre homme et femme dans les média.*

L'INA fournit des jeux de données à ce sujet. Mais c'est sur Opendatasoft que j'ai préféré choisir le jeu de donnée. En effet en comparaison a ceux de l'INA, ce jeux de données ne mentionnait pas le taux d'expression selon les heures en journées (jeux de données très denses, qui n'a pas été supporté), réunit à la fois les données télé et radio, et possède déjà une colonne qui fait la moyenne de toutes les chaines radio et chaines télévisée. Cela m'a permi de gagner du temps, je n'ai pas eu a modifier le jeu d'origine.

### #1-1 : Taux d'expression homme femme selon type de média <a name="visuel_1_1"></a>

On constate que les données concernants la télévision étudiée plus récemment, on a donc moins d'historique que pour la radio.

<iframe src="https://data.opendatasoft.com/chart/embed/?dataChart=eyJxdWVyaWVzIjpbeyJjaGFydHMiOlt7InR5cGUiOiJzcGlkZXJ3ZWIiLCJmdW5jIjoiQVZHIiwieUF4aXMiOiJmZXhwciIsInNjaWVudGlmaWNEaXNwbGF5Ijp0cnVlLCJjb2xvciI6InJhbmdlLU9yUmQiLCJkaXNwbGF5VmFsdWVzIjpmYWxzZSwiZGlzcGxheVVuaXRzIjp0cnVlLCJ5TGFiZWxPdmVycmlkZSI6IkhvbW1lIn0seyJhbGlnbk1vbnRoIjp0cnVlLCJ0eXBlIjoic3BpZGVyd2ViIiwiZnVuYyI6IkFWRyIsInlBeGlzIjoiaGV4cHIiLCJzY2llbnRpZmljRGlzcGxheSI6dHJ1ZSwiY29sb3IiOiJyYW5nZS1jdXN0b20iLCJ5TGFiZWxPdmVycmlkZSI6IiIsImRpc3BsYXlVbml0cyI6ZmFsc2V9XSwieEF4aXMiOiJ5ZWFyIiwibWF4cG9pbnRzIjoyMDAsInNvcnQiOiIiLCJ0aW1lc2NhbGUiOiJ5ZWFyIiwic2VyaWVzQnJlYWtkb3duIjoibWVkaWFfdHlwZSIsImNvbmZpZyI6eyJkYXRhc2V0IjoidGVtcHMtZGUtcGFyb2xlLWRlcy1ob21tZXMtZXQtZGVzLWZlbW1lcy1hLWxhLXRlbGV2aXNpb24tZXQtYS1sYS1yYWRpb0BwdWJsaWMiLCJvcHRpb25zIjp7ImRpc2p1bmN0aXZlLmhvdXIiOnRydWUsInRpbWV6b25lIjoiRXVyb3BlL0JlcmxpbiJ9fX1dLCJ0aW1lc2NhbGUiOiJ5ZWFyIiwiZGlzcGxheUxlZ2VuZCI6dHJ1ZSwiYWxpZ25Nb250aCI6dHJ1ZSwic2luZ2xlQXhpcyI6dHJ1ZX0%3D&static=false&datasetcard=true" width="800" height="600" frameborder="0"></iframe>

### #1-2 : Taux d'expression homme femme par chaine <a name="visuel_1_2"></a>

Après l'aperçu global, j'ai voulu faire ressortir le détail par chaine. 
Le taux d'expression féminin ou masculin sont les temps de parole a l'entenne. L'un se mesure par rapport a l'autre en pourcentage, la somme des deux donnes donc toujours 100. La palme de la disparité dans les temps de parole revient à la chaine sport.
Sur certaine chaine, les montés ou descentes du taux de parole des femmes sont sans doutes du a des changements de présentateur/présentatrice. Le temps de parle des femmes augemente en moyenne depuis le début. Le temmps de parole des hommes diminuent donc au même rythme.

<iframe src="https://data.opendatasoft.com/chart/embed/?dataChart=eyJxdWVyaWVzIjpbeyJjaGFydHMiOlt7InR5cGUiOiJjb2x1bW4iLCJmdW5jIjoiQVZHIiwieUF4aXMiOiJmZXhwciIsInNjaWVudGlmaWNEaXNwbGF5Ijp0cnVlLCJjb2xvciI6IiM5MzExN0UifSx7ImFsaWduTW9udGgiOnRydWUsInR5cGUiOiJjb2x1bW4iLCJmdW5jIjoiQVZHIiwieUF4aXMiOiJoZXhwciIsInNjaWVudGlmaWNEaXNwbGF5Ijp0cnVlLCJjb2xvciI6IiM0MUNGQzUifV0sInhBeGlzIjoiY2hhbm5lbF9uYW1lIiwibWF4cG9pbnRzIjpudWxsLCJzb3J0Ijoic2VyaWUxLTEiLCJ0aW1lc2NhbGUiOiIiLCJzZXJpZXNCcmVha2Rvd24iOiIiLCJjb25maWciOnsiZGF0YXNldCI6InRlbXBzLWRlLXBhcm9sZS1kZXMtaG9tbWVzLWV0LWRlcy1mZW1tZXMtYS1sYS10ZWxldmlzaW9uLWV0LWEtbGEtcmFkaW9AcHVibGljIiwib3B0aW9ucyI6eyJkaXNqdW5jdGl2ZS5ob3VyIjp0cnVlLCJzb3J0IjoiLWZleHByIiwidGltZXpvbmUiOiJFdXJvcGUvQmVybGluIn19LCJzZXJpZXNCcmVha2Rvd25UaW1lc2NhbGUiOiIiLCJzdGFja2VkIjoicGVyY2VudCJ9XSwidGltZXNjYWxlIjoiIiwiZGlzcGxheUxlZ2VuZCI6dHJ1ZSwiYWxpZ25Nb250aCI6dHJ1ZSwic2luZ2xlQXhpcyI6dHJ1ZX0%3D&static=false&datasetcard=true" width="800" height="600" frameborder="0"></iframe>

On peut donc comprendre pourquoi certaines personnes s'indigne de ce genre de comportement :

<iframe width="560" height="315" src="https://www.youtube.com/embed/9soYj3O4Ud8" frameborder="100" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

+ Plus d'info FR à ce sujet : [Billet et vidéo France TV du 18/10/16 ](https://www.francetvinfo.fr/economie/emploi/carriere/vie-professionnelle/emploi-des-femmes/video-ces-hommes-qui-interrompent-les-femmes_1877937.html)
<br/>
<br/>
## 2/ S'entourer de belles choses (18/01/2021) <a name="Theme2"></a>
***

> *Ce matin je me suis reveillée une fois de plus face a un mur tout blanc. Je ne sais pas si c'est le manque de décoration, ou le manque de sortie, mais je revais de ballade de les quais de seine, de week end à la campagne. Alors prisonière de la journée de travail qui m'attendais, sans possibilité de sortir, j'ai fais une requête wikidata.*

J'ai crée un jeu de données sur les peintures ayant pour sujet la Seine. L'enjeu premier était de récupéré une certaine quantité d'images pour usage personnel. Je me suis ensuite posée la question de leur date de réalisation (mon idée étant, que ce serait des peinture de la période impressioniste pour la majorité) et de la nationnalité de leur auteurs (des auteurs étrangés se sont ils donnés a l'exercice de peindre la seine ?)

Voici la requête : 

```sparql
SELECT DISTINCT ?item ?Titre ?createur (YEAR(?date) AS ?AnneeCreation) ?image WHERE {
  ?item (wdt:P31/(wdt:P279*)) wd:Q3305213;
    wdt:P180 wd:Q1471;
    rdfs:label ?Titre.
  FILTER((LANG(?Titre)) = "fr")
  OPTIONAL {
    ?item wdt:P170 ?Qcreateur.
    ?Qcreateur rdfs:label ?createur.
    FILTER((LANG(?createur)) = "fr")
  }
  OPTIONAL { ?item wdt:P571 ?date. }
  OPTIONAL { ?item wdt:P18 ?image. }
}
```

### #2-1 : Dans Palladio : les peintures représentant la Seine <a name="visuel_2_1"></a>

J'ai importé ce jeux de données dans paladio, pour créer une grille d'image un peu plus solide que celle proposé par wikidata service, avec affichage de certaine information.

<iframe style="width: 80vw; height: 50vh; border: none;" src="https://query.wikidata.org/embed.html#SELECT%20DISTINCT%20%3Fitem%20%3FTitre%20%3Fcreateur%20(YEAR(%3Fdate)%20AS%20%3FAnneeCreation)%20%3Fimage%20%3Fcoord%20WHERE%20%7B%0A%20%20%3Fitem%20(wdt%3AP31%2F(wdt%3AP279*))%20wd%3AQ3305213%3B%0A%20%20%20%20wdt%3AP180%20wd%3AQ1471%3B%0A%20%20%20%20wdt%3AP180%20wd%3AQ1311%3B%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%0A%20%20%20%20rdfs%3Alabel%20%3FTitre.%0A%20%20FILTER((LANG(%3FTitre))%20%3D%20%22fr%22)%0A%20%20OPTIONAL%20%7B%0A%20%20%20%20%3Fitem%20wdt%3AP170%20%3FQcreateur.%0A%20%20%20%20%3FQcreateur%20rdfs%3Alabel%20%3Fcreateur.%0A%20%20%20%20FILTER((LANG(%3Fcreateur))%20%3D%20%22fr%22)%0A%20%20%7D%0A%20%20OPTIONAL%20%7B%20%3Fitem%20wdt%3AP571%20%3Fdate.%20%7D%0A%20%20OPTIONAL%20%7B%20%3Fitem%20wdt%3AP18%20%3Fimage.%20%7D%0A%20%20OPTIONAL%20%7B%20%3Fitem%20wdt%3AP625%20%3Fcoord.%20%7D%0A%7D" referrerpolicy="origin" sandbox="allow-scripts allow-same-origin allow-popups"></iframe>

![Graphique palladio](https://user-images.githubusercontent.com/77386089/106517153-654a1700-64d8-11eb-9ad4-16c17d16e4cc.PNG)

Grace au facettes, j'observe rapidement en quel année ce sujet était le plus à la mode, et qui a été le plus productif sur le sujet, selon les données récoltées.

![Facette palladio](https://user-images.githubusercontent.com/77386089/106517158-65e2ad80-64d8-11eb-9236-354a8aa6edc8.PNG)



### #2-2 Dans palladio : naissance et mort des peintres ayant peint la Seine <a name="visuel_2_2"></a>

Pour ce faire, j'ai augmenter ce jeux de données via openrfine, en reconcialiant le nom des peintres et en ajoutant leur lieux de naissance et de mort, ainsi que les coordonnées correspondante. A partir des lieux réconcilier (la plupart sur "commune de france" "ville" "grande ville"), j'ai récupéré les coordonnées geographiques. Ainsi cette carte a été formée : 

![Carte palladio](https://user-images.githubusercontent.com/77386089/106517157-65e2ad80-64d8-11eb-8998-98b863f3b3e8.PNG)

J'ai utilisé deux calques
- Un qui relie les deux points lieu de naissance et lieu de mort en rouge
- Un qui colore en violet le lieu de la mort
- Les labels ont été associés aux nom de peintre, pour pouvoir identifer au passage de la souris a qui ils correspondent.

![Zoom Carte palladio](https://user-images.githubusercontent.com/77386089/106517156-65e2ad80-64d8-11eb-9eaa-2ea99684493e.PNG)

### #UPDATE #Visuel bonus : Map <a name="visuel_2_2"></a>

> *Il a neigé, et cela me rappelle que je trouve les peintures avec de la neige vraiment très belle. Cela m'a donné envie de créer ce visuel flourish pour une amie, qui je sais, à les mêmes gouts que moi.*

<iframe src='https://flo.uri.sh/visualisation/5118736/embed' title='Interactive or visual content' frameborder='0' scrolling='no' style='width:100%;height:600px;'></iframe><div style='width:100%!;margin-top:4px!important;text-align:right!important;'><a class='flourish-credit' href='https://public.flourish.studio/visualisation/5118736/?utm_source=embed&utm_campaign=visualisation/5118736' target='_top' style='text-decoration:none!important'><img alt='Made with Flourish' src='https://public.flourish.studio/resources/made_with_flourish.svg' style='width:105px!important;height:16px!important;border:none!important;margin:0!important;'> </a></div>

Même requête, depeint "hiver", "neige" :
```sparql
    wdt:P180 wd:Q7561, wd:Q1311;
```
<br/>
<br/>
## 3/ Avoir des projets (21/01/2021)<a name="Theme3"></a>
***

> *Ces peintures impressionistes m'ont rappelée quelques cours d'histoire de l'art. Comme un plein airiste du XXe siècle, mois aussi je veux filé vers la normandie pour voir un peu de verdure.*

J'ai trouvé ce jeu de données SNCF. J'ai du totalement le remodeler sur openrefine pour l'exploité dans Flourish, sous forme d'une course. Voici un extrait du jeu de donnée d'origine, le traitement openrefine, et un extrait du jeu après modification. Outre la transformation dans la forme, j'ai réduit le jeu de données a 10 lignes de train, partant toutes de paris, vers la cote ouest de la France. 

**Jeu de donnée brut, avant : (extrait)**

| Relations        | Année | Temps estimé en minutes |
|------------------|-------|-------------------------|
| BORDEAUX - LILLE | 1951  |                         |
| BORDEAUX - LILLE | 1962  |                         |
| BORDEAUX - LILLE | 1979  |                         |
| BORDEAUX - LILLE | 1994  |                         |
| BORDEAUX - LILLE | 1998  | 301.0                   |
| BORDEAUX - LILLE | 2001  | 298.0                   |
| BORDEAUX - LILLE | 1978  |                         |
| BORDEAUX - LILLE | 1984  |                         |

**Traitement OpenRefine : (extrait)**
Remise en ordre par date et transposition colonne en ligne clef-valeur. J'ai également corrigé des formats sur les nombres, et supprimer tous les enregistrements ne contenant pas Paris dans la ligne de train, par une facette par mot. Puis j'ai selectionner toutes les lignes que je voulais gardé par une facette textuelle, et en inversant la selection, j'ai supprimé tout le reste.

```json
[
  {
    "op": "core/row-reorder",
    "mode": "row-based",
    "sorting": {
      "criteria": [
        {
          "valueType": "string",
          "column": "Relations",
          "blankPosition": 2,
          "errorPosition": 1,
          "reverse": false,
          "caseSensitive": false
        },
        {
          "valueType": "string",
          "column": "Année",
          "blankPosition": 2,
          "errorPosition": 1,
          "reverse": false,
          "caseSensitive": false
        }
      ]
    },
    "description": "Reorder rows"
  },
  {
    "op": "core/key-value-columnize",
    "keyColumnName": "Année",
    "valueColumnName": "Temps estimé en minutes",
    "noteColumnName": "",
    "description": "Columnize by key column Année and value column Temps estimé en minutes with note column "
  }
]
```

**Jeu de donnée après traitement : (total)**

| Relations           | 1920 | 1928 | 1929 | 1930 | 1931 | 1932 | 1933 | 1934 | 1935 | 1936 | 1937 | 1938 | 1939 | 1940 | 1941 | 1942 | 1943 | 1944 | 1945 | 1946 | 1947 | 1948 | 1949 | 1950 | 1951 | 1952 | 1953 | 1954 | 1955 | 1956 | 1957 | 1958 | 1959 | 1960 | 1961 | 1962 | 1963 | 1964 | 1965 | 1966 | 1967 | 1968 | 1969 | 1970 | 1971 | 1972 | 1973 | 1974 | 1975 | 1976 | 1977 | 1978 | 1979 | 1980 | 1981 | 1982 | 1983 | 1984 | 1985 | 1986 | 1987 | 1988 | 1989 | 1990 | 1991 | 1992 | 1993 | 1994 | 1995 | 1996 | 1997 | 1998 | 1999 | 2000 | 2001 | 2002 | 2003 | 2004 | 2005 | 2006 | 2007 | 2008 | 2009 | 2010 | 2011 | 2012 | 2013 | 2014 | 2015 | 2016 | 2017 |
|---------------------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|
| PARIS - BOULOGNE    |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      | 166  |      |      |      | 202  |      | 172  |      |      | 162  | 150  | 150  | 150  | 150  | 150  | 150  | 147  | 142  | 142  | 142  | 140  | 133  | 136  | 136  | 133  | 133  | 133  | 138  | 138  | 138  | 135  | 135  | 134  | 135  | 140  | 144  | 144  | 150  | 143  | 149  | 118  | 119  | 119  | 119  | 117  | 117  | 116  | 116  | 118  | 121  | 119  | 121  | 119  | 119  | 119  | 119  | 119  | 120  | 127  | 127  | 127  | 127  | 130  | 128  |
| PARIS - BREST       |      | 489  | 479  | 479  | 469  | 469  | 469  | 470  | 468  | 443  |      |      |      |      |      |      |      |      |      |      |      | 524  | 489  | 473  | 465  | 465  | 471  | 453  | 451  | 450  |      | 457  |      | 459  |      |      | 447  | 447  | 446  | 355  | 355  | 346  | 340  | 336  | 327  | 327  | 327  | 325  | 325  | 330  | 330  | 330  | 328  | 330  | 334  | 339  | 339  | 340  | 339  | 337  | 333  | 333  | 242  | 239  | 238  | 239  | 236  | 236  | 236  | 235  | 241  | 240  | 254  | 241  | 255  | 247  | 243  | 243  | 243  | 243  | 252  | 252  | 262  | 256  | 249  | 249  | 251  | 251  | 247  | 247  | 205  |
| PARIS - CAEN        |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      | 142  |      |      |      | 144  |      | 144  |      |      | 144  | 148  | 148  | 142  | 142  | 138  | 138  | 120  | 109  | 108  | 108  | 108  | 108  | 108  | 109  | 118  | 115  | 110  | 110  | 112  | 113  | 113  | 112  | 112  | 112  | 112  | 124  | 125  | 125  | 126  | 126  | 127  | 128  | 104  | 104  | 105  | 104  | 106  | 112  | 104  | 104  | 104  | 105  | 105  | 104  | 107  | 107  | 107  | 107  | 114  | 108  | 108  | 109  | 110  | 110  |
| PARIS - CHERBOURG   |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      | 303  |      |      |      | 281  |      | 280  |      |      | 236  | 239  | 238  | 231  | 229  | 229  | 229  | 238  | 176  | 177  | 176  | 176  | 176  | 176  | 179  | 186  | 184  | 183  | 183  | 183  | 185  | 185  | 185  | 188  | 184  | 186  | 197  | 207  | 208  | 208  | 205  | 206  | 192  | 162  | 162  | 162  | 163  | 168  | 178  | 165  | 165  | 165  | 165  | 164  | 164  | 166  | 166  | 166  | 165  | 176  | 169  | 169  | 181  | 181  | 182  |
| PARIS - LA ROCHELLE |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      | 286  |      |      |      | 274  |      | 274  |      |      | 268  | 268  | 268  | 267  | 275  | 279  | 279  | 279  | 249  | 249  | 238  | 225  | 223  | 235  | 231  | 231  | 230  | 230  | 239  | 237  | 239  | 238  | 238  | 227  | 228  | 229  | 237  | 201  | 210  | 212  | 171  | 178  | 170  | 176  | 175  | 179  | 171  | 170  | 168  | 169  | 170  | 168  | 169  | 169  | 169  | 169  | 169  | 169  | 171  | 194  | 194  | 185  | 190  | 188  | 163  |
| PARIS - LE HAVRE    | 202  | 160  | 160  | 160  | 144  | 144  | 144  | 120  | 118  | 118  |      | 119  |      |      |      |      |      |      |      |      |      | 148  | 130  | 128  | 127  | 142  | 144  | 144  | 141  | 134  | 142  | 142  | 138  | 139  | 142  | 144  | 142  | 147  | 146  | 141  | 140  | 115  | 107  | 107  | 107  | 105  | 105  | 105  | 105  | 105  | 110  | 110  | 111  | 110  | 111  | 110  | 110  | 114  | 115  | 114  | 114  | 115  | 119  | 117  | 119  | 120  | 121  | 114  | 115  | 112  | 112  | 111  | 114  | 114  | 115  | 110  | 110  | 114  | 114  | 118  | 115  | 115  | 115  | 115  | 115  | 115  | 115  | 115  | 125  | 124  | 124  |
| PARIS - NANTES      | 433  | 312  | 308  | 316  | 307  | 291  | 280  | 275  | 270  | 270  |      | 286  |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      | 250  | 240  | 244  | 243  | 250  | 233  | 238  | 238  | 239  | 239  | 239  | 239  | 224  | 219  | 218  | 216  | 198  | 198  | 198  | 187  | 185  | 185  | 185  | 185  | 186  | 187  | 194  | 196  | 197  | 197  | 183  | 173  | 173  | 175  | 175  | 119  | 119  | 118  | 119  | 120  | 120  | 122  | 121  | 121  | 123  | 119  | 119  | 119  | 119  | 119  | 119  | 119  | 119  | 119  | 119  | 119  | 120  | 123  | 124  | 124  | 125  | 123  | 123  | 116  |
| PARIS - QUIMPER     |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      | 476  |      |      |      | 490  |      | 490  |      |      | 480  | 476  | 475  | 428  | 427  | 353  | 356  | 356  | 336  | 335  | 335  | 335  | 328  | 333  | 333  | 333  | 333  | 338  | 336  | 337  | 338  | 338  | 338  | 337  | 337  | 339  | 274  | 277  | 265  | 252  | 251  | 252  | 254  | 254  | 254  | 257  | 258  | 250  | 255  | 253  | 253  | 251  | 251  | 251  | 251  | 251  | 251  | 251  | 254  | 260  | 263  | 263  | 252  | 252  | 212  |
| PARIS - RENNES      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      | 238  |      | 237  | 237  | 245  | 235  | 235  | 211  | 218  | 206  | 206  | 206  | 181  | 181  | 181  | 180  | 180  | 175  | 175  | 177  | 177  | 177  | 178  | 178  | 178  | 177  | 175  | 175  | 176  | 176  | 176  | 177  | 177  | 174  | 173  | 124  | 124  | 122  | 126  | 123  | 123  | 123  | 122  | 123  | 125  | 129  | 123  | 123  | 123  | 123  | 123  | 123  | 123  | 123  | 123  | 123  | 123  | 127  | 126  | 126  | 124  | 124  | 124  | 85   |
| PARIS - ROUEN       |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      | 83   |      |      |      | 79   |      | 79   |      |      | 82   | 86   | 85   | 81   | 71   | 71   | 67   | 65   | 65   | 63   | 63   | 63   | 63   | 63   | 67   | 67   | 70   | 68   | 68   | 68   | 68   | 68   | 69   | 69   | 70   | 69   | 67   | 66   | 67   | 66   | 72   | 70   | 72   | 69   | 69   | 68   | 65   | 65   | 66   | 65   | 66   | 66   | 65   | 68   | 66   | 68   | 68   | 70   | 71   | 68   | 69   | 69   | 68   | 68   | 68   |


Il faut bien sure garder en tête que les distances entre Paris et ces différentes villes ne sont pas les mêmes.
On peut jouer la visualisation en mettant les temps en minutes en ordonnée.
On constate que l'enregistrement des durées de trajet commence plus tard pour certaine ligne : après recherche cela correspond (ou non) a la creation des lignes.
Certaines données sont manquantes dans les années 39-45


### #Bar chart race Flourish : évolution des temps de trajet <a name="visuel_2_1"></a>

<iframe src='https://flo.uri.sh/visualisation/5105944/embed' title='Interactive or visual content' frameborder='0' scrolling='no' style='width:100%;height:600px;'></iframe><div style='width:100%!;margin-top:4px!important;text-align:right!important;'><a class='flourish-credit' href='https://public.flourish.studio/visualisation/5105944/?utm_source=embed&utm_campaign=visualisation/5105944' target='_top' style='text-decoration:none!important'><img alt='Made with Flourish' src='https://public.flourish.studio/resources/made_with_flourish.svg' style='width:105px!important;height:16px!important;border:none!important;margin:0!important;'> </a></div>
<br/>
<br/>
## 4/ Etre curieux, s'autoriser à la rêverie <a name="Theme4"></a>
***

> En parcourant les données ouvertes de la SNCF, j'ai trouvé leur données sur les objets perdues en gare. Ca m'a fait sourire, et ça a piqué ma curiosité. Je ne compte plus les fois ou j'ai perdu mon passe navigaux, ou trouvé des documents administratifs oublié sur le banc d'un quaie. (il se trouve que je dois avoir une sorte de chance, car ce ne sont pas les plus courant !)

A paris on perd plus son porte feuille qu'a toulouze, ou on a surtout perdu des sacs a dos.

### #Story Flourish : ce que l'on perd dans les gares <a name="visuel_4_1"></a>

<iframe src='https://flo.uri.sh/story/742905/embed' title='Interactive or visual content' frameborder='0' scrolling='no' style='width:100%;height:600px;'></iframe><div style='width:100%!;margin-top:4px!important;text-align:right!important;'><a class='flourish-credit' href='https://public.flourish.studio/story/742905/?utm_source=embed&utm_campaign=story/742905' target='_top' style='text-decoration:none!important'><img alt='Made with Flourish' src='https://public.flourish.studio/resources/made_with_flourish.svg' style='width:105px!important;height:16px!important;border:none!important;margin:0!important;'> </a></div>

C'est aussi bien pouvoir voyager depuis la maison.



