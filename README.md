# Di-Higgs-Graph-Dataset
Manipulate collision events from the di-Higgs production.

Each event is a graph with 5/6 nodes. Each node is built from the raw file as follows:
     | Particle          | Feature 1 | Feature 2 | Feature 3   |
     |-------------------|-----------|-----------|-------------|
     | tau               |  'pTt1'   | 'etat1'   |   'phit1'   |
     | lepton            |  'pTl1'   | 'etal1'   |   'phil1'   |
     | b1                |  'pTb1'   | 'etab1'   |   'phib1'   |
     | b2                |  'pTb2'   | 'etab2'   |   'phib2'   |
     | ETMiss            |  'ETMiss' | 'nan'     |  'ETMissPhi'|
     | jet               | 'pTj1'    |   etaj1   |   'phij1'   |
