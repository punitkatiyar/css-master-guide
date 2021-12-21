# css3 animation



<pre>
 .banner {
            position: relative;
            width: 100%;
            height: 80vh;
            background-image: url(https://images.pexels.com/photos/2041627/pexels-photo-2041627.jpeg);
            background-size: cover;
            animation-name: slide;
            animation-duration: 10s;
            animation-iteration-count: infinite;
        }

        .banner h1,
        h2 {
            position: absolute;
            font-size: 4rem;
            color: white;
            padding: 1%;
            background: rgba(65, 105, 225, 0.50);
            border-left: 10px solid tomato;
            transform: skewX(150deg);
        }

        .p1 {
            top: 10px;
            left: 150px;
        }

        .p2 {
            top: 200px;
            left: 250px;
        }

        @keyframes slide {
            0% {
                background-image: url(https://images.pexels.com/photos/2041627/pexels-photo-2041627.jpeg);
            }

            25% {
                background-image: url(https://images.pexels.com/photos/925786/pexels-photo-925786.jpeg);
            }

            50% {
                background-image: url(https://images.pexels.com/photos/1586973/pexels-photo-1586973.jpeg);
            }

            75% {
                background-image: url(https://images.pexels.com/photos/1015568/pexels-photo-1015568.jpeg);
            }

            100% {
                background-image: url(https://images.pexels.com/photos/1595385/pexels-photo-1595385.jpeg);
            }

        }

</pre>
