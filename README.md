# Pokémon Éclat Originel

Une aventure française basée sur Rouge Feu. Chacun garde son équipe, sa sauvegarde et sa progression.

**[Télécharger pour Windows — 0.4.0-preview.3](https://github.com/Nagaraaa/Pokemon-Eclat-Originel-Downloads/releases/download/v0.4.0-preview.3/Pokemon-Eclat-Originel-Windows-0.4.0-preview.3.zip)** · [Notes de version](https://github.com/Nagaraaa/Pokemon-Eclat-Originel-Downloads/releases/tag/v0.4.0-preview.3)

Le premier Pokémon apte de votre équipe vous suit à pied dehors et dans les bâtiments, en Solo et en Coop. Les œufs et Pokémon K.O. sont écartés. Après une porte ou un escalier, marcher d'un pas complet pour le faire revenir. Menus, dialogues, combats, vélo et surf le masquent temporairement. Les grottes restent exclues. Le premier combat duo reste disponible, sans récompense et avec restauration des équipes.

## Installer

1. Extraire entièrement le ZIP dans un **nouveau dossier** ; conserver l'ancien.
2. Ouvrir **EclatOriginel.exe**. L'émulateur et ses dépendances sont inclus.
3. Choisir **Solo** pour reprendre son aventure, ou **Coop** pour rejoindre le serveur.

Les sauvegardes restent dans `%LOCALAPPDATA%/EclatOriginel/saves`. Les touches PS4/PS5, réglages de manette et raccourcis de vitesse existants sont conservés. Software (Qt) est l'affichage initial des nouveaux profils.

Reprendre avec une sauvegarde normale du jeu. Les anciens états instantanés d'une autre ROM ne sont pas compatibles.

## Jouer avec un ami

Le **serveur Xiaomi 0.4.0-preview.2 est compatible**. Chaque joueur utilise Windows **0.4.0-preview.3**, puis :

1. Cliquer sur **Coop** : la connexion au Xiaomi est automatique.
2. Dans le jeu, l'un crée un salon et l'autre le rejoint.
3. Choisir **CONTINUER** : le menu d'origine de Rouge Feu s'ouvre, puis **CONTINUER** y charge sa sauvegarde. Sans sauvegarde : **NOUVELLE PARTIE**. En jeu, **START → SALONS**, puis **REPRENDRE**, revient à l'aventure.
4. Se retrouver à pied, dehors ou dans la même maison, pour voir les deux dresseurs et leurs Pokémon.

Aucun émulateur séparé, outil réseau ou compte VPN à installer. Les déplacements et vitesses restent indépendants. Le guide **POKEMON-SUIVEURS.md** inclus détaille les essais ; **COMBAT-DUO.md** décrit le combat à deux.

Les tests de cette version couvrent la reprise de sauvegarde normale et de secours, deux vraies ROM sur un PC sous latence simulée, les changements d'étage et coupures, puis le programme Windows et son rendu. Le serveur Xiaomi n'a pas besoin d'une nouvelle mise à jour. **Votre partie réelle sur deux PC reste à valider.**

## Héberger sur PC

Pour un essai sur le même Wi-Fi, l'hôte ouvre **Paramètres → Serveur dédié**. Les deux joueurs sélectionnent ce serveur dans **Paramètres → Réseau local**, puis rejoignent le même salon.

L'[archive serveur Windows](https://github.com/Nagaraaa/Pokemon-Eclat-Originel-Downloads/releases/download/v0.4.0-preview.2/Pokemon-Eclat-Originel-Serveur-Windows-0.4.0-preview.2.zip) permet un hébergement séparé. Le [paquet Termux](https://github.com/Nagaraaa/Pokemon-Eclat-Originel-Downloads/releases/download/v0.4.0-preview.2/Pokemon-Eclat-Originel-Serveur-Termux-0.4.0-preview.2.zip) sert à l'administration Android. Ces deux archives sont inutiles sur le PC d'un joueur qui utilise le Xiaomi.

## Commandes

Flèches pour marcher, **X = A**, **Z = B**, **Entrée = START**, **Retour arrière = SELECT**. **Commandes** permet de régler le clavier, les manettes PS4/PS5 et les raccourcis ×2/×4/×8. Les IV/EV sont accessibles avec SELECT sur la page des statistiques.

Les licences accompagnent les archives. **SHA256SUMS-0.4.0-preview.3.txt**, joint à la version, permet de vérifier le jeu téléchargé. Les paquets serveur restent en preview.2, avec leur propre fichier de sommes.
