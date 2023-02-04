## Classe

## Exception

## JSON

- Les classes en JavaScript
  - https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Classes
- Les erreurs en JavaScript
  - https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Global_Objects/Error
- Convertir une chaine JSON en objet
  - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON/parse
- Convertir un objet en chaine JSON
  - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON/stringify

## Sujet du TP

1) Mettre en place la classe Article, qui prendra en paramètre un id numérique, un titre et une description. Si l'un des éléments est vide ou non défini, alors une erreur de type RequiredFieldError sera déclenchée. Dans le cas où une erreur de type RequiredFieldError est catché, alors on affichera un message d'erreur dans la div ayant pour id errorForm.

2) Mettre en place une classe ArticleHtml, qui prendra en paramètre de son constructeur un objet de type Article. Elle possèdera en plus, une méthode toHtmlElement, qui renverra un NodeElement construit à partir de l'article et qui représentera le code HTML suivant `<article data-id="$ID" class="article"><span>$TITLE</span><p>$DESCRIPTION</p></article>`

3) Mettre en place une chaîne de caractères JSON représentant une liste d'article. Au chargement de la page, les articles JSON devront être parsés pour être intégrés au sein de la page (dans la div ayant pour l'id newsList). Ceci devra être fait au sein d'une classe ArticleService.

4) Au clic sur le bouton "Exporter", il faudra récupérer l'intégralité des articles présents sur la page, les convertir en Article et les convertir en chaine de caractère JSON. Le résultat sera affiché dans la console. Ceci devra être fait au sein d'une classe ArticleService.

## Ressources

- Lien des slides : https://drive.google.com/drive/folders/1tFK4F2RrTWAvqqEG-RpGvnTMCGohaNcz?usp=share_link
- Lien vers la documentation : https://developer.mozilla.org/fr/docs/Web/JavaScript