# Osint-APTtool
<figure><img src="https://cdn.discordapp.com/attachments/1311292098405863446/1311692585252818944/image.png?ex=6749c86a&is=674876ea&hm=a83f85b73cd42ccfc98f2fb9717061a70a479cf26a2db7dac733c6da74f87485&" alt=""><figcaption></figcaption></figure>

APTtool est un outil OSINT robuste qui facilite les recherches rapides de comptes utilisateurs par nom d'utilisateur ou email sur une large gamme de plateformes, améliorant ainsi les enquêtes numériques. Il propose une intégration avec WhatsMyName, des options d'exportation au format PDF, CSV et HTTP, ainsi que des filtres de recherche personnalisables.

## Configuration

## Cloner le dépôt
`git clone https://github.com/GupS3c/Osint-APTool.git
cd APTool`
 
###Assure-toi d'avoir Python et venv installés
Vérifie si tu as Python installé sur ton système avec cette commande :


`python3 --version
`

ou 


`python --version`


i Python est installé et que tu n'as pas venv, tu peux l'installer avec cette commande :

Sur Ubuntu/Debian :



`sudo apt-get install python3-venv`

Sur Windows :
`venv est inclus par défaut avec les versions récentes de Python. Si tu rencontres des problèmes, assure-toi que Python est correctement ajouté à la variable d'environnement PATH.`

2. Créer un environnement virtuel
Accède au répertoire où tu souhaites créer ton environnement virtuel et exécute cette commande :


`python3 -m venv nom_de_l'environnement`

 Example :


 `python3 -m venv .venv`












### Ensuite activer votre environnement virtuel 


Sur Linux/MacOS :

`source .venv/bin/activate`


Sur Windows :

`.venv\Scripts\activate`








### Installer les dépendances 


Avec l'environnement activé, installe les dépendances nécessaires pour ton projet. Si tu as un fichier requirements.txt, tu peux l'utiliser pour installer les paquets requis :

`pip install -r requirements.txt`















# Utilisation

Rechercher par nom d'utilisateur 


`python3 APTool.py --username username1 username2 username3 `









### Rechercher par email 


`python3 apttool.py -e  ./ -e [EMAIL ...], --email [EMAIL ...] `

### Exporter les résultats en PDF



`python3 APTool.py --email email1@email.com --pdf`



 ##  🐸  IA

## APTtool utilise des modèles NER alimentés par l'IA pour améliorer l'extraction des métadonnées, identifiant les entités clés pour des informations plus rapides et plus précises.


`python3 APTool.py --username username1 --ai
` 




### Disclaim 





"Ce programme ou les précédents sont destinés à des fins éducatives UNIQUEMENT. Ne l'utilisez pas sans autorisation.
L'avertissement habituel s'applique, notamment le fait que moi (P1ngul1n0) ne suis pas responsable de tout
dommage causé par l'utilisation directe ou indirecte des informations ou de la fonctionnalité fournie par ces
programmes. L'auteur ou tout fournisseur d'accès Internet ne porte AUCUNE responsabilité pour le contenu ou la mauvaise utilisation
de ces programmes ou de leurs dérivés. En utilisant ces programmes, vous acceptez le fait
que tout dommage (perte de données, plantage système, compromission système, etc.) causé par l'utilisation de ces
programmes n'est pas de la responsabilité de GupS3c. 
"
