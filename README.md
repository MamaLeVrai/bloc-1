# Méthodes GET et POST
1) la methode `GET` demande une représentation d'une ressource alors que `POST` envoie une représentation vers une ressource qui est passé en parametre.
j'ai utilisé comme source ce [lien](https://developer.mozilla.org/fr/docs/Web/HTTP/Methods)
# Comparaison méthodes
| GET | POST|
| :-- |:---:|
|	Visible pour l’utilisateur dans le champ d’adresse|Invisible pour l’utilisateur|
|Les paramètres de l’URL sont stockés en même temps que l’URL|L’URL est enregistrée sans paramètres URL|
|Les paramètres de l’URL sont stockés sans chiffrement|Les paramètres de l’URL ne sont pas enregistrés automatiquement|
|Les paramètres de l’URL ne sont pas envoyés à nouveau|Le navigateur avertit que les données du formulaire doivent être renvoyées|
|Caractères ASCII uniquement|Caractères ASCII mais également données binaires|
|Limitée - longueur maximale de l’URL à 2 048 caractères|Illimitée|
