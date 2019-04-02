# Apache et les hôtes virtuels

## Résolution de noms

Dans un premier temps, modifier les fichiers **hosts** du client ET du serveur pour assurer une bonne résolution des noms.

**/etc/hosts**

## Création des fichiers de configuration des VirtualHosts

DÃ©poser les fichiers de configuration dans **/etc/apache2/sites-available**

## Activation des VirtualHosts

<code>
a2ensite www.cesi.fr
a2ensite www.clement.cesi.fr
a2ensite www.even.fr
a2ensite damien.cesi.fr
</code>
