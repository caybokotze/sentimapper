# Sentimapper

## The Basic Idea
In essence the library is more or less a instance of a conventional based mapping tool with some added bonus features that do not need to be used if not required.

Sentimapper supports mapping entities by convention or by sentiment currently using the Levenshtein Distance Algorithm. I do personally want to look at a integration of Bayes Theorem to make the algorithm more efficient, however that will have to wait for now.

## Singleton Injection
To save time on computations you can inject the singleton of this project into your middleware which will implement a cache to save your mapping configurations.

## Levenshtein Distance Algorithm Definition

<a href="https://en.wikipedia.org/wiki/Levenshtein_distance">Read More about it here</a>
<img href="levenshtein-definition.png">

## Library Features
 - Map properties between models / classes by convention (Set as the default).
 - Map properties between models by sentiment (which takes a parameter.)
 - Cache your mapping results to save computational expense.
 - Just use your mapping. No need to declare it beforehand.
 - Compare the similarity of model data like name, surname, skillsets etc...
 
