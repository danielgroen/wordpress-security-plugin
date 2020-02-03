# Must use security plugin for WordPress

add the following code in your packagist `composer.json` file under the object `repositories`:

```json
  {
    "type": "package",
    "package": {
      "name": "danielgroen/wordpress-security-plugin",
      "version": "1.0",
      "type": "wordpress-muplugin",
      "source": {
        "type": "git",
        "url": "git@github.com:studio-fonkel/mu-plugin-security.git",
        "reference": "master"
      }
    }
  },
```

and now install the package by typing:

``` bash
$ composer require danielgroen/wordpress-security-plugin;
```
