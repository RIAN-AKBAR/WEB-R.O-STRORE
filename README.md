<!DOCTYPE html>  
<html lang="en">  
<head>  
    <meta charset="UTF-8">  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  
    <title>Web R.O Store</title>
    <link rel="icon" href="logo R.O Store.png" type="image/x-png">
    <!--ganti logo sesuai logo yang anda pingin gunakan-->
    <style>  
        body {  
            font-family: Arial, sans-serif;  
            text-align: center;
            display: and;
            margin-top: 50px;  
            background-color: aqua;

        }  
        #myButton {  
            padding: 10px 20px;  
            font-size: 16px;  
        }
        #buton {
            border-radius: 20px;
        }
    </style>  
</head>  
<body> 
    <img src="logo R.O Store.png" height="180vh">
    <em><h1>selamat datang di web kami!</h1></em>  
    <strong><p id="myParagraph">ini adalah web R.O Store </p></strong>  
    <div class="buton">
    <button class="button" onclick="redirectToFile()">untuk menu silahkan klik</button>  
</div>
    <script>  
       function redirectToFile() {
        //ganti hh.html dengan fail yang di tuju//
        window.location.href = 'hh.html';
       }
    </script>  
</body>  
</html>