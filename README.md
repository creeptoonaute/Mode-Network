<h1 align="center"> Mode Network </h1>
Au début, utilisons le pont et ayons un peu de notre jeton de test sur le réseau Mode.

Vous pouvez utiliser le pont ici. J'aime vraiment le Mode Network.

bash
Copy code
# Informations RPC :
Mode Testnet
https://sepolia.mode.network
919
mETH
Tout d'abord, ici, sélectionnez "create API keys", donnez-lui un nom et cliquez sur "next".
Enregistrez la clé secrète qui apparaît. Vous en aurez besoin plus tard.

Ensuite, ici, attendez que le terminal apparaisse en cliquant sur "Use This Template".
![image](https://github.com/AbdullahCoban28/Mode-Network/assets/111288151/9dbf6e75-e012-4922-bc0f-a90410b24834)

Une fois que le terminal apparaît, saisissez les commandes nécessaires :

bash
Copy code
sudo apt update
sudo apt upgrade

# Téléchargeons npm :
sudo apt install nodejs

# Téléchargeons thirdweb :
npm i -g thirdweb

# Pour créer un jeton :
npx thirdweb create
# Après cette commande, vous pouvez sélectionner ou entrer les valeurs comme indiqué dans l'image :
![image](https://github.com/ruesandora/Mode-Network/assets/101149671/0be295d1-3e9c-428e-81a4-a4203b42df63)

Maintenant, nous avons un jeton sur notre propre chaîne mode. J'aime vraiment Thirdweb, vous pouvez le faire sur presque toutes les chaînes EVM.

Maintenant, saisissons cette commande et déployons notre contrat.

css
Copy code
npx thirdweb deploy --key <votre clé secrète de thirdweb>
Lorsque vous entrez cela, votre jeton sera créé avec succès et vous serez redirigé vers le site de thirdweb.

Dans la section Contracts, cliquez sur "Deploy contract".

![image](https://github.com/AbdullahCoban28/Mode-Network/assets/111288151/f6e62762-1c38-4f8a-af50-13bd0269c0e2)

Une page s'ouvre vous offrant de nombreuses options. Je suis passé à la création de jetons en cliquant sur la cinquième option.

![image](https://github.com/AbdullahCoban28/Mode-Network/assets/111288151/cff2c59c-3d15-4b3a-bfa9-e0d47b81fcd6)

Ici, vous pouvez ajouter ou supprimer des lignes de code sous forme de code, mais je ne l'ai pas fait. Cliquez sur "Deploy Now".

![image](https://github.com/AbdullahCoban28/Mode-Network/assets/111288151/3b7a97a8-d714-4537-a4d3-e8ee808ac903)

Lorsque vous cliquez sur "Deploy Now", il vous demandera des informations. Après avoir sélectionné le nom, le symbole et l'image de votre jeton, assurez-vous que dans la section "network chain" en bas, vous avez bien sélectionné MODE NETWORK et cliquez sur le pont en haut.

![image](https://github.com/AbdullahCoban28/Mode-Network/assets/111288151/0e30ae9a-db9c-4988-9cb3-4e390ddfd1ca)

Votre jeton est maintenant créé et apparaîtra dans la section Contracts.

En cliquant sur votre jeton, vous pouvez effectuer des opérations de "Burn", "Airrop", "Transfer" et "Mint". Vous pouvez mint autant de jetons que vous le souhaitez et les transférer.

![image](https://github.com/AbdullahCoban28/Mode-Network/assets/111288151/6964fd05-dcce-4d13-8461-d3de8c064217)

Partagez vos actions dans ce référentiel sous forme de dossier "PR" pour apprendre davantage, voire même envoyez-moi des jetons.

Mon adresse : 0x55853288c0470E771A815D47A23A4184B5E43d41

De plus, pour obtenir le rôle OG, il y a des galaxies ou quelque chose comme ça, mais je ne les connais pas, vous pouvez les vérifier. Voici le lien de la galaxy pour le Mode Network.

Mode Network Galaxy https://galxe.com/mode Il n'y a pas encore d'événements actifs, ils commenceront probablement bientôt.

bash
Copy code
<h1 align="center"> Pour ceux qui rencontrent une erreur de jeton inattendue </h1>

# Supprimons-le
sudo apt remove nodejs npm

# Réinstallons-le :
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.5/install.sh | bash

source ~/.bashrc
nvm install node
Ensuite, téléchargez thirdweb et continuez à partir de l'étape de commande.

En outre, pour ceux qui rencontrent des erreurs de déploiement, entrez la commande de déploiement après être entré dans le dossier de votre projet créé avec cd.
