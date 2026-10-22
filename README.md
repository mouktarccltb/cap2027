# Kit Cap 2027

Kit de préparation des rendez-vous Cap 2027 de la CCLTB. Document de travail interne : le COMEX prépare et oriente, le conseil communautaire débat et décide.

Le contenu est **chiffré** : la page d'accès (`index.html`) ne s'ouvre qu'avec le mot de passe commun transmis dans le courriel d'envoi. Les explications en PDF (`docs/*.pdf.enc`) et le fichier des créneaux (`creneaux.enc`) sont chiffrés avec la même clé.

## Liens

- Kit : https://mouktarccltb.github.io/cap2027/
- Lien direct vers un pôle ou une direction : ajouter `#ressources`, `#petite-enfance`, `#eej`, `#patrimoine`, `#environnement`, `#culture`, `#developpement` ou `#amenagement`.
- Console du DGA : ajouter `#dga` (protégée par son propre mot de passe).

## Modifier les créneaux

Dans la Console, « Enregistrer » télécharge un fichier `creneaux.enc`. Le déposer à la racine du dépôt (« Add file » → « Upload files » → « Commit changes ») : le kit affiche les nouveaux créneaux quelques minutes après.

## Modifier le contenu

Le contenu en clair n'est pas dans le dépôt. Pour le modifier, demander à Claude en lui donnant le mot de passe commun : il déchiffre `index.html`, fait la modification, puis rechiffre la page et les PDF avec ce même mot de passe.
