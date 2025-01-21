# SpamClassifier_Jeanneau

Objet : Concevoir un classifieur de détection automatique de SPAM.

Dataset : La collection SMS Spam est un ensemble de messages SMS marqués qui ont été collectés pour la recherche sur les SMS Spam. Elle contient un ensemble de messages SMS en anglais de 5 574
messages, étiquetés selon qu'ils sont ham (légitimes) ou spam.
Le fichier contient un message par ligne. Chaque ligne est composée de deux colonnes : v1
contient le label (ham ou spam) et v2 contient le texte brut.
Ce corpus a été collecté à partir de sources libres ou gratuites pour la recherche sur Internet.


Etude préliminaire : 
Le dataset comprend 5574 entrées constituées d'un message et de son étiquetage (spam ou
ham). 
- 425 entrées spam proviennent d'une extraction manuelle d'un forum britannique d'utlisateurs
denonçant des spams.
- 3375 entrées ham proviennent d'une extraction aléatoire parmi 10000 messages provenant
essentiellement d'étudiants volontaires d'une université Singapourienne.
- 450 entrées ham proviennent d'une thèse de doctorat (pas plus d'information car le rapport de
these ne semble plus accessible).
- 1002 entrées ham et 322 entrées spam provenant de recherches académiques

=> On constate que le dataset se réparti comme suit :
747 spams (13,4% du dataset)
4827 hams ( 86,6% dud dataset) 

=> Les sources de données datent de plus de 10 ans apparemment et il pous faudrait un
dataset plus récent pour que le modèle soit plus adapté aux types de spams d'aujourd'hui. On remarquera plus tard que les spams sont concentrés dans une dans une zone jusqu-au- dessous de 160 caractères!!! Est-ce que les spams recoltés ne datent-ils pas d'une période où les sms étaient limités à 160 caracteres alors que l'on aurait des hams de périodes différentes

Questions et biais : Cette répartition reflète-t-elle la réalité ? Quel impact cela peut-il avoir ? Age du dataset ?
