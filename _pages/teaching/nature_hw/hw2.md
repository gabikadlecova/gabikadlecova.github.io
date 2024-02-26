---
layout: default 
title: Nature inspired algorithms - HW 2
permalink: /teaching/2023_2024_inspinature_hw2/
---
(scroll down for English)

# Zpětnovazební učení s využitím neuroevoluce
## Deadline - 14. května 2024 (23:59 UTC+2)
Vyberte si pár (dvě až tři) prostředí z knihovny [gymnasium](https://gymnasium.farama.org) (tuto knihovnu jsme používali na druhých
cvičeních) a vyřešte je za pomoci neuroevoluce. Vaším úkolem je tedy integrovat zpětnovazební učení
a neuroevoluci a otestovat výsledek na zvolených prostředích.

Doporučuji vybrat některá prostředí z Classic Control nebo Toy Text skupin, ale pokud hledáte výzvu, můžete zkusit i
některá prostředí ze skupiny Box2D nebo MuJoCo (např. prostředí LunarLander, Hopper a Swimmer by
měla jít vyřešit, ale určitě nedoporučuji třeba prostředí Humanoid, či snad dokonce Humanoid
Standup).

Co se volby algortimu týče, můžete vyzkoušet NEAT (nebo libovolný podobný algoritmus, o kterém se
někde dočtete), nebo klidně i jen vyvíjet vektor vah fixní topologie sítě, volba je na vás.

Pro vyhodnocení navrženého algoritmu je potřeba pustit jej pro více běhů s různými random seedy.
Best practices pro design experimentů si probereme na některém ze cvik.

**Řešení mi odevzdávejte mailem**, ten by měl obsahovat:

- Seznam prostředí, která jste vyzkoušeli
- Popis algoritmu spolu s jeho nastavením (hyperparametry, apod.)
- Kód algoritmu + instrukce k spuštění
- Grafy toho, jak se měnil výkon nejlepšího jedince v průběhu generací


# Reinforcement learning using neuroevolution
## Deadline - 14th May 2024 (23:59 UTC+2)

Choose a few (two to three) environments from the [gymnasium](https://gymnasium.farama.org) library
(we used this library in the second labs) and solve them using neuroevolution. Specifically, your
task is to integrate reinforcement learning and neuroevolution and test the result on the selected
environments.

I recommend selecting some environments from the Classic Control or Toy Text groups, but if you're
looking for a challenge, you can also try some environments from the Box2D or MuJoCo groups
(for example, environments like LunarLander, Hopper, and Swimmer should be solvable, but I
definitely don't recommend environments like Humanoid or Humanoid Standup).

As for the choice of algorithm, you can try NEAT (or any similar algorithm you find elsewhere), or
you can simply evolve the weight vector of a fixed network topology; the choice is yours.

To evaluate the proposed algorithm, it needs to be run multiple times with different random
seeds. We will discuss best practices for designing experiments in one of the practicals.

**Submit your solution via email**, which should include:

- List of environments you tried
- Description of the algorithm along with its settings (hyperparameters, etc.)
- Algorithm code + instructions for running it
- Graphs showing the performance of the best individual over generations
