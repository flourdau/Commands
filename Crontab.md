`crontab -e`

    * * * * *
    ┬ ┬ ┬ ┬ ┬
    │ │ │ │ │
    │ │ │ │ │
    │ │ │ │ └───── Numéro du jour de  la semaine(0 - 7) (0 & 7 === Dimanche)
    │ │ │ └────────── du moi (1 - 12)
    │ │ └─────────────── du jour du moi (1 - 31)
    │ └──────────────────── heure (0 - 23)
    └───────────────────────── minute (0 - 59)

Exemple :  

`0 0 * * *  /home/USERNAME/backup.sh` # backup.sh tous les jours à minuit.  
`@reboot python /home/USERNAME/backup.sh` # Au démarage  
`@reboot python /home/USERNAME/backup.sh &` # Au démarage et en arrière plan  

`crontab -l`
