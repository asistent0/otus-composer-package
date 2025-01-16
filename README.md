# Процессор строк

Краткое описание проекта

## Требования

- PHP 8.2

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