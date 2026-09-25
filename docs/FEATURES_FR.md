# Features
## 1. Calendrier de disponibilités

Un calendrier où on peut rentrer sur quelles dates et à quelle période de la journée on est dispos (matin/après-midi/soir/journée). Ce calendrier est uniquement affiché pour l’utilisateur, il n’a pas accès à ceux des autres. 3 possibilités: dispo (vert), pas sûr (orange, défaut), pas dispo (rouge). Dispo journée = (dispo matin ET après-midi). On peut définir des récurrences (”jamais dispo le mercredi soir”).

## 2. Liste d’activités

Chaque utilisateur peut ajouter des activités: il précise à quelle période on le fait (ex: bar le soir, ou événement sur plusieurs jours), et des infos générales: prix estimé par personne, le.s organisateur.s (créateur par défaut), lieu, capacité (facultative et informative), date “à faire avant le” (facultative). Il est possible d’indiquer une activité comme “récurrente” (restau, bar, just dance). 

Chaque utilisateur indique si il est intéressé, et la liste des intéressés est visible par tous. Quand on se déclare intéressé, l’app pré-remplit automatiquement un calendrier de dispos spécifique à cette activité, que l’utilisateur peut ensuite modifier. Si il y a une modif du calendrier général (Feature 1), elle est répercutée dans les calendriers spécifiques sauf sur les créneaux modifiés manuellement dans le calendrier spécifique.

Pour trouver une date, les dispos requises dépendent de la période de l'activité. Une activité « journée » nécessite une dispo « journée » ou bien « matin » et « après-midi ». Une activité sur plusieurs jours nécessite une dispo « journée » sur chacun des jours.

Ensuite, l’organisateur peut créer une proposition d’activité et il est proposé une liste de dates pour l’événement (avec le nombre de dispos + pas sûr à côté) avant la date “à faire avant le”. Chaque date affiche le nombre de personnes dispos et “pas sûr”, de manière anonyme (chiffres). L’organisateur choisit une date. 

*Sondages.* Chaque activité comporte une section “Sondages”. Chaque activité comporte une section « Sondages ». Les organisateurs peuvent y créer des sondages pour trancher des questions d'organisation : durée, lieu, budget, logistique, etc. Un sondage peut être à choix unique, à choix multiples ou à réponse libre, avec une date de clôture optionnelle. Les intéressés sont notifiés et les votes sont publics. Une fois un sondage clôturé, l'organisateur peut reporter le résultat dans les infos de l'activité. La section reste accessible après le choix de la date pour les questions pratiques, comme le covoiturage ou qui apporte quoi.

## 3. Calendrier des événements organisés

Une fois que la date est choisie par l’organisateur, elle apparait dans le calendrier de toutes les personnes intéressées et une notification leur est envoyée. Elles indiquent si elles y participent: oui, non ou peut-être. Choisir “peut-être” affiche un popup qui incite à trancher. Un “oui” bloque automatiquement le calendrier général et les calendriers spécifiques. Des rappels par notif sont envoyés aux personnes n’ayant pas répondu.

Si un utilisateur modifie une dispo sur un créneau où il a confirmé sa présence, une popup le lui signale et lui demande si il souhaite se désister.

L’organisateur peut annuler un événement ou le repasser de “validé” à “en cours d’organisation”, par exemple pour changer la date. Dans les 2 cas, les participants sont notifiés et les créneaux bloqués sont libérés. Pour une activité récurrente, une fois l’événement passé, l’activité reste dans la liste avec ses intéressés, et les calendriers spécifiques sont réinitialisés.

## 4. Administration

Un rôle Admin permet de gérer l’app. L’inscription n’est pas ouverte: chaque nouveau compt eest créé en statut “en attente”. L’admin reçoit une notif puis valide ou refuse la demande manuellement. Il a accès à la liste des utilisateurs et peut désactiver ou supprimer un compte. Il peut modérer le contenu en modifiant ou supprimant des activités, événements ou sondages. Côté maintenante, il peut activer un mode maintenance, envoyer une annonce à tous et consulter les journaux d’erreur.

### Evols envisagées

- Actuellement, on considère un seul groupe. A terme, on pourrait gérer plusieurs groupes distincts, chacun avec ses membres, activités et event.
- Une messagerie pourrait être ajoutée.
- Une connexion à des calendriers externes peut être envisagée, pour importer des périodes d'indisponibilités et pour exporter un événement.