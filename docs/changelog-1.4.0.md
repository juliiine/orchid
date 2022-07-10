-- Changelog de la version 1.4.0 --

Fixs :

- Mauvais chemin utilisé par l'ISO ne prennant pas en compte les fixs de la 1.3.4.
- Finalisation du stage plasma et stabilisation en sortie release de l'ensemble des stages qui restaient en testing.
- Divers problèmes sur le support de la langue anglaise.
- Fixs divers améliorant les performances en jeu, notamment sur F1 2022 et Final Fantasy XIV.

Ajouts : 

- Ajout de l'utilitaire orchid-fetch, qui est neofetch spécifique à Orchid (made by Captive).
- Ajout de l'utilitaire orchid-workaround, qui est l'opposé de orchid-version (nécessaire pour compiler certains paquets se basant sur os-release, ex: Geoclue).
- Orchid est installable en Anglais, en Roumain, et aussi en Allemand désormais, choix possible dans le script.
- Orchid-swap-suite pour changer le mode de syncro des dépots Gentoo, git ou rsync.
- Mise à jour de orchid-help avec les nouveaux outils. 
- get est une commande égale à orchid-install.
- orchid-edit permets l'édition du make.conf rapidement.
- Notre ISO officiel est désormais pleinement utilisable, dans un format ultra réduit (- de 300mo). Elle lance le script d'installation en auto.
- Nouvelles éditions qui rejoignent le pool (en testing) : Mate et Mate Gaming !
- Support du partionnement manuel, et donc du dualboot.
- Divers ajouts pour rendre Orchid encore plus performant.
- Préparation au support LTO et O3 lors d'un orchid-optimizer (niveau de performances maximales théorique sur Gentoo).

Organisationel : 

- Mise à jour des stages stables, sorti de testing de l'ensemble des éditions précédentes.
- Ajout du bot discord tenant informé l'avacement des constructions, essais, testing, mises à jours ...
- Un nouveau membre rejoint l'équipe de développement : Maité.
- Définition du release plan jusqu'à 2.0.
- Divers remaniement organisationnel.
- Préparation au support de la méthode de mise à jour continue, Orchid Nightly.
