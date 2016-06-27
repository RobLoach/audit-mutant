# Modules

List of modules
-   Present but not installed
-   Installed but not enabled
-   Enabled

Any scary modules with performance-crushing powers like field permissions.

## Site Audit Drush Component

1. Install [Site Audit](https://www.drupal.org/project/site_audit) Drush component
  ```
  git clone --branch 7.x-1.16 https://git.drupal.org/project/site_audit.git ~/.drush/commands/site_audit
  ```

2. Clear the Drush cache
  ```
  drush cc drush
  ```

3. Run all Site Audit reports
  ```
  drush aa
  ```
