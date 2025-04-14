# 💶 Exercice JavaScript : Rendu de monnaie (CashMachine)

Dans cet exercice, tu vas implémenter un algorithme qui simule une machine à rendre la monnaie.  
L’objectif est de décomposer un montant donné en billets et pièces, **en utilisant le moins d’éléments possible**.

---

## 🎯 Objectif

Écrire une fonction nommée `cashMachine` qui :

- Reçoit un **nombre entier positif** représentant un montant en euros.
- Retourne un **objet** qui indique **le nombre de billets et pièces à utiliser** pour rendre ce montant.

Le rendu doit utiliser **le moins d’unités possible**, en commençant par les plus gros billets.

---

## 💰 Billets et pièces disponibles

Tu peux utiliser uniquement les valeurs suivantes :  
**50€, 20€, 10€, 5€, 2€, 1€**

Soit le tableau suivant :  
```js
[50, 20, 10, 5, 2, 1]

## Exemple

cashMachine(87);


{
  50: 1,
  20: 1,
  10: 1,
  5: 1,
  2: 1
}
