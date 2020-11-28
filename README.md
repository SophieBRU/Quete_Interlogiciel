# Quete_Interlogiciel

# Challenge
Crée un projet ASP.Net sans MVC, configuré pour être une API. Supprime le corps de la méthode Startup.Configure. Ajoute un intergiciel qui vérifie que le paramètre allow est présent dans l'URL (ex: http://localhost:12345?allow). Si le paramètre allow est présent, la fonction déléguée paramètre de IApplicationBuilder.Run écrit "Hello, World!" dans le corps de la réponse.

# Critères de validation
Un lien vers un dépôt hébergé sur GitHub est fourni en tant que solution de la quête
Le projet est une API ASP.Net générée avec Visual Studio
La méthode Startup.Configure ajoute un intergiciel vérifiant que le paramètre allow est présent dans l'URL
Si le paramètre n'est pas présent dans l'URL, une exception est soulevée
Si le paramètre est présent, l'application renvoie "Hello, World!" dans le corps de la réponse
Aucune modification de la requête HTTP n'est exécutée dans un intergiciel
