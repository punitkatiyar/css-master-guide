# CSS 2d transform Methods

> translate(x,y)

> rotate( 25deg)

> scaleX()

> scaleY()

> scale()

> skewX()

> skewY()

> skew()

> matrix( scaleX(), skewY(), skewX(), scaleY(), translateX(), translateY())

# CSS 3D Transform

> rotateX(150deg)

> rotateY(150deg)

> rotateZ(150deg)

```
<style>
        .main{
            width: 300px;
            height: 300px;
            background-color: aqua;
            margin: 20vh auto;
            position: relative;
            perspective: 100px;
        }
        .child{
            width: 300px;
            height: 300px;
            background-color: tomato;
            position: absolute;
            transform-style: preserve-3d;
            transform: rotateY(50deg);
        }
    </style>
```
