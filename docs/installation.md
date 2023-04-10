# Installation

This document details the step to install the project on your local environment.

Server requirements:

- Apache Version: 2.4.7+
- MySQL Version: 5.7.8+
- PHP Version: 8.0+
- [Composer](https://getcomposer.org/) installed
- Git installed

#### Clone the project

Run the command below to clone the project from Git.

```
$ git clone https://github.com/nasAtchia/drupal-blog.git
```

#### Create your database

Create your database on your MySQL server and import the latest ****.mysql.gz**** file from the [db](../docs/db) folder.

#### Configure your services.yml and settings.php file

Copy the [services.yml.dist](../web/sites/default/services.yml.dist) file and rename to services.yml and update the configurations according to your environment.

Copy the [settings.php.dist](../web/sites/default/settings.php.dist) file and rename to settings.php and update the configurations according to your environment.

#### Composer and Drush configurations

In your terminal and the project root directory, run the following commands to install the project dependencies:

```
$ composer install
$ vendor/drush/drush/drush updb
$ vendor/drush/drush/drush cr
$ vendor/drush/drush/drush cim
$ vendor/drush/drush/drush cr
```

#### Update your public files directory

Extract and copy the latest **.tar.gz** file from the [docs/files](../docs/files) directory in the [/web/sites/default/files](../web/sites/default/files) directory.