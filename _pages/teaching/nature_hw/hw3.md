---
layout: default 
title: Nature inspired algorithms - HW 3
permalink: /teaching/2023_2024_inspinature_hw3/
---
(scroll down for English)

# Vehicle routing problem
## Deadline - 28. května 2024 (23:59 UTC+2)
Vaším úkolem bude vyřešit takzvaný Vehicle Routing Problem (VRP) pomocí algoritmu Ant Colony
Optimization. VRP je ve své podstatě jen jakýmsi zobecněním problému obchodního cestujícího, kde
cílem je optimalizovat dodání zásilek pro nějakou poštovní společnost. Máme dány sklady, každý s
vlastními příslušnými vozidly s danou kapacitou, která začínají a nutně i končí cestu v daném
skladě, a množinu zásilek, které musejí být doručeny jejich adresátům. Úkol je pak najít takovou 
množinu doručovacích tras, že *všechny* zásilky jsou doručeny svým adresátům, a že celková cena 
těchto tras je co nejmenší - tedy že je využito co nejméně rozvážkových vozidel a cesty jsou co 
nejkratší.

V rámci tohoto úkolu budeme uvažovat zjednodušenou verzi tohoto problému, kde máme pouze jeden 
centrální sklad a neomezeně identických vozidel. Optimalizovat budete tři instance tohoto problému, 
které dostanete jako [soubory v XML formátu](/assets/zips/inspinature/hw3.zip) - dvě malé instance
a jednu větší. Každý vstupní soubor obsahuje následující:

- Seznam uzlů s příslušnými koordináty x a y určujícími jejich pozici ve světě. Uzel typu 0 je sklad, 
  ostatní uzly s typem 1 jsou lokace zákazníků.
- Seznam vozidel (v našem případě jediný typ vozidla), spolu s jejich příslušností k danému skladu 
  a kapacitou, kterou jsou schopny uvézt najednou.
- Seznam požadavků zákazníků, respektive zásilek, které je nutno doručit do jejich místa určení.

**Své řešení mi pošlete na mail.** Měli byste uvést následující:

- Popis toho, jak jste adaptovali zdrojové kódy ze cvičení na vyřešení tohoto problému
- Kód algoritmu + instrukce k spuštění
- Grafy konvergence algoritmu pro všechny tři vstupy
- Nejlepší nalezená řešení pro všechny instance


# Vehicle routing problem
## Deadline - 28th May 2024 (23:59 UTC+2)

Your task will be to solve the so-called Vehicle Routing Problem (VRP) using the Ant Colony
Optimization algorithm. VRP is essentially a generalization of the traveling salesman problem,
where the goal is to optimize the delivery of shipments for a postal company. We are given depots,
each with their own respective vehicles with a given capacity, which start and necessarily end 
their journey at the depot, and a set of shipments that must be delivered to their recipients.
The task is to find a set of delivery routes such that *all* shipments are delivered to their 
recipients, and the total cost of these routes is minimized - that is, as few distribution
vehicles are used as possible, and the routes are as short as possible.

In the context of this task, we will consider a simplified version of this problem, where we have
only one central depot and an unlimited number of identical vehicles. You will optimize three
instances of this problem, which you will receive as files in
[XML format](/assets/zips/inspinature/hw3.zip) - two small instances and one larger instance.
Each input file contains the following:

- A list of nodes with their respective x and y coordinates determining their position in the world. A node of type 0 is the depot, and the other nodes of type 1 are customer locations.
- A list of vehicles (in our case, only one type of vehicle), along with their home depot and capacity.
- A list of customer demands (shipments), that must be delivered to their destination.

**Send your solution to me by email.** You should provide the following:

- Description of how you adapted the source code from the practicals to solve this problem
- Algorithm code + instructions for running it
- Convergence graphs of the algorithm for all three inputs
- Best solutions (found using the algorithm) for all three instances
