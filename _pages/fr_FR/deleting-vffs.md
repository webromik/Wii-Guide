---
title: "Suppression des VFF"
---

{% include toc title="Table des matières" %}

Si vous avez besoin d'aide concernant ce tutoriel, veuillez rejoindre [le serveur Discord de RiiConnect24](https://discord.gg/b4Y7jfD) (recommandé, en anglais) ou [envoyez-nous un mail à support@riiconnect24.net](mailto:support@riiconnect24.net).
{: .notice--info}

![RiiConnect24 Logo](/images/WiiRC24Logo.jpg)

Si vous obtenez l'une de ces erreurs (et aucune autre erreur), vous devriez être en mesure de réparer la chaîne en supprimant votre VFF.

+ Discontinued Message
+ NEWS/FORE000001
+ NEWS/FORE000003
+ NEWS/FORE000005
+ NEWS/FORE000099

#### Ce dont vous avez besoin
* Une carte SD ou un périphérique USB
* [WiiXplorer](https://sourceforge.net/projects/wiixplorer/files/latest/download)

#### Dossier à supprimer

+ Chaîne météo
  + 48414645
  + 4841464a
  + 48414650

+ Chaîne infos
  + 48414745
  + 4841474a
  + 48414750

#### Instructions

1. Ouvrez WiiXplorer.
2. Accédez à `Start` -> `Settings` -> `Boot Settings` -> `Enable NAND write access` puis sélectionnez `Yes` pour les deux fenêtres de dialogue qui apparaissent à l'écran.
3. Appuyez sur "Back" (retour) jusqu'à ce que vous ayez atteint l'écran de l'explorateur de fichiers.
4. Sélectionnez la petite icône bleue de la carte SD, puis sélectionnez ` NAND `.
5. Accédez à ` title ` -> ` 00010002 ` -> XXXXXXXX -> ` data `, où XXXXXXXX est l'un des dossiers ci-dessus.
6. Survolez ` wc24dl.vff `, appuyez sur le bouton + et sélectionnez `Delete `.

Essayez de lancer la chaîne avec laquelle vous rencontrez des problèmes.

[Retour à la page d'installation de RiiConnect24](riiconnect24)
{: .notice--info}
