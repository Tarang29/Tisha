## Content Hub 8.x-2.2 - April 24,2017
| The Content Hub 8.x-2.2 client for Drupal 8 ![download](https://www.drupal.org/project/acquia_contenthub/releases/8.x-2.2) contains the following updates:|                                                                    
|-----------------------------------------------------------------------------------------------------------------------------|

```Fix```    Drush commands refactoring: `acquia:contenthub-connect-site,`  `acquia:contenthub-disconnect-site,`  ` acquia:contenthub-webhooks`

```Feature```  Get timezone from [drupal](https://www.drupal.org) and remove hard coded value.

```Change ``` _In function names_, rename **'CDF'** to **'Cdf'**.

```Change```  Recurssively find dependencies and make `ModerationStateFieldItemList::generateSampleItems()` return sane data.

```Feature```     Entity Override Layout Builder support.

```Fix```     Better account warning in `purge` command and updated coding standards.

```Fix```     Refactor `content hub settings` form.

```Fix```     Using reflection until core patch for _issue #3046814_is reviewed.

```Change```  Need to pass`array_unique()`to do a fair comparison.

```Change```  Added initial work for the new ``` import and export drush commands.```

```Feature``` Adding newest _discovery interface_ code.
