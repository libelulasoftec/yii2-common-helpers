Helpers
=======
Common helpers para yii2 y mongodb

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
composer require libelulasoft/yii2-common-helpers
```

or add

```
"libelulasoft/yii2-common-helpers": "~1.0.0"
```

to the require section of your `composer.json` file.

Migration
-----

Si se quiere migrar de la version `taguz91/yii2-common-helpers` a la nueva version `libelulasoft/yii2-common-helpers` se debe seguir los siguientes pasos: 

1. Eliminar la version actual

```
composer remove taguz91/yii2-common-helpers
```

2. Instalar la nueva version 

```
composer require libelulasoft/yii2-common-helpers
```

3. Se debe cambiar el namespace `taguz01\CommonHelpers` a `Libelulasoft\CommonHelpers` en todo el proyecto.

4. Probar que todo funcione de forma correcta.

Usage
-----
