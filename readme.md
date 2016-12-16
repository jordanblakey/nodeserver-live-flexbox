
#CSS Flexbox Primer

CSS Primer
------

####Flex Parent

```
.container  {  
display: flex; *or inline-flex*  
flex-direction: row | row-reverse | column | column-reverse;  
flex-wrap: nowrap | wrap | wrap-reverse;  
flex-flow: <‘flex-direction’> || <‘flex-wrap’>  
justify-content: flex-start | flex-end | center | space-between | space-around;  
align-items: flex-start | flex-end | center | baseline | stretch;  
align-content: flex-start | flex-end | center | space-between | space-around | stretch;  
}
```
####Flex Child

```
.item  {  
order: <integer>;  
flex-grow: <number>; *default 0*  
flex-shrink: <number>; *default 1*  
flex-basis: <length> | auto; *default auto*  
flex: none | [ <'flex-grow'> <'flex-shrink'>? || <'flex-basis'> ];  
align-self: auto | flex-start | flex-end | center | baseline | stretch;  
}
```

More New CSS Properties to Become Familiar With
------

####CSS3 Calc Use Cases##

```
div {  
 font-size: calc(3em + 5px); *combine units*  
 padding: calc(1vmax + -1vmin); *useful for defining relative to viewport, for example fluid text sizes*  
 transform: rotate(calc(1turn - 32deg)); *radian calculations, calc within other CSS functions*  
 background: hsl(180, calc(2*25%), 65%); *calc color values. Read: relative colors*  
 line-height: calc(8/3); *don't have to do the math*  
 width: calc(23vmin - 2*3rem);} *don't understand this one*  
}  
```

####Object-Fit & Object-Position Properties

```
img.object-fit {  
object-fit: fill | contain | cover | none | scale-down; *fill: stretch to fill. contain: letterbox. cover: constrain and fill. * /  
object-position: 50% 50%; *default value: image is centere*  
object-position: 0 0; *positioned top left of the content box*  
}  
```

####Transition Timing Function in CSS
```
*  {
transition-timing-function: ease | ease-in | ease-out |ease-in-out | linear | step-start | step-end | steps(4, end) | cubic-bezier(0.1, 0.7, 1.0, 0.1);  
}
```
