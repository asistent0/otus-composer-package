# Процессор строк

Краткое описание проекта

## Требования

- PHP 7.0

## Установка

```sh
    composer require konstantin-rudenko/otus-composer-package
```

## Использование
 
```php
    <?php
    
    $calc = new \KonstantinRudenko\OtusComposerPackage\CalculateCube();
    echo $calc->getCube(2); // 8
```