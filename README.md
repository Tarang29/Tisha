***********************************
Content Hub 8.x-2.2 - April 24,2017
***********************************

| The Content Hub 8.x-2.2 client for Drupal 8 ![download](https://www.drupal.org/project/acquia_contenthub/releases/8.x-2.2) contains the following updates: |
|:---------------------------------------------------------------------------------------------------------------------- |

```Feature``` Entity Override Layout Builder support.
- User is able to override the Layout Default and create a custom layout for that entity. Once a Layout is overridden on an entity, it allows you to override the Layout default and create a custom layout for an entity.


```Feature``` Adding newest _discovery interface_ code.
- This helps in creating new cloud filters, and for defining what content is destined for which webhooks.

```Change ``` _In function names_, rename **'CDF'** to **'Cdf'**.

```Change```  Recurssively find dependencies and make `ModerationStateFieldItemList::generateSampleItems()` return sane data.

```Change```  The `array_unique()` is used to do a fair comparison.

```Change```  Initial work for the new ``` import and export drush commands``` are added.

```Feature``` In this Release, following ```Drush``` commands are re-factored: 
- `acquia:contenthub-connect-site,`helps to connect cleint to Content Hub.
- `acquia:contenthub-disconnect-site,`helps to disconnect client from Content Hub.
- ` acquia:contenthub-webhooks`to perform a webhook management operation.

```Fix```  Get timezone from [drupal](https://www.drupal.org) and remove hard coded value.

```Fix```     Better account warning in `purge` command and updated coding standards.

```Fix```     Refactor `content hub settings` form.

```Fix```     Using reflection until core patch for _issue #3046814_is reviewed.
