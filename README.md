![](https://img.shields.io/badge/project%20size-2.4To-green)

# Start-up Display

## Contextualisation de la création de Display

Tout d'abord, Display est une start-up créée par six étudiants chez MyDigitalSchool Nantes, une école du digital. Au sein de cette équipe, nous comptons différents profils. Du développeur informatique à l'UX/UI designer en passant par du digital marketing, nous nous sommes réunis afin de fonder cette start-up qui nous suivra sur nos deux années de master (et peut-être plus loin encore !). 

### *Display, qu'est-ce que c'est ?*

Display est une agence évènementielle proposant des services aux entrerprises. L'objectif est l'organisation d'évènements professionnels types séminaires, *ice-breaker*, *team building*, avec l'aide du jeu vidéo. Passionnés par ce monde, nous avons décidé de créer cette start-up afin de donner une place au jeu vidéo dans le monde de l'entreprise et permettre aux gens de découvrir ou redécouvrir ce genre de formats. Par le biais de plusieurs packs, nous offrons la possibilité à une équipe ou plus globalement une entreprise, de renforcer / améliorer la cohésion entre les différents salariés dans une optique de meilleures performances, meilleure efficacité et surtout créer du lien et une ambiance méliorative au sein du groupe. 

---

## Intérêt et présentation du site

Le site de Display centralisera toutes les informations nécessaires pour se renseigner et prendre contact avec nous pour réserver un créneau avec une offre.

Il s'agit d'un site vitrine présentant nos offres, il n'y a donc pas de backend prévu. Toute cette gestion est géré par un CRM externe au contexte du site.

L'intérêt du site est surtout de créer un support de contact entre clients et Display.  

### **Déployer le site en local**

Il suffit de cloner le site sur votre *desktop* et de suivre quelques étapes très simples : 

**Cloner le projet en local**
- Récupérer le lien HTTPS du projet (ou SSH pour ceux qui ont associé leur clef avec git) 
 
  ->  Bouton "Code" -> HTTPS -> Copier le lien dans la zone de texte
- git clone "lien HTTPS ou SSH" dans le répertoire souhaité
- Se placer dans le dossier frontend
- Faire un **yarn dev** ou **npm run start** pour lancer l'application sur le port 3000 (*localhost:3000*)

*Vous pouvez directement passer à l'étape 3 si vous avez téléchargé l'archive*  

---

## Choix des technologies utilisées

Front : NextJS - React
Electron pour intégrer en application desktop

Back : Dans l'idéal, utiliser Java serait la solution adéquate. Néanmoins, étant seul développeur sur le projet, il me paraît compliqué de devoir gérer toute cette complexité. 
