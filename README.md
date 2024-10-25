# FCSC 2023 Fibonacci

Cette fois, on vous demande de coder en assembleur la suite de Fibonacci.

La machine est initialisée avec une valeur ```n``` aléatoire (mise dans le registre ```R5```) 
et devra contenir (dans ```R0```) l’élément ```Fib(n)``` une fois le code exécuté. Pour rappel :

- ```Fib(0) = 0```,
- ```Fib(1) = 1```,
- ```Fib(n) = Fib(n - 1) + Fib(n - 2)```.

Le code machine (bytecode) sera envoyé sous un format hexadécimal, qu’on pourra générer à l’aide de 
l’assembleur fourni (fichier ```assembly.py```).

La documentation de la machine virtuelle est disponible sur cette page.


Fichiers:
- [assembly.py](assembly.py)
- [challenge.py](challenge.py)
- [machine.py](machine.py)


Auteur : Neige

Origine : [Fibonacci](https://hackropole.fr/fr/challenges/hardware/fcsc2023-hardware-asm-fibonacci/)


-----------

## Connectez vous en WEBSSH
> http://localhost

#### tentez 
> nc fibonacci.cyrhades.fr:4000

-----------

## Ou directement avec netcat
> nc localhost:4000


-----------


## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2023-hardware-asm-fibonacci.git

> cd fcsc2023-hardware-asm-fibonacci


-----------


## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/hardware/fcsc2023-hardware-asm-fibonacci/