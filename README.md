# Hidden-Markov-Model
Salut les loulous, c'est le github qui concerne la projet prog, travaillez bien ! ;)

Pensez à jeter un oeil au PEPS ainsi qu'au tutoriel numpy, comme ça on sera encore plus fort ! : 

https://www.python.org/dev/peps/

https://docs.scipy.org/doc/numpy-dev/user/quickstart.html

Allez zou au travail ! 



Voici ce qu'il faudrait faire :


2. On définit un format de fichier texte pour mémoriser des HMMs :


" # The numbers of letters
2
" # The numbers of states 
2
" # The initial transitions
0.5
0.5
" # The internal transitions
0.9 0.1
0.1 0.9
" # The emissions
0.5 0.5
0.7 0.3


 Écrivez la méthode statique load(adr) qui permet de charger un
 HMM à partir d’un fichier texte au format ci-dessus. On pourra
 supposer que toutes les lignes commençant par le caractère # sont
 ignorées.

 3. Écrivez la méthode gen rand(self, n) qui génère aléatoirement une
 séquence de longueur n à partir d’un HMM. Indications : on pourra
 utiliser la méthode random du module random qui génère aléatoirement
 un nombre réel compris entre 0 et 1 ; ne pas oublier d’initialiser (une
 fois seulement) le générateur aléatoire à l’aide de la méthode seed() ;
 on pourra écrire une méthode statique draw multinomial(L) qui
 prend en entrée une liste (ou un np.array) dont les éléments sont po-
 sitifs et somment à 1, et retourne un indice de la liste (ou du tableau)
 selon le modèle multinomial correspondant.

 4. Écrivez la méthode save(self, adr): qui permet de sauver un HMM
 dans un fichier texte selon le format ci-dessus.

 5. Proposez une implémentation permettant de faire cohabiter les HMMs
 et les HMMs généralisés.
