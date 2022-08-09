# Rem & Em units:
<pre>
html {
font-size: 62.5%; /* 62.5% of 16px = 10px */

@media (min-width: 20rem) {
/* 20*16px = 320px */
background-color: lemonchiffon;
font-size: 200%;
/* 200% of 16px = 32px */
}

@media (min-width: 30em) {
/* 30*16px = 480px */
background-color: lightblue;
font-size: 300%; /* 300% of 16px = 48px */
}
}
</pre>
