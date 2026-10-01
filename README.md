# Moreau Island

Dépôt de test pour découvrir les sessions cloud de Claude Code.

## C'est quoi une session cloud ?

Une session cloud, c'est Claude Code qui tourne sur un serveur Anthropic plutôt que sur votre ordinateur.

1. **Un conteneur isolé** est créé pour la session.
2. **Le dépôt GitHub est cloné** dedans.
3. **Claude travaille sur une branche dédiée** (ici `claude/stoic-allen-vecpa7`). Il lit, modifie, lance des commandes, puis commit et push.
4. **Vous suivez et dialoguez** depuis l'app web ou mobile. Votre machine n'a pas besoin d'être allumée.
5. **Le conteneur est éphémère.** Ce qui n'est pas commité et poussé est perdu à la fin de la session.

## Ce qu'il faut retenir

- Rien n'est modifié sur `main` directement : tout passe par la branche de la session.
- Une pull request n'est créée que si vous la demandez.
- Les changements sont à relire sur GitHub avant de les fusionner.

## Pour essayer

Demandez à Claude une petite modification (ajouter un fichier, corriger une faute, écrire un script), puis regardez le commit apparaître sur la branche.
