#Project : Server

##Creation of a personal server used in a local network

###Cahier des charges

*Un espace de stockage redondant d’une capacité de 1 To minimum pour toutes les données sensibles (Documents administratifs, bulletins de paies, factures, photos, …). Cet espace ne doit être accessible que pour certains utilisateurs.
*Un espace de stockage non redondant de grande capacité, environ 4 To, pour stocker toutes les autres données (médias audios et vidéos, fichiers CAO, …). Cet espace peut être accessible pour tous les utilisateurs.
Les disques durs doivent être accessible et interchangeables rapidement.
*Le serveur sera allumé 24/24h, il doit donc avoir une faible consommation électrique.
*Le serveur doit être le plus silencieux possible.

###Configuration des disques
*Configuration 1
|Utilisation         |Capacité|Nb disques|Raid |
|:---:               |:---:   |:---:     |:---:|
|Documents imprtants |1 To    |2 x 1 To  |1    |
|Photos et vidéos    |1 To    |2 x 1 To  |1    |
|Medias et divers    |4 To    |4 x 1 To  |_    |

*Configuration 2
|Utilisation         |Capacité|Nb disques|Raid |
|:---:               |:---:   |:---:     |:---:|
|Documents + Photos  |2 To    |2 x 2 To  |1    |
|Medias et divers    |4 To    |2 x 2 To  |_    |

