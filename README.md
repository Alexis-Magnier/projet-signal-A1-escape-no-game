# 🕵️ ESCAPE NO GAME

> Projet d'ingénierie du signal, agence fictive **AIL3C** (Agence Indépendante de Lutte Contre la CyberCriminalité)

## 🎯 Contexte

L'agent K57 s'est infiltré dans la base secrète de cyberpirates et a récupéré des données sensibles. Piégé dans une salle de conférence, sans accès réseau et avec les ondes radio bloquées par les murs, il n'a pu communiquer avec l'extérieur. Le seul équipement disponible : un **micro relié au système d'audioconférence**.

**Problématique :** quelle solution permettrait la communication vers l'extérieur dans ce genre de situation ?

## 🛠️ Technologies

Python · Jupyter · NumPy · SciPy · Matplotlib · LTSpice / CircuitJS

## 💡 Solution proposée

Transmettre le message de l'agent dans un **signal sonore haute fréquence, inaudible**, superposé aux communications captées par le micro. L'agent à l'écoute du réseau extrait ensuite ce message du signal reçu.

- **Fréquence porteuse :** `[X kHz]`
- **Modulation :** `[ASK / FSK / PSK]`
- **Mode de communication :** simplex
- **Trames + détection d'erreur :** `[parité / CRC]`
