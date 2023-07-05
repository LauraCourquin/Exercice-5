# Exercice : Pipeline NodeJS

----

Cet exercice a pour objectif de vous permettre de pratiquer les pipelines avec NodeJS.

----

## Contexte

Vous intervenez en support pour une équipe de développement front Angular qui prépare un projet degrande envergure. Ils ont déjà commencé à coder et tester les premiers composants mais ne savent pascomment automatiser leur travail.

Plusieurs tickets vous ont été attribué, et vous devez les mener à bien. Pour chaque ticket, il va sans dire quevous devez vérifier la bonne exécution de votre pipeline, et respecter toute les contraintes de ces dernières. Eneffet, une mauvaise automatisation peut avoir un effet desastreux sur le projet (comme supprimer mesmauvaises branches par exemple).

L'équipe que vous intégrez utilise le **workflow gitflow** ainsi que les **conventionnal commits**. Vous deveez doncrespecter ces conventions. L'ensemble des features sont donc développées sur des branches nommées features/<nom_feature>, qui sont tirées depuis la branche develop. Les branches hotfix/<nom_hotfix>sont tirées depuis la branche main. Une fois terminé, elles sont mergées et les branches sont suppriméesmanuellement.

Pour faciliter le travail, les développeurs ont ajouté deux commandes dans le projet : 

- `npm run test`: pour lancer les tests
- `npm run test:coverage`: pour lancer les tests et afficher le coverage