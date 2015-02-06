# Composer demo package composer zip

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
        }
    ],
    "require": {
        "demo/jquery": "2.1.3"
    }
}
```
