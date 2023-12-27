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
