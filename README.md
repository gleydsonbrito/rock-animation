# falling-rock-css

## Falling rock animation

## Check it out: https://gleydsonbrito.github.io/rock-animation/

### Folow me for more css tricks

```
body {
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #614124;
}

.d {
    height: 22%;
    position: relative;
    margin-bottom: 100px;
    margin-right: -40px;
    animation-name: pow;
    animation-duration: 1s;
    animation-timing-function:ease-out;
    animation-delay: 0.3s;
}

.r {
    position: relative;
    height: 100px;
    width: auto;
    animation-name: fall;
    animation-duration: .7s;
    animation-timing-function: ease-out;
}

@keyframes pow {
    0% {right: 0; bottom: 0; transform: rotate(360deg);}
    100% {right: 1200px; bottom: 350px;}
}

@keyframes fall {
    0% {left: 200px; top: calc(100vh / -2); transform: rotate(360deg);}
    10% {left: 100px; top: 0}
    20% {left: 50px; top: -10px; right: 3px;}
    30% {top: 0; right: 0;}
    40% {top: -13px; left: 2px;}
    50% {top: 0; left: 0}
    60% {top: -16px; right: 4px;}
    70% {top: 1; right: 0;}
    80% {top: -13px; left: 6px}
    90% {top: 3; left: 0;}
    95% {top: -5px; left: 3px}
    100%{top: 0; left: 0}
}
```
