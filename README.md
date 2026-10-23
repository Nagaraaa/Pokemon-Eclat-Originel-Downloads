# Pokémon Éclat Originel

Une aventure coopérative basée sur Rouge Feu. Chacun garde son équipe, sa sauvegarde et sa progression.

**[Télécharger pour Windows — 0.5.0-preview.2](https://github.com/Nagaraaa/Pokemon-Eclat-Originel-Downloads/releases/download/v0.5.0-preview.2/Pokemon-Eclat-Originel-Windows-0.5.0-preview.2.zip)** · [Notes de version](https://github.com/Nagaraaa/Pokemon-Eclat-Originel-Downloads/releases/tag/v0.5.0-preview.2)

Cette version apporte un nouveau lanceur dessiné comme un écran de Rouge Feu, avec le PC de Léo, et une nouvelle chambre de départ. Le Casino de Céladopole et le Comptoir des Œufs sont toujours là. Le premier Pokémon apte suit le dresseur dehors et dans les bâtiments, en Solo et en Coop. Le combat duo permet à chacun de commander son premier Pokémon, sans récompense et avec restauration des équipes.

## Installer

1. Extraire entièrement le ZIP dans un **nouveau dossier** ; conserver l'ancien.
2. Ouvrir **EclatOriginel.exe**. L'émulateur et ses dépendances sont inclus.
3. Au premier lancement, glisser son original **Rouge Feu 1.0 français** ou **FireRed 1.0 anglais US** sur la fenêtre, ou cliquer sur le **PC de Léo**. Le lanceur le vérifie et prépare le jeu ; Léo répond en bas de la fenêtre.
4. Choisir **Solo** pour reprendre son aventure, ou **Coop** pour rejoindre le serveur.

Le paquet contient les correctifs UPS des deux langues et **aucune ROM**. Garder la langue de sa sauvegarde : le lanceur ne la convertit pas.

Les sauvegardes restent dans `%LOCALAPPDATA%/EclatOriginel/saves`. Les touches PS4/PS5, réglages de manette et raccourcis de vitesse existants sont conservés. Software (Qt) est l'affichage initial des nouveaux profils. Reprendre avec une sauvegarde normale du jeu ; les états instantanés d'une ancienne ROM restent incompatibles.

## Jouer avec un ami

Le **serveur Xiaomi en 0.5.0-preview.1** reste compatible avec cette version. Sur chaque PC :

1. Cliquer **Coop** : la connexion au Xiaomi est automatique.
2. Dans le jeu, l'un crée un salon et l'autre le rejoint.
3. Choisir **CONTINUER**, puis **CONTINUER** dans le menu d'origine de Rouge Feu pour reprendre sa partie. Sans sauvegarde : **NOUVELLE PARTIE**.
4. Depuis le terrain, **START → SALONS → REPRENDRE** revient à l'aventure.

Aucun émulateur séparé, outil réseau ou compte VPN à installer. Les cartes, déplacements et vitesses restent indépendants. Le guide Windows inclus détaille les parcours et le dépannage.

Au Casino de Céladopole, les trois nouvelles tables proposent méga-machines, plinko et blackjack, en Éclats ou en jetons. Une main interrompue reprend sa monnaie ; après dix minutes sans action, le serveur la termine comme RESTER. Un gain expiré en jetons est récupéré à la table et sauvegardé avant confirmation. S'il ne tient pas dans la poche, il reste disponible.

## Héberger sur PC

Pour le même Wi-Fi, l'hôte ouvre **Paramètres → Serveur dédié**. Les deux joueurs sélectionnent ce serveur dans **Paramètres → Réseau local**, puis rejoignent le même salon.

Les archives [Serveur Windows](https://github.com/Nagaraaa/Pokemon-Eclat-Originel-Downloads/releases/download/v0.5.0-preview.1/Pokemon-Eclat-Originel-Serveur-Windows-0.5.0-preview.1.zip) et [Serveur Termux](https://github.com/Nagaraaa/Pokemon-Eclat-Originel-Downloads/releases/download/v0.5.0-preview.1/Pokemon-Eclat-Originel-Serveur-Termux-0.5.0-preview.1.zip) permettent un hébergement séparé. Elles ne sont pas nécessaires pour rejoindre le Xiaomi.

## Commandes et vérifications

Flèches pour marcher, **X = A**, **Z = B**, **Entrée = START**, **Retour arrière = SELECT**. **Commandes** permet de régler le clavier, les manettes PS4/PS5 et les raccourcis ×2/×4/×8. **SELECT** sur les statistiques affiche les IV/EV : IV colorés, étoile à31 et MAX pour les EV.

Les tests couvrent le vrai cœur GBA, les trois jeux avec le serveur SQLite, les reprises et coupures, le lanceur, Qt Windows et le trajet Internet vers le Xiaomi. Une nouvelle partie humaine sur deux PC reste à valider. Les mises ordinaires en jetons attendent une sauvegarde native pour devenir durables : sauvegarder avant de fermer le jeu.

Les licences accompagnent les archives. **SHA256SUMS-0.5.0-preview.2.txt** permet de vérifier le ZIP Windows ; les archives serveur, inchangées, restent vérifiables avec **SHA256SUMS-0.5.0-preview.1.txt**. Les versions précédentes restent dans l'historique des publications.
