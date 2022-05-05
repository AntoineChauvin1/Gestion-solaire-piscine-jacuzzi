# Gestion-solaire-piscine-jacuzzi
Gestion du chauffage solaire de la Piscine et du Jacuzzi

Gestion à partir d'un esp8266
Fonctionnement en francais:

Récupérer l'heure sur internet
Autoriser le fonctionnement du système complet sur une plage horaire réglable dans HA
Définition d'une plage horaire et semaine de fonctionnement du Jacuzzi réglable dans HA

Définition de 4 variables de températures modifiables dans HA
Température souhaitée jacuzzi
Température souhaitée Piscine
Ecart de température Jacuzzi
Ecart de température Piscine


3 sondes de température affichables dans HA
sonde piscine
sonde jacuzzi 
sonde PS

Récupération de la tension de la batterie 12V dans HA (schéma physique à définir)

Activation des pompes 1 à 3 5secondes toutes les 10 minutes (pour mise a jour des températures plus efficaces)

Quand la température du jacuzzi est inférieur à la température souhaitée jacuzzi
Vérification si la plage horaire de fonctionnement du jacuzzi est ok
Vérification si la température des panneaux solaire est supérieur de l'écart de température Jacuzzi plus la température du jacuzzi
Mise en marche de la pompe 1 et 3 jusqu’à ce que la température soit atteinte

Quand la température de la piscine est inférieur à la température souhaité de la piscine
Vérification si la plage horaire de fonctionnement de la piscine est ok
Vérification si la température des panneaux solaire est supérieur de l'écart de température Piscine plus la température de la piscine
Mise en marche de la pompe 1 et 2 jusqu’à ce que la température soit atteinte
