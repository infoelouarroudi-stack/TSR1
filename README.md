# Séance 1 — Bases de calcul algébrique et préparation aux fonctions

> **Niveau :** Terminale — spécialité Mathématiques  
> **Durée :** 2 heures  
> **Objectif :** consolider les automatismes de calcul indispensables avant d'attaquer les études de fonctions.

---

## 1. Objectifs de la séance

À la fin de cette séance, l'élève doit être capable de :

- manipuler correctement les fractions et les puissances ;
- développer et factoriser une expression ;
- reconnaître et utiliser les identités remarquables ;
- résoudre des équations du premier et du second degré ;
- résoudre des inéquations simples ;
- factoriser une expression avant de résoudre une équation ou une inéquation ;
- déterminer les valeurs interdites d'une expression rationnelle ;
- comprendre pourquoi le **domaine de définition** est une étape indispensable dans une étude de fonction ;
- éviter les erreurs classiques de signe et de calcul.

### Organisation des 2 heures

| Temps | Activité |
|---|---|
| 0–10 min | Échange rapide + diagnostic oral |
| 10–30 min | Rappels de cours et méthodes |
| 30–50 min | 5 exercices faciles |
| 50–75 min | 5 exercices moyens |
| 75–100 min | 5 exercices difficiles |
| 100–115 min | 5 exercices très difficiles |
| 115–120 min | Bilan + erreurs à retenir + travail personnel |

> **Méthode pédagogique :** ne pas donner immédiatement la correction. Laisser l'élève chercher, lui demander d'expliquer sa méthode, puis corriger en insistant sur les erreurs de raisonnement.

---

## 2. Diagnostic flash — 10 minutes

Faire les questions suivantes **sans cours et sans aide**.

### Question 1
Simplifier :

$$
A=3(2x-5)-2(x+4)
$$

### Question 2
Factoriser :

$$
B=x^2-9
$$

### Question 3
Résoudre :

$$
2x-7=5
$$

### Question 4
Résoudre :

$$
x^2-5x+6=0
$$

### Question 5
Déterminer les valeurs interdites de :

$$
f(x)=\frac{x+2}{x-3}
$$

<details>
<summary>👉 Voir la correction du diagnostic</summary>

**Question 1**

$$
A=6x-15-2x-8=4x-23
$$

**Question 2**

$$
x^2-9=x^2-3^2=(x-3)(x+3)
$$

**Question 3**

$$
2x-7=5
$$

$$
2x=12
$$

$$
\boxed{x=6}
$$

**Question 4**

$$
x^2-5x+6=(x-2)(x-3)
$$

Donc :

$$
\boxed{x=2\quad\text{ou}\quad x=3}
$$

**Question 5**

Le dénominateur ne doit pas être nul :

$$
x-3\neq0
$$

Donc :

$$
\boxed{x\neq3}
$$

Le domaine est :

$$
\boxed{D_f=\mathbb R\setminus\{3\}}
$$

</details>

---

## 3. Résumé de cours

### 3.1 Priorités et signes

Toujours respecter l'ordre :

1. Parenthèses
2. Puissances
3. Multiplications et divisions
4. Additions et soustractions

#### Règles de signes

$$
(+)\times(+)=+
$$

$$
(-)\times(-)=+
$$

$$
(+)\times(-)=-
$$

$$
(-)\times(+) = -
$$

Même principe pour une division.

---

### 3.2 Fractions

Pour additionner deux fractions, il faut un dénominateur commun :

$$
\frac{a}{b}+\frac{c}{d}
=
\frac{ad+bc}{bd}
$$

avec $b\neq0$ et $d\neq0$.

Pour multiplier :

$$
\frac{a}{b}\times\frac{c}{d}
=
\frac{ac}{bd}
$$

Pour diviser par une fraction, on multiplie par son inverse :

$$
\frac{a}{b}\div\frac{c}{d}
=
\frac{a}{b}\times\frac{d}{c}
$$

avec $c\neq0$.

#### Attention

On ne simplifie pas une addition terme à terme :

$$
\frac{x+2}{x}
\neq
1+2
$$

En revanche :

$$
\frac{x(x+2)}{x}=x+2
$$

à condition que $x\neq0$.

---

### 3.3 Puissances

Pour $a\neq0$ :

$$
a^m\times a^n=a^{m+n}
$$

$$
\frac{a^m}{a^n}=a^{m-n}
$$

$$
(a^m)^n=a^{mn}
$$

$$
a^{-n}=\frac1{a^n}
$$

Exemple :

$$
x^3\times x^4=x^7
$$

---

### 3.4 Développement

La distributivité :

$$
a(b+c)=ab+ac
$$

Exemple :

$$
3(x+5)=3x+15
$$

Double distributivité :

$$
(a+b)(c+d)=ac+ad+bc+bd
$$

Exemple :

$$
(x+2)(x+5)
=x^2+7x+10
$$

---

### 3.5 Identités remarquables

#### Première identité

$$
(a+b)^2=a^2+2ab+b^2
$$

#### Deuxième identité

$$
(a-b)^2=a^2-2ab+b^2
$$

#### Troisième identité

$$
(a-b)(a+b)=a^2-b^2
$$

Exemple :

$$
x^2-16=(x-4)(x+4)
$$

---

### 3.6 Factorisation

Factoriser signifie transformer une somme ou une différence en produit.

#### Facteur commun

$$
ax+ay=a(x+y)
$$

Exemple :

$$
3x^2+6x=3x(x+2)
$$

#### Identité remarquable

$$
x^2-25=(x-5)(x+5)
$$

#### Objectif

Avant de résoudre une équation, toujours se demander :

> **« Est-ce que je peux factoriser ? »**

---

### 3.7 Équation du premier degré

Exemple :

$$
3x-7=11
$$

$$
3x=18
$$

$$
\boxed{x=6}
$$

---

### 3.8 Équation du second degré

Pour :

$$
ax^2+bx+c=0
$$

on peut utiliser le discriminant :

$$
\Delta=b^2-4ac
$$

#### Si $\Delta>0$

Deux solutions :

$$
x_1=\frac{-b-\sqrt\Delta}{2a}
$$

$$
x_2=\frac{-b+\sqrt\Delta}{2a}
$$

#### Si $\Delta=0$

Une solution double :

$$
x_0=-\frac{b}{2a}
$$

#### Si $\Delta<0$

Aucune solution réelle.

---

### 3.9 Produit nul

Si :

$$
A\times B=0
$$

alors :

$$
A=0\quad\text{ou}\quad B=0
$$

Exemple :

$$
(x-2)(x+5)=0
$$

Donc :

$$
\boxed{x=2\quad\text{ou}\quad x=-5}
$$

---

### 3.10 Inéquations

Pour une inéquation, **changer le sens de l'inégalité lorsqu'on multiplie ou divise par un nombre négatif**.

Exemple :

$$
-2x>6
$$

En divisant par $-2$ :

$$
\boxed{x<-3}
$$

#### Pour un produit

Exemple :

$$
(x-2)(x+3)>0
$$

On étudie le signe des deux facteurs.

Racines :

$$
x=2,\qquad x=-3
$$

Le produit est positif sur :

$$
\boxed{]-\infty,-3[\cup]2,+\infty[}
$$

---

### 3.11 Domaine de définition : premier réflexe avant une fonction

Avant de travailler avec une fonction, il faut déterminer pour quelles valeurs de $x$ l'expression existe.

#### Cas d'un quotient

$$
f(x)=\frac{2x+1}{x-4}
$$

Le dénominateur ne peut pas être nul :

$$
x-4\neq0
$$

Donc :

$$
\boxed{D_f=\mathbb R\setminus\{4\}}
$$

#### Cas d'une racine carrée

$$
f(x)=\sqrt{x-3}
$$

Il faut :

$$
x-3\geq0
$$

Donc :

$$
\boxed{D_f=[3,+\infty[}
$$

> **Réflexe à retenir pour les prochaines séances :**
>
> **Domaine de définition → limites si nécessaire → dérivée → signe de la dérivée → variations → conclusion.**

---

## 4. Exercices — Niveau facile

### Exercice 1 — Réduction

Réduire :

$$
A=5x+3-2x+7
$$

<details>
<summary>👉 Voir la correction</summary>

$$
A=(5x-2x)+(3+7)
$$

$$
\boxed{A=3x+10}
$$

</details>

---

### Exercice 2 — Développement

Développer :

$$
B=4(x-3)
$$

<details>
<summary>👉 Voir la correction</summary>

$$
B=4x-12
$$

$$
\boxed{B=4x-12}
$$

</details>

---

### Exercice 3 — Identité remarquable

Développer :

$$
C=(x+5)^2
$$

<details>
<summary>👉 Voir la correction</summary>

$$
(x+5)^2=x^2+10x+25
$$

$$
\boxed{C=x^2+10x+25}
$$

</details>

---

### Exercice 4 — Équation

Résoudre :

$$
4x-9=15
$$

<details>
<summary>👉 Voir la correction</summary>

$$
4x=24
$$

$$
\boxed{x=6}
$$

</details>

---

### Exercice 5 — Valeur interdite

Déterminer les valeurs interdites de :

$$
f(x)=\frac{3x-1}{2x+6}
$$

<details>
<summary>👉 Voir la correction</summary>

$$
2x+6\neq0
$$

$$
x\neq-3
$$

Donc :

$$
\boxed{D_f=\mathbb R\setminus\{-3\}}
$$

</details>

---

## 5. Exercices — Niveau moyen

### Exercice 6 — Développement

Développer et réduire :

$$
A=(2x-3)(x+4)
$$

<details>
<summary>👉 Voir la correction</summary>

$$
A=2x^2+8x-3x-12
$$

$$
\boxed{A=2x^2+5x-12}
$$

</details>

---

### Exercice 7 — Factorisation

Factoriser :

$$
B=3x^2-12x
$$

<details>
<summary>👉 Voir la correction</summary>

Le facteur commun est $3x$.

$$
\boxed{B=3x(x-4)}
$$

</details>

---

### Exercice 8 — Second degré factorisable

Résoudre :

$$
x^2-7x+12=0
$$

<details>
<summary>👉 Voir la correction</summary>

On cherche deux nombres dont le produit vaut $12$ et la somme vaut $-7$.

$$
x^2-7x+12=(x-3)(x-4)
$$

Donc :

$$
(x-3)(x-4)=0
$$

Ainsi :

$$
\boxed{x=3\quad\text{ou}\quad x=4}
$$

</details>

---

### Exercice 9 — Inéquation

Résoudre :

$$
3x-5\leq10
$$

<details>
<summary>👉 Voir la correction</summary>

$$
3x\leq15
$$

$$
\boxed{x\leq5}
$$

Donc :

$$
\boxed{]-\infty,5]}
$$

</details>

---

### Exercice 10 — Simplification rationnelle

Simplifier :

$$
A=\frac{x^2-9}{x-3}
$$

en précisant la condition sur $x$.

<details>
<summary>👉 Voir la correction</summary>

On factorise :

$$
x^2-9=(x-3)(x+3)
$$

Donc :

$$
A=\frac{(x-3)(x+3)}{x-3}
$$

Pour $x\neq3$ :

$$
\boxed{A=x+3}
$$

Attention : la condition $x\neq3$ reste valable.

</details>

---

## 6. Exercices — Niveau difficile

### Exercice 11 — Équation avec fractions

Résoudre :

$$
\frac{x+1}{2}-\frac{x-3}{3}=2
$$

<details>
<summary>👉 Voir la correction</summary>

On multiplie par $6$ :

$$
3(x+1)-2(x-3)=12
$$

$$
3x+3-2x+6=12
$$

$$
x+9=12
$$

$$
\boxed{x=3}
$$

</details>

---

### Exercice 12 — Inéquation produit

Résoudre :

$$
(x-4)(2x+3)\geq0
$$

<details>
<summary>👉 Voir la correction</summary>

Les valeurs qui annulent les facteurs sont :

$$
x=4
$$

et

$$
x=-\frac32
$$

Le produit est positif ou nul à l'extérieur de l'intervalle formé par les deux racines.

Donc :

$$
\boxed{x\in]-\infty,-\frac32]\cup[4,+\infty[}
$$

</details>

---

### Exercice 13 — Domaine de définition

Déterminer le domaine de définition de :

$$
f(x)=\frac{\sqrt{x+2}}{x-1}
$$

<details>
<summary>👉 Voir la correction</summary>

Pour la racine :

$$
x+2\geq0
$$

donc :

$$
x\geq-2
$$

Pour le dénominateur :

$$
x-1\neq0
$$

donc :

$$
x\neq1
$$

Ainsi :

$$
\boxed{D_f=[-2,1[\cup]1,+\infty[}
$$

</details>

---

### Exercice 14 — Factorisation intelligente

Résoudre :

$$
x^3-4x=0
$$

<details>
<summary>👉 Voir la correction</summary>

On met $x$ en facteur :

$$
x(x^2-4)=0
$$

Puis :

$$
x(x-2)(x+2)=0
$$

Donc :

$$
\boxed{x=-2,\quad x=0,\quad x=2}
$$

</details>

---

### Exercice 15 — Fraction et équation

Résoudre :

$$
\frac{x+2}{x-1}=3
$$

<details>
<summary>👉 Voir la correction</summary>

Condition :

$$
x\neq1
$$

On multiplie par $x-1$ :

$$
x+2=3(x-1)
$$

$$
x+2=3x-3
$$

$$
5=2x
$$

$$
\boxed{x=\frac52}
$$

Cette valeur respecte $x\neq1$, donc elle est solution.

</details>

---

## 7. Exercices — Niveau très difficile / réflexion

### Exercice 16 — Paramètre

Pour quelles valeurs de $m$ l'équation

$$
x^2-2x+m=0
$$

admet-elle deux solutions réelles distinctes ?

<details>
<summary>👉 Voir la correction</summary>

Le discriminant vaut :

$$
\Delta=(-2)^2-4m
$$

$$
\Delta=4-4m
$$

Pour avoir deux solutions réelles distinctes :

$$
\Delta>0
$$

Donc :

$$
4-4m>0
$$

$$
m<1
$$

Ainsi :

$$
\boxed{m<1}
$$

</details>

---

### Exercice 17 — Inéquation rationnelle

Résoudre :

$$
\frac{x-2}{x+1}>0
$$

<details>
<summary>👉 Voir la correction</summary>

Valeurs importantes :

$$
x=2
$$

annule le numérateur, et :

$$
x=-1
$$

annule le dénominateur et est donc interdit.

Étude des signes :

- sur $]-\infty,-1[$ : quotient positif ;
- sur $]-1,2[$ : quotient négatif ;
- sur $]2,+\infty[$ : quotient positif.

L'inégalité est stricte, donc $x=2$ n'est pas inclus.

$$
\boxed{x\in]-\infty,-1[\cup]2,+\infty[}
$$

</details>

---

### Exercice 18 — Simplification avec condition

On considère :

$$
A=\frac{x^2-5x+6}{x^2-4}
$$

1. Factoriser numérateur et dénominateur.
2. Simplifier l'expression.
3. Donner les valeurs interdites.

<details>
<summary>👉 Voir la correction</summary>

Numérateur :

$$
x^2-5x+6=(x-2)(x-3)
$$

Dénominateur :

$$
x^2-4=(x-2)(x+2)
$$

Donc :

$$
A=\frac{(x-2)(x-3)}{(x-2)(x+2)}
$$

On peut simplifier par $x-2$, mais seulement avec :

$$
x\neq2
$$

Le dénominateur initial impose aussi :

$$
x\neq-2
$$

Donc :

$$
\boxed{A=\frac{x-3}{x+2}}
$$

avec :

$$
\boxed{x\neq2\quad\text{et}\quad x\neq-2}
$$

</details>

---

### Exercice 19 — Problème de méthode

Résoudre :

$$
(x^2-5x+6)(x-4)=0
$$

sans développer.

<details>
<summary>👉 Voir la correction</summary>

On factorise directement :

$$
x^2-5x+6=(x-2)(x-3)
$$

Donc :

$$
(x-2)(x-3)(x-4)=0
$$

Un produit est nul si au moins un facteur est nul :

$$
\boxed{x=2,\quad x=3,\quad x=4}
$$

**Méthode à retenir :** ne pas développer lorsqu'une factorisation permet de résoudre directement.

</details>

---

### Exercice 20 — Problème de synthèse

On considère :

$$
f(x)=\frac{x^2-4}{x-1}
$$

1. Déterminer le domaine de définition.
2. Factoriser le numérateur.
3. Peut-on simplifier l'expression ?
4. Calculer $f(0)$.
5. Résoudre $f(x)=0$.

<details>
<summary>👉 Voir la correction</summary>

#### 1. Domaine

Le dénominateur ne doit pas être nul :

$$
x-1\neq0
$$

Donc :

$$
\boxed{D_f=\mathbb R\setminus\{1\}}
$$

#### 2. Factorisation

$$
x^2-4=(x-2)(x+2)
$$

Donc :

$$
f(x)=\frac{(x-2)(x+2)}{x-1}
$$

#### 3. Simplification

Aucun facteur $x-1$ n'est présent au numérateur.

Donc l'expression ne se simplifie pas.

#### 4. Calcul de $f(0)$

$$
f(0)=\frac{-4}{-1}=4
$$

Donc :

$$
\boxed{f(0)=4}
$$

#### 5. Résolution de $f(x)=0$

Une fraction est nulle lorsque son numérateur est nul et son dénominateur non nul.

$$
(x-2)(x+2)=0
$$

Donc :

$$
x=2\quad\text{ou}\quad x=-2
$$

Ces deux valeurs appartiennent au domaine.

Ainsi :

$$
\boxed{S=\{-2,2\}}
$$

</details>

---

## 8. Bilan de fin de séance

### Les 5 réflexes à retenir

#### Réflexe 1 — Avant de calculer

**Je regarde les parenthèses, les signes et les priorités.**

#### Réflexe 2 — Avant de résoudre

**Je cherche si je peux factoriser.**

#### Réflexe 3 — Avec une fraction

**Je cherche toujours les valeurs interdites.**

#### Réflexe 4 — Avec une inéquation

**Si je multiplie ou divise par un nombre négatif, j'inverse le sens.**

#### Réflexe 5 — Avant une étude de fonction

$$
\boxed{\text{Domaine de définition}}
$$

doit être l'un des premiers réflexes.

---

## 9. Mini-évaluation de sortie — 5 minutes

À faire sans aide.

### A

Factoriser :

$$
x^2-10x+25
$$

### B

Résoudre :

$$
(x-3)(2x+5)=0
$$

### C

Déterminer le domaine de :

$$
f(x)=\frac{\sqrt{x-1}}{x-4}
$$

### D

Résoudre :

$$
\frac{x-3}{x+2}\leq0
$$

<details>
<summary>👉 Voir les réponses</summary>

**A**

$$
\boxed{(x-5)^2}
$$

**B**

$$
\boxed{x=3\quad\text{ou}\quad x=-\frac52}
$$

**C**

Il faut :

$$
x-1\geq0
$$

et :

$$
x\neq4
$$

Donc :

$$
\boxed{D_f=[1,4[\cup]4,+\infty[}
$$

**D**

Valeurs importantes :

$$
x=3,\qquad x=-2
$$

Le quotient est négatif ou nul sur :

$$
\boxed{]-2,3]}
$$

</details>

---

## 10. Travail personnel avant la séance 2

Si l'élève a besoin de consolider :

- refaire les exercices 8, 10, 12, 13, 15 et 17 ;
- refaire sans regarder la correction les exercices qu'il a ratés ;
- apprendre les trois identités remarquables ;
- revoir les règles de signes ;
- revoir la méthode du discriminant ;
- être capable d'expliquer à l'oral pourquoi le **domaine de définition** est important.

### Pour le professeur

Noter à la fin de la séance :

- erreurs de calcul ;
- erreurs de signe ;
- difficultés de factorisation ;
- difficultés avec les équations ;
- difficultés avec les inéquations ;
- compréhension du domaine de définition ;
- autonomie face à un exercice ;
- temps nécessaire pour résoudre un exercice.

Ces observations serviront à adapter les séances suivantes.

---

## Suite des quatre séances

| Séance | Thème principal |
|---|---|
| **1** | **Bases de calcul algébrique + équations/inéquations + domaine de définition** |
| **2** | **Fonctions et dérivation : étude de fonction complète** |
| **3** | **Suites + trigonométrie**, selon le niveau observé |
| **4** | **Probabilités + sujet de synthèse type Terminale + bilan** |

> **Principe :** les quatre séances ne doivent pas être indépendantes. Le diagnostic de la séance 1 doit permettre d'adapter le contenu des séances 2, 3 et 4 aux difficultés réelles de l'élève.
