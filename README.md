# Image → app.icns

Outil HTML pour convertir une image en icône macOS (`app.icns`) directement dans le navigateur.
Aucune installation, aucun serveur — tout se passe en local.

-----

## Utilisation

Ouvrez `index.html` dans votre navigateur, glissez votre image, puis cliquez sur **Générer app.icns**.

-----

## Formats acceptés

|Format|Extension                           |
|------|------------------------------------|
|PNG   |`.png`                              |
|JPEG  |`.jpg` / `.jpeg`                    |
|WebP  |`.webp`                             |
|GIF   |`.gif` *(première image uniquement)*|
|BMP   |`.bmp`                              |
|SVG   |`.svg`                              |


> **Poids maximum : 20 Mo**

-----

## ⚠️ Image carrée obligatoire

Une icône macOS est toujours carrée. Il est donc **indispensable d’utiliser une image dont la largeur et la hauteur sont identiques** (ratio 1:1), par exemple 512×512 ou 1024×1024 px.

Une image non carrée sera déformée lors de la conversion (étirement horizontal ou vertical).

**Résolution recommandée : 1024 × 1024 px minimum** pour garantir une qualité optimale sur les écrans Retina.

-----

## Résolutions générées

L’outil produit automatiquement les 10 résolutions requises par macOS :

`16px` `32px` `64px` `128px` `256px` `512px` `1024px` + variantes Retina @2x