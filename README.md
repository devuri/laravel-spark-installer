# Laravel Spark Installer
install laravel spark

## # 1: Laravel Installer.
 Before getting started, make sure you have the laravel/installer package globally installed using Composer.
```bash
composer global require laravel/installer
```

## Step 2: Add Laravel Installer globally
```bash
export PATH="~/.config/composer/vendor/bin:$PATH"
```

## # 3: Spark installer
clone the laravel/spark-installer repository from GitHub into any location on your machine.
```bash
git clone https://github.com/laravel/spark-installer.git
```

## # 4: Spark installer Dependencies
Once you have cloned the installer, be sure to run the composer install command within the cloned directory so the installer's dependencies will be installed.
```bash
composer install
```

## # 5: Add Spark to the $PATH variable
Next, make sure the spark-installer directory is added to your systems $PATH variable, so that your machine will be able to locate the spark executable when you issue Spark commands.
```bash
export PATH=$PATH:$PWD 
```

## # 6: Try Laravel Spark Installer
You can test this by typing  the spark in the command. This should give you back some information like the usage information version number etc
```bash
spark
```

## # 7: Registering Your API Token
Now that you have the Spark installer, you need to register your Spark API token with the installer. You may create an API token from the API settings dashboard. Once you have created a token, register it with the installer using the register command:
```bash
spark register token-value
```

## # 8: Check Token
If you would like to view the currently registered token, you may use the token command:
```bash
spark token
```
