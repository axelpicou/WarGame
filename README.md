# 🔥 WAR GAME - Prototype de Simulation de Véhicules de Guerre 🔥

> *"Tank ou Avion... À toi de dominer les airs et la terre."*

![WarGame Banner](https://capsule-render.vercel.app/api?type=wave&color=auto&height=150&section=header&text=WAR%20GAME&fontSize=50&animation=twinkling)

---

## 🎮 Présentation rapide

> WarGame est un prototype Unreal Engine de simulation de véhicules de guerre.  
Actuellement, deux machines de destruction sont jouables :
- Un Tank ultra détaillé, lourd et puissant
- Un Avion agile pour les amateurs de voltige et de dogfight  

Ce projet est un bac à sable technique mêlant gameplay, physique réaliste et FX badass.

---

## 🎮 Contrôles en jeu

### 🪖 Mode TANK
| Action                 | Touche / Contrôle       |
|-----------------------|-------------------------|
| Avancer / Reculer     | Z / S                   |
| Tourner à gauche      | Q                       |
| Tourner à droite      | D                       |
| Tourner la tourelle   | Souris (gauche / droite)|
| Lever / baisser le canon | Souris (haut / bas)  |
| Zoom viser            | Clic droite     |
| Tirer un obus        |  clic gauche  |
| Menu               | P                  |

---

### ✈️ Mode AVION
| Action                 | Touche / Contrôle       |
|-----------------------|-------------------------|
| Accélérer / Freiner   | Shift / CTRL                   |
| Pitch (haut / bas)    | Souris haut / bas       |
| Yaw (gauche / droite) | Q / D                   |
| Roll (rotation avion) | A / E                   |
| Monter / Descendre    | Contrôle automatique (selon vitesse et inclinaison) |
| Menu               | P                  |

---

## 🛠️ Tech et outils utilisés

- Unreal Engine 5  
- Skeleton Mesh + ChaosVehicle (Tank)  
- Template Véhicule UE (HUD & UI)  
- Niagara VFX : fumée, explosions, tirs  
- Sons custom pour les tirs, impacts, explosions  
- Simulation physique avancée (Tank & Avion)  

---

## 🚀 Fonctionnalités principales

### Mode TANK
- Animation réaliste des roues & suspensions
- Tourelle & Canon contrôlables
- Tir d'obus avec zoom (clic gauche) + viseur
- FX de fumée & explosion avec Niagara
- Sons des tirs / impacts / explosions
- Cooldown après chaque tir (reload time)

### Mode AVION
- Simulation de vol & physique réaliste
- Contrôle fluide & réactif en 3D
- Sensations de pilotage type simulateur

---

## 📸 Aperçu du jeu

### 🛞 Mode TANK
> Simulation de Tank avec FX, HUD et contrôles réalistes.

![tank](https://github.com/user-attachments/assets/67edf54d-8c95-4e96-9640-44d090819c2b)
![tank2](https://github.com/user-attachments/assets/872ca1bb-7f1b-44a4-b76c-ece385ee158b)

---

### ✈️ Mode AVION
> Pilotage d’un avion avec physique avancée et maniabilité style simu.

![avion](https://github.com/user-attachments/assets/951a10e1-a646-4087-98b2-eb810a77004c)
![avion2](https://github.com/user-attachments/assets/bd728ff7-96dd-47ff-be99-1c7ffaa3706d)

---

### 🧭 Menu principal
> Sélection du mode de jeu : Tank ou Avion.

![menu](https://github.com/user-attachments/assets/2bffe5ac-0e9c-4f92-a06e-a9ead04d7a9f)
![Wargame](https://github.com/user-attachments/assets/f3723766-53e2-4528-9629-1f40f969a5ea)

---

## 🎮 Comment lancer le projet

Telecharger la build ou cloner le repo :
```bash
git clone https://github.com/axelpicou/WarGame.git
