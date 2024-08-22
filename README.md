# Méthodes GET et POST
1) la methode `GET` demande une représentation d'une ressource alors que `POST` envoie une représentation vers une ressource qui est passé en parametre.
j'ai utilisé comme source ce [lien](https://developer.mozilla.org/fr/docs/Web/HTTP/Methods)
# Comparaison méthodes
| GET | POST|
| :-- |:---|
|	Visible pour l’utilisateur dans le champ d’adresse|Invisible pour l’utilisateur|
|Les paramètres de l’URL sont stockés en même temps que l’URL|L’URL est enregistrée sans paramètres URL|
|Les paramètres de l’URL sont stockés sans chiffrement|Les paramètres de l’URL ne sont pas enregistrés automatiquement|
|Les paramètres de l’URL ne sont pas envoyés à nouveau|Le navigateur avertit que les données du formulaire doivent être renvoyées|
|Caractères ASCII uniquement|Caractères ASCII mais également données binaires|
|Limitée - longueur maximale de l’URL à 2 048 caractères|Illimitée|
# Extensible
le protocole `HTTPS` est extenssible car de nouvelles fonctionnalité peuvent y être introduite par un simple accord entre le serveur et le client.
# Sans état
`HTTPS` est califié "sans état" car sur une page internet aucune forme n'est prise ou mis en place par celle ci. La principale conséquence est que la page n'aura aucunne mise en forme et sera part moment illisible car suivant ce que l'on souhaite mettre en forme cela peut être illisible sans du `CSS` qui permet la mise en forme d'une page internet.
# URL
![image](https://github.com/user-attachments/assets/d01e6b5d-d25b-455d-b223-d55954d905bd) \
voici la decomposition d'une `URL`
# Codes Status
1xx réponse informationnelle, 2xx succès, 3xx redirection, 4xx erreur client et 5xx erreur serveur.
# Négociation de contenu
Lorsqu'un client souhaite obtenir une ressource, il la demande via une URL. Le serveur utilise alors cette URL pour choisir l'une des variantes disponibles. Chaque variante est appelée une représentation. Le serveur renvoie alors une représentation donnée au client.
![image](https://github.com/user-attachments/assets/cf5e0842-cae6-4962-989d-4cf7ce5f62e0) \
# Installation Apache & configuration
