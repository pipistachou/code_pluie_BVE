CODES POUR L'ANALYSE DES DONNÉES DE PRÉCIPITATION LIQUIDE AU BASSIN VERSANT EXPÉRIMENTAL DE SAINTE-MARTHE

Réalisé par Gaëlle da Silva dans le cadre d'un stage de premier cycle à l'été 2025, supervisé par Annie Poulin.

À partir d'un fichier de données pluviales csv (disponible sur le serveur de HC3), ce code permet de créer plusieurs
graphiques ainsi que dataframe

Graphiques
- Hyétogramme : hyétogramme de l'intensité maximale journalière des précipitations, pour chaque année
- Hyétogramme intéractif : hyétogramme interactif de l'intensité des précipitations aux 15 minutes, pour chaque année
- Courbe de la hauteur de pluies cumulées: courbe de l'accumulation annuelle des pluies, pour chaque année
- Courbe de la hauteur de pluies cumulées interactive : courbe interactive de l'accumulation annuelle des pluies, pour
  chaque année
- Courbes totales des hauteurs de pluies cumulées: toutes les courbes de hauteur cumulées d'une station réunis sur un
  seul graphique
- Accumulation journalière : graphique de l'accumulation de pluie journalière, pour chaque année
- Intensité maximale saisonnière des précipitation (RX1h) : graphique de l'intensité maximale saisionnière des précipitation,
  de toutes les années sur un seul graphique, avec sa date (mm-jj)
- Nombre de jour consécutifs de pluies (consecutive wet day): graphique du nombre de jour consécutif maximale où il a plu pour
  chaque saison. Chaque barre représente une journée, et on peut y lire son accumulation journalière
- Nombre de jour consécutifs sans pluies: graphique du nombre de jour consécutif maximale sans pluie pour chaque saison

DataFrames
- Accumulation journalière : données, sous format csv, contenant le jour ainsi que la quantité de pluie cette journée là
- Intensité maximale saisonnière des précipitation (RX1h) : données, sous forme de DataFrame, contenant l'année, la saison, le
  timestamp (aaaa-mm-jj hh:mm:ss), et l'intensité maximale des précipitation cette saison là
- Nombre de jour consécutifs de pluies (consecutive wet day): données, sous forme de DataFrame, contenant l'accumulation totale
  pour chaque journée, le nombre de journée consécutives maximales, la saison, et la date (jour_timestamp, mois, année)
- Nombre de jour consécutifs sans pluies (consecutive dry day): données, sous forme de DataFrame, contenant  l'accumulation totale
  pour chaque journée (0.0), le nombre de journée consécutives maximales, la saison, et la date (jour_timestamp, mois, année)

Ouvrir les fichier .ipynb pour le code des différentes stations, et .csv pour les données tests (une seule année) des différentes stations 
