***
### Note d'intention
Ces data-visualisations ont été conçues au cours du mois de janvier 2021 selon des questions/besoins que j'ai rencontrés dans mon quotidien. Le rendu de ce devoir prend donc la forme d'un journal/blog illustré, avec le parti-pris d'un storytelling personnel. En espérant que cela vous divertisse ! 

### Données et outils utilisés
Les jeux de données utilisés sont en langue française et dépeignent des situations centrées autour de la France/du monde francophone (média francophone, paysage, donnée SNCF). Les outils utilisés sont Openrefine pour le datawrangling et la vérification des données, Wikidata query service, Palladio, Opendatasoft et Flourish.
<br/><br/> Tous fichiers utilisés ou obtenus (données ou traitement) non référencés ou présent dans leur intégralité sur cette page figurent ici : 
[Fichiers manipulés/obtenus et historique des traitements OpenRefine](https://github.com/nolwennbdr/journal_datavisualisation/issues/2#issue-799173485)

***

### Sommaire
Thème 1 - "L'importance des rituels" : 
 <br/>
[La radio, la télévision et le genre : Taux d'expression homme-femme](#Theme1)
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1.1. [Visuel Opendatasoft : taux d'expression homme femme selon type de média](#visuel_1_1)
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1.2. [Visuel Opendatasoft : taux d'expression homme femme par chaine](#visuel_1_2)
<br/>
<br/>
Thème 2 - "S'entourer de belles choses" : 
 <br/>
[La peinture : représentation la seine et origine de leur auteur](#Theme2)
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.1. [Visuel Palladio : grille d'image, graphique, facettes](#visuel_2_1)
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.2. [Visuel Palladuo : coordonnéees géographiques des lieux de naissance et mort des peintres (jeu de données augmentés)](#visuel_2_2)
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.3. [Carrousel Flourish : peintures hivernales ](#visuel_2_3)
 <br/> 
 <br/>
Thème 3 - "Avoir des projets" : 
 <br/>
[Les voyages en train : évolution de la performance du réseau férré du XXe à aujourd'hui](#Theme3)
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; > [Visuel Flourish : bar chart race des lignes en fonction de leur temps de trajet ](#visuel_3_1)
 <br/>
 <br/>
Thème 4 - "Etre curieux" : 
 <br/>
[Les objets perdus : gares françaises et objets perdus et restitués](#Theme4)
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; > [Story Flourish : treemap sur les cas de 4 gares ](#visuel_4_1)

![separation](https://www.inharmonydentalcare.com/wp-content/uploads/2019/08/divider-line-png.png)
# Cher Journal : 
***

#### Note du lundi 1er février 2021.

*Le mois de janvier peut parfois être un peu difficile : c'est à la fois une nouvelle année qui s'annonce, avec tout ce que cela apporte d'espoir et de mélancolie, mais également le milieu de l'hiver, et bien souvent une période d'examen et de reprise pour tout le monde. D'autant plus qu'en ce moment, les loisirs sont restreint, et la chaleur humaine se cristallisée de plus en plus dans des écrans froid. Je voulais donc profiter de la fin de ce mois pour établir un premier bilan, et partager 4 choses que je juge importante, et qu'il faut travailler tout au long de l'année, surtout quand les temps sont diffuciles.*
 <br/>

## 1/ L'importance des rituels : se tenir informer. (13/01/2021) <a name="Theme1"></a>
***

> *La routine n'est pas toujours synonyme d'ennuie. Elle peut être bénéfique. Tous les matins, j'écoute la radio. Il arrive parfois que j'entende des femmes se faire couper la parole. Je me suis souvent demandé si je le remarquais plus que lorsque les hommes se faisaient couper, par pure identification envers mes consoeurs. Au-delà de cet aspect, j'ai voulu comparer le temps de parole entre homme et femme dans les média.*

C'est l'[INA](https://www.data.gouv.fr/fr/datasets/temps-de-parole-des-hommes-et-des-femmes-a-la-television-et-a-la-radio/#_) qui a créé les jeux de données à ce sujet. Mais c'est sur Opendatasoft que j'ai préféré prendre directement ![le jeu de données utilisé](
https://data.opendatasoft.com/explore/dataset/temps-de-parole-des-hommes-et-des-femmes-a-la-television-et-a-la-radio%40public/information/?disjunctive.hour&sort=-fexpr&dataChart=eyJxdWVyaWVzIjpbeyJjaGFydHMiOlt7InR5cGUiOiJjb2x1bW4iLCJmdW5jIjoiQVZHIiwieUF4aXMiOiJmZXhwciIsInNjaWVudGlmaWNEaXNwbGF5Ijp0cnVlLCJjb2xvciI6IiM5MzExN0UifSx7ImFsaWduTW9udGgiOnRydWUsInR5cGUiOiJjb2x1bW4iLCJmdW5jIjoiQVZHIiwieUF4aXMiOiJoZXhwciIsInNjaWVudGlmaWNEaXNwbGF5Ijp0cnVlLCJjb2xvciI6IiM0MUNGQzUifV0sInhBeGlzIjoiY2hhbm5lbF9uYW1lIiwibWF4cG9pbnRzIjpudWxsLCJzb3J0Ijoic2VyaWUxLTEiLCJ0aW1lc2NhbGUiOiIiLCJzZXJpZXNCcmVha2Rvd24iOiIiLCJjb25maWciOnsiZGF0YXNldCI6InRlbXBzLWRlLXBhcm9sZS1kZXMtaG9tbWVzLWV0LWRlcy1mZW1tZXMtYS1sYS10ZWxldmlzaW9uLWV0LWEtbGEtcmFkaW9AcHVibGljIiwib3B0aW9ucyI6eyJkaXNqdW5jdGl2ZS5ob3VyIjp0cnVlLCJzb3J0IjoiLWZleHByIn19LCJzZXJpZXNCcmVha2Rvd25UaW1lc2NhbGUiOiIiLCJzdGFja2VkIjoicGVyY2VudCJ9XSwidGltZXNjYWxlIjoiIiwiZGlzcGxheUxlZ2VuZCI6dHJ1ZSwiYWxpZ25Nb250aCI6dHJ1ZSwic2luZ2xlQXhpcyI6dHJ1ZX0%3D). En comparaison à ceux de l'INA, ce jeu de données avait déjà été retravaillé : il mentionnait pas le taux d'expression selon les heures en journées (jeux de données très denses, qui n'a pas été supporté par OpenRefine), il réunit à la fois les données télé et radio, et possède déjà deux colonnes qui font la moyenne de toutes les chaines radio et chaines télévisée. Cela m'a permis de gagner du temps, je n'ai pas eu à modifier le jeu d'origine.
Les données sont receuillies à l'aide du logiciel InaSpeechSegmenter que j'ai déjà eu l'occasion de tester à l'inatheque de la BNF l'année dernière. Si l'identification des voix sur les enfants ou les voix cartoonesques n'était pas idéale, l'utilisation du logiciel pour du contenu radio me semble tout a fait adéquat.


### #1-1 : Taux d'expression homme femme selon type de média <a name="visuel_1_1"></a>

Il y a 700 000 heures de programme de 1995 à 2018. On constate que les enregistrements concernant la télévision ne commence qu'en 2010, on a donc moins d'historique que pour la radio, ce qui nous donne un demi cercle sur ce radar chart.

<iframe src="https://data.opendatasoft.com/chart/embed/?dataChart=eyJxdWVyaWVzIjpbeyJjaGFydHMiOlt7InR5cGUiOiJzcGlkZXJ3ZWIiLCJmdW5jIjoiQVZHIiwieUF4aXMiOiJmZXhwciIsInNjaWVudGlmaWNEaXNwbGF5Ijp0cnVlLCJjb2xvciI6InJhbmdlLU9yUmQiLCJkaXNwbGF5VmFsdWVzIjpmYWxzZSwiZGlzcGxheVVuaXRzIjp0cnVlLCJ5TGFiZWxPdmVycmlkZSI6IkhvbW1lIn0seyJhbGlnbk1vbnRoIjp0cnVlLCJ0eXBlIjoic3BpZGVyd2ViIiwiZnVuYyI6IkFWRyIsInlBeGlzIjoiaGV4cHIiLCJzY2llbnRpZmljRGlzcGxheSI6dHJ1ZSwiY29sb3IiOiJyYW5nZS1jdXN0b20iLCJ5TGFiZWxPdmVycmlkZSI6IiIsImRpc3BsYXlVbml0cyI6ZmFsc2V9XSwieEF4aXMiOiJ5ZWFyIiwibWF4cG9pbnRzIjoyMDAsInNvcnQiOiIiLCJ0aW1lc2NhbGUiOiJ5ZWFyIiwic2VyaWVzQnJlYWtkb3duIjoibWVkaWFfdHlwZSIsImNvbmZpZyI6eyJkYXRhc2V0IjoidGVtcHMtZGUtcGFyb2xlLWRlcy1ob21tZXMtZXQtZGVzLWZlbW1lcy1hLWxhLXRlbGV2aXNpb24tZXQtYS1sYS1yYWRpb0BwdWJsaWMiLCJvcHRpb25zIjp7ImRpc2p1bmN0aXZlLmhvdXIiOnRydWUsInRpbWV6b25lIjoiRXVyb3BlL0JlcmxpbiJ9fX1dLCJ0aW1lc2NhbGUiOiJ5ZWFyIiwiZGlzcGxheUxlZ2VuZCI6dHJ1ZSwiYWxpZ25Nb250aCI6dHJ1ZSwic2luZ2xlQXhpcyI6dHJ1ZX0%3D&static=false&datasetcard=true" width="800" height="600" frameborder="0"></iframe>

Le taux d'expression féminin ou masculin sont les temps de parole à l'antenne. 
En bleu les données concernant les hommes, en orange les données des femmes. Bleu vif et orange vif pour les données télévisuelles, bleu sombre et orange pale pour les données radios.

Lorsque l'on fait le même diagramme pour toutes les chaines, les montés ou descentes du taux de parole des femmes sont sans doutes du à des changements de présentateur/présentatrice. Le temps de parlole des femmes augmente en moyenne depuis le début comme on le constate ci dessus. Le temmps de parole des hommes diminuent donc au même rythme.

### #1-2 : Taux d'expression homme femme par chaine <a name="visuel_1_2"></a>

**Ce graphique faisait parti de mon projet mais était déjà présent dans OpenDataSoft. Je ne l'ai pas réalisé !** Je l'ai trouvé très bien fait par rapport au taux d'expression homme femme : l'un se mesure par rapport à l'autre en pourcentage, la somme des deux donnes donc toujours 100. C'est donc très lisible et complète parfaitement bien le premier, apportant le gros du détail. La palme de la disparité dans les temps de parole revient à la chaine sport.

<iframe src="https://data.opendatasoft.com/chart/embed/?dataChart=eyJxdWVyaWVzIjpbeyJjaGFydHMiOlt7InR5cGUiOiJjb2x1bW4iLCJmdW5jIjoiQVZHIiwieUF4aXMiOiJmZXhwciIsInNjaWVudGlmaWNEaXNwbGF5Ijp0cnVlLCJjb2xvciI6IiM5MzExN0UifSx7ImFsaWduTW9udGgiOnRydWUsInR5cGUiOiJjb2x1bW4iLCJmdW5jIjoiQVZHIiwieUF4aXMiOiJoZXhwciIsInNjaWVudGlmaWNEaXNwbGF5Ijp0cnVlLCJjb2xvciI6IiM0MUNGQzUifV0sInhBeGlzIjoiY2hhbm5lbF9uYW1lIiwibWF4cG9pbnRzIjpudWxsLCJzb3J0Ijoic2VyaWUxLTEiLCJ0aW1lc2NhbGUiOiIiLCJzZXJpZXNCcmVha2Rvd24iOiIiLCJjb25maWciOnsiZGF0YXNldCI6InRlbXBzLWRlLXBhcm9sZS1kZXMtaG9tbWVzLWV0LWRlcy1mZW1tZXMtYS1sYS10ZWxldmlzaW9uLWV0LWEtbGEtcmFkaW9AcHVibGljIiwib3B0aW9ucyI6eyJkaXNqdW5jdGl2ZS5ob3VyIjp0cnVlLCJzb3J0IjoiLWZleHByIiwidGltZXpvbmUiOiJFdXJvcGUvQmVybGluIn19LCJzZXJpZXNCcmVha2Rvd25UaW1lc2NhbGUiOiIiLCJzdGFja2VkIjoicGVyY2VudCJ9XSwidGltZXNjYWxlIjoiIiwiZGlzcGxheUxlZ2VuZCI6dHJ1ZSwiYWxpZ25Nb250aCI6dHJ1ZSwic2luZ2xlQXhpcyI6dHJ1ZX0%3D&static=false&datasetcard=true" width="800" height="600" frameborder="0"></iframe>

On peut donc comprendre pourquoi certaines personnes s'indignent de ce genre de comportement :

<iframe width="560" height="315" src="https://www.youtube.com/embed/9soYj3O4Ud8" frameborder="100" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

+ Plus d'info FR à ce sujet : [Billet et vidéo France TV du 18/10/16 ](https://www.francetvinfo.fr/economie/emploi/carriere/vie-professionnelle/emploi-des-femmes/video-ces-hommes-qui-interrompent-les-femmes_1877937.html)
<br/>
<br/>
## 2/ S'entourer de belles choses (18/01/2021) <a name="Theme2"></a>
***

> *Ce matin je me suis réveillée une fois de plus face à un mur tout blanc. Je ne sais pas si c'est le manque de décoration, ou le manque de sortie, mais je rêvais de ballade de les quais de seine, de week-end à la campagne. Alors prisonnière de la journée de travail qui m'attendais, sans possibilité de sortir, j'ai fait une requête sparql sur Wikidata.*

J'ai créé un jeu de données sur les peintures ayant pour sujet la Seine. L'enjeu premier était de récupérer une certaine quantité d'images pour usage personnel. Je me suis ensuite posée la question de leur date de réalisation (mon idée première étant que ce serait des peinture de la période impressioniste pour la majorité) et de la nationnalité de leur auteurs (des auteurs étrangés se sont ils donnés à l'exercice de peindre la Seine ?)

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

J'ai obtenu 298 résultat.

### #2-1 : Dans Palladio : les peintures représentant la Seine <a name="visuel_2_1"></a>

J'ai importé ce jeux de données dans Palladio, directement via le sparql endpoint pour éviter tout problème d'encodage. L'étape une était de créer une grille d'image d'image un peu plus solide que celle proposé par wikidata service, avec affichage de certaine information. Une fois cela fait, j'ai exploré les données en quête de réponses à mes questions : milieu de la fin du XIXe, sans surprise, nous avons bien une majorité d'amateur du plein air.

![Graphique palladio](https://user-images.githubusercontent.com/77386089/106517153-654a1700-64d8-11eb-9ad4-16c17d16e4cc.PNG)

Grace au facettes, j'observe rapidement en quelle année ce sujet était le plus à la mode, et qui a été le plus productif sur le sujet, selon mes données récoltées.

![Facette palladio](https://user-images.githubusercontent.com/77386089/106517158-65e2ad80-64d8-11eb-9236-354a8aa6edc8.PNG)



### #2-2 Dans palladio : naissance et mort des peintres ayant peint la Seine <a name="visuel_2_2"></a>

Pour ce faire, j'ai augmenter ce jeux de données via Openrefine, en reconcialiant le nom des peintres avec les données wikidata et en ajoutant leur lieux de naissance et de mort. A partir des lieux réconcilier (la plupart sur "commune de france" "ville" "grande ville"), j'ai récupéré les coordonnées geographiques. Ainsi cette carte à été formée : 

![Carte palladio](https://user-images.githubusercontent.com/77386089/106517157-65e2ad80-64d8-11eb-8998-98b863f3b3e8.PNG)

J'ai utilisé deux calques
- Un qui relie les deux points lieu de naissance et lieu de mort, le tout en rouge
- Un qui colore en violet le lieu de la mort
- Les labels ont été associés aux nom de peintre, pour pouvoir identifer au passage de la souris à qui les points correspondent.

![Zoom Carte palladio](https://user-images.githubusercontent.com/77386089/106517156-65e2ad80-64d8-11eb-9eaa-2ea99684493e.PNG)

De nombreux artistes née ou mort a Paris, ainsi que sur les bords de Seine, certains venant de loin, qui a l'inverse de Gauguin on passé leur vieux jour non loin des rives. Certains artistes, née et mort hors de France, parfois loin comme en Amerique du Sud, on eu l'occasion de peindre la seine lors de leur formation auprès de grand maitre à Paris.

### #UPDATE #Visuel bonus : carrousel Flourish suite à intemperie  <a name="visuel_2_3"></a>

> *Il a neigé, et cela me rappelle que je trouve les peintures avec de la neige vraiment très belle. Cela m'a donné envie de créer ce visuel flourish pour une amie, qui je sais, à les mêmes gouts que moi.*

<iframe src='https://flo.uri.sh/visualisation/5118736/embed' title='Interactive or visual content' frameborder='0' scrolling='no' style='width:100%;height:600px;'></iframe><div style='width:100%!;margin-top:4px!important;text-align:right!important;'><a class='flourish-credit' href='https://public.flourish.studio/visualisation/5118736/?utm_source=embed&utm_campaign=visualisation/5118736' target='_top' style='text-decoration:none!important'><img alt='Made with Flourish' src='https://public.flourish.studio/resources/made_with_flourish.svg' style='width:105px!important;height:16px!important;border:none!important;margin:0!important;'> </a></div>

Même requête, depeint "hiver", "neige" :
```sparql
    wdt:P180 wd:Q7561, wd:Q1311;
```
J'ai retiré les lignes lorsque la donnée image n'était pas disponible : 

```json
[
  {
    "op": "core/row-removal",
    "engineConfig": {
      "facets": [
        {
          "type": "list",
          "name": "image",
          "expression": "value",
          "columnName": "image",
          "invert": false,
          "omitBlank": false,
          "omitError": false,
          "selection": [],
          "selectBlank": true,
          "selectError": false
        }
      ],
      "mode": "row-based"
    },
    "description": "Remove rows"
  }
]
```
<br/>
<br/>
## 3/ Avoir des projets (21/01/2021)<a name="Theme3"></a>
***

> *Ces peintures impressionnistes  m'ont rappelée quelques cours d'histoire de l'art. Comme un plein airiste du début du XXe siècle, moi aussi profiter du developpement des rails pour filer vers la Normandie.*

J'ai trouvé [ce jeu de données SNCF](https://ressources.data.sncf.com/explore/dataset/meilleurs-temps-des-parcours-des-trains/table/?disjunctive.relations&sort=annee) sur l'évolution des temps de parcours des trains. J'ai du totalement le remodeler sur OpenRefine pour l'exploiter dans Flourish, sous forme d'une course. Voici un extrait du jeu de donnée d'origine, un extrait du traitement OpenRefine, et le jeu après modification. Outre la transformation dans la forme, j'ai réduit le jeu de données a 10 lignes de train, partant toutes de paris, vers la côte Ouest de la France. 

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
Remise en ordre par date et transposition colonne en ligne sur un modèle clef-valeur. J'ai également corrigé des formats sur les nombres, et supprimer tous les enregistrements ne contenant pas Paris dans la ligne de train, par une facette par mot. Puis j'ai selectionner toutes les lignes que je voulais garder via une facette textuelle, et en inversant la selection, j'ai supprimé tout le reste.

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



### #Bar chart race Flourish : évolution des temps de trajet <a name="visuel_2_1"></a>

Il faut bien sure garder en tête que les distances entre Paris et ces différentes villes ne sont pas les mêmes.
On peut jouer la visualisation en mettant les temps en minutes en ordonnée.

<iframe src='https://flo.uri.sh/visualisation/5105944/embed' title='Interactive or visual content' frameborder='0' scrolling='no' style='width:100%;height:600px;'></iframe><div style='width:100%!;margin-top:4px!important;text-align:right!important;'><a class='flourish-credit' href='https://public.flourish.studio/visualisation/5105944/?utm_source=embed&utm_campaign=visualisation/5105944' target='_top' style='text-decoration:none!important'><img alt='Made with Flourish' src='https://public.flourish.studio/resources/made_with_flourish.svg' style='width:105px!important;height:16px!important;border:none!important;margin:0!important;'> </a></div>

Ces données sont récoltées par la Direction des Statistiques et de La Régulation des Informations Economiques de la SNCF. Je n'ai malheureusement pas trouvé d'informations plus spécifique sur ce jeux de données, notemment : 
- On constate que l'enregistrement des durées de trajet commence plus tard pour certaine ligne : soit ces lignes n'existaient pas encore, soit l'historique de la durée est introuvable ou non vérifiable
- Certaines données sont manquantes après début de l'existance de la la ligne : on imagine des périodes de travaux, ou bien des mises hors services (periode de la seconde guerre mondiale)
- Deux vagues d'enregistrement arrivent en 1953 et 1963 

<br/>
<br/>
## 4/ Etre curieux, s'autoriser à la rêverie <a name="Theme4"></a>
***

> En parcourant les données ouvertes de la SNCF, j'ai trouvé leur données sur les objets perdues en gare. Ca m'a fait sourire, et ça a piqué ma curiosité. Je ne compte plus les fois ou j'ai perdu mon passe navigaux, ou trouvé des documents administratifs oublié sur le banc d'un quaie. (il se trouve que je dois avoir une sorte de chance, car ce ne sont pas les plus courant !)

A paris on perd plus son porte feuille qu'a toulouze, ou on a surtout perdu des sacs a dos.

### #Story Flourish : ce que l'on perd dans les gares <a name="visuel_4_1"></a>

Ce [jeu de données](https://ressources.data.sncf.com/explore/dataset/objets-trouves-restitution/information/?sort=date) étant très massif, OpenRefine n'a pas voulu de lui. LibreOffice a également beaucoup mouliné, c'est donc via Excel que j'ai du le couper et filtré sur certaines gares. 

J'ai selectionné au moins 10 000 enregistrement pour chaque gare : la gare Saint Lazare, Marseilles Saint Charles, Lille Flandre et Europe, et Toulouse Matabiau. Je voulais voir si des disparités existaient entre objet perdu selon ces villes. J'aurais également aimé voir si certain objet était plus perdu selon certaine période de l'année, mais l'extraction aurait été trop importante. En résultat cette story flourish. Chaque treemap est navigable dans le détail.

<iframe src='https://flo.uri.sh/story/742905/embed' title='Interactive or visual content' frameborder='0' scrolling='no' style='width:100%;height:600px;'></iframe><div style='width:100%!;margin-top:4px!important;text-align:right!important;'><a class='flourish-credit' href='https://public.flourish.studio/story/742905/?utm_source=embed&utm_campaign=story/742905' target='_top' style='text-decoration:none!important'><img alt='Made with Flourish' src='https://public.flourish.studio/resources/made_with_flourish.svg' style='width:105px!important;height:16px!important;border:none!important;margin:0!important;'> </a></div>


#### C'est ici que le voyage prend fin

Et nous avons vécu quelques embuches, comme le temps d'actualisation de cette page GitHub, plus proche d'une nuit que de 15 minutes !


