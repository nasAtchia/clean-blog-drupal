# Clean Blog #

An example website on Drupal showcasing a blog.

Drupal version: **9.5.7**

Theme: [Clean Blog](https://startbootstrap.com/theme/clean-blog)

## Installation

Please read the [Installation](doc/installation.md) guide.

Once the installation has been completed, you can access the website via the following URL: `http://127.0.0.1/clean-blog-drupal/web`.

Login via the following URL `http://127.0.0.1/clean-blog-drupal/user/login` in order to access the Drupal back office.
You can use the following accounts:

- Administrator:
  - Username: admin
  - Password: admin
- Content editor:
  - Username: contenteditor
  - Password: contenteditor

## Development

### Coding Standards

Fix coding standards in custom modules or themes by running the following commands.

#### Check Drupal best practices
```
$ ./vendor/bin/phpcs --standard=Drupal --extensions=php,module,inc,install,test,profile,theme,css,info,txt,md,yml /path/to/drupal/custom_module_or_theme
```

#### Automatically fix coding standards
```
$ ./vendor/bin/phpcs --standard=Drupal --extensions=php,module,inc,install,test,profile,theme,css,info,txt,md,yml /path/to/drupal/custom_module_or_theme
```

For further information about the usage of PHP CodeSniffer, please see [PHP CodeSniffer - Command Line Usage](https://www.drupal.org/docs/contributed-modules/code-review-module/php-codesniffer-command-line-usage).
