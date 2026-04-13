---
layout: default
title: Plateforme de Stewart
---

# Plateforme de Stewart

## 🔹 Qu’est-ce qu’une plateforme de Stewart ?

Une **plateforme de Stewart**, également appelée **plateforme hexapode**, est un système mécatronique permettant de positionner et d’orienter une plateforme mobile dans l’espace selon **six degrés de liberté**.

Ces six degrés de liberté correspondent à :
- trois **translations** : X, Y, Z  
- trois **rotations** : roulis (*roll*), tangage (*pitch*) et lacet (*yaw*)
  
Hexapod_general_Anim.gif
``
---

## 🧩 Principe de fonctionnement

La structure est composée de :
- une **base fixe**
- une **plateforme mobile**
- **six actionneurs** (vérins ou bras motorisés) reliant la base à la plateforme mobile

Chaque actionneur peut varier sa longueur.  
En ajustant précisément la longueur des six actionneurs, il est possible de contrôler simultanément la **position** et l’**orientation** de la plateforme mobile.

Les mouvements sont obtenus grâce au calcul de la **cinématique inverse** :  
à partir d’une position et d’une orientation souhaitées, le système détermine la longueur que doit prendre chaque actionneur.

---


