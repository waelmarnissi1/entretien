Cas de test GET: <br>
1- Test-01-Get-contrat-ok <br>
- ouvrir une nouvelle requête Postman  en utilisant l’url /api/contacts/{id}, l’id doit être existant dans la base <br>
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
- Sélectionner la methode GET dans postman <br>
- exécuter la requete <br>
- Vérifier le code de retour 404 <br>
- vérifier que le body retourné est vide <br>


Cas de test PUT: <br>
1- Test-01-PUI-contrat-ok <br>
- ouvrir une nouvelle requête Postman  en utilisant l’url /api/contacts/{id}, l’id doit être existant dans la base <br>
- Sélectionner la methode PUT dans postman <br>
- Ajouter ce body dans la requete <br>
 {
firstname: "Morgan",
lastname: "Freeman",
number: 33765489234
}
- exécuter la requete <br>
- Vérifier le code de retour 201 ok <br>
- Exécuter le cas de test 1 avec id utilisé pour vérifier que le body a été bien updaté
