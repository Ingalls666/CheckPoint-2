Q.3.1

- Le materiel **A** est un switch. Il permet de rediriger des données entre les PC1, PC2, PC3, PC4 et PC5.

Q.3.2

- Le materiel **B** est un routeur . il permet de sortir du réseau 10.10.0.0/16

Q.3.3

-```f0/0``` est une interface "FastEthernet en port 0

-```g1/0``` est une interface "GigaBitEthernet" en port 1

Q.3.4

- ```/16``` est le CIDR de l'adresse IP

Q.3.5

- ```10.10.225.254``` est l'adresse IP de la passerelle par défaut

---

Q.3.6

- ```PC1```
    - '10.10.0.0/16'
    - '10.10.0.1/16'
    - '10.10.255.254/16'
    - '10.10.255.255/16'

- ```PC2```
    - '10.11.0.0/16'
    - '10.11.0.1/16'
    - '10.11.255.254/16'
    - '10.11.255.255/16'

- ```PC5```
    - '10.10.0.0/15'
    - '10.10.0.1/15'
    - '10.11.255.254/15'
    - '10.11.255.255/15'

Q.3.7

- Le ```PC1``` communiquera avec les PC : ```PC3```,```PC4```,```PC5```

- Le ```PC2``` communiquera avec le PC : ```PC5```

- Le ```PC3``` communiquera avec les PC : ```PC1```,```PC4```,```PC5```

- Le ```PC4``` communiquera avec les PC : ```PC1```,```PC3```,```PC5```

- Le ```PC5``` communiquera avec tout les PC

Q.3.8

- Tout les PC pourront atteindre le réseau ```172.16.5.0/24```

Q.3.9

- Il n'y aura aucune incidence particulière.

Q.3.10

- Si on passe sur une allocation dynamique des adresses IP, un changement de adresse IP des PC est à prevoir

#### - FICHIER 1
---

Q.3.11

- L'adresse MAC de source est : ```00:50:79:66:68:00```. Elle correspond  a ```PC1```.

Q.3.12

- La communication a bien reussi entre ```PC1``` et ```PC4``` .

Q.3.13

- Le ```PC1``` ping vers ```PC4```

- ```PC1```
    - IP : 10.10.4.1/16
    - MAC : 00:50:79:66:68:00

- ```PC4```
    - IP : 10.10.4.2/16
    - MAC : 00:50:79:66:68:03

Q.3.14

- Le protocole encapsulé est du ```ARP``` , il permet d'associer l'adresse IP à une adresse MAC

Q.3.15

- Ils font la correspondance entre les adresses IP et MAC sur le réseau

#### - FICHIER 2
---

Q.3.16

- Le ```PC3``` avec l'adresse IP ```10.10.80.3/16``` 

Q.3.17

- Le protocole encapsulé est du ```ICMP```, il permet de controler la transmission des paquets

Q.3.18

- La communication n'a pas fonctionné car le materiel est inacessible

Q.3.19

- Le chemin entre ```10.10.255.254``` et ```10.10.80.3``` est inacessible

Q.3.20

- Ils font la correspondance entre les adresses IP et MAC sur le réseau

#### - FICHIER 3
---

Q.3.21

- Materiel Source 
    - ```PC4``` 
    - IP ```10.12.2.254/24```

- Materiel Destination
    - ***Materiel Inconnu*** (adresse dans le cloud???)
    - IP ```172.16.5.253/24```

Q.3.22

- Adresse MAC Source : ```CA:01:DA:D2:00:1C```

- Adresse MAC Destination : ```CA:03:9E:EF:00:38```

Q.3.23

- La communication se situe entre le  ```Routeur B``` et le ```Routeur R2```
