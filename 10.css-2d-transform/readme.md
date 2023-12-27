# CSS 2D Transform Methods

**CSS (Cascading Style Sheets) is primarily a 2D styling language, meaning it deals with the layout and presentation of elements in two dimensions. However, CSS can be used to create effects that simulate a third dimension or give the illusion of depth. For true 3D transformations and animations, additional technologies such as WebGL or CSS 3D transforms are often used.**

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

## 3D View Example

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
