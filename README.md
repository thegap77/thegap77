<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link rel = "preconnect" href = "https://fonts.gstatic.com">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <title>ShadowMC</title>
<body>
<header>
    <a href="#" class="logo"><span>Shadow</span>MC</a>
    <div class="menuToggle" onclick="toggleMenu();"></div>
    <ul class="navbar">
        <li><a href="#banniere" onclick="toggleMenu();">Accueil</a></li>
        <li><a href="#apropos" onclick="toggleMenu();">boutique</a></li>
        <li><a href="#menu" onclick="toggleMenu();">réseaux sociaux</a></li>
        <li><a href="#expert" onclick="toggleMenu();">notre equipe</a></li>
        <li><a href="#temoignage" onclick="toggleMenu();">wiki</a></li>
        <li><a href="#contact" onclick="toggleMenu();">s'inscrire</a></li>
        <a href="#" class="btn-reserve"onclick="toggleMenu();">VOTE</a>
    </ul>
</header>
<section class="banniere" id="banniere">
    <div class="contenu">
        <h2><img src="./images/1643705400240.png" alt="image"></h2>
        <p>soon</p>
        <a href="#" class="btn1">comment nous rejoindre</a>
        <a href="#" class="btn2">info sur le serveur</a>
    </div>
</section>
<section class="apropos" id="apropos">
    <div class="row">
        <div class="col50">
            <h2 class="titre-texte"><span>bou</span>tique</h2>
            <p>soon</p>
        </div>
        <div class="col50">
            <div class="img">
                <img src="./images/shop.jfif" alt="image">
            </div>
        </div>
    </div>
</section>
<section class="menu" id="menu">
    <div class="titre">
        <h2 class="titre-texte"><span>reseaux</span>social</h2>
        <p>pour connetre la suite et mise a jour,vener nous rejoindre sur c reseaux la</p>
    </div>
    <div class="contenu">
        <div class="box">
            <div class="imbox">
                <img src="./images/discord.png" alt="">
            </div>
            <div class="text">
                <h3>discord https://discord.gg/94ys8yC3</h3>
            </div>
        </div>
        <div class="box">
            <div class="imbox">
                <img src="./images/instagram-1.jpg" alt="">
            </div>
            <div class="text">
                <h3>instagram/soon</h3>
            </div>
        </div>
        <div class="box">
            <div class="imbox">
                <img src="./images/twitter.png" alt="">
            </div>
            <div class="text">
                <h3>twitter/soon</h3>
            </div>
        </div>
<section class="expert" id="expert">
    <div class="titre">
        <h2 class="titre-texte"><span>nos</span> Modérateur</h2>
        <p>les 4 fondateur du serveur</p>
    </div>
    <div class="contenu">
        <div class="box">
            <div class="imbox">
                <img src="./images/telecharge.png" alt="">
            </div>
            <div class="text">
                <h3>thegap77</h3>
            </div>
        </div>
        <div class="box">
            <div class="imbox">
                <img src="./images/tu.png" alt="">
            </div>
            <div class="text">
                <h3>friz</h3>
            </div>
        </div>
        <div class="box">
            <div class="imbox">
                <img src="./images/telecharge_1.png" alt="">
            </div>
            <div class="text">
                <h3>dorienVTX77</h3>
            </div>
        </div>
        <div class="box">
            <div class="imbox">
                <img src="./images/tg.png" alt="">
            </div>
            <div class="text">
                <h3>i grec</h3>
            </div>
        </div>
    </div>
 </div>
</section>
 <section class="temoignage" id="temoignage">
    <div class="titre blanc">
        <h2 class="titre-texte"><span>W</span>iki</h2>
        <p>les nouveute</p>
    </div>
    <div class="contenu">
        <div class="box">
            <div class="imbox">
                <img src="./images/detail-picture-3105.png" alt="">
            </div>
            <div class="text">
                <p>un staff a lecoute et qui poura faire de leur mieux pour vous donner une caliter de jeu tres bien</p>
                <h3>un staff de caliter</h3>
            </div>
        </div>
        <div class="box">
            <div class="imbox">
                <img src="./images/detail-picture-3105.png" alt="">
            </div>
            <div class="text">
                <p>mine en 3x3(le hammer)</p>
                <h3>les outie en emraude</h3>
            </div>
        </div>
        <div class="box">
            <div class="imbox">
                <img src="./images/detail-picture-3105.png" alt="">
            </div>
            <div class="text">
                <p>plus uttile que le steff en diamons et donne un effect de fire res</p>
                <h3>le steff en rubis</h3>
            </div>
        </div>
    </div>
 </section>
 <section class="contact" id="contact">
     <div class="titre noir">
         <h2 class="titre-text"><span>s'</span>inscrire</h2>
         <p>s'inscrire et la meilleur des facon pour nous rejoindre</p>
     </div>
     <div class="contactform">
         <h3> S'inscrire</h3>
         <div class="inputboite">
             <input type="text" placeholder="pseudo">
         </div>
         <div class="inputboite">
            <input type="text" placeholder="email">
         </div>
         <div class="inputboite">
            <input type="text" placeholder="mot de passe">
        </div>
        <div class="inputboite">
         </div>
     </div>
 </section>
 <div class="copyright">
     <p>site pour thegap<a href="#">,friz,i grec,</a>site serveur mc</p>
 </div>
 <script type="text/javascript">
     window.addEventListener('scroll', function(){
         const header =document.querySelector('header');
         header.classList.toggle("sticky", window.scrollY > 0 );
     });

     function toggleMenu(){
         const tmenuToggle = document.querySelector('.menuToggle');
         const navbar = document.querySelector('.navbar');
         navbar.classList.toggle('active');
         menuToggle.classList.toggle('active');
     }
 </script>
</body>
</html>
