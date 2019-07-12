

**WARNING 12/07/2019 : Due to update in viessmann Oauth process, method call with version before 12/07/2019 now fails(message  Call to a member function getProperty() on null). I had to update authorization method from OAuth to Bearer and add an extra Header. This has been fixed in 1.1-SNAPSHOT(available in example directory). As soon as I have enough feedback, I will do a release 1.1 with this fix !**

**ATTENTION: A cause d'un changment dans la procédure Oauth de Viessmann, les appels avec la version datant d'avant 12/07/20119 échouent systématiquement(messsage  Call to a member function getProperty() on null).  J'ai du passer en Token Bearer plutôt qu'OAuth et ajouter  un header supplémentaire. Ca a été corrigé dans la version 1.1-SNAPSHOT(dispo dans le répertoire example). Dès que j'ai assez de retour, je ferai une release 1.1 officielle.**

Version 1.0.1 available here ! : https://github.com/thetrueavatar/Viessmann-Api/releases/tag/1.0.1

Translated documentation can be found here:
- English: https://github.com/thetrueavatar/Viessmann-Api/blob/develop/README-en.md 

Implémentation d'une interface pour récupérer les données exposées par le service Viessmann.

Ce service accessible via autorisation OAUTH2 expose les données via l'approche HATEOAS implémentée par Siren dont la spécification est définie ici:

https://github.com/kevinswiber/siren

Le but de l'api est de cacher ces aspects techniques poru exposer directement les données.

Je suis novice en php(JAVAEE Dev) donc il se peut que je ne connaisse pas les conventions/habitudes php. Tout conseil/remarque est apprécié et n'hésitez pas à contribuer !

Je précise aussi que je partage mon dev perso mais ne souhaite pas faire un support intensif (pas le temps). Je ne donne donc pas de garantie sur la résolution de tel ou tel bug en terme de délais de résolution.
De toute façon, cmme on dit dans l'open-source "Please contribute" ;-)

Pour voir les explications sur l'utilisation voir wiki: https://github.com/thetrueavatar/Viessmann-Api/wiki/French ou le code de example/Main.php

Si vous souhaitez me soutenir ou me remercier vous pouvez me faire un don paypal :[![paypal](https://www.paypalobjects.com/fr_FR/BE/i/btn/btn_donate_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=3DAXXVZV7PCR6)


Voici la doc des méthodes de l'api [**Viessmann API**](http://htmlpreview.github.com/?https://github.com/thetrueavatar/Viessmann-Api/blob/develop/docs/namespace-Viessmann.API.html):
