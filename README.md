# Composer demo package zip

## How load the library using source

```
{
    "repositories": [
        {
            "type": "package",
            "package": {
                "name": "demo/jquery",
                "version": "dev-master",
                "source": {
                    "url": "https://github.com/jquery/jquery.git",
                    "type": "git",
                    "reference": "origin/master"
                },
            "autoload": {
                }
            }
        }
    ],
    "require": {
        "demo/jquery": "dev-master"
    }
}
``` 

## How load the library using zip

```
{
    "repositories": [
        {
            "type": "package",
            "package": {
                "name": "demo/jquery-zip",
                "version": "dev-master",
                "dist": {
                    "url": "https://github.com/jquery/jquery/archive/master.zip",
                    "type": "zip"
                },
            "autoload": {
                }
            }
        }
    ],
    "require": {
        "demo/jquery-zip": "dev-master"
    }
}
```
