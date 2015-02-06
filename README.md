# Composer demo package zip

## How load the library using source

```
{
    "repositories": [
        {
            "type": "package",
            "package": {
                "name": "demo/jquery",
                "version": "2.1.3",
                "source": {
                    "url": "https://github.com/jquery/jquery.git",
                    "type": "git",
                    "reference": "origin/master"
                },
            "autoload": {
                }
        }
    ],
    "require": {
        "demo/jquery": "2.1.3"
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
    ],
    "require": {
        "demo/jquery-zip": "dev-master"
    }
}
```
