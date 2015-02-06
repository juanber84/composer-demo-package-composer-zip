# Composer demo package composer zip

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
        "demo/php": "demo/jquery"
    }
}
