# Compiler_miniML
## Version 1
Le but est d'apprendre à écrire un interpréteur (sémantique dynamique)
pour un langage à partir de l'arbre abstrait des programmes.

Le principe de cet interpréteur et les structures de données associées
ont été présenté en cours.

L'objectif est d'implanter ces règles en exploitant les
structures de données proposées.
L'arbre abstrait est décrit par le type ast dans le fichier Ast.ml.

Un fichier dune est fourni pour compiler et exécuter les tests. Vous utiliserez donc la commande habituelle :

" dune runtest "

## Version 2
Le but est d'introduire dans l'interprete,
les aspects impératifs du MiniML (reference, affectation, séquence
d'instructions) ainsi que le typage des expressions.

Les règles d'inférence sans mémoire sont dans la verion 1 et avec mémoire 
dans cette verion, et le code Caml dans 'Semantics.ml'. 
