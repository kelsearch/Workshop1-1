# Workshop1 - Set up ton environnement 
👾Bienvenue pour ce premier workshop ;) 

🧵 Nous allons partir d’un fil rouge : déployer son premier smart contract sur Ethereum. Nous n’allons pas rentrer dans les détails technique, cela sera dans les prochains workshop. Pour l’instant, c'est au travers de notre premier smart contract, que nous allons installer tout les outils nécessaires pour développer sur différentes blockchain. 

## Pourquoi installer ces softwares, et logiciel ?
✔️ Gagner du temps 

✔️ Coder sur différentes blockchain : Ethereum, Algorand, Solana …

✔️ Suivre des tutos assez simplement car les programmes seront déjà installés

✔️ Utile pour les hackathons, mais aussi pour de futur opportunités ( mission de freelance, carrière dans le web3 en tant que dev … )

<details>
  <summary><h1>Installation des logiciels principaux</h1></summary>
  
  - Visual Studio Code
  
  Comme pour un peintre, il faut sa toile. La developeuse à besoin de son environnement de programmation pour coder.  Il en existe plein sur le marché, Sublim text, Vim ect …  
Mais Visual Studio Code à l’avantage de relier plusieurs application, tel que Github et d’être assez ergonomique. 
  https://visualstudio.microsoft.com/fr/downloads/
  
  - Installation de node js 
  
  NPM (Node Package Manager) est un gestionnaire de paquets permettant l’installation facile des modules (bibliothèques de code) qui peuvent être utilisés dans votre projet  
  [Node.js](https://nodejs.org/en/)
  ```bash
  npm -v 
  npm install <library-name> 
  npm run build 
  ```
  
  - Installation de yarn ( similaire à npm, c'est un gestionnaire de paquet, permettant l'installation des bibliothèques et des librairies).
  ```bash
  npm install yarn
  ```
  
  - Le terminal: déjà installer sur VS Code. Voici les commandes prinipales sur le terminal. 
  
  **`ls`**: affiche la liste des fichiers et des répertoires dans le répertoire courant
  
  **`cd`**: change de répertoire
  
  **`mkdir`**: crée un nouveau répertoire
  
  **`touch`**: crée un nouveau fichier vide
  
  **`rm`  :**  supprime un répertoire
  
  **`rm -r <nom du fichier>` :** supprime un fichier 
  
  **`echo`**: affiche du texte à l'écran
  
</details>
  
  
👉🏽 A partir de votre terminal, placez-vous dans le dossier “Document” . Puis, créée un nouveau dossier appelé “H.E.R DAO”

  
<details>
  <summary><h1>Les outils de la développeuse</h1></summary> 
  - Github : l'outils open source
  
  C'est LA plateforme permettant d'échanger du code entre dév, de stocker et de gérer notre code, ainsi que de travailler en collaboration sur des projets de développement de logiciels. 
  
Pour s'approprier un peu l'outil, nous allons forker le projet. Un fork c’est une copie d’un dépôt. Cette opération nous permettra de copier le projet sans le modifier. Le pont entre Github et notre éditeur de code (Visual Studio Code), sera GIthub Destkop 
  
  - Github Desktop : 
  [GitHub Desktop](https://desktop.github.com/)
</details>
👉🏽 Forker le projet Workshop1 dans votre ordinateur en local. 
1. Dans ton Github, ajoute un nouveau répertoire 
  
2. Clone le projet dans ton ordinateur en local 
  
3. Depuis GithubDesktop, ouvre Visual Studio Code. 
  
4. Done, tu as forker ton premier projet 🔆

<details>

  <summary><h1>Coder sur une blockchain</h1></summary>
Nous avons maintenant à peu près tous les outils dans notre trousse nous permettant de coder. Mais, chaque blockchain à un environnement et un langage bien spécifique. Par exemple Ethereum utilise le langage de programmation Solidity pour ces smarts contracts. Et nous allons explorer cela. Mais, Algorand par exemple, utilise un autre environnement de programmation, et nous verrons cela lors du prochain workshop. 
Pour le moment, voyons comment déployer un smart contract sur Ethereum. 

✌🏽 Pas de panique l'objectif n'est pas de tout comprendre, simplement de prendre en main les outils principaux. 
  
  - Installation de solidity sur VS CODE
  
  Dans extension, il est possible de télécharger les langages de programmations que l'on souhaite.
  
  - Installation de Hardhat 
  
  Pour écrire un smart contract, nous avons besoin d’un outil de développement de smart contract, visant à simplifier le processus de construction, de déploiement et de test de ces contrats. Les plus utilisés sont Hardhat, Truffle, Brownie, Ganache et Remix. Nous n’allons pas tous les utiliser, mais ils fonctionnent à peu près tous de la même façon. 
Pour notre fil rouge, nous allons installer hardhat. 
  ```bash
  npm install --save-dev hardhat
  ```
</details>
👉🏽 Créez un nouveau projet 'javaScript project", valider toutes les optionnalités. Supprimez tous les fichiers dans le dossier *contracts* et intégrer le fichier forker précèdement. 



✅ Vous avez maintenant tous les outils nécessaire pour commencer à coder ! 

Have fun xxx
 
