<html>
    <head>
        <style>
            body {
                display: flex;
                justify-content: center;
                align-items: center;
                height: 100vh;
            }
            a {
                text-decoration: none;
            }
            .box {
                font-size: 20px;
                color: white;
                height: 250px;
                width: 350px;
                border-radius: 10px;
                background: #191919;
                flex-direction: column;
                display: flex;
                align-items: center;
                justify-content: center;
            }
            .buttons-container {
                display: flex;
                justify-content: space-around;
                height: 50px;
                width: 15px;
            }
            button {
                height: 30px;
                width: 50px;
                background: white;
                border-radius: 5px;
                color: blueviolet;
                font-weight: 600;
            }
        </style>
    </head>
    <body>
        <div clas="box">
            <p>já pode?</p>
            <div class="buttons-container">
                <button>
                    <a href-"https://link.com">Sim</a>
                </button>
                <button id="no">Não</button>
            </div>
        </div>
    </body>
    <script>
        let button = document.getElementById('no');
        let height = window.innerHeight - 50;
        let width = window.innerWidth - 50;

        button.addEventListener('mouseover', function(){
            button.style.position = "absolute";
            button.style.top = Math.random() * height + "px";
            button.style.left = Math.random() * width + "px";
        })
    </script>
</html>
