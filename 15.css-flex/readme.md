```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Flex Master Guide</title>
    <style>
        *{ margin: 0; padding: 0; box-sizing: border-box;}
        .bg1{ background-color: rgba(65, 105, 225,0.80);}
        .bg2{ background-color: rgba(0, 128, 128,0.70);}
        .bg3{ background-color: rgba(138, 43, 226,0.80);}
        .bg4{ background-color: rgba(0, 255, 255,0.70);}
        .banner{ 
            width: 100%; 
            height: 90vh;
            background-color: whitesmoke;
            background-image: url(bg.jpg);
            background-repeat: no-repeat;
            background-size: cover;
            background-position: center;
            display: flex;
            
            /* flex-direction: row; */
            /* flex-direction: row-reverse; */
            /* flex-direction: column; */
            /* flex-direction: column-reverse; */
            
            /* flex-wrap: nowrap; */
            /* flex-wrap: wrap; */
            /* flex-wrap: wrap-reverse; */

            flex-flow: row wrap;

            /* Alignment [x] */
            /* justify-content: left; */
            /* justify-content: right; */
            /* justify-content: start; */
            /* justify-content: end; */
            justify-content: center;
            /* justify-content: space-between; */
            /* justify-content: space-around; */
            /* justify-content: space-evenly; */
            /*  verticle Alignment */
            /* align-items: start; */
            align-items: end;
            /* align-items: center; */
            /* align-items: stretch; */
            
            
            
            /* align-content: start; */
            /* align-content: end; */
            align-content: center;
            /* align-content: space-around; */
            
            gap:50px 10px;
        }
        .item{
            width: 20%;
            height: 20vh;
            font-size: 5rem;
            text-align: center;
            line-height: 20vh;
            color: white;
            /* float: right; */
            border: 10px solid white ;
            border-radius: 20px;
          
           
        }
    </style>
</head>
<body>
    <div class="banner">

        <div class="item bg1">1</div>
        <div class="item bg2">2</div>
        <div class="item bg3">3</div>
        <div class="item bg4">4</div>
        <div class="item bg1">1</div>
        <div class="item bg2">2</div>
        <div class="item bg3">3</div>
        <div class="item bg4">4</div>
        <div class="item bg1">1</div>
        <div class="item bg2">2</div>
        <div class="item bg3">3</div>
        <div class="item bg4">4</div>
        <!-- <div class="item bg3">5</div> -->
        <!-- <div class="item bg4">6</div> -->
    </div>
</body>
</html>
```
