Cas de test GET: <br>
1- Test-01-Get-contrat-ok <br>
- ouvrir une nouvelle requête Postman  en utilisant l’url /api/contacts/{id}, l’id doit être existant dans la base <br>
- Url Ajouté <br>
- Sélectionner la methode GET dans postman <br>
- exécuter la requete <br>
- Vérifier le code de retour 200 <br>
- vérifier que le body retourné est le suivant: <br>
 {
firstname: "Morgan",
lastname: "Freeman",
number: 33765489234
}


1- Test-01-Get-contrat-KO <br>
- ouvrir une nouvelle requête Postman  en utilisant l’url /api/contacts/{id}, l’id doit être inexistant dans la base <br>
- Url Ajouté <br>
- Sélectionner la methode GET dans postman <br>
- exécuter la requete <br>
- Vérifier le code de retour 404 <br>
- vérifier que le body retourné est vide <br>
