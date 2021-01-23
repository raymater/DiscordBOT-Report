# DiscordBOT-Report
Bot de signalement de comportements inappropiés sur Discord (JavaScript)
*par @raymater*


## Utilisation du bot de rapport sur Discord
Pour signaler un comportement qui vous semble inapproprié sur Discord, utilisez la commande `!report`.

Utilisée toute seule, cette commande affichera l'aide.

Pour signaler un utilisateur à l'équipe de modération, tapez `!report @unUtilisateur`. Vous pouvez en signaler plusieurs en tapant `!report @unUtilisateur1 @unUtilisateur2`. L'option `-r:` est optionnelle, en la renseignant vous pouvez alors préciser une raison précise du signalement comme ceci : `!report @unUtilisateur -r:"Une raison"`. Dans tous les cas un rapport de signalement sera alors envoyé à la modération en MP (message privé) qui sera alors avertie du signalement du moment où le signalement a été effectué par quel utilisateur envers quel autre utilisateur sur quel topic de quel serveur pour telle raison.

Attention cette commande de signalement ne doit être utilisée qu'en cas de nécessité (absence de modérateurs connectés ou actifs sur un contenu ou un comportement considéré comme véritablement prohibé). Ainsi il n'est possible d'effectuer qu'un seul signalement toutes les 3 minutes maximum pour éviter tout abus ou spam.


## Compilation depuis le code source
Créez votre Discord App sur https://discordapp.com/developers/applications/me puis rentrez le token de votre app dans le fichier *bot.js* à la ligne 10 (var token).

Pour lancer le bot, vous pouvez soit lancer nodeJS via la commande *node bot.js* soit utiliser le fichier *start.bat*.

N'oubliez pas d'ajouter votre app bot à votre serveur en passant le clientID de votre app Discord en paramètre de cette URL : https://discordapp.com/oauth2/authorize?client_id=votreClientID&scope=bot&permissions=0
