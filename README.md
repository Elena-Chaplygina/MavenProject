## Запуск тестов

- все тесты

```
mvn test
```

- только тесты из модуля «api-tests»

```
mvn test -pl api-tests
```

- только тесты из модуля «ui-tests»

```
mvn test -pl ui-tests
```

- только Smoke-тесты обоих модулей (по тэгу «smoke»)

```
mvn test -Dtest=* -Dgroups=smoke
```