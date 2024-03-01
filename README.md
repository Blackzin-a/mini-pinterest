<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Projeto pinterest</title>
    <style>
* {
   background-color: black;
   color: white;
   font-family: sans-serif;
   font-style: normal;
   font-weight: bold;
   }

div {
display: flex;
justify-content: center;
padding: 4px;
gap: 30px;
margin: 0;
}

a {
    text-align: center;
    text-decoration: none;
}

section {
    display: flex;
    flex-wrap: wrap;
    justify-content: left;
    gap: 10px;
}

img {
    max-width: calc(50% - 5px);
    height: 50%; 
    border-radius: 50px;
} 

    </style>
</head>
<body>
    <header>
<div>

    <a href="#" target="_blank">All</a>
    <a href="#" target="_blank">Anime</a>
    <a href="#" target="_blank">Papel de parede naruto</a>

</div>

    </header>

    <main>

    <section>
        <img src="img/1.jpg" alt="img1">
        
        <img src="img/2.jpg" alt="img2">
        <br>
        <img src="img/3.jpg" alt="img3">
    </section>

    </main>

    <footer>




    </footer>


</body>
</html>
