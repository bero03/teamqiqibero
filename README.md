<?php
$title = "Home - TeamWork";
$project = "stackmasters";
$intro = "Welkom op onze projectwebsite! Hier vindt u alle informatie
over ons team, de opdrachten en onze aanpak via Scrum.";
?>
<!DOCTYPE html>
<html lang="nl">
<head>
    <meta charset="utf-8">
    <title>Home Pagina</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400..700&family=Quicksand:wght@300..700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="homestyle.css" type="text/css">
        <link href='https://fonts.googleapis.com/css?family=Smooch Sans' rel='stylesheet'>
<style>
body {
    font-family: 'Smooch Sans';font-size: 22px;
}
</style>
</head>
<body>
<nav>
    <a class="logo" href="home.php">
        <img src="fotos/sitelogo.png" alt="Stack Masters Logo">
        <span>STACK <strong>MASTERS</strong></span>
    </a>
 
    <ul>
        <li><a href="home.php">Home</a></li>
        <li><a href="ons-team.php">Ons Team</a></li>
        <li class="dropdown">
            <a href="#" class="dropbtn">Opdrachten ▼</a>
            <ul class="dropdown-content">
                <li><a href="nezar.php">Nezar</a></li>
                <li><a href="qixuan.php">Qi Xuan</a></li>
                <li><a href="justin.php">Justin</a></li>
            </ul>
        </li>
 
        <li><a href="dailyscrum.php">Daily Scrum</a></li>
        <li><a href="planning.php">Planning</a></li>
    </ul>
</nav>
<main>
    <h2>Welkom</h2>
    <p><?php echo $intro; ?></p>
        <section class="intro">
            <p>
             Op deze website vindt u alle onderdelen van ons project overzichtelijk terug.
             We laten zien wie er in ons team zitten, welke opdrachten we hebben gemaakt en
             hoe we werken met de Scrum-methode.
            </p>
            <p>
             Ons project <strong>TeamWork</strong> is onderdeel van Sprint 2.
             We bouwen samen een webapplicatie met de pagina’s <em>Home, Ons Team, Opdrachten</em> en <em>Daily Scrum</em>.
            Iedereen in het team heeft een eigen taak en we werken volgens de <strong>Scrum-methode</strong> met dagelijkse stand-ups.
              Het eindresultaat is een complete website die onze samenwerking en opdrachten laat zien.
            </p>
        </section>
    </main>
<footer>
    <p>&copy; <?php echo date("Y"); ?> Stack Masters</p>
</footer>
 
</body>
</html>
 
 



# teamqiqibero
