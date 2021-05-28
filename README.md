# AODV-AOMDV-comparison-ns3

Autor: Matúš Sabol

Bakalárska práca (Praktická časť)

Odolný prenos IoT dát využívajúci alternatívne metódy smerovania v hybridných mobilných sieťach.

KEMT FEI TUKE 2021

Tento repozitár obsahuje zdrojové kódy vypracovanej praktickej časti bakalárskej práce - Porovnanie protokolov AODV a AOMDV  pohľadu odolnosti komunikácie


Stručný opis suborov:

1. Súbor manet-routing-compare.cc obsahuje simulačný skript protokolu AODV pre simulátor NS-3 v jazyku C++.

2. Súbor finalsimulationRandom.cc obsahuje simulačný skript protokolu AOMDV pre simulátor NS-3 v jazyku C++.

3. Výsledky zo simulácie protokolu AODV sú zapisované do súboru manet-routing.output.csv

4. Vizulaziácia pre protokol AODV je vygenerovaná po spustení simulácie a uložená v XML formáte do súboru animation_AODV.xml

5. Výsledky zo simulácie protokolu AOMV sú zapisované do súboru outputSimulationRandom.csv

6. Vizulaziácia pre protokol AOMDV je vygenerovaná po spustení simulácie a uložená v XML formáte do súboru animation_AOMDV.xml

 
- Pre spustenie simulácie protokolu AODV je potrebné nainštalovať softvér NS-3 vo verzii ns3.32 a nakopírovať súbor manet-routing-compare.cc do zložky ns3.32/scratch

https://www.nsnam.org/releases/ns-3-32/

- Pre spustenie simulácie protokolu je potrebné nainštalovať softvér NS-3 vo verzii ns3.29 a nakopírovať súbor finalsimulationRandom.cc do zložky ns3.29/scratch

https://www.nsnam.org/releases/ns-3-29/
