# **Exercice CSS**

## **Objectif**

Apprendre à :

- Sélectionner les éléments HTML via **balises, classes et ID**
- Appliquer des **styles de base** : couleurs, polices, tailles, marges et paddings
- Comprendre comment chaque style affecte un élément

---

## **1. HTML de base**

Copie ce code HTML dans un fichier `index.html` :

```html
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Exercice CSS Débutant</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <header id="main-header">
        <h1 class="title">Bienvenue sur ma page</h1>
        <p class="subtitle">Apprenons le CSS pas à pas !</p>
    </header>

    <nav class="menu">
        <ul>
            <li class="menu-item">Accueil</li>
            <li class="menu-item">À propos</li>
            <li class="menu-item">Contact</li>
        </ul>
    </nav>

    <section class="content">
        <h2>Section principale</h2>
        <p>Voici un paragraphe pour tester vos styles CSS.</p>
        <p class="highlight">Ce paragraphe doit ressortir avec une couleur différente.</p>
    </section>

    <footer id="main-footer">
        <p>Copyright 2025 - Tous droits réservés</p>
    </footer>

</body>
</html>

```

---

## **2. Tâches CSS**

Crée un fichier `styles.css` et applique les styles suivants. Lis attentivement chaque instruction et applique-les correctement.

### **2.1 Header**

- Sélecteur : `#main-header`
- Styles :
    - `background-color` : #f0f0f0
    - `padding` : 20px
    - `text-align` : center
- Sélecteur : `.title`
- Styles :
    - `color` : #2c3e50
    - `font-family` : Arial, sans-serif
    - `font-size` : 36px
- Sélecteur : `.subtitle`
- Styles :
    - `color` : #7f8c8d
    - `font-size` : 18px

---

### **2.2 Menu**

- Sélecteur : `.menu`
- Styles :
    - `background-color` : #3498db
    - `padding` : 10px
- Sélecteur : `.menu-item`
- Styles :
    - `display` : inline-block
    - `margin-right` : 15px
    - `color` : white
    - `font-weight` : bold
    - `cursor` : pointer

---

### **2.3 Section principale**

- Sélecteur : `.content`
- Styles :
    - `padding` : 20px
    - `background-color` : #ecf0f1
- Sélecteur : `.content h2`
- Styles :
    - `color` : #34495e
    - `font-size` : 28px
- Sélecteur : `.content p`
- Styles :
    - `color` : #2c3e50
    - `line-height` : 1.6
- Sélecteur : `.highlight`
- Styles :
    - `color` : #e74c3c
    - `font-weight` : bold

---

### **2.4 Footer**

- Sélecteur : `#main-footer`
- Styles :
    - `background-color` : #2c3e50
    - `color` : white
    - `text-align` : center
    - `padding` : 15px
    - `font-size` : 14px

---

## **3. Bonus (facultatif)**

- Ajouter un **hover** sur les `.menu-item` pour changer leur couleur au survol :

```css
.menu-item:hover {
    color: #f1c40f;
}

```

---

## **4. Instructions**

1. Commence par appliquer les styles pour le header et observe le rendu.
2. Passe au menu, puis à la section principale et au footer.
3. Vérifie que chaque élément a bien pris la couleur, la taille, le padding ou la marge indiquée.
4. Expérimente : change les couleurs, polices et tailles pour voir l’effet.