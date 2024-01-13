## ProgettoReti


![Traccia](https://github.com/Ranchoo28/ProgettoReti/assets/114573233/b163d15f-d0a6-4455-90a0-0c9075c9b15e)

# Configurazione delle Reti

Questo documento descrive la configurazione delle reti all'interno di un sistema, divise in varie sottoreti e segmenti. Le informazioni sono fornite per ogni componente di rete.

## RED Area

### CD1
- Indirizzo di rete: 10.0.8.0 / 24
- Netmask: 255.255.255.0
- Broadcast: 10.0.8.255

Calcolo degli indirizzi IP:
- CD1: 24 → Indirizzo IP: 10.0.8.24

### CD2
- Indirizzo di rete: 10.0.9.0 / 30
- Netmask: 255.255.255.252
- Broadcast: 10.0.9.3

Calcolo degli indirizzi IP:
- CD2: 30 → Indirizzo IP: 10.0.9.2

### CD4
- Indirizzo di rete: 10.0.9.4 / 30
- Netmask: 255.255.255.252
- Broadcast: 10.0.9.7

Calcolo degli indirizzi IP:
- CD4: 30 → Indirizzo IP: 10.0.9.6

### CD5
- Indirizzo di rete: 10.0.9.8 / 30
- Netmask: 255.255.255.252
- Broadcast: 10.0.9.11

Calcolo degli indirizzi IP:
- CD5: 30 → Indirizzo IP: 10.0.9.10

### CDTAP
- Indirizzo di rete: 10.0.9.12 / 30
- Netmask: 255.255.255.252
- Broadcast: 10.0.9.15

Calcolo degli indirizzi IP:
- CDTAP: 30 → Indirizzo IP: 10.0.9.14

## GREEN Area

### CD6
- Indirizzo di rete: 10.0.0.0 / 23
- Netmask: 255.255.254.0
- Broadcast: 10.0.1.255

Calcolo degli indirizzi IP:
- CD6: 384 → 2X – 2 ≥ 384 → X = 9 → Indirizzo IP: 10.0.0.23

### CD7
- Indirizzo di rete: 10.0.2.0 / 24
- Netmask: 255.255.255.0
- Broadcast: 10.0.2.255

Calcolo degli indirizzi IP:
- CD7: 219 → 2X – 2 ≥ 219 → X = 8 → Indirizzo IP: 10.0.2.24

### CD8
- Indirizzo di rete: 10.0.2.0 / 24
- Netmask: 255.255.255.0
- Broadcast: 10.0.2.255

Calcolo degli indirizzi IP:
- CD8: 144 → 2X – 2 ≥ 144 → X = 8 → Indirizzo IP: 10.0.2.24

### GREEN (Generale)
- Indirizzo di rete: 10.0.0.0 / 22
- Netmask: 255.255.252.0
- Broadcast: 10.0.3.255

## DMZ Area

### CD9
- Indirizzo di rete: 10.0.4.0 / 23
- Netmask: 255.255.254.0
- Broadcast: 10.0.5.255

Calcolo degli indirizzi IP:
- CD9: 445 → 2X – 2 ≥ 445 → X = 9 → Indirizzo IP: 10.0.4.23

### DMZ (Generale)
- Indirizzo di rete: 10.0.4.0 / 22
- Netmask: 255.255.252.0
- Broadcast: 10.0.7.255

## Note
- **X**: Calcolo del valore di X basato sulla formula 2X – 2 ≥ [Numero specificato].
- **Calcolo degli indirizzi IP**: Calcolo degli indirizzi IP per ogni dispositivo in base alla formula di calcolo fornita.



