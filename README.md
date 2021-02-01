***
### Note d'intention au lecteur
Ces datavisualisations ont été conçues au cours du mois de janvier 2021 selon des questions/besoins que j'ai rencontré dans mon quotidien. Le rendu de ce devoir prend donc la forme d'un journal/blog illustré, avec le parti pris d'un storytelling personnel. En espérant que cela vous diverstisse ! 

### Données et outils utilisés
Les jeux de données utilisés sont en langue française et dépeignent des situations centré autour de la france/du monde francophone (média francophone, paysage, donnée SNCF). Les outils utilisés sont Openrefine (pour remodelage et vérification des données), l'interface Wikidata query service, Palladio, opendatasoft, et flourish.

***

### Sommaire
1. [Thème 1 : La radio, la télévision : Taux d'expression homme-femme : radio et télévision](#Theme1)
    1. [Visuel 1 : Taux d'expression homme femme selon type de média](#visuel_1_1)
    2. [Visuel 2 : Taux d'expression homme femme par chaine](#visuel_1_2)
2. [Thème 2 : la peinture : représentation la seine et origine de leur auteur](#Theme2)
    1. [Visuel 1 : Palladio : grille d'image](#visuel_2_1)
    2. [Visuel 2 : Map des lieux de naissance et mort des peintres](#visuel_2_2)
3. [Thème 3 : les voyages en train : évolution de la performance du réseaux féré au du XXe a aujourd'hui](#Theme3)
    1. [Visuel : race sur Flourish ](#visuel_3_1)
4. [Thème 4 : les objets perdus : gares françaises et objets perdus](#Theme4)
    1. [Visuel : story treemap sur Flourish ](#visuel_4_1)

***

# Cher Journal

##### Note du lundi 1er février 2021.

*Le mois de janvier peut parfois être un peu difficile : c'est à la fois une nouvelle année qui s'annonce, avec tout ce que cela apporte d'espoir et de mélancolie, mais également le milieu de l'hiver, et bien souvent une période d'examen et de reprise pour tout le monde. D'autant plus qu'en ce moment, les loisirs sont restreint, et la chaleur humaine se cristallisée de plus en plus dans des écrans froid. Je voulais donc profiter de la fin de ce mois pour établir un premier bilan, et partager 4 choses que je juge importante, et qu'il faut travailler tout au long de l'année, surtout quand les temps sont diffuciles.*

## 1/ L'importance des rituels, apprendre. (13/01/2021) <a name="Theme1"></a>



*La routine n'est pas toujours synonyme d'ennuie. Elle peut être bénéfique. Tous les matins, j'écoute la radio. Il arrive parfois que j'entende des femmes se faire couper la parole. Je me suis souvent demandé si je le remarquais plus que les hommes se faisant couper, par identification. Au delà de ce phénomène, j'ai voulu comparé le temps de parole entre homme et femme dans les média.*

L'INA fournit des jeux de données à ce sujet. Mais c'est sur Opendatasoft que j'ai préféré choisir le jeu de donnée. En effet en comparaison a ceux de l'INA, ce jeux de données ne mentionnait pas le taux d'expression selon les heures en journées (jeux de données très denses, qui n'a pas été supporté), réunit à la fois les données télé et radio, et possède déjà une colonne qui fait la moyenne de toutes les chaines radio et chaines télévisée. Cela m'a permi de gagner du temps, je n'ai pas eu a modifier le jeu d'origine.

On constate que les données concernants la télévision étudiée plus récemment, on a donc moins d'historique que pour la radio.
Le taux d'expression féminin ou masculin sont les temps de parole a l'entenne. L'un se mesure par rapport a l'autre en pourcentage, la somme des deux donnes donc toujours 100.
La palme de la disparité dans les temps de parole revient à la chaine sport.
Sur certaine chaine, les montés ou descentes du taux de parole des femmes sont sans doutes du a des changements de présentateur/présentatrice. Le temps de parle des femmes augemente en moyenne depuis le début. Le temmps de parole des hommes diminuent donc au même rythme.

### Visuel 1 : Taux d'expression homme femme selon type de média <a name="visuel_1_1"></a>

<iframe src="https://data.opendatasoft.com/chart/embed/?dataChart=eyJxdWVyaWVzIjpbeyJjaGFydHMiOlt7InR5cGUiOiJzcGlkZXJ3ZWIiLCJmdW5jIjoiQVZHIiwieUF4aXMiOiJmZXhwciIsInNjaWVudGlmaWNEaXNwbGF5Ijp0cnVlLCJjb2xvciI6InJhbmdlLU9yUmQiLCJkaXNwbGF5VmFsdWVzIjpmYWxzZSwiZGlzcGxheVVuaXRzIjp0cnVlLCJ5TGFiZWxPdmVycmlkZSI6IkhvbW1lIn0seyJhbGlnbk1vbnRoIjp0cnVlLCJ0eXBlIjoic3BpZGVyd2ViIiwiZnVuYyI6IkFWRyIsInlBeGlzIjoiaGV4cHIiLCJzY2llbnRpZmljRGlzcGxheSI6dHJ1ZSwiY29sb3IiOiJyYW5nZS1jdXN0b20iLCJ5TGFiZWxPdmVycmlkZSI6IiIsImRpc3BsYXlVbml0cyI6ZmFsc2V9XSwieEF4aXMiOiJ5ZWFyIiwibWF4cG9pbnRzIjoyMDAsInNvcnQiOiIiLCJ0aW1lc2NhbGUiOiJ5ZWFyIiwic2VyaWVzQnJlYWtkb3duIjoibWVkaWFfdHlwZSIsImNvbmZpZyI6eyJkYXRhc2V0IjoidGVtcHMtZGUtcGFyb2xlLWRlcy1ob21tZXMtZXQtZGVzLWZlbW1lcy1hLWxhLXRlbGV2aXNpb24tZXQtYS1sYS1yYWRpb0BwdWJsaWMiLCJvcHRpb25zIjp7ImRpc2p1bmN0aXZlLmhvdXIiOnRydWUsInRpbWV6b25lIjoiRXVyb3BlL0JlcmxpbiJ9fX1dLCJ0aW1lc2NhbGUiOiJ5ZWFyIiwiZGlzcGxheUxlZ2VuZCI6dHJ1ZSwiYWxpZ25Nb250aCI6dHJ1ZSwic2luZ2xlQXhpcyI6dHJ1ZX0%3D&static=false&datasetcard=true" width="800" height="600" frameborder="0"></iframe>

### Visuel 2 : Taux d'expression homme femme par chaine <a name="visuel_1_2"></a>

<iframe src="https://data.opendatasoft.com/chart/embed/?dataChart=eyJxdWVyaWVzIjpbeyJjaGFydHMiOlt7InR5cGUiOiJjb2x1bW4iLCJmdW5jIjoiQVZHIiwieUF4aXMiOiJmZXhwciIsInNjaWVudGlmaWNEaXNwbGF5Ijp0cnVlLCJjb2xvciI6IiM5MzExN0UifSx7ImFsaWduTW9udGgiOnRydWUsInR5cGUiOiJjb2x1bW4iLCJmdW5jIjoiQVZHIiwieUF4aXMiOiJoZXhwciIsInNjaWVudGlmaWNEaXNwbGF5Ijp0cnVlLCJjb2xvciI6IiM0MUNGQzUifV0sInhBeGlzIjoiY2hhbm5lbF9uYW1lIiwibWF4cG9pbnRzIjpudWxsLCJzb3J0Ijoic2VyaWUxLTEiLCJ0aW1lc2NhbGUiOiIiLCJzZXJpZXNCcmVha2Rvd24iOiIiLCJjb25maWciOnsiZGF0YXNldCI6InRlbXBzLWRlLXBhcm9sZS1kZXMtaG9tbWVzLWV0LWRlcy1mZW1tZXMtYS1sYS10ZWxldmlzaW9uLWV0LWEtbGEtcmFkaW9AcHVibGljIiwib3B0aW9ucyI6eyJkaXNqdW5jdGl2ZS5ob3VyIjp0cnVlLCJzb3J0IjoiLWZleHByIiwidGltZXpvbmUiOiJFdXJvcGUvQmVybGluIn19LCJzZXJpZXNCcmVha2Rvd25UaW1lc2NhbGUiOiIiLCJzdGFja2VkIjoicGVyY2VudCJ9XSwidGltZXNjYWxlIjoiIiwiZGlzcGxheUxlZ2VuZCI6dHJ1ZSwiYWxpZ25Nb250aCI6dHJ1ZSwic2luZ2xlQXhpcyI6dHJ1ZX0%3D&static=false&datasetcard=true" width="800" height="600" frameborder="0"></iframe>

On peut donc comprendre pourquoi certaines personnes s'indigne de ce genre de comportement :

<iframe width="560" height="315" src="https://www.youtube.com/embed/9soYj3O4Ud8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

https://www.francetvinfo.fr/economie/emploi/carriere/vie-professionnelle/emploi-des-femmes/video-ces-hommes-qui-interrompent-les-femmes_1877937.html


## 2/ S'entourer de belles choses (18/01/2021) <a name="Theme2"></a>

*Un matin je me suis reveillée une fois de plus face a un mur tout blanc. Je ne sais pas si c'est le manque de décoration, ou le manque de sortie, mais je revais de ballade de les quais de seine, de week end à la campagne. Alors prisonière de la journée de travail qui m'attendais, sans possibilité de sortir, j'ai fais une requête wikidata.*

J'ai crée un jeu de données sur les peintures ayant pour sujet la Seine. Je me suis posée la question de leur date de réalisation (mon idée étant, que ce serait des peinture de la période impressioniste pour la plus part) et de la nationnalité de leur auteurs (des auteurs étrangés se sont ils donnés a l'exercice ?)

```sparql
SELECT DISTINCT ?item ?Titre ?createur (YEAR(?date) AS ?AnneeCreation) ?image WHERE {
  ?item (wdt:P31/(wdt:P279*)) wd:Q3305213;
    wdt:P180 wd:Q1471;
    wdt:P180 wd:Q1311;                      
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


### Visuel 1 : Grille d'image <a name="visuel_2_1"></a>

J'ai importé ce jeux de données dans paladio, pour créer une grille d'image un peu plus solide que celle proposé par wikidata service, avec affichage de certaine information.

<iframe style="width: 80vw; height: 50vh; border: none;" src="https://query.wikidata.org/embed.html#SELECT%20DISTINCT%20%3Fitem%20%3FTitre%20%3Fcreateur%20(YEAR(%3Fdate)%20AS%20%3FAnneeCreation)%20%3Fimage%20%3Fcoord%20WHERE%20%7B%0A%20%20%3Fitem%20(wdt%3AP31%2F(wdt%3AP279*))%20wd%3AQ3305213%3B%0A%20%20%20%20wdt%3AP180%20wd%3AQ1471%3B%0A%20%20%20%20wdt%3AP180%20wd%3AQ1311%3B%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%0A%20%20%20%20rdfs%3Alabel%20%3FTitre.%0A%20%20FILTER((LANG(%3FTitre))%20%3D%20%22fr%22)%0A%20%20OPTIONAL%20%7B%0A%20%20%20%20%3Fitem%20wdt%3AP170%20%3FQcreateur.%0A%20%20%20%20%3FQcreateur%20rdfs%3Alabel%20%3Fcreateur.%0A%20%20%20%20FILTER((LANG(%3Fcreateur))%20%3D%20%22fr%22)%0A%20%20%7D%0A%20%20OPTIONAL%20%7B%20%3Fitem%20wdt%3AP571%20%3Fdate.%20%7D%0A%20%20OPTIONAL%20%7B%20%3Fitem%20wdt%3AP18%20%3Fimage.%20%7D%0A%20%20OPTIONAL%20%7B%20%3Fitem%20wdt%3AP625%20%3Fcoord.%20%7D%0A%7D" referrerpolicy="origin" sandbox="allow-scripts allow-same-origin allow-popups"></iframe>


### Visuel 2 : Map <a name="visuel_2_2"></a>

Pour ce faire, j'ai augmenter ce jeux de données via openrfine, en reconvialiant le nom des peintres et en ajoutant leur lieux de naissance et de mort, ainsi que les coordonnées correspondante. Ainsi cette carte a été formée : 

### Visuel bonus : Map <a name="visuel_2_2"></a>

Il a neigé et je trouve les peintures avec de la neige vraiment très belle. J'ai partagé ce visuel flourish avec une amie, qui je sais, à les mêmes gouts que moi.

## 3/ Avoir des projets <a name="Theme3"></a>

Ces peintures impressionistes m'ont rappelée quelques cours d'histoire de l'art. Comme un plein airiste du XXe siècle, mois aussi je veux filé vers la normandie pour voir un peu de verdure. 

J'ai trouvé ce jeu de données SNCF. J'ai du totalement le remodeler sur openrefine pour l'exploité dans Flourish, sous forme d'une course. Voici un extrait du jeu de donnée d'origine, le traitement openrefine, et un extrait du jeu après modification. Outre la transformation dans la forme, j'ai réduit le jeu de données a 10 lignes de train, partant toutes de paris, vers la cote ouest de la France. 

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

Voici un extrait de la transformation OpenRefine : remise en ordre et transposition colonne en ligne clef-valeur. J'ai également corrigé des formats sur les nombres, et supprimer tous les enregistrements ne contenant pas Paris dans la ligne de train, par une facette par mot. Puis j'ai selectionner toutes les lignes que je voulais gardé par une facette textuelle, et en inversant la selection, j'ai supprimé tout le reste. 

Il faut bien sure garder en tête que les distances entre Paris et ces différentes villes ne sont pas les mêmes.
On peut jouer la visualisation en mettant les temps en minutes en ordonnée.
On constate que l'enregistrement des durées de trajet commence plus tard pour certaine ligne : après recherche cela correspond (ou non) a la creation des lignes.
Certaines données sont manquantes dans les années 39-45


### Visuel 3 : Race <a name="visuel_2_1"></a>

<iframe src='https://flo.uri.sh/visualisation/5105944/embed' title='Interactive or visual content' frameborder='0' scrolling='no' style='width:100%;height:600px;'></iframe><div style='width:100%!;margin-top:4px!important;text-align:right!important;'><a class='flourish-credit' href='https://public.flourish.studio/visualisation/5105944/?utm_source=embed&utm_campaign=visualisation/5105944' target='_top' style='text-decoration:none!important'><img alt='Made with Flourish' src='https://public.flourish.studio/resources/made_with_flourish.svg' style='width:105px!important;height:16px!important;border:none!important;margin:0!important;'> </a></div>


## 4/ Etre curieux, s'autoriser à la rêverie <a name="Theme4"></a>

En parcourant les données ouvertes de la SNCF, j'ai trouvé leur données sur les objets perdues en gare. Ca m'a fait sourire, et ça a piqué ma curiosité. Je ne compte plus les fois ou j'ai perdu mon passe navigaux, ou trouvé des documents administratifs oublié sur le banc d'un quaie. (il se trouve que je dois avoir une sorte de chance, car ce ne sont pas les plus courant !)

A paris on perd plus son porte feuille qu'a toulouze, ou on a surtout perdu des sacs a dos.

### Visuel 3 : Story <a name="visuel_4_1"></a>

<iframe src='https://flo.uri.sh/story/742905/embed' title='Interactive or visual content' frameborder='0' scrolling='no' style='width:100%;height:600px;'></iframe><div style='width:100%!;margin-top:4px!important;text-align:right!important;'><a class='flourish-credit' href='https://public.flourish.studio/story/742905/?utm_source=embed&utm_campaign=story/742905' target='_top' style='text-decoration:none!important'><img alt='Made with Flourish' src='https://public.flourish.studio/resources/made_with_flourish.svg' style='width:105px!important;height:16px!important;border:none!important;margin:0!important;'> </a></div>

C'est aussi bien pouvoir voyager depuis la maison.



