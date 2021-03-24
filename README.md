# CryptageHomomorphe
Description : Un schéma de chiffrement complètement homomorphe permet à tout participant de transformer de façon publique un ensemble de chiffrés (correspondant à des clairs x1, …, xn) en un chiffré correspondant à une certaine fonction (resp. circuit) f(x1, …, xn) des clairs, sans que ce participant connaisse les clairs eux‐mêmes. Un tel schéma peut servir à construire des protocoles respectant la vie privée (privacy‐ preserving) : un utilisateur peut stocker des données chiffrées sur un serveur, et autoriser le serveur à effectuer des opérations sur les données chiffrées, sans avoir à révéler les données elles‐mêmes au serveur. Le travail consistera ici à implémenter entièrement l’algorithme de chiffrement homomorphe de van Dijk, Gentry, Halevi et Vaikuntanathan [1] puis à le faire fonctionner entre un client et un serveur.   Selon le nombre d’étudiants participant au projet pourront aussi être considérés l’implémentation d’une méthode de cryptanalyse (dite de PGCD approché), permettant de choisir les bonnes tailles de clé, ainsi que l’utilisation d’une technique de chiffrement hybride pour limiter la bande passante nécessaire entre le client et le serveur. [1] M. van Dijk, C. Gentry, S. Halevi and V. Vaikuntanathan, "Fully Homomorphic Encryption over the Integers". Proceedings of Eurocrypt 2010.