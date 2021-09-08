#Simulation Blues Brothers 

Bienvenue dans ce ReadMe qui va vous expliquer pas à pas comment simuler l'espérance et la variance de la durée d'une prise par Elwood !

1. Lancez le script Python bluesbros.
Retenez l'url indiquée par le terminal en ajoutant la route "/simu".

2. Postman est une plateforme API qui permet de faire des requêtes HTTP. Pour l'installer postman écrire dans le terminal :

sudo snap install postman.

Puis s'inscrire gratuitement à Postman.

3. Lancez postman depuis le terminal. 
Dans l'encart "Start with something new", cliquez sur "Create New". Choisissez "HTTP Request". Sélectionnez le type de requête POST, indiquez l'url que vous aviez retenue à l'étape 2. Cliquez sur "Body", sélectionnez "raw" et JSON.
Dans la zone de texte, entrez les paramètres à simuler comme ceci:
{
    "nb_musicians": 3,
    "theta": [0.8, 1, 0.9]
}
Pour vous authentifierm cliquez sur "Authorization", dans "Type", choisissez "Basic Auth". En username et en password, écrivez "Edwood".
Cliquez sur "Send". 

Visualisez la réponse en-dessous !
