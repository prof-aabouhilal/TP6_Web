# TP 6 : Mini-Application Web Avancée (HTML + CSS + JS) & Introduction au PHP
Ce TP vise à combiner les technologies HTML, CSS et JavaScript pour construire une mini-application web dynamique.
Une deuxième petite partie introduit PHP à partir de l’affichage de variables simples (sans formulaires).

## Travail Demandé
Vous devez créer une page Web professionnelle et interactive, qui :
✔ Utilise une structure HTML sémantique
✔ Utilise un design responsive CSS moderne
✔ Manipule le DOM via JavaScript
✔ Implémente une petite calculatrice locale
✔ Affiche dans une autre page PHP des variables simples

## Structure des fichiers 
tp6-web/
│ index.html
│ style.css
│ app.js
└─ info.php

# Partie 1 — HTML (Interface)

## Créez un fichier index.html contenant :
une structure sémantique (header, main, footer)
un titre
un formulaire avec :
Nombre A
Nombre B
Menu déroulant (choix de l’opération : + − × ÷)
Bouton “Calculer”
une zone d’affichage des messages d’erreurs
une section “Historique des opérations”

# Partie 2 — CSS

Dans le fichier style.css, vous devez :
✔ Utiliser Flexbox ou Grid
✔ Rendre la page responsive
✔ Ajouter effets hover/transitions
✔ Créer une card visuelle pour afficher l’historique

# Partie 3 — JavaScript (DOM & Validation)

Le fichier app.js doit contenir :
Récupération des valeurs saisies dans le formulaire
Validation des données :
Vérifier que les champs ne sont pas vides
Interdire la division par zéro
Affichage dynamique des erreurs dans la page (pas d’alert())
Ajout des opérations dans un tableau JS
Mise à jour de la section “Historique” :
✔ Affichage dynamique (DOM)
✔ Historique visible sous forme de liste

# Partie 4 — Introduction au PHP 
Créer un fichier info.php qui :
Déclare plusieurs variables PHP
chaînes de caractères
entiers
résultats d'opérations
Les affiche dans la page avec echo
Effectue des calculs simples
Affiche les résultats dans une page structurée

## Exemple de contenu attendu :
Nom de l’établissement
Module
Année
Exemples de variables numériques
Résultat d’addition et multiplication
