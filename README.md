[Lien de ma Vcard](https://menozzilorenzo.github.io/VCard/)

# Description

Ce repo représente la Vcard que j'ai dû créée, le 2 Mai 2019, dans le cadre de ma formation chez BeCode.

# Contenu

Dans ce repo, vous y trouverez :
- le fichier HTML
- le fichier CSS
- un dossier comprenant la font que j'ai utilisée
- un dossier comprenant les images 

# Objectifs

Les objectifs définis consistaient à :
- Améliorer la sémantique HTML
- Connaître plus de propriétés CSS
- Améliorer ses compétences en positionnement CSS

# Présentation de mon code

Pour la création de ma Vcard, je me suis servi du système de grid pour placer mes différents éléments.
La mise en place de mes grid s'est faite via CSS, avec comme procédé : 

```css

.grid-container {
    display: grid;
    grid-template-columns: 30% 26% 40%;
    grid-template-rows: 80% 20%;
    grid-template-areas: "photo info info" "link link link";
    background: linear-gradient(#3d4451,#e8676b)
}
```
Par la suite j'ai défini la place des éléments :

```css

.photo { 
    grid-area: photo;
}

.info { 
    grid-area: info;
    font-family: 'open_sansregular';
}

.link { 
    grid-area: link;
    position: relative;
}
```
