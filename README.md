# Bookmarklet-Detection-Doublon-Moderation
Cette version contient  la partie modération du script Bookmarklet-duplicate-detection-HAL disponible ici https://github.com/Amiantedeluxe/Bookmarklet-duplicate-detection-HAL

Les notices présentes en modération ne sont pas encore indexées dans la base documentaire de HAL avant leur validation technique et leur mise en ligne. Pour les interroger, on utilise donc un point d’entrée spécifique de l’API (/crac/hal), qui permet d’accéder aux notices en modération grâce au docid ; que l’on retrouve notamment dans l’URL de ces notices dans l’interface de modération. À partir de la requête basée sur le docid, on récupère le halId de la notice renvoyé par l’API, ce qui permet ensuite au bookmarklet de fonctionner comme pour une notice classique présente en ligne. 

![bookmarklet doublon moderation](https://github.com/torousselle/Bookmarklet-Detection-Doublon-Mod-ration/blob/main/bookmarklet%20doublon%20moderation.PNG?raw=true)
