# Drupal 8 

## Theming
 * Pour afficher des champs de variations dans un template ```product--****.html.twig``` => Il faut passer par le preprocess,
```{{ product.variation_**** }}``` ne fonctionnera pas.

* Les modes d'affichage pour les taxonomy tels que ```taxonomy_term--taxonomy-name--view-mode.html.twig``` ne fonctionnent pas.
