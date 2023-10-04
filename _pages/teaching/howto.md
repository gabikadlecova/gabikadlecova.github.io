---
layout: default 
title: Howto python
permalink: /teaching/2021_2022_programming_algorithms/howto/
---

## Návod na různé věci v pythonu

### Syntaxe a programování
Pokud si s nejste jisti, jak se něco píše v pythonu:
- Adam Dingle má na [svých stránkách](https://ksvi.mff.cuni.cz/~dingle/2021-2/prog_1/programming_1.html)
skvělé přehledy (sekce notes)
- Rychlý [přehled](https://learnxinyminutes.com/docs/cs-cz/python/)
- Odpovědi na všechny možné otázky najdete na [stackoverflow](https://stackoverflow.com)
   - Proč nefunguje VS code
   - Proč nefunguje něco v pythonu
   - Jak se programuje něco v pythonu
   - (jen to se stackoverflow nepřehánějte, když tam najdete celé řešení nějakého úkolu,
     nic se nenaučíte a na těžších úkolech budete ztraceni)

### Debugging a hledání chyb
Základním nástrojem je debugging - zde je
[návod](https://www.youtube.com/watch?v=w8QHoVam1-I) na debugging ve VS Code. Alternativou
je používat print() pro výpis hodnot v proměnných (ale není dobré to přehánět - mít v kódu spoustu printů).

Vytvoření vlastních vstupů - typicky hledám tzv. edge cases, tj. zvláštní vstupy,
při kterých se mi program rozbil, protože jsem na ně nemyslel/a. Pro úspěšné odhalení
bugu v programu je často důležité přijít na konkrétní příklad, který program rozbíjí,
protože pak můžeme použít debugging.

Časté příklady:
- Prázdné vstupní pole / string, pouze 1 hodnota
- Opakující se hodnoty / pouze jedna unikátní hodnota
- Hodnoty na indexu 0 nebo -1 (poslední)
- Vstupy nedělitelné nějakým číslem
- Velké nebo naopak hodně malé vstupy
- ...

