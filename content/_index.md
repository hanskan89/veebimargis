---
title: 'Veebienergiamärgis'
date: 2018-11-28T15:14:39+10:00
---

Energia hinnad on kõrgemad kui varem ja paljud tahavad energiat säästa. Selleks on vaja ülevaadet, kuhu see täpselt kulub. Pole raske mõõta, kui palju elektrit kulub arvuti töös hoidmiseks või telefoni laadimiseks. Aga mida me selle energiaga arvutis teeme?

Internetti sirvides võtavad selle energia meilt ära veebilehtede tegijad. Mõned veebilehed on tehtud energiasäästlikult, teised aga käituvad meie seadmetes nagu rehepapp mõisa aidas.

See projekt hindab Eesti levinumate veebilehtede energiakasutuse jalajälge.



## Top lehed: uudised

{{< table "static/data/top-uudised.json" >}}

## Top lehed: teenused, varia

{{< table "static/data/top-varia.json" >}}


{{< card title="Kuidas tabelit lugeda?" >}}Mida kõrgem on näitaja "CPU kasutus", seda energiat raiskavam on veebileht.{{< /card >}}

## Metoodika

Kuidas tabel koostatakse?

1. Võtsime valimisse Eesti enimkülastatuimad veebilehed Gemiuse ja [station.ee](https://metrix.station.ee) andmete põhjal.
2. Mõõdame ...
3. 
4. Tulemusi uuendatakse kord nädalas.

Viimane uuendus: 22.02.2022.

{{< badge text="kehv" color="orange" >}}
{{< badge text="halb" color="red" >}}
{{< badge text="hea" color="green" >}}
{{< badge text="uus info" >}}
