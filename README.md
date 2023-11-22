<!DOCTYPE html>
<html>
    <head>
        <title>Visibility</title>
        <style>
           * {
                padding:0;
                margin:0;
            }
            .nav{
                background-color: rgb(253,185,185);
                height: 20px;
                padding: 10px;
                text-align:center;
                margin-bottom:10px;
            }
            .banner{
                background-color:aqua;
                height:200px;
            }
            .content{
                background-color: rgb(246, 213, 213);
                height:400px;
            }
            .footer{
                background-color:rgb(37,27,17);
                height:20px;
                height:100px;
            }
            img{
                width:100%;
                
                filter:grayscale(100%) invert(100%);
            }
        </style>
    </head>
    <body>
        <div class="nav">
            <a href="#">Home</a>
            <a href="#">About</a>
            <a href="#">Contact</a>
        </div>
        
        <div class="banner">
            <img src="https://cdn.britannica.com/37/231937-050-9228ECA1/Drake-rapper-2019.jpg?w=400&h=300&c=crop">
        </div>
        
        <div class="content">
            <p>1234</p>
        </div>
        
        <div class="footer">
            <p>1234</p>
        </div>
    </body>
</html>
