---
title: 'Encoder/Décoder une commande powershell'
---

Avec Powershell, il est possible d'executer des commandes encodé en base64 via la commande suivante :

````powershell.exe -encodedCommand <Commande en base64>````

Seulement l'encodage en base64 de la commande n'est pas suffisante.

## Encoder une commande Powershell

Pour encoder une commande Powershell, il est d'abord nécessaire d'encoder la chaine de caractère en UTF-16LE, puis en Base64

## Décoder une commande Powershell

Pour Décoder une commande Powershell, il faut commencer par décoder la base64, puis décoder l'UTF-16LE