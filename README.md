# VENTURA_18

<!DOCTYPE html>
<html>
<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>De Ventura</title>
    <meta name='viewport' content='width=device-width, initial-scale=1'>
    <style>
        body {
            background-color: rgb(185, 45, 138);
        }
    </style>
    <script>
        function accionParaCuandoEllaDigaQueSi(){
            alert('Te jodiste ahora ya somos novios <3');
        }

        function mueveElBoton(){
            width = window.innerWidth;
            height = window.innerHeight;

            newWidth = (Math.random() * width);
            newHeight = (Math.random() * height);

            document.getElementById('btnNo').style.position = "absolute";
            document.getElementById('btnNo').style.left = newWidth + "px";
            document.getElementById('btnNo').style.top = newHeight + "px";


        }
    </script>
</head>
<body>
    <h3>NICOLE :3 ¿quires ser mi novia?</h3>
    <input type="button" onclick="accionParaCuandoEllaDigaQueSi()" id="btnSi" value="Si" />
    <input type="button" id="btnNo" onmouseover="mueveElBoton()" value="No" />
    <img src="chuec.png" width="300">

</body>
</html>
