Exercice 1
Carte de profil simple.

HTML à utiliser (sans id ni classe) :

```html
<div>
    <img src="https://via.placeholder.com/150" alt="avatar">
    <h2>Jean Dupont</h2>
    <p>Développeur Web</p>
    <button>Me contacter</button>
</div>
```

Tâches :

– Sélectionner l’élément racine de la carte (le premier div) et lui donner un fond clair, une largeur fixe, du padding, un border-radius et une ombre légère.
Indication : ce conteneur est la carte entière.

– Sélectionner l’image située directement en premier enfant du conteneur et lui donner une taille fixe ainsi qu’un arrondi complet.
Indication : c’est le seul élément img dans ce div.

– Sélectionner les éléments de texte du nom et du rôle (les deux éléments juste après l’image) et leur appliquer couleur, police et alignement.
Indication : ce sont le h2 puis le p dans ce conteneur.

– Sélectionner le bouton final et définir couleur de fond, couleur du texte, padding et un hover modifiant la couleur de fond.
Indication : c’est l’unique bouton du conteneur.

– Créer un espacement vertical cohérent entre tous les enfants du conteneur en sélectionnant les enfants directs du div ou en réglant chaque élément individuellement.
Indication : utilisez le sélecteur enfant direct.

---

Exercice 2
Mini-layout deux colonnes.

HTML (sans id ni classe) :

```html
<div>
    <aside>
        <h3>Menu</h3>
        <ul>
            <li>Dashboard</li>
            <li>Ventes</li>
            <li>Clients</li>
        </ul>
    </aside>

    <main>
        <h1>Tableau de bord</h1>
        <p>Voici des informations importantes.</p>
        <p>Données mises à jour récemment.</p>
    </main>
</div>
```

Tâches :

– Sélectionner le conteneur global (le premier div) et activer un affichage en flex avec un espace entre les colonnes.
Indication : c’est le seul div englobant aside + main.

– Sélectionner la colonne latérale (aside) et lui donner une largeur fixe, un fond sombre, une couleur de texte claire.
Indication : l’unique élément aside.

– Sélectionner chaque élément de liste dans aside et leur appliquer padding, curseur pointeur et un hover changeant la couleur.
Indication : utilisez aside li.

– Sélectionner la zone principale de contenu (main) et appliquer padding, fond clair, border-radius.
Indication : unique main.

– Différencier les deux paragraphes dans main en stylisant le premier comme texte normal, et le second comme texte mis en avant avec couleur différente, poids plus fort, ou bordure gauche colorée.
Indication : utilisez main p:nth-of-type(2) pour la mise en avant.

---

Exercice 3
Petite galerie responsive.

HTML (sans id ni classe) :

```html
<section>
    <h2>Galerie</h2>
    <div>
        <img src="https://via.placeholder.com/200" alt="">
        <img src="https://via.placeholder.com/200" alt="">
        <img src="https://via.placeholder.com/200" alt="">
        <img src="https://via.placeholder.com/200" alt="">
    </div>
</section>
```

Tâches :

– Styliser la section comme conteneur principal : padding, alignement horizontal du contenu, couleur du titre.
Indication : utilisez section pour le conteneur global.

– Styliser le div interne comme grille : display grid, nombre de colonnes, gap.
Indication : c’est le div juste après le h2.

– Styliser toutes les images dans ce div : arrondi léger, ombre, transition fluide, et un hover agrandissant légèrement l’image via transform: scale().
Indication : utilisez section div img.

– Modifier le titre en l’atteignant via un sélecteur descendant section h2 pour appliquer une couleur ou un espacement spécifique.
