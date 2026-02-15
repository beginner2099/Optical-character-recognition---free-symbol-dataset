# Optical-character-recognition---free-symbol-dataset
A repository that contains the files dataset.txt (a dataset containing  some  symbols) and labels.txt for the different labels. 
They are contained in the compressed files dataset.zip and labels.zip respectively. 
All the symbols are  originally grayscale images (the symbols are all the letters of the alphabet , the digits + somme additionnal symbols).
Each row of dataset.txt must be reshaped into a 64x64 array to visualize the symbol.
See dictionnary.txt to know what label is associated to what symbol.
There must be some neglectible mistackes on a few symbols. A weakness of the dataset comes from the rescaling (into 64x64 images) that make the symbols 'i' and 'l' difficult to spot a difference.



Un dossier contenant les fichiers dataset.txt et labels.txt respectivement les symboles et labels.txt pour les labels.
Ils sont contenus dans les fichiers compressés dataset.zip et labels.zip.
Tous les symboles proviennent d'images noir et blanc (les symboles sont toutes les lettres de l'alphabet, les chiffres + quelque autres symboles).
Voir disctionnary.txt pour savoir quel symbole est associé à quel label
Chaque ligne du dataset doit être reshaped en tableaux 64x64 pour visualiser le symbole.
Il peut y avoir quelques erreurs de labelisation (négligeables). Une faiblesse du dataset provient du fait du rescaling en images 64x64, le symbole 'i' et le symbole 'l' sont difficiles à différencier.
