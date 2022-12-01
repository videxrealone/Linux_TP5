# Linux_TP5
---

## Exercice 1: Ls filters

![image](https://user-images.githubusercontent.com/91763346/204003872-38e6e47f-e770-48b9-80d5-9bf8a82cfebd.png)

* **se terminant par 5**

![image](https://user-images.githubusercontent.com/91763346/204004413-fd98faf4-b21e-40c9-8ef3-cf7baaa0c459.png)

* **commençant par annee4**

![image](https://user-images.githubusercontent.com/91763346/204004454-22fc3242-6d2e-45c6-9854-44bfecee2b5f.png)

* **commençant par annee4 et de 7 lettres maximum**

![image](https://user-images.githubusercontent.com/91763346/204004500-3ea36272-31e0-4af0-84b8-30ef85ae962f.png)

* **commençant par annee dont le 6 ème caractère n’est pas un chiffre numérique**

![image](https://user-images.githubusercontent.com/91763346/204004843-5d2aa401-49c1-47c9-bc3a-f17a6166ecfd.png)

* **contenant la chaine ana**

![image](https://user-images.githubusercontent.com/91763346/204004933-c9050350-edd6-4d6d-b44a-e172c12af510.png)

* **commençant par a ou A**

![image](https://user-images.githubusercontent.com/91763346/204005022-fb004477-56bd-4d45-8bb0-4313e182a194.png)

* **dont l’avant dernier caractère est 4 ou 1**

![image](https://user-images.githubusercontent.com/91763346/204005162-815e06e6-e159-4fa3-b279-c1635810db86.png)

* **lister les fichiers cachés (c’est-à-dire ceux commençant par le caractère '.' situés dans votre répertoire personnel.**

![image](https://user-images.githubusercontent.com/91763346/204005886-dcb01c3d-32e3-4417-8283-d5b56bb43f91.png)

## Exercice 2 : Find

* **Après avoir consulté le guide de find à propos du critère -mtime, trouvez tous les fichiers du répertoire Ex2 modifiés au moins il y a deux mois (' 60 jours). Le critère -mtime est à connaître.**

![image](https://user-images.githubusercontent.com/91763346/204010053-29a8e846-66da-4cb8-8e2f-877bef250796.png)

* **Trouvez tous les fichiers du répertoire Ex2 modifiés au plus il y a deux mois et se terminant par .txt** 

![image](https://user-images.githubusercontent.com/91763346/204011459-102e79a1-ce29-4bf6-9f1b-2faa911d96e8.png)

* **Chercher tous les répertoires se trouvant sous aA36/** 

![image](https://user-images.githubusercontent.com/91763346/204011617-252a356d-d486-41ef-b8c1-9a477c43f7c5.png)

* **Trouvez tous les fichiers qui correspondent à des répertoires ou aux fichiers ordinaires ne contenant pas la chaîne .txt**

![image](https://user-images.githubusercontent.com/91763346/204013497-937ea251-fe4c-40ee-a998-3e0f2787a801.png)


* **Trouvez tous les fichiers dont les noms se commencent par un a ou un A suivi d’éventuellement quelques lettres ou chiffres et se terminant par un chiffre entre 3 et 6.**

![image](https://user-images.githubusercontent.com/91763346/204012734-c5be88a9-04db-4716-9924-351727ed7af3.png)

## Exercice 3: La commande GREP.
Téléchargez les archives Germinal.zip et Poesies.zip dans tp_grep. Décompressez les
archives ainsi téléchargées. Résoudre les questions suivantes à l’aide de la commande grep.

* **Dire si le mot soldat apparaît dans le fichier Verlaine2.txt. Si vous arrivez à afficher ce mot, faire apparaître les numéros de ligne (option -n).**

![image](https://user-images.githubusercontent.com/91763346/205153662-08a85258-52c3-4aa5-b4a1-8df3209a57d0.png)

* **Dire si le mot soldat apparaît dans d’autres fichiers du répertoire Poesies.**

![image](https://user-images.githubusercontent.com/91763346/205153917-c24055bc-fc4f-484b-ba99-f679f1901d87.png)

* **Lister les fichiers du répertoire Poesies ne contenant pas le mot soldat.**

![image](https://user-images.githubusercontent.com/91763346/205154923-b6808b9d-5f91-46a8-8a6f-fd97b2e69786.png)

* **La structure \(mot1\|\mot2\) permet de chercher plusieurs mots. En une seule ligne de commande rechercher les mots soleil et parfums dans le fichier Rimbaud.txt**

![image](https://user-images.githubusercontent.com/91763346/205155443-7001e648-cd3d-4f2c-ba70-2c15af2b97d0.png)

* **Dans combien de lignes la chaîne de caractères mine apparaît dans les fichiers du répertoire Germinal ?**

![image](https://user-images.githubusercontent.com/91763346/205157308-d89966da-a8f1-44b3-9f58-ae552bf3f01e.png)

* **La structure \<mot\> permet de délimiter les mots. Trouvez les occurrences du mot mine (au singulier) dans les fichiers zola1.txt, . . ., zola4.txt.**

![image](https://user-images.githubusercontent.com/91763346/205158305-bb4787ab-4e8d-427e-9078-9a243464bc10.png)

* **Dans combien de lignes les mots commençant par mine apparaissent-ils dans zola1.txt, . . ., zola5.txt ?**

![image](https://user-images.githubusercontent.com/91763346/205158459-5bdec386-0403-4fc7-8c62-49844d02939d.png)

* **Afficher le nombre de lignes blanches dans les fichiers du répertoire Germinal.**

![image](https://user-images.githubusercontent.com/91763346/205158877-b336d892-51c3-46b6-9e7a-c0e6c0556630.png)


## Exercice 4: Redirections & Pipes

* **Accèdez à tp5 et créez un fichier bonjour.txt en utilisant la commande
echo Bonjour > bonjour.txt.**

![image](https://user-images.githubusercontent.com/91763346/205160346-383319e0-c88e-4b37-8c73-9de3b924a03a.png)

* **Afficher le contenu de bonjour.txt par la commande cat.**

![image](https://user-images.githubusercontent.com/91763346/205160374-743605ad-379d-4530-8d98-5c9f65379200.png)

* **Taper > bonjour.txt, que fait cette commande ?**

![image](https://user-images.githubusercontent.com/91763346/205160444-a7747d13-d2a3-4918-b172-cde0b98170a9.png)

* **Quelle différence entre les 2 lignes de commandes suivantes ?**

```
echo Bonjour > bonjour . txt ; echo Bonjour > bonjour . txt
echo Bonjour > bonjour . txt ; echo Bonjour >> bonjour . txt

```
La premiere ( > ) va écraser le contenu du fichier bonjour.txt
la deuxieme ( >> ) va appender le mot "Bonjour" et ne va pas écraser le contenu du bonjour.txt

* **Redirigez la sortie de la commande ls -l dans le fichier sortie.**

![image](https://user-images.githubusercontent.com/91763346/205161072-e84c3f21-9aa6-4d3d-8f5b-5153000de90c.png)

* **Créez dans le même repertoire 10 fichiers fich1, . . ., fich10.**

![image](https://user-images.githubusercontent.com/91763346/205161663-50e537da-1e43-48cb-b0e5-5dd0723a3374.png)


* **Redirigez l’entrée de la commande grep sur le fichier sortie afin que grep affiche les lignes correspondant à fich2, fich4, fich8.**

![image](https://user-images.githubusercontent.com/91763346/205164168-01acb05a-a631-40a5-bdb1-90ee543a69b1.png)

* **Répétez la question précédente, mais cette fois en faisant une redirection de la sortie de grep dans le fichier sortie (sans écrasement du contenu de ce dernier).**

![image](https://user-images.githubusercontent.com/91763346/205164319-40daf1a5-4e78-4e89-bbef-7ddf02c3cf42.png)

* **Lancez la ligne de commande ls -l /dev .**

![image](https://user-images.githubusercontent.com/91763346/205164417-91c6374d-43ee-4e21-aeec-cafa9d337b0a.png)

* **À l’aide des tubes (ou pipe : | ) affichez le nombre de fichiers et répertoires de /dev.**

![image](https://user-images.githubusercontent.com/91763346/205164541-5260e652-c337-4be0-b0fa-a3d3bb0018eb.png)

* **Affichez le nombre de fichiers (sans les répertoires) de /dev.**

![image](https://user-images.githubusercontent.com/91763346/205165542-ff1a107d-d72d-4f6b-9a25-2bfc6c2e2e3f.png)

* **Affichez le nombre de fichiers, puis le nombre de liens symboliques dans le répertoire /bin.**

![image](https://user-images.githubusercontent.com/91763346/205166389-060935e8-66f7-4911-8285-fb2f26ccd01d.png)












