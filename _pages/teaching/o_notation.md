---
layout: default 
title: O notace
permalink: /teaching/2021_2022_programming_algorithms/o_notation/
---
# O notace – náhradní úkol
[Zde](/assets/img/o_notace/new_assignments.pdf) najdete zadání pár cvičných
neřešených úloh + domácích úkolů, které můžete vyřešit a dostat body (pokud
jste nevyřešili původní úkol). Kdo má body z původního úkolu, může tyto úlohy
použít jako přípravu ke zkoušce.

Úlohy k procvičení (první část 1.-3.) se mnou můžete probírat přes mail nebo osobně,
v části 2. jsou úkoly které odevzdáte na body.

# O notace – příklady

## Důkaz - potvrzení platnosti tvrzení

- důležité je najít jedno konkrétní k a n0, ale definice může být splněna i pro jiná k a/nebo n0
- definice musí být splněna pro *všechna* n větší než n0, nestačí to ověřit jen pro naše k a n0 - musíme si být jisti,
  že to platí i pro všechna větší n.
- v příkladu ukazuju hodně formální důkaz, ale občas stačí k a n0 jen "tipnout"

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/o_notace/dukaz_easy.jpg" title="dukaz easy" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

## Důkaz - potvrzení platnosti tvrzení

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/o_notace/dukaz_tezsi.jpg" title="dukaz tezsi" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

## Vyvrácení tvrzení

- dokazuje se sporem
    - předpokládám, že to už pro nějaké *konkrétní* k a n0 platí - tj. nehledám je, ale snažím se to pro ně vyvrátit
    - cílem je upravit nerovnost tak, abych dostala spor
    - viz příklad na obrázku
         - spor je v tom, že n0 < n < k, ale zároveň jsme našli n, které je větší než n0, ale n > k,
           takže máme spor s nerovností z definice
         - tímto jsme tvrzení vyvrátili

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/o_notace/vyvraceni_easy.jpg" title="vyvraceni easy" class="img-fluid rounded z-depth-1" %}
    </div>
</div>


## Vyvrácení tvrzení
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/o_notace/vyvraceni.jpg" title="vyvraceni tezsi" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
