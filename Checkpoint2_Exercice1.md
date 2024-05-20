Q1.1 

- La machine Serveur -> Client ne ping car elles ne sont pas sur le même réseau. 
- Le serveur est sur le réseau 172.16.**10**.0/24 et le Client sur le réseau 172.16.**100**.0/24
![ping non-fonctionnel](file:///c%3A/Users/bugch/Images/Captures%20d%E2%80%99%C3%A9cran/Capture%20d%27%C3%A9cran%202024-05-17%20094432.png)
![changement adresse ip client](file:///c%3A/Users/bugch/Images/Captures%20d%E2%80%99%C3%A9cran/Capture%20d%27%C3%A9cran%202024-05-17%20100223.png)
![ping fonctionnel](file:///c%3A/Users/bugch/Images/Captures%20d%E2%80%99%C3%A9cran/Capture%20d%27%C3%A9cran%202024-05-17%20100320.png)

Q.1.2

- la machine Serveur ping vers le Client via le nom du Pc Client en IPv6
![ping via nom client IPv6](file:///c%3A/Users/bugch/Images/Captures%20d%E2%80%99%C3%A9cran/Capture%20d%27%C3%A9cran%202024-05-17%20100935.png)

Q.1.3 

- la machine Serveur ping vers le Client via le nom du Pc Client en IPv4
![ping via nom client IPv4](file:///c%3A/Users/bugch/Images/Captures%20d%E2%80%99%C3%A9cran/Capture%20d%27%C3%A9cran%202024-05-17%20102320.png)

Q.1.4 

Q.1.5 

![ip client dhcp](file:///c%3A/Users/bugch/Images/Captures%20d%E2%80%99%C3%A9cran/Capture%20d%27%C3%A9cran%202024-05-17%20104751.png)
- le Client ne récupère pas la premiere adresse car il y a une zone d'exclusion de 172.16.10.1 -> 17.16.10.19  
![zone d'exclusion](file:///c%3A/Users/bugch/Images/Captures%20d%E2%80%99%C3%A9cran/Capture%20d%27%C3%A9cran%202024-05-17%20104730.png)

Q.1.6

- dans les Serveur DHCP, créer une reservation dans la plage avec les informations nécessaires. 
![reservation](file:///c%3A/Users/bugch/Images/Captures%20d%E2%80%99%C3%A9cran/Capture%20d%27%C3%A9cran%202024-05-17%20105539.png)
![ip client](file:///c%3A/Users/bugch/Images/Captures%20d%E2%80%99%C3%A9cran/Capture%20d%27%C3%A9cran%202024-05-17%20110145.png)

Q.1.7 

Q.1.8 