---
layout: default
title: Plateforme de Stewart
---

# Plateforme de Stewart

## Sommaire 
* TOC
{:toc}

## 🔹 Qu’est-ce qu’une plateforme de Stewart ?

Une **plateforme de Stewart**, également appelée **plateforme hexapode**, est un système mécatronique permettant de positionner et d’orienter une plateforme mobile dans l’espace selon **six degrés de liberté**.

Ces six degrés de liberté correspondent à :
- trois **translations** : X, Y, Z  
- trois **rotations** : roulis (*roll*), tangage (*pitch*) et lacet (*yaw*)
  
<table style="border: none;">
  <tr style="border: none;">
    <td style="border: none;" width="30%">
      <img src="assets/Hexapod_general_Anim.gif" alt="Animation Hexapode" style="width:100%;">
    </td>
    <td style="border: none;" width="70%">
      <img src="assets/stewart-plateform-ouilogique.jpg" alt="Plateforme Stewart" style="width:100%;">
    </td>
  </tr>
</table>
---

## 🧩 Principe de fonctionnement

La structure est composée de :
- une **base fixe**
- une **plateforme mobile**
- **six actionneurs** (vérins ou bras motorisés) reliant la base à la plateforme mobile

Chaque actionneur peut faire varier sa longueur.  
En ajustant précisément la longueur des six actionneurs, il est possible de contrôler simultanément la **position** et l’**orientation** de la plateforme mobile.

Les mouvements sont obtenus grâce au calcul de la **cinématique inverse** :  
à partir d’une position et d’une orientation souhaitées, le système détermine la longueur que doit prendre chaque actionneur.

---

## Première version

Cette première itération a été conçue comme une **Preuve de Concept (PoC)** à coût maîtrisé. En utilisant des matériaux simples et des techniques de prototypage rapide, l'objectif était de valider la chaîne de contrôle et les algorithmes de cinématique inverse avant d'engager le développement d'une version optimisée. 

### ⚙️ Assemblage mécanique

Les **plateformes inférieure et supérieure** sont réalisées à partir **d'hexagones** qui est une des géométrie les plus courante de plateforme de stewart. 


