# 🎮 Carottes-Vaches-Humains Egoiste

## 📝 Description
Simulation explorant les dynamiques de coopération et d'égoïsme entre agents en compétition pour des ressources.

---

## ⚙️ Caractéristiques

### 🌍 Monde
- **Taille** : 2000x3000 pixels  
- **Durée d'une journée** : 30 secondes  
- **Points par vache** : 100  
- **Nombre de vaches** : 200  
- **Seuil de survie** : 55 points  
- **Reproduction** : 1 descendant tous les 50 points supplémentaires  
- **Capacité maison** : 100 agents  

### 🤝 Système de Partage

| Situation                                 | Effet                                                      |
|------------------------------------------- |------------------------------------------------------------|
| **Sous-demande** (≤100%)                  | Pas de perte, reste partagé selon niveaux d'altruisme       |
| **Sur-demande** (>100%)                   | Perte minimum 25%, croissante avec l'avidité                |
| **Agent le plus égoïste**                 | Pénalité supplémentaire de 25%                              |
| **Deux agents très égoïstes** (>70%)      | Perte de 50% en forte demande                               |

---

## 🎛️ Contrôles

- **M** : Basculer mode Auto/Tour  
- **N** : Démarrer jour suivant (mode Tour)  
- **H** : Réinitialiser position caméra  

---

## 👥 Préréglages Population

| Préréglage      | Description                                 |
|-----------------|---------------------------------------------|
| uniform10each   | 10 agents à chaque niveau d'égoïsme (0-100%)|
| all70           | 1000 agents à 70% d'égoïsme                 |
| all30           | 1000 agents à 30% d'égoïsme                 |

---

## 🚀 Installation

> Précisez ici les étapes pour installer et lancer le projet si besoin.

---

## 🛠️ Technologies

- TypeScript
- Canvas HTML5
- Hachage spatial
- Suivi statistiques temps réel

---

## 📄 Licence

MIT
