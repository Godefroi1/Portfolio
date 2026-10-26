---
layout: default
title: Mon Portfolio
---

<script data-goatcounter="https://godefroi.goatcounter.com/count"
        async src="//gc.zgo.at/count.js"></script>

# Godefroi TRUCHE
**Ingénieur en Mécatronique | IMT Mines Alès**

# Bienvenue sur mon portfolio !

Passionné par la **robotique mobile** et l'**Intelligence Artificielle**, je combine une formation théorique solide avec une pratique concrète du prototypage. 
Mon objectif est de concevoir des systèmes intelligents en intégrant des technologies comme **ROS 2** et **YoloV8** afin de développer de nouvelles technologies.

### 🛠 Compétences Techniques (Issues de mon parcours)

| Catégorie | Technologies & Logiciels |
| :--- | :--- |
| **Robotique & IA** | ROS 2, Python (intermédiaire), Vision par ordinateur (YoloV8) |
| **Conception & Simulation** | SolidWorks, COMSOL Multiphysics, Ansys, PrePoMax |
| **Systèmes Embarqués** | ESP32, Raspberry Pi, Arduino (Communication série, I2C/SPI), FPGA  |
| **Langues** | Anglais (TOEIC 970/990), Français (Maternel) |

## Projets personnels

- [Plateforme de Stewart](projet-stewart.md)
  *  **Système Embarqué :** Développement sur ESP32 et implémentation d'algorithmes de cinématique inverse.
  *  **Contrôle :** Création d'une IHM sous Processing pour le pilotage en temps réel.
  *  **Mécatronique :** Synchronisation de 6 servomoteurs pour des mouvements fluides et précis.

<div style="display: flex; gap: 1.5em; align-items: center; flex-wrap: wrap; margin: 1.5em 0;">

<div style="flex: 1 1 320px;" markdown="1">

- [Tourelle autonome](projet-tourelle.md)
  * **Suivi Autonome :** Intégration du traitement du flux vidéo en temps réel de la webcam par le modèle d'IA YoloV8.
  * **Electronique :** Création d'une architecture de commande et puissance commandée par un ESP32 qui communique en USB avec le PC.
  * **Mécanique :** Modélisation et impression 3d des pièces de la tourelle (bâti, poulies, galet tendeur).

</div>

<a href="{{ '/projet-tourelle.html' | relative_url }}" style="flex: 0 1 280px; max-width: 100%;">
  <img src="{{ '/assets/tourelle/photo_tourelle_.jpg' | relative_url }}"
       alt="Tourelle autonome avec suivi par YOLOv8"
       style="width: 100%; height: auto; display: block; border-radius: 8px;">
</a>

</div>

### Projets académiques

- [Robot de démantèlement (partenariat CEA)](projet-cea.md)

   * **Modélisation URDF & Simulation :**
      * Conception et rédaction du fichier **URDF** (Unified Robot Description Format) pour définir la structure cinématique du robot (joints et links).
      * Intégration du modèle sous **Foxglove** pour le monitoring de l'état du robot en temps réel.

   * **Perception par Intelligence Artificielle (YOLOv8) :**
      * Implémentation d'un nœud de vision utilisant **YOLOv8** pour la reconnaissance et le tri d'objets spécifiques.

   * **Architecture Logicielle ROS :**
      * Développement de l'architecture de communication série entre Raspberry Pi 5 et Arduino Uno et Méga.
      * Rédaction d'une documentation technique exhaustive pour l'utilisateur final.

#### Contact
