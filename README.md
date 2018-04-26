Enable the content_moderation moderation Then use drush <a href="https://drushcommands.com/drush-8x/config/config-import/">config-import</a> to import the configuration into your Drupal 8.6.0-dev site. The configuration will probably work in any site above Drupal 8.5.x.

drush cim --partial --source=/PATH_TO_REPO/content_moderation

Users are content in Drupal. After importing the configuration, make three users:    
<ol>
  <li>Reviewer with Reviewer role</li>
  <li>Author with Autor role</li>
  <li>Publisher with Publisher role</li>
</ol>

