## Transforms in CSS :

**transform* 

we can describ it by 2D & 3D , and each one has it's own properties and values .

**Transform Syntax**

div {
  -webkit-transform: scale(1.5);
     -moz-transform: scale(1.5);
       -o-transform: scale(1.5);
          transform: scale(1.5);
}

**2D Transforms**

work on X-axis Y-axis or horizonal and vertical axis

**3D Transforms**

like the 2D but with the depth or z-axis .

**Combining Transforms**

we can do that by listing the transform values within the transform property one after the other without the use of commas.

.box-2 {
  transform: skew(10deg, 20deg) translateX(20px);
}


## Transitions & Animations:

CSS transitions allows you to change property values smoothly, over a given duration.

**How to Use CSS Transitions?**

To create a transition effect, you must specify two things:

1- the CSS property you want to add an effect to

2- the duration of the effect

**for transsition we can change**

- it's duration 

- it's time 

.box {
  background: #2db34a;
  border-radius: 6px;
  transition-property: background, border-radius;
  transition-duration: .2s, 1s;
  transition-timing-function: linear;
}


- it's delay 

.box {
  background: #2db34a;
  border-radius: 6px
  transition-property: background, border-radius;
  transition-duration: .2s, 1s;
  transition-timing-function: linear, ease-in;
  transition-delay: 0s, 1s;
}


**CSS Animations**

CSS allows animation of HTML elements without using JavaScript or Flash!


**we can change this properties**

- animation-name

- animation-duration

- animation-delay

- animation-iteration-count

- animation-direction

- animation-timing-function

- animation-fill-mode

.stage:hover .ball {
  animation-name: slide;
  animation-duration: 2s;
  animation-timing-function: ease-in-out;
  animation-delay: .5s;
}

# CSS3:

give the developer more awesome transition effect that will excite the user 

1. Fade in

2. Change color

3. Grow & Shrink

4. Rotate elements

5. Square to circle

6. 3D shadow

7. Swing

8. Inset border