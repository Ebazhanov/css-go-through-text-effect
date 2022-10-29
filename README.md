# CSS effect: Go through text by hover it.

#### Don't forget to enable hover effect by disabling infinite animation: 

```css
.text {
    position: fixed;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%) scale(1);
    height: 100%;
    width: 100%;
    background-color: white;
    color: black;
    font-size: 4vw;
    display: grid;
    align-items: center;
    justify-items: center;
    mix-blend-mode: screen;
    transition: 0.9s;
    backdrop-filter: brightness(80%);
    /* disable infinite animation here */
    //animation: animatime 5s infinite;
}

.text:hover {
    transform: translate(-50%, -50%) scale(190);
    backdrop-filter: brightness(100%);
}
```

![demo](css_effect.gif)

