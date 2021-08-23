# drupa-test-theme

## Enabling Debug
You enable Twig Debugging in sites/default/services.yml.

Set the debug variable to true. And clear cache.

parameters:
  twig.config:
    debug: true


## Enabling Xdebug

Far and beyond the best way to deal with Viewing variables is to use Xdebug.

Other common drush commands

```
drush cr

#import config mgmt
drush cim -y


#Export
drush cex -y

composer self-update --1
composer install


#if drush doesn't work
#install composer first

drush pmu module_name -y
drush pm-enable project_name
drush pm-disable project_name
drush pm-update


variable_get (vget)
drush variable_get variable_name

drush pm-list | grep modulename

```
