This repo contains data on extended named entites (XNE) discussed in the 3rd chapter of the thesis of Noémi Ligeti-Nagy (The Right Edge of the Hungarian NP -- A Computational Approach. Pázmány Péter Catholic University, Doctoral School of Linguistics. Submitted in 2021)

The strings in the files are all retrieved from Szeged Treebank 2.0 (Csendes, Dóra; Csirik, János; Gyimóthy, Tibor; Kocsor, András 2005: The Szeged Treebank. In: Matoušek, Václav et al. (eds.): Proceedings of the 8th International Conference on Text, Speech and Dialogue (TSD 2005), Karlovy Vary, Czech Republic, September 12-16, 2005, Springer LNAI 3658, pp. 123-131.).

all_NOUN+NOUNs: list of all word combninations retrieved from the corpus. These are noun + noun pairs, where both are tagged as the members of the same noun phrase.

all_names: list of all extended named entities retrieved from the list "all_NOUN+NOUNs" by a manual filtering

XNEs_Szeged_lemmas_freq: The complete list of the lemmas of the names (the tokens *St. Antonio herceg-nek* 'St. Antonio prince-Dat' and *St. Antonio herceg* 'St. Antonio prince' are one type) in a frequency order. The list contains 902 types. 

XNEs modified: list of extended named entities that consist of one or more proper nouns and a common noun and its modifier.

endings_lemma_sorted: List of the second parts of XNEs, the common noun, sorted by frequency. 

w2v_try: folder containing the results of my attempt to collect as many members to the different groups of XNE endings as possible. I retrieved the 100 closest words (according to the word embedding vectors of these words (see Siklósi, B., and Novák, A. (2016a). Beágyazási modellek alkalmazása lexikai kategorizációsfeladatokra \[Using word embedding models for lexical categorization\]. In A. Tanács,V. Varga, and V. Vincze (Eds.) XII. Magyar Számítógépes Nyelvészeti Konferencia (MSZNY 2016), (pp. 3–14).) to the members of the different categories (*néven*, geographical common nouns, courtesy formulas, occupations, institution names and brand names and products). Then I used a clustering and visualisation tool (Novák, A., Siklósi, B., and Wenszky, N. (2017). Szóbeágyazási modellek vizualizációjára és böngészésére szolgáló webes felület \[Online interface for the visualization and browsingof word embedding models\]. In XIII. Magyar Számítógépes Nyelvészeti Konferencia, (pp. 355–362).) to group the results. 
