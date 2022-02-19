# SITE-CMS-WORDPRESS-VOYAGE
<!doctype html>
<html lang="fr">
<head>
  <meta charset="utf-8">
  <title>Accueil | Voyage</title>
  <link rel="stylesheet" href="INDEX.css">
  <script src="INDEX.js"></script>
</head>
<body>
    <nav>
        <ul>
          <li class="menu-deroulant">
            <a href="#">Accueil</a>
          </li>
          <li><a href="#">À propos</a></li>
          <li class="menu-deroulant">
            <a href="#">Séjours/destinations</a>
            <ul class="sous-menu">
              <li><a href="#">France</a></li>
              <li><a href="#">Europe & Monde</a></li>
            </ul>
          </li>
          
          <li><a href="#">Contactez-nous</a></li>

          <li><a href="file:///C:/Users/axelt/Desktop/STUDI/EXERCICES%20RESOLUS/CREER%20UN%20SITE%20AVEC%20CMS%20WORDPRESS/CONTACT.html">Mon Espace</a></li>
        </ul>
      </nav>

    </body>  
      
      <div style='display:flex'>
        <footer class="site-footer">
          <div class="container">
            <div class="row">
              
    
              
  
</html>
            
    /* PARTIE  CONTACT  */     
  
  <html>
    <head>
       <meta charset="utf-8">
        <!-- importer le fichier de style -->
        <link rel="stylesheet" href="style.css" media="screen" type="text/css" />
    </head>
    <body>
        <div id="container">
            <!-- zone de connexion -->
            
            <form action="verification.php" method="POST">
                <h1>Connexion</h1>
                
                <label><b>Nom d'utilisateur</b></label>
                <input type="text" placeholder="Entrer le nom d'utilisateur" name="username" required>

                <label><b>Mot de passe</b></label>
                <input type="password" placeholder="Entrer le mot de passe" name="password" required>

                <input type="submit" id='submit' value='LOGIN' >
                
            </form>
        </div>
    </body>
</html>
            
            
            /* PARTIE CSS */
 
li {
    list-style:none !important;
    color:#FFF;
    padding:10px;
    font-size:20px;
    text-decoration:none;
    }
    nav ul {
    background-color:#64abfb;
    padding:0;
    margin:0;
    
    text-align: center;
    }
    nav ul li {
    list-style: none;
    line-height:44px;
    float:left;
    background-color:#64abfb;
    text-align: center;
    }
    nav ul li a {
    color:#FFF;
    padding:10px;
    font-size:20px;
    text-decoration:none;
    text-align: center;
    }
    li a:hover {
    border-bottom:3px #FFF solid;
    }
    nav ul li ul { display:none; } /* Rend le menu déroulant caché par défaut */
    nav ul li:hover ul { /* Affiche la dropNav au survol de la souris avec la class .drop */
    z-index:99999;
    display:list-item !important;
    position:absolute;
    margin-top:5px;
    margin-left:-10px;
    }
    nav ul li:hover ul li {
    float:none;
    }
    body {
        color:black;
        background-color:white;
        background-image:url(https://cache.magazine-avantages.fr/data/photo/w1000_ci/1mo/coronavirus-comment-voyager.jpg);
        background-repeat:no-repeat;
        background-position:100% 0%;
        background-size: 100%;
        }
        .site-footer
{
  background-color:#26272b;
  padding:45px 0 20px;
  font-size:15px;
  line-height:24px;
  color:#737373;
}
.site-footer hr
{
  border-top-color:#bbb;
  opacity:0.5
}
.site-footer hr.small
{
  margin:20px 0
}
.site-footer h6
{
  color:#fff;
  font-size:16px;
  text-transform:uppercase;
  margin-top:5px;
  letter-spacing:2px
}
.site-footer a
{
  color:#737373;
}
.site-footer a:hover
{
  color:#3366cc;
  text-decoration:none;
}
.footer-links
{
  padding-left:0;
  list-style:none
}
.footer-links li
{
  display:block
}
.footer-links a
{
  color:#737373
}
.footer-links a:active,.footer-links a:focus,.footer-links a:hover
{
  color:#3366cc;
  text-decoration:none;
}
.footer-links.inline li
{
  display:inline-block
}
.site-footer .social-icons
{
  text-align:right
}
.site-footer .social-icons a
{
  width:40px;
  height:40px;
  line-height:40px;
  margin-left:6px;
  margin-right:0;
  border-radius:100%;
  background-color:#33353d
}
.copyright-text
{
  margin:0
}
@media (max-width:991px)
{
  .site-footer [class^=col-]
  {
    margin-bottom:30px
  }
}
@media (max-width:767px)
{
  .site-footer
  {
    padding-bottom:0
  }
  .site-footer .copyright-text,.site-footer .social-icons
  {
    text-align:center
  }
}
.social-icons
{
  padding-left:0;
  margin-bottom:0;
  list-style:none
}
.social-icons li
{
  display:inline-block;
  margin-bottom:4px
}
.social-icons li.title
{
  margin-right:15px;
  text-transform:uppercase;
  color:#96a2b2;
  font-weight:700;
  font-size:13px
}
.social-icons a{
  background-color:#eceeef;
  color:#818a91;
  font-size:16px;
  display:inline-block;
  line-height:44px;
  width:44px;
  height:44px;
  text-align:center;
  margin-right:8px;
  border-radius:100%;
  -webkit-transition:all .2s linear;
  -o-transition:all .2s linear;
  transition:all .2s linear
}
.social-icons a:active,.social-icons a:focus,.social-icons a:hover
{
  color:#fff;
  background-color:#29aafe
}
.social-icons.size-sm a
{
  line-height:34px;
  height:34px;
  width:34px;
  font-size:14px
}
.social-icons a.facebook:hover
{
  background-color:#3b5998
}
.social-icons a.twitter:hover
{
  background-color:#00aced
}
.social-icons a.linkedin:hover
{
  background-color:#007bb6
}
.social-icons a.dribbble:hover
{
  background-color:#ea4c89
}
@media (max-width:767px)
{
  .social-icons li.title
  {
    display:block;
    margin-right:0;
    font-weight:600
  }
}
