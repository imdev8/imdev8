<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="all.min.css">
    <link href="https://fonts.googleapis.com/css?family=Share+Tech+Mono|Ubuntu+Mono:400,700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="main.css">
</head>
<body>
    
    <div class="intro">
        <div class="intro-container">
            <h2><span class="intro-heavy">Hey I'm <span class="colorize">IMD</span>,</span><br>a junior web <span class="colorize2">designer</span> :)</h2>
        </div>
    </div>

    <div id="more-active" class="more-active"></div>
    
    <div id="more" class="more">
        
        <div id="less-active" class="less-active"></div>
        
        <h2 class="abilities">Abilities.</h2>
        <ul>
            <li>HTML 5</li>
            <li>CSS</li>
            <li>SASS</li>
            <li>React</li>
            <li>Little JS ;)</li>
            <li class="special-ability">And improving...</li>
        </ul>
        
    </div>
    
    <footer>
            <div class="first-footer-item"><i class="far fa-envelope"></i> <p>contactIMDev@gmail.com</p></div>
            <div class="second-footer-item"><i class="fab fa-discord"></i>  <p>IMD8#6981</p></div>
    </footer>
 

    <script>
        const moreButton = document.getElementById('more-active')
        const more = document.getElementById('more')
        const lessButton = document.getElementById('less-active')

        moreButton.addEventListener('click', ()=>{
            more.classList.add('more-actived')
        })

        lessButton.addEventListener('click', ()=>{
            more.classList.remove('more-actived')
        })

    </script>


</body>
</html>
