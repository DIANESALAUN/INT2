Exercice final Move Academy
===========================

L’ensemble du contenu fait 1200px de large et est centré sur la page du navigateur 
mais la couleur de fond du pied de page fait toute la largeur de la page du navigateur quelle que soit sa taille.

# COULEURS :
////- textes : #363636
- violet foncé : #7e4a7c
- violet moyen : #b878b5
- violet fond clair (tableau et formulaire) : padding: 1em;
  border: 1px solid #7e4a7c;

# POLICES :
//- par défaut : (Google Font)
//- Economica (Google Font) pour titres, nav, boutons

# TAILLE DES POLICES :
//- par défaut : 16px
//- titre : 50px
//- titres rubriques : 40px
//- titres sous-rubriques : 30px
- menu : 24px
- boutons "more" : 20px
- bouton validation formulaire : 25px
- copyright : 14px

# Les pictos de réseaux sociaux sont des Font Awesome

faire calculs pour px rem

font-size : calc(45/16 * 1rem); /* convertit 45px en rem */


*******************************************************************

<div id="rouge" class="2col-flex">
  <article id="green" class="2col-flex">
    <img>
    <div class="article-card">
      .....
    <div/>
  <article/>
  <article id="green" class="2col-flex">
    <img>
    <div id="yellow" class="article-card">
      .....
    <div/>
  <article/>
</div>

.2col-flex{
width: 100%; /* remplit la largeure dispo*/
display : flex;
}
.2col-flex>*{
flex-grow : 1 ; /* les enfants de 2col flex se partagent l'espace dispo */
}



