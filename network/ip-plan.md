# Plan d’adressage IP – Hôtel Le Ndiambour (Réel)

## VLAN 10 – ADMINISTRATION / ÉCRANS
| Équipement       | Adresse IP      | Masque          | Passerelle     |
|------------------|-----------------|-----------------|----------------|
| Routeur (Sub-int)| 192.168.1.1     | 255.255.255.0   | –              |
| Écran 1          | 192.168.1.10    | 255.255.255.0   | 192.168.1.1    |
| ...              | ...             | ...             | ...            |
| Écran 10         | 192.168.1.20    | 255.255.255.0   | 192.168.1.1    |
| Serveur          | 192.168.1.45    | 255.255.255.0   | 192.168.1.1    |

## VLAN 20 – SERVICES (Prévu)
| Équipement       | Adresse IP      | Masque          | Passerelle     |
|------------------|-----------------|-----------------|----------------|
| Routeur (Sub-int)| 192.168.20.1    | 255.255.255.0   | –              |

## VLAN 30 – GUEST (Prévu)
| Équipement       | Adresse IP      | Masque          | Passerelle     |
|------------------|-----------------|-----------------|----------------|
| Routeur (Sub-int)| 192.168.30.1    | 255.255.255.0   | –              |