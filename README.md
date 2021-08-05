# **Introdução a testes unitários**

## Executar Testes
    
    ./vendor/bin/phpunit tests

## Code Coverage ##

    vendor/bin/phpunit --whitelist src/ --coverage-text tests/
    vendor/bin/phpunit --whitelist src/ --coverage-html cover/ tests/
