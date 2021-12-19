# BORN2BEROOT

Ce projet a pour but de vous faire découvrir le merveilleux monde de la virtualisation.
Vous allez créer votre première machine en respectant des consignes précises et en
utilisant VirtualBox (ou UTM si VirtualBox ne fonctionne pas sur votre machine). Ainsi,
à la suite de ce projet, vous serez capable d’installer votre propre système d’exploitation
implémentant des règles strictes.

vous devrez mettre en place un petit script nommé monitoring.sh. Ce dernier
sera à développer en bash.

Dès le lancement de votre serveur, le script écrira des informations toutes les 10 minutes sur tous les terminaux (jetez un oeil du côté de wall). La bannière est facultative.

À aucun moment la moindre erreur ne doit être visible.

Votre script devra toujours pouvoir afficher les informations suivantes :

• L’architecture de votre système d’exploitation ainsi que sa version de kernel.
• Le nombre de processeurs physiques.
• Le nombre de processeurs virtuels.
• La mémoire vive disponible actuelle sur votre serveur ainsi que son taux d’utilisation sous forme de pourcentage.
• La mémoire disponible actuelle sur votre serveur ainsi que son taux d’utilisation
  sous forme de pourcentage.
• Le taux d’utilisation actuel de vos processeurs sous forme de pourcentage.
• La date et l’heure du dernier redémarrage.
• Si LVM est actif ou pas.
• Le nombre de connexions actives.
• Le nombre d’utilisateurs utilisant le serveur.
• L’adresse IPv4 de votre serveur, ainsi que son adresse MAC (Media Access Control).
• Le nombre de commande executées avec le programme sudo.
