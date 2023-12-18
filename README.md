# TD_mapping_FR

Créer pour le mapping dans TouchDesigner

## Introduction

L'[Introduction à Touchdesigner](https://github.com/LucieMrc/IntroTD_FR).

L'[Introduction à Madmapper](https://github.com/LucieMrc/Madmapper_2spi).

## Faire apparaître les contours

Prendre une photo de l'objet à mapper.

L'ouvrir dans TD avec `Movie File In` TOP.

Créer à la suite un `Level` TOP, et créer du contraste avec les différents paramètres.

Créer un `Edge` TOP.

## Masquer et faire apparaîres des zones

`Composite` TOP

## Export / video temps réel

Pour exporter une vidéo en .mov : créer un `Movie File Out` TOP à la toute fin du network, choisir un nom et une dossier d'enregistrement pour le fichier dans l'encart "File". Pour commencer à enregistrer, il suffit d'acord le bouton "Record" dans les paramètres et le désactiver pour arrêter d'enregistrer.

<img src="images/screen15.png"/>

Il faut décocher le bouton "Realtime" au milieu du menu en haut, pour que la vidéo ne perdent pas en qualité si Touchdesigner lag un peu.

Pour envoyer la vidéo sur un media server en temps réel ou pour l'envoyer vers MadmApper, il faut installer Syphon (sur mac) ou  Spout (sur windows).

Il suffit ensuite de créer un `Syphon/Spout Out` TOP à la toute fin du network.

# Pour aller + loin
