## Tâche 1 : Ecrire un crawler Trip-Advisor en Ruby

-	Il s’agit d’écrire un script qui va aller sur trip-advisor faire une recherche d’hôtels par ville et importer dans une base de données SQL (de ton choix) tous les commentaires qu’ont reçus les hôtels qui ressortent dans les résultats de recherche (sans les classer nécessairement par hotel)
-	Pour chaque hotel dans les résultats de recherche, tu vas devoir aller sur la page de l’hotel et prendre ses commentaires
-	En terme de limitation, tu prends que les hôtels de la première page des résultats de recherche et que les 10 premiers commentaires sur la page de chaque hotel
-	Si le commentaire est trop long et ne s’affiche pas en entier, tu ne prends que le début
-	Ton script doit prendre en argument la ville dans laquelle tu dois chercher
-	En base, les attributs d’un commentaire sont : le contenu, la date à laquelle il a été écrit, le nom de la personne qui l’a écrit, le nom de l’hotel, la ville.


## Tips:

- Checkout `gem nokogiri` et `gem mechanize`
- Pas la peine d'écrire un code hyper clean, il s'agit d'un petit script tout simple
