# Box Layout Using CSS 

> ## width :px %

> ## height :px vh

> ## background-color : color-name | hex | rgb | hsl | rgba | hsla

> ## background-image :url();

> ## float : left | right

> ## clear : both

> ## margin :top | right | bottom | left

> ## padding :top | right | bottom | left
>


## Exampe two
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nested Div Example 2</title>
    <style>
        *{ margin: 0;}
        .bg1{ background-color: aqua;}
        .bg2{ background-color: tomato;}
        .bg3{ background-color: teal;}
        .bg4{ background-color: springgreen;}
        .fl{ float: left;}
        .fr{ float: right;}
        .wrapper{
            width: 80vw;
            height:70vh;
            margin:15vh auto;
            /* background-color: #404040; */
        }
        .row{
            width: 80vw;
            height: 34vh;
            margin-bottom: 2vh;

        }
        .col-2{ width: 39.70vw; height: 34vh;}
        .col-2-sub{ width: 19vw; height: 34vh;}
    </style>
</head>
<body>
    <div class="wrapper">
        <div class="row">
            <div class="col-2 fl">
                <div class="col-2-sub bg1 fl"></div>
                <div class="col-2-sub bg2 fr"></div>
            </div>
            <div class="col-2 bg2 fr"></div>
        </div>
        <div class="row">
            <div class="col-2 fl">
                <div class="col-2-sub bg1 fl"></div>
                <div class="col-2-sub bg2 fr"></div>
            </div>
            <div class="col-2 fr">
                <div class="col-2-sub bg3 fl"></div>
                <div class="col-2-sub bg4 fr"></div>
            </div>
        </div>
    </div>
    
</body>
</html>
```
