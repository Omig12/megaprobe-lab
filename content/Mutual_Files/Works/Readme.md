Read me:
=======

_This Readme file is aimed at helping in the reproduction of the technical report <https://www.sharelatex.com/project/574b21300c338a4e5406de46>._

#### Suggested Reads:
* Heuristics Pairwise Alignment utilizing de Bruijn graphs to recover shared transcripts.
* Velvet Manual

#### Needed files:

- Install FastQC
- Install Scythe
- Install Sickle
- Install Velvet
- Install Oases
- Install Blast
- Install Mutual
- Install Bandage


#### Useful Shell scripts contained in repository:
- data\_prep.sh  _(Help's with the quality control by edge trimming and removing adapters, using scythe and Sickle)_ 
- mutual.sh      _(Aid's the preparation of the necesarry set up to run mutual by specifing the working enviorement)_
- LGParser.py    _(Parses LastGraph file and returns a folder filled with the connected components contained in the Graph)_
