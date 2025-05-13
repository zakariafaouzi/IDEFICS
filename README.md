# IDEFICS

**IDEFICS** est un modèle multimodal de 80 milliards de paramètres qui accepte des séquences d'images et de textes en entrée et génère un texte cohérent en sortie. Il peut répondre à des questions sur les images, décrire du contenu visuel, créer des histoires basées sur plusieurs images, etc.

IDEFICS est une reproduction en libre accès de Flamingo et offre des performances comparables à celles du modèle original à code source fermé sur divers tests de compréhension image-texte. Il est disponible en deux variantes : 80 milliards de paramètres et 9 milliards de paramètres ($idefics-80B-instruct$ et $idefics-9B-instruct$).

## Caractéristiques

- **Multimodalité** : IDEFICS peut traiter à la fois des images et du texte, ce qui lui permet de répondre à des questions sur des images, de décrire du contenu visuel et de créer des histoires basées sur plusieurs images.
- **Performance** : IDEFICS offre des performances comparables à celles du modèle Flamingo à code source fermé sur divers tests de compréhension image-texte.
- **Variantes** : IDEFICS est disponible en deux variantes : 80 milliards de paramètres et 9 milliards de paramètres.

## Installation

```bash
pip install idefics
```


# MedIDEFICS

## About the project 
<p align="center">
  <img src="MedIDEFICS.png" alt="Logo" width="200" height="200" style="display: block; margin: auto;">
</p>


MedIDEFICS (**M**edical **I**mage-aware **D**ecoder **E**nhanced à la **F**lamingo with **I**nterleaved **C**ross-attention**S**) est une version fine-tunée du modèle IDEFICS-9b-instruct, lui-même une version optimisée du modèle IDEFICS-9b, adaptée au suivi d’instructions.

MedIDEFICS a été spécifiquement ajusté pour répondre à des questions médicales liées à des images. Ses capacités incluent la description de contenu visuel (diagnostic), la génération de recommandations, ou encore le fonctionnement en tant que modèle de langage médical, même sans entrée visuelle.



