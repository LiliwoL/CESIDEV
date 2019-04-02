# Apache et les h√tes virtuels

## R√solution de noms

Dans un premier temps, modifier les fichiers **hosts** du client ET du serveur pour assurer une bonne r√©solution des noms.

**/etc/hosts**

## Cr√©ation des fichiers de configuration des VirtualHosts

D√©poser les fichiers de configuration dans **/etc/apache2/sites-available**

## Activation des VirtualHosts

<code>
a2ensite www.cesi.fr
a2ensite www.clement.cesi.fr
a2ensite www.even.fr
a2ensite damien.cesi.fr
</code>
