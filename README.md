<h1>Hello World!</h1>
 <style>
   h1 {
     text-align: center;
     font-size: large;
   }
   @keyframes color {
    0% {
        color: #fdc5f5
    }

    30% {
        color: #f7aef8
    }

    60% {
        color: #b388eb
    }

    90% {
        color: #8093f1
    }

    100% {
        color: #72ddf7
    }
}

h1 {
    -webkit-animation: color 20s infinite;
    animation: color 10s infinite;
    -webkit-animation-direction: alternate;
    animation-direction: alternate;
}
 </style>

