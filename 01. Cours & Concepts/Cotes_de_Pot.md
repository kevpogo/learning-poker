---
title: 📘 Cotes de Pot – Est-ce qu'on a la cote pour payer ? (inclut KO)
parent: 01. Cours & Concepts
---

# 📘 Cotes de Pot – Est-ce qu'on a la cote pour payer ? (inclut KO)

---

## 🎯 Objectif

Comprendre si on peut **payer un bet ou un all-in** en fonction :
- de la **taille du pot**
- de notre **équité contre la range adverse**
- de la **valeur du KO** en tournoi bounty

---

## 🔢 1. Formule de base

> **Cote (%) = Montant à payer / (Pot total final après call)**

### 📌 Exemple simple :
- Pot = 10, vilain shove 5, tu dois call 5
- Pot final = 10 + 5 + 5 = 20
- **Cote = 5 / 20 = 25 %**

---

## 🧠 2. Règle de décision

- Si ton **équité estimée** est **supérieure à la cote**, alors :
✅ **Tu peux payer**

- Sinon : ❌ Fold

---

## 🧮 3. Estimer son équité

Tu peux utiliser Equilab, Flopzilla ou des repères simples :

| Ta main vs sa range         | Équité approximative |
|-----------------------------|----------------------|
| ATo vs 22–88                | ~43 %                |
| KQs vs TT+, AK              | ~35 %                |
| 98s vs AJo                  | ~40 %                |
| T9s vs random               | ~48 %                |

---

## 💥 4. Spécial KO – Prendre en compte la prime

### 💰 Calcul de la valeur d’un KO :
> **Valeur prime KO = (Prime / 2) × (1 - rake)**  
_(souvent rake = 8 % donc on garde 92 % du bounty)_

📌 Exemple :
- Prime visible = 4 €
- KO = 4 / 2 = 2 €  
- 2 € × 0.92 = **1.84 €** ajoutés à la value du pot

---

### 🔄 Nouvelle formule avec KO :

> **Cote corrigée = Montant à payer / (Pot final + prime effective)**

💡 Tu peux **payer plus loose** car tu gagnes *plus* qu’un simple pot !

---

### 🧠 Exercice KO :

> Pot = 10 €, vilain shove 5 €, prime KO = 6 €

1. Valeur prime KO = 6 / 2 × 0.92 = **2.76 €**
2. Pot final après call = 20 €
3. Nouveau pot total = 22.76 €
4. Cote corrigée = 5 / 22.76 ≈ **22 %**

✅ Si tu as 25 % d’équité, tu peux call profitablement !

---

## 📌 À retenir

- **Sans KO** → utilise la formule classique
- **Avec KO** → ajoute la valeur du bounty au pot final
- **Estime ton équité** (même à la louche)
- Ne call pas "parce que c’est pas cher" — call parce que c’est **+EV**
