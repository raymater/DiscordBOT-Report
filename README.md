# DiscordBOT-Report
Bot de signalement pour Discord (JS)

## Mode d'emploi
Pour l'implémenter, créez votre Discord App sur https://discordapp.com/developers/applications/me puis rentrez le token de votre app dans le fichier *bot.js* à la ligne 10 (var token).

Pour lancer le bot, vous pouvez soit lancer nodeJS via la commande *node bot.js* soit utiliser le fichier *start.bat*.

N'oubliez pas d'ajouter votre app bot à votre serveur en passant le clientID de votre app Discord en paramètre de cette URL : https://discordapp.com/oauth2/authorize?client_id=votreClientID&scope=bot&permissions=0
