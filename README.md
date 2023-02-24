# REPO ANIMATION AN TRANSITION WITH CSS

## A cosa serve?
1. Esercitazione con le animazioni presenti in `CSS`
2. Ripasso selettori 
3. Scoperta di nuove funzioinalità  
--------------------------------------------------
## Linguaggi utilizzati `HTML`  /  `CSS`
--------------------------------------------------
## Risorse utilli 
- [Recap dei filtri e del loro effetto sull'immagine](https://css-tricks.com/almanac/properties/f/filter/)
- [Bibbia dello sviluppatore W3s](https://www.w3schools.com/css/css3_animations.asp)  
-------------------------------------------------------------
## Esempio di un keyframe


 `.`**NomeDellaClasse** `{`    
>- `animation-name` : **antiorario** ;  
>- `animation-iteration-count` : **infinite** ;  
>- `animation-duration` : **1s** ;  
>- `animation-timing-function` : **linear** ;

`}`

 **_@keyframes_ "antiorario"** `{` 
>0% {  
`transform` : rotate(0deg);  
>}  
>50% {  
>`transform` : rotate(-180deg);  
>}  
>100% {  
>`transform` : rotate(-360deg);  
>}  

`}`

--------------------------------------------------------------


