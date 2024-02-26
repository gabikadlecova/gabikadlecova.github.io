---
layout: default 
title: Nature inspired algorithms - HW 1
permalink: /teaching/2023_2024_inspinature_hw1/
---
(scroll down for English)

# Problém batohu
## Deadline - 9. dubna 2024 (23:59 UTC+2)

Je dána množina $$n$$ objektů s váhami $$w_i$$ a cenami $$c_i$$. Cílem v problému batohu je najít
takovou podmnožinu těchto objektů maximalizující kumulativní cenu (tedy součet cen objektů v této
podmnožině), že jejich společná váha (tedy součet vah objektů v podmnožině) je menší nebo rovna
zadanému limitu $$W$$.

Úkolem je implementovat evoluční algoritmus řešící tento problém. Můžete buď naprogramovat celý
algoritmus od začátku, nebo klidně využít něco z toho, co jsme implementovali na cvičeních.

Dostanete [čtyři soubory](/assets/zips/inspinature/hw1.zip) specifikující vstup. Každý z těchto
souborů obsahuje množství řádků. První řádek obsahuje dvě čísla, a to množství objektů $$n$$ a
kapacitu batohu $$W$$. Pak následuje $$n$$ řádků, na každém je cena $$c_i$$ a váha $$w_i$$ jednoho
objektu. Hodnoty na jednotlivých řádcích jsou odděleny mezerou.

Pro vstupní soubory `debug_10.txt` a `debug_20.txt` je kumulativní cena optimálního řešení 295,
respektive 1024. Této znalosti můžete využít ke kontrole korektnosti a k ladění své implementace.
Vaším cílem je pak najít řešení (kumulativní cenu podmnožiny) pro soubory `input_100.txt` a 
`input_1000.txt`.

**Řešení mi odevzdávejte na mail.** Vámi odevzdané řešení by mělo obsahovat:

- Popis algoritmu (kódování jedince, genetické operátory, způsob selekce etc.)
- Kód algoritmu + instrukce k spuštění
- Graf toho, jak se měnila fitness v průběhu generací
- Nejlepší řešení, které jste objevili (hlavně jeho cena)


# Knapsack problem
## Deadline - 9th April 2024 (23:59 UTC+2)
A set of $$n$$ objects is given with weights $$w_i$$ and prices $$c_i$$. The goal in the knapsack
problem is to find a subset of these objects that maximizes the cumulative price (i.e., the sum of
the prices of objects in this subset), such that their total weight (i.e., the sum of the weights
of objects in the subset) is less than or equal to a given limit $$W$$.

The task is to implement an evolutionary algorithm to solve this problem. You can either program 
the entire algorithm from scratch or use something we implemented in the exercises.

You will receive [four files](/assets/zips/inspinature/hw1.zip) specifying the input. Each of these
files contains several lines. The first line contains two numbers: the number of objects $n$ and 
the capacity of the knapsack $$W$$. Then there are $$n$$ lines, each containing the price $$c_i$$
and weight $$w_i$$ of one object. The values on individual lines are separated by a space.

For the input files `debug_10.txt` and `debug_20.txt`, the cumulative price of the optimal solution
is 295 and 1024, respectively. You can use this knowledge to check the correctness and debug your
implementation. Your goal is then to find the solution (cumulative price of the subset) for the
files `input_100.txt` and `input_1000.txt`.

**Submit your solution via email.** Your submitted solution should include:

- Description of the algorithm (encoding of individuals, genetic operators, chosen selection method, etc.)
- Algorithm code + instructions for running it
- Graph showing how fitness changed over generations
- The best solution you discovered (especially its price)