# 🔍 Détection de Défauts Industriels par CNN

![Python](https://img.shields.io/badge/Python-3.10-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![Accuracy](https://img.shields.io/badge/Précision-99.07%25-green)

## Description
Système de détection automatique de défauts de surface 
sur pièces métalliques par CNN interprétable.

## Dataset
- **NEU Surface Defect Database**
- 1440 images — 6 classes — 224×224 pixels
- Niveaux de gris

## Classes détectées
| Classe | Description |
|--------|-------------|
| Crazing | Fissures réseau |
| Inclusion | Particules étrangères |
| Patches | Taches irrégulières |
| Pitted Surface | Surface piquée |
| Rolled-in Scale | Écailles incrustées |
| Scratches | Rayures |

## Résultats
- ✅ Précision : **99.07%** sur le jeu de test
- ✅ Grad-CAM pour l'interprétabilité
- ✅ Réseau Siamois + t-SNE
- ✅ Interface web Gradio

## Lancer le projet
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](LIEN_TON_NOTEBOOK)

## Technologies
- TensorFlow / Keras
- OpenCV
- Grad-CAM
- Gradio
- Scikit-learn

## Auteur
Projet réalisé dans le cadre du module Deep Learning  
EPI Digital School — 4ème Année IoT  
Encadrante : Mme Souhir MABROUK
