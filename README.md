# Drupal 8 

## Theming

### Product
* Pour afficher des champs de variations dans un template ```product--name.html.twig``` => Il faut passer par le preprocess,
```{{ product.variation_**** }}``` ne fonctionnera pas.

### Taxonomy
* Les modes d'affichage pour les taxonomy tels que ```taxonomy_term--taxonomy-name--view-mode.html.twig``` ne fonctionnent pas.

### Block
* Pour afficher un block dans n'importe quel fichier *twig* avec [Twig tweak](https://www.drupal.org/project/twig_tweak) il faudra utiliser ``` {{ drupal_entity('block','block_name', check_access=false) }} ```


### Devel
* Pour pouvoir utiliser ```kint()``` sans être redirigé vers l'install de Drupal :
``` kint_require(); ```
```Kint::$maxLevels = 3; ```

