Le CSS utilise une syntaxe composée de selecteurs, de propriètés et de valeur.
``` 
   selecteur {                              p {
        propriété: valeur;                      color: blue;          
    }                                           font-size: 16px;
                                              }
```
Cela applique la couleur bleue et une taile de police à 16px à tous les paragraphes `p`

4 manières de mettre du CSS:\
1 CSS en ligne (inline CSS) ajout directement dans l'attribut style d'une balise html\
2 CSS interne (dans `style`) ajout dans une balise `style` dans l'entête `head` du document html\
3 CSS externe (dans un fichier .css) création d'un fichier externe (style.css) relié avec `link` dans html\
4 CSS via un preprocesseur (ex: SASS/SCSS) permet une meilleur organisation avec des variables et des mixins 
## 📝 1. Mise en forme du texte

| Propriété | Description | Exemple |
|-----------|------------|---------|
| `color` | Définit la couleur du texte | `color: blue;` |
| `font-size` | Définit la taille de la police | `font-size: 18px;` |
| `font-weight` | Épaisseur du texte (`normal`, `bold`, etc.) | `font-weight: bold;` |
| `font-style` | Style du texte (`normal`, `italic`) | `font-style: italic;` |
| `font-family` | Police de caractères | `font-family: Arial, sans-serif;` |
| `text-align` | Alignement (`left`, `center`, `right`, `justify`) | `text-align: center;` |
| `text-transform` | Transformation (`uppercase`, `lowercase`) | `text-transform: uppercase;` |
| `letter-spacing` | Espacement entre lettres | `letter-spacing: 2px;` |
| `line-height` | Espacement entre lignes | `line-height: 1.5;` |
| `text-decoration` | Décoration (`none`, `underline`, etc.) | `text-decoration: underline;` |
| `text-shadow` | Ombre au texte | `text-shadow: 2px 2px 5px gray;` |

---

## 🎨 2. Couleurs et arrière-plan

| Propriété | Description | Exemple |
|-----------|------------|---------|
| `background-color` | Couleur de fond | `background-color: lightgray;` |
| `background-image` | Image de fond | `background-image: url("image.jpg");` |
| `background-size` | Taille de l’image (`cover`, `contain`) | `background-size: cover;` |
| `background-repeat` | Répétition (`repeat`, `no-repeat`) | `background-repeat: no-repeat;` |
| `background-position` | Position de l’image (`top`, `center`) | `background-position: center;` |

---

## 📏 3. Dimensions et Espacements

| Propriété | Description | Exemple |
|-----------|------------|---------|
| `width` | Largeur de l’élément | `width: 300px;` |
| `height` | Hauteur de l’élément | `height: 200px;` |
| `margin` | Espace **extérieur** | `margin: 10px;` |
| `padding` | Espace **intérieur** | `padding: 15px;` |
| `box-sizing` | Gestion de la taille (`content-box`, `border-box`) | `box-sizing: border-box;` |

---

## 🔳 4. Bordures et Ombres

| Propriété | Description | Exemple |
|-----------|------------|---------|
| `border` | Bordure (`épaisseur type couleur`) | `border: 2px solid black;` |
| `border-radius` | Coins arrondis | `border-radius: 10px;` |
| `box-shadow` | Ombre autour de l’élément | `box-shadow: 5px 5px 10px gray;` |

---

## 🎭 5. Effets au survol et animations

| Propriété | Description | Exemple |
|-----------|------------|---------|
| `:hover` | Effet au survol | `button:hover { background-color: red; }` |
| `transition` | Effet fluide | `transition: all 0.3s ease-in-out;` |
| `@keyframes` | Animation personnalisée | `@keyframes anim { 0% {opacity: 0;} 100% {opacity: 1;} }` |
| `animation` | Appliquer une animation | `animation: anim 2s infinite;` |

---

| Selecteur | Utilisation |
|-----------|-------------|
|Element (`div`, `p`, `h1`) | Selectionne tous les éléments du même type |
| Classe (`.maClasse`) | Appliqué à plusierus éléments |
| ID (`#monID`) | Unique pour un élément |
| Pseudo-classe (`:hover`, `:nth-child(n)`) | Applique un style sous certaines conditions |
| Pseudo-élément (`: : before`, `: : after`) | Permet de styliser une partie d'un élément |
| Selecteur universel (`*`) | Selectionne tous les éléments |
---