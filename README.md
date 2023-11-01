# Diplom_1

Учебный проект по покрытию кода Unit тестами.

## Описание

Версия Java 11.

Проект использует следующие библиотеки:

* JUnit 4
* Mockito
* Jacoco

### Запуск Unit тестов

Для запуска тестов необходимо:

Скачать код
git clone https://github.com/Misteriya89/Diplom_1.git

### Для создания отчета в Jacoco ввести команду

**mvn clean verify**

Отчет будет находиться в target/site/jacoco/index.html

### Структура проекта

```
src
|-- main
|   |-- java
|   |   |-- praktikum
|   |   |   |-- Bun.java
|   |   |   |-- Burger.java
|   |   |   |-- Database.java
|   |   |   |-- Ingredient.java
|   |   |   |-- IngredientType.java
|   |   |   |-- Praktikum.java
|-- test
|   |-- java
|   |   |-- BunParameterizedTest.java
|   |   |-- BunTest.java
|   |   |-- BurgerMockTest.java
|   |   |-- IngredientParameterizedTest.java
|   |   |-- IngredientTest.java
.gitignore
pom.xml
README.md
```
