Gentelella based Gii CRUD template generator
==================

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist zgb7mtr/yii2-gii-crud-gentelella "*"
```

or add

```json
"zgb7mtr/yii2-gii-crud-gentelella": "1.0.0"
```

to the require section of your composer.json.

To use this template, add to main config in gii section following code:

```php
    'gii' => [
            ...
            'generators' => [ //here
            'crud' => [ // generator name
                'class' => 'yii\gii\generators\crud\Generator', // generator class
                'templates' => [ //setting for the templates
                    'Gentelella' => '@vendor/zgb7mtr/yii2-gii-crud-gentelella/src',
                ]
            ]
            ....
        ],
```
Changing "Code Template" to Gentelella in Gii Generator panel.
