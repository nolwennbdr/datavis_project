# Cher Journal




## 8:00 - La routine, c'est important. Le matin, j'écoute la radio.


Tous les matins, j'écoute la radio. Il arrive parfois que j'entende des femmes se faire couper la parole. Je me suis souvent demandé si je le remarquais plus que les hommes se faisant couper, par identification. Au delà de ce phénomène, j'ai voulu comparé le temps de parole entre homme et femme dans les média. 

L'INA fournit des jeux de données à ce sujet

<iframe src="https://data.opendatasoft.com/chart/embed/?dataChart=eyJxdWVyaWVzIjpbeyJjaGFydHMiOlt7InR5cGUiOiJzcGlkZXJ3ZWIiLCJmdW5jIjoiQVZHIiwieUF4aXMiOiJmZXhwciIsInNjaWVudGlmaWNEaXNwbGF5Ijp0cnVlLCJjb2xvciI6InJhbmdlLU9yUmQiLCJkaXNwbGF5VmFsdWVzIjpmYWxzZSwiZGlzcGxheVVuaXRzIjp0cnVlLCJ5TGFiZWxPdmVycmlkZSI6IkhvbW1lIn0seyJhbGlnbk1vbnRoIjp0cnVlLCJ0eXBlIjoic3BpZGVyd2ViIiwiZnVuYyI6IkFWRyIsInlBeGlzIjoiaGV4cHIiLCJzY2llbnRpZmljRGlzcGxheSI6dHJ1ZSwiY29sb3IiOiJyYW5nZS1jdXN0b20iLCJ5TGFiZWxPdmVycmlkZSI6IiIsImRpc3BsYXlVbml0cyI6ZmFsc2V9XSwieEF4aXMiOiJ5ZWFyIiwibWF4cG9pbnRzIjoyMDAsInNvcnQiOiIiLCJ0aW1lc2NhbGUiOiJ5ZWFyIiwic2VyaWVzQnJlYWtkb3duIjoibWVkaWFfdHlwZSIsImNvbmZpZyI6eyJkYXRhc2V0IjoidGVtcHMtZGUtcGFyb2xlLWRlcy1ob21tZXMtZXQtZGVzLWZlbW1lcy1hLWxhLXRlbGV2aXNpb24tZXQtYS1sYS1yYWRpb0BwdWJsaWMiLCJvcHRpb25zIjp7ImRpc2p1bmN0aXZlLmhvdXIiOnRydWUsInRpbWV6b25lIjoiRXVyb3BlL0JlcmxpbiJ9fX1dLCJ0aW1lc2NhbGUiOiJ5ZWFyIiwiZGlzcGxheUxlZ2VuZCI6dHJ1ZSwiYWxpZ25Nb250aCI6dHJ1ZSwic2luZ2xlQXhpcyI6dHJ1ZX0%3D&static=false&datasetcard=true" width="800" height="600" frameborder="0"></iframe>

<iframe src="https://data.opendatasoft.com/chart/embed/?dataChart=eyJxdWVyaWVzIjpbeyJjaGFydHMiOlt7InR5cGUiOiJjb2x1bW4iLCJmdW5jIjoiQVZHIiwieUF4aXMiOiJmZXhwciIsInNjaWVudGlmaWNEaXNwbGF5Ijp0cnVlLCJjb2xvciI6IiM5MzExN0UifSx7ImFsaWduTW9udGgiOnRydWUsInR5cGUiOiJjb2x1bW4iLCJmdW5jIjoiQVZHIiwieUF4aXMiOiJoZXhwciIsInNjaWVudGlmaWNEaXNwbGF5Ijp0cnVlLCJjb2xvciI6IiM0MUNGQzUifV0sInhBeGlzIjoiY2hhbm5lbF9uYW1lIiwibWF4cG9pbnRzIjpudWxsLCJzb3J0Ijoic2VyaWUxLTEiLCJ0aW1lc2NhbGUiOiIiLCJzZXJpZXNCcmVha2Rvd24iOiIiLCJjb25maWciOnsiZGF0YXNldCI6InRlbXBzLWRlLXBhcm9sZS1kZXMtaG9tbWVzLWV0LWRlcy1mZW1tZXMtYS1sYS10ZWxldmlzaW9uLWV0LWEtbGEtcmFkaW9AcHVibGljIiwib3B0aW9ucyI6eyJkaXNqdW5jdGl2ZS5ob3VyIjp0cnVlLCJzb3J0IjoiLWZleHByIiwidGltZXpvbmUiOiJFdXJvcGUvQmVybGluIn19LCJzZXJpZXNCcmVha2Rvd25UaW1lc2NhbGUiOiIiLCJzdGFja2VkIjoicGVyY2VudCJ9XSwidGltZXNjYWxlIjoiIiwiZGlzcGxheUxlZ2VuZCI6dHJ1ZSwiYWxpZ25Nb250aCI6dHJ1ZSwic2luZ2xlQXhpcyI6dHJ1ZX0%3D&static=false&datasetcard=true" width="400" height="300" frameborder="0"></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/9soYj3O4Ud8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Il était déjà midi, et j'ai trouvé les murs de mon appartement trop blanc. J'ai révé d'un ailleurs.

Alors au lieu d'allez dejeuné, j'ai fais une requête wikidata. A nous cette balade en bord de scène.

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


<iframe style="width: 80vw; height: 50vh; border: none;" src="https://query.wikidata.org/embed.html#SELECT%20DISTINCT%20%3Fitem%20%3FTitre%20%3Fcreateur%20(YEAR(%3Fdate)%20AS%20%3FAnneeCreation)%20%3Fimage%20%3Fcoord%20WHERE%20%7B%0A%20%20%3Fitem%20(wdt%3AP31%2F(wdt%3AP279*))%20wd%3AQ3305213%3B%0A%20%20%20%20wdt%3AP180%20wd%3AQ1471%3B%0A%20%20%20%20wdt%3AP180%20wd%3AQ1311%3B%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%0A%20%20%20%20rdfs%3Alabel%20%3FTitre.%0A%20%20FILTER((LANG(%3FTitre))%20%3D%20%22fr%22)%0A%20%20OPTIONAL%20%7B%0A%20%20%20%20%3Fitem%20wdt%3AP170%20%3FQcreateur.%0A%20%20%20%20%3FQcreateur%20rdfs%3Alabel%20%3Fcreateur.%0A%20%20%20%20FILTER((LANG(%3Fcreateur))%20%3D%20%22fr%22)%0A%20%20%7D%0A%20%20OPTIONAL%20%7B%20%3Fitem%20wdt%3AP571%20%3Fdate.%20%7D%0A%20%20OPTIONAL%20%7B%20%3Fitem%20wdt%3AP18%20%3Fimage.%20%7D%0A%20%20OPTIONAL%20%7B%20%3Fitem%20wdt%3AP625%20%3Fcoord.%20%7D%0A%7D" referrerpolicy="origin" sandbox="allow-scripts allow-same-origin allow-popups"></iframe>



## Il fallait partir très vite, vers la mer ! Une sorte de conquêtes de l'ouest.

<iframe src='https://flo.uri.sh/visualisation/5105944/embed' title='Interactive or visual content' frameborder='0' scrolling='no' style='width:100%;height:600px;'></iframe><div style='width:100%!;margin-top:4px!important;text-align:right!important;'><a class='flourish-credit' href='https://public.flourish.studio/visualisation/5105944/?utm_source=embed&utm_campaign=visualisation/5105944' target='_top' style='text-decoration:none!important'><img alt='Made with Flourish' src='https://public.flourish.studio/resources/made_with_flourish.svg' style='width:105px!important;height:16px!important;border:none!important;margin:0!important;'> </a></div>


## Puis j'ai divagué, sur tout ces inconnus qui voyagent, qui parfois la tête ailleurs, perdent leur bagage.

A paris on perd plus son porte feuille qu'a toulouze, ou on a surtout perdu des sacs a dos.


C'est aussi bien pouvoir voyager depuis la maison.



