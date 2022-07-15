# -sunitseth1-docu.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mobile tab navigation</title>

    <script src="https://kit.fontawesome.com/e1e62f897a.js" crossorigin="anonymous"></script>
                <style>
                    * {

            padding: 0;

            margin: 0;

            box-sizing: border-box;

            }

            body {
            font-family: "Karla", sans-serif;
            line-height: 0;
            font-weight: 400;
            background-color: hsl(211, 36%, 17%);
            }
            html {
            font-size: 62.5%;
            }
            .image {
            max-width: 500px;
            height: 730px;
            margin: 0 auto;
            display: flex;
            align-items:flex;
            justify-content: center;
            width: 30%; 
       
          overflow: hidden;
            }
            .mob-tab{
         
            max-width: 410px;
            height: 60px;
            background-color: rgb(221, 212, 212);
            margin: 0 auto;
            display: flex;
            align-items:flex;
            justify-content: center;
            width: 30%; 
        }
        .tabs{
            display: flex;
            align-items: center;
            justify-content: space-evenly;
            width: 100%;
            list-style-type: none;
        }
        .body{
                height: calc(105vh - 100px);
            }
            .tabs a{
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-decoration: none;
            color: rgb(48, 22, 22);
            font-weight: 600;
        }
        .tabs a i {
            font-size: 20px;
            margin: 5px;
        }
        .tabs a:hover{
            color: rgb(223, 239, 221);
        }
        @media screen and (max-width:600px) {
           
           .body{
               height: calc(0px);
           }
           .image {
           max-width: 500px;
            height: 730px;
            background-color: rgb(221, 212, 212);
            margin: 0 auto;
            display: flex;
            align-items:flex;
            justify-content: center;
            width: 76%; 
           }
           .mob-tab{
          
            max-width: 410px;
            height: 60px;
            background-color: rgb(221, 212, 212);
            margin: 0 auto;
            display: flex;
            align-items:flex;
            justify-content: center;
            width: 76%; 
       }
       .tabs{
           display: flex;
           align-items: center;
           justify-content: space-evenly;
           width: 100%;
           list-style-type: none;
       }
       .tabs a{
           display: flex;
           flex-direction: column;
           justify-content: center;
           align-items: center;
           text-decoration: none;
           color: rgb(70, 66, 66);
           font-weight: 600;
       }
       
       .tabs a:hover{
           color: rgb(148, 159, 147);
       }
       .tabs a i {
           font-size: 20px;
           margin: 5px;
       }
       }
          </style>
   
</head>
<body>
    <div class="image">
        <img src="https://wallpaperaccess.com/full/2588104.jpg" alt="">
    </div>
    <div class="mob-tab">
        <ul class="tabs">
            <li class="tab-items">
                <a href=""><i class="fas fa-home"></i><p>Home</p></a>
            </li>
            <li class="tab-items">
                <a href=""><i class="fa-solid fa-briefcase"></i><p>Work</p></a>
            </li>
            <li class="tab-items">
                <a href=""><i class="far fa-address-book"></i><p>Contact</p></a>
            </li>
            <li class="tab-items">
                <a href=""><i class="fas fa-users"></i><p>About Us </p></a>
            </li>
            
        </ul>
    </div>

    <div class="body">
     
    </div>

    
</body>
</html>
