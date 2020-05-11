# Sentimapper

## The Basic Idea
In essence the library is more or less a instance of a conventional based mapping tool with some added bonus features that do not need to be used if not required.

Sentimapper supports mapping entities by convention or by sentiment currently using the Levenshtein Distance Algorithm. I do personally want to look at a integration of Bayes Theorem to make the algorithm more efficient, however that will have to wait for now.

## Singleton Injection
To save time on computations you can inject the singleton of this project into your middleware which will implement a cache to save your mapping configurations.

## Levenshtein Distance Algorithm Definition

<img href="levenshtein-definition.png">

