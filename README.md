# VSCode PDF Template
## Template for projects under Visual Studio Code.
---

<div class="page"/>


<div class="table-of-content"/>

## Table of content:

<div class="table-of-content"/>

- [1. Introduction:](#1-introduction)
- [2. Resolvable marqueurs:](#2-resolvable-marqueurs)
  - [2.1. Table of content:](#21-table-of-content)
  - [2.2. Courrier Expéditeur:](#22-courrier-expéditeur)
  - [2.3. Factures et Devis:](#23-factures-et-devis)
  - [2.3. Documents:](#23-documents)
    - [Information du document:](#information-du-document)

<div class="page"/>

### 1. Introduction:

Ce projet permet de générer à partir d'un markdown un PDF avec un template sur mesure correspondant aux exigences de l'entreprise.

<div class="page"/>





### 2. Resolvable marqueurs:

<!-- Table des matières ========================= -->
#### 2.1. Table of content:

```markdown
<div class="table-of-content"/>

## Table des matières:

<div class="table-of-content"/>

- [1. Introduction:](#1-introduction)
- [3. Resolvable marqueurs:](#3-resolvable-marqueurs)
  - [2. Table of content:](#2-table-of-content)
  - [3.1. Courrier Expéditeur:](#31-courrier-expéditeur)
  - [3.2. Factures et Devis:](#32-factures-et-devis)

```

**Résultat:**

<div class="table-of-content"/>

## Table of content:

<div class="table-of-content"/>

- [1. Introduction:](#1-introduction)
- [2. Resolvable marqueurs:](#2-resolvable-marqueurs)
  - [2.1. Table of content:](#21-table-of-content)
  - [2.2. Courrier Expéditeur:](#22-courrier-expéditeur)
  - [2.3. Factures et Devis:](#23-factures-et-devis)
  - [2.3. Documents:](#23-documents)
    - [Information du document:](#information-du-document)

<div class="page"/>





<!-- Courriers, Lettres ========================= -->

#### 2.2. Courrier Expéditeur:

```markdown
<div class="courrier-expediteur" />

**SAS RESOLVABLE**
Adresse...
CODE Postal + Ville...
FRANCE
```

```markdown
<div class="courrier-destinataire" />

**Client...**
Adresse...
CODE Postal + Ville...
PAYS...
```

```markdown
<div class="courrier-objet" />

***Objet du courrier***
*Complément...*
```

**Résultat:**

<div class="courrier-expediteur" />

**SAS RESOLVABLE**
Adresse...
CODE Postal + Ville...
FRANCE

<div class="courrier-destinataire" />

**Client...**
Adresse...
CODE Postal + Ville...
PAYS...

<div class="courrier-objet" />

***Objet du courrier***
*Complément...*

<div class="page"/>




<!-- Factures et devis ========================= -->
#### 2.3. Factures et Devis:

```markdown
<div class="facture-validite" />

| Date d'émission : JJ/MM/AAAA | Validité: *30 jours* |
| :--------------------------- | -------------------: |
```

```markdown
<div class="facture-content" />

| REF: | DESIGNATION |  TVA | PRIX HT |
| :--- | :---------- | ---: | ------: |
| REF: | DESIGNATION |  20% |    620€ |
| REF: | DESIGNATION |  20% |    620€ |
| REF: | DESIGNATION |  20% |    620€ |
| REF: | DESIGNATION |  20% |    620€ |
| REF: | DESIGNATION |  20% |    620€ |
| REF: | DESIGNATION |  20% |    620€ |
```


```markdown
<div class="facture-conditions" />

En cas de retard de paiement, une pénalité de 3 fois le taux d'intérêt légal sera appliqué à laquelle s'ajoutera une indemnité forfaitaire pour frais de recouvrement de 40€.
**Virement à effectuer sur le compte:**
**IBAN: *XXXX XXXX XXXX XXXX***
**BIC: *MA BANQUE***
```

```markdown
<div class="facture-total" />

|       TOTAL HT | 65000€ |
| -------------: | -----: |
|    Montant TVA | 13000€ |
|      TOTAL TTC | 78000€ |
| Durée (Ouvrés) |  135 J |


```

**Résultat:**

<div class="facture-validite" />

| Date d'émission : JJ/MM/AAAA | Validité: *30 jours* |
| :--------------------------- | -------------------: |

<div class="facture-content" />

| REF: | DESIGNATION |  TVA | PRIX HT |
| :--- | :---------- | ---: | ------: |
| REF: | DESIGNATION |  20% |    620€ |
| REF: | DESIGNATION |  20% |    620€ |
| REF: | DESIGNATION |  20% |    620€ |
| REF: | DESIGNATION |  20% |    620€ |
| REF: | DESIGNATION |  20% |    620€ |
| REF: | DESIGNATION |  20% |    620€ |


<div class="facture-conditions" />

En cas de retard de paiement, une pénalité de 3 fois le taux d'intérêt légal sera appliqué à laquelle s'ajoutera une indemnité forfaitaire pour frais de recouvrement de 40€.
**Virement à effectuer sur le compte:**
**IBAN: *XXXX XXXX XXXX XXXX***
**BIC: *MA BANQUE***

<div class="facture-total" />

|       TOTAL HT | 65000€ |
| -------------: | -----: |
|    Montant TVA | 13000€ |
|      TOTAL TTC | 78000€ |
| Durée (Ouvrés) |  135 J |



<div class="page" />

<!-- Documents ========================= -->
#### 2.3. Documents:

##### Information du document:
###### Statut d'avancement:

```markdown
<div class="document-status" />

| DOCUMENT STATUS: | IN PROGRESS |
| :--------------- | :---------- |
```
###### Résumé du document:

```markdown
<div class="document-resume" />

***RESUME:***
Voici le résumé de mon histoire ça peut être court comme long et c'est tant mieux.
```
###### Validation du document:

```markdown
<div class="document-validation" />

| VALIDATION CIRCUIT | NAME  | FUNCTION | SIGNATURE and DATE |
| :----------------- | :---: | :------: | :----------------: |
| WRITTEN BY:        |       |          |                    |
| APPROUVED BY:      |       |          |                    |
| CLIENT APPROVAL:   |       |          |                    |
```

**Résultat:**

<div class="document-status" />

| DOCUMENT STATUS: | IN PROGRESS |
| :--------------- | :---------- |


<div class="document-resume" />

***RESUME:***
Voici le résumé de mon histoire ça peut être court comme long et c'est tant mieux.


<div class="document-validation" />

| VALIDATION CIRCUIT | NAME  | FUNCTION | SIGNATURE and DATE |
| :----------------- | :---: | :------: | :----------------: |
| WRITTEN BY:        |       |          |                    |
| APPROUVED BY:      |       |          |                    |
| CLIENT APPROVAL:   |       |          |                    |

