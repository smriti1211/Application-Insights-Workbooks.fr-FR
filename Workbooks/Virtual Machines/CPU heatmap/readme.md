# <a name="cpu-heatmap"></a>Carte thermique du processeur

Ce classeur est un bon moyen de visualiser les zones réactives dans l’utilisation du processeur de vos machines virtuelles.

![Image d’une carte thermique de processeur](cpu-heatmap.png)

## <a name="changing-the-cpu-threshold"></a>Changement du seuil de processeur
Par défaut, ce classeur met en évidence les machines virtuelles avec un `Percentage CPU` moyen supérieur à 75 %. Si vous souhaitez augmenter ou diminuer ce seuil, voici les étapes à suivre :

1. Cliquez sur l’élément `Edit` dans la barre d’outils.
2. Cliquez sur le bouton `↑ Edit` en bas à droite du contrôle hive.
3. Faites défiler la liste `Columns Available After Merge` vers le bas et sélectionnez l’élément `[Added column] - Cell Color`.
4. Cliquez sur le bouton `Edit added item` dans la barre d’outils du contrôle hive.
5. Dans le volet qui apparaît, cliquez sur `Edit` sur l’élément qui indique `Percentage CPU > 75 Result is E8976A` pour voir une fenêtre contextuelle de paramètres.
    1. Affectez au champ `Second operand` le seuil de votre choix, par exemple 90.
        ![Image d’une carte thermique de processeur](cpu-heatmap-column-settings.png)
    2. Cliquez sur op dans la fenêtre contextuelle.
6. Cliquez sur Enregistrer et fermer.
7. Choisissez `Done Editing` dans la barre d’outils du classeur.
