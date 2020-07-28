# PolysemyTheories
All resources are published under the CC-BY 4.0 licence (https://creativecommons.org/licenses/by/4.0/).\
Copyright (c) 2020, Francis Bond, Marek Maziarz and Ewa Rudnicka. All rights reserved.\

Description of resources:

1) LEX-MW-merged-graph-distances.txt\
Description: The presented data were obtained through merging information on 25 sample words from two online English dictionaries (Lexico, www.lexico.com, and Merriam-Webster, www.merriam-webster.com). Macro- and microstructures from the dictionaries were manually transformed into graphs, then distances between pairs of WordNet senses in each graph were calculated. We present only the distance information.

    Symbols:\
    lemma - is a sampled word\
    sense1 - first sense from a given pair\
    sense2 - second sense from a given pair\
    distLEX - Dijkstra's distance calculated on Lexico graph\
    distMW - Dijkstra's distance calculated on Merriam-Webster graph\
    distOpti - averaged distance\
    syn1 - synset identifier in WordNet 3.0 for the first sense\
    syn2 - synset identifier in WordNet 3.0 for the second sense\


2) Mapping files

    Symbols:\
    PWNsynset - mapped WordNet sense\
    choiceE - the choice of the E annotator\
    choiceM - the choice of the M annotator (they are the same after the third phase of annotation process)\
    LEXsense - a target sense from Lexico\
    MWsense - a target sense from Merriam-Webster\
    EG - an etymology group\
    sup - a superordinate sense number\
    subno - a subordinate sense number\

3) No POS split files

    File names:\
    EX - the exemplar algorithm\
    LO - the locally chaining algorithm\
    NN - the nearest-neighbor chaining algorithm\
    PP - the prototype algorithm\
    PR - the progenitor algorithm\
    RA - the random algorithm\
    "comparison" - these files contain a comparison between dictionaries and joint polysemy nets for 25 sample words\
    "joint-polysemy-nets" - these files comprise sense edges from joint polysemy networks\
    "25words" - only nets for 25 sample words\
    "allWN" - all polysemy nets for WordNet polysemous words\
    
    3a) Comparison files\
    Symbols:\
    lemma - base word form\
    sense1, sense2 - WordNet senses\
    syn1, syn2 - WordNet 3.0 synset identifiers\
    distLEX - distances calculated on the Lexico graph\
    distMW - distances calculated on the Merriam-Webster graph\
    distOpti - merged measure\
    distances - distances calculated on joint polysemy networks\


    3b) Polysemy network files\
    Symbols:\
    lemma - base word form\
    syn1, syn2 - WordNet 3.0 synset identifiers\
    dist - distance calculated on WordNet graph (the shortest path length)\
    sim - similarity measure calculated as the inverse of the squared dist measure plus one, i.e., sim = 1/(dist^2+1)\


4) POS split files

    The files with POS split were marked with analogical symbols as no POS split files.





