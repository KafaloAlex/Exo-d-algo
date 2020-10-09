# Exo-d-algo


Afin d'améliorer le système informatique d'une école primaire, il t'ai demandé de réaliser un jeu de pendu.
Fonctionnment : 
	-L'ordinateur choisit un mot au hasard dans une liste 
	-Le joueur tente de trouver les mots composants se mot
	-A chaque coup, il saisit une lettre. Si la lettre se trouve dans le mot, l'ordi affiche le mot et la les lettres 
	déjà trouvé.
	-Les lettres qui ne sont pas encore trouvées seront remplacer par des étoiles;

NB: Le joueur n'a que 10 coups, passer cette limite il echoue au jeu.

Voici la liste : 
 List<string> wordsList = new List<string> {
                "ANANAS",
                "AMOUR",
                "HAINE",
                "SOLITUDE",
                "REGRET",
                "PASSION",
                "ORANGE",
                "VOITURE",
                "EXPLORATION",
                "VIOLATION",
                "OEUF",
                "GARBA",
                "IGNAME",
                "CONSTITUTIONNEL",
                "MAUVAIS"
            };
