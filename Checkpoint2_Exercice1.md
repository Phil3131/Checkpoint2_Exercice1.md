Q.1.1 Pourquoi le ping avec les adresses IP des machines ne fonctionnent pas ?
Modifie la configuration sur le client pour que cela soit possible.
Explique ce que tu as fait et montre le par des copies d'écran.
On doit avoir la copie d'écran d'un ping fonctionnel.

les deux machines ne sont pas sur le meme reseau . En changean l'adresse IP du client 172.16.100.50/24 en 172.16.10.50 par exemple cela fonctionne.

Q.1.3 Modifie la configuration réseau du client pour qu'il soit en DHCP.
Vérifie le paramétrage DHCP sur le serveur et compare le avec l'adresse IP du client.
Explique pourquoi le client ne récupère pas la 1ère adresse disponible sur la plage DHCP du serveur ?
Fais une copie d'écran montrant l'adresse IP prise par le client.

dans la configuration du serveur DHCP la 1ere Adresse Est exclue.

Q.1.4 Est-ce que ce client peut avoir l'adresse IP 172.16.10.15 en DHCP ?
Si oui fais les manipulations nécessaires.
Explique ce que tu as fait et montre par une copie d'écran le résultat de la commande ipconfig /all sur le client.

oui dans le serveur DHCP il faut reserver l ' adresse IP 172.16.10.15 avec l'adresse MAC du client. 
