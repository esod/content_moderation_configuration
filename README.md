Enable the content_moderation module. Use the following drush <a href="https://drushcommands.com/drush-8x/config/config-import/">config-import</a> command to import the configuration into your Drupal 8.6.0-dev site.

drush config-import --partial --source=/PATH_TO_REPO/content_moderation_configuration

Users are content in Drupal. After importing the configuration, make three users with roles assigned like this:    
<ol>
  <li>Reviewer user with Reviewer role</li>
  <li>Author user with Author role</li>
  <li>Publisher user with Publisher role</li>
</ol>
