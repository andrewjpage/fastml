This repository provides some additional functionality to fastml to allow it to work with Gubbins.
The original code is available from http://fastml.tau.ac.il/source.html and should be your first port of call.
To modify the original code, or use parts of it for other purposes, permission should be requested. Please contact Tal Pupko: talp@post.tau.ac.il

In citing the FASTML server please refer to:

Ashkenazy H, Penn O, Doron-Faigenboim A, Cohen O, Cannarozzi G, Zomer O, Pupko T. 2012
FastML: a web server for probabilistic reconstruction of ancestral sequences 
Nucleic Acids Res. 40(Web Server issue):W580-4. [pdf] [abs] 


Pupko T, Pe'er I, Hasegawa M, Graur D, Friedman N. 2002
A branch-and-bound algorithm for the inference of ancestral amino-acid sequences when the replacement rate varies among sites: Application to the evolution of five gene families. 
Bioinformatics 18(8): 1116-1123. [pdf] [abs] 


Pupko T, Pe'er I, Shamir R, Graur D. 2000.
A fast algorithm for joint reconstruction of ancestral amino-acid sequences.
Mol. Biol. Evol. 17(6): 890-896. [pdf] [abs] 


Pupko, T. and Pe'er I. 2000.
Maximum likelihood reconstruction of ancestral amino-acid sequences.
Currents in Computational Molecular Biology. Ed. Miyano, S., Shamir, R, and Takagi, T. pp. 184-185. Universal Academy Press, Tokyo, Japan. [pdf]

#To install from source:
```
autoreconf -i
./configure
make
make install
```

#To install on Ubuntu (trusty):
```
sudo apt-get-repository ppa:ap13/gubbins
sudo apt-get update
sudo apt-get install fastml2
```
