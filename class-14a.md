# Read 14a - CSS Transforms, Transitions, and Animations

  - Transform syntax - transform followed by the value (can include prefixes: webkit, moz, o)
  - CSS transform property happens in either 2D or 3D planes.

  - 2D: 
    - rotate: ability to rotate an element from 0 to 360 degrees
    - scale: changes the appeared size of an element (defalt value is 1)
    - translate: pushes/pulls an element in different directions without disrupting flow
    - skew: distorts elements on an axis
      - skewX: distorts horizontally
      - skewY: distorts vertically
    - multiple transforms can be used at once, as a list without the use of commas
    - transform-origin: used to change the default position of the center of an element
    - perspective: can be used as a parent property to transform a group or within a transform property to work on a single element
      - perspective value can be set as none or a length measurement, a length measurement gives the element depth
    - perspective origin: used to change the default position of the vanishing point

  - 3D:
    - rotate: in 3D, the values include the x, y and z axis
    - scaleZ: used to transform the elements on the Z axis
    - translateZ: pushes an element away or pulls it in closer on the Z axis
  
  - backface visibility: hidden, does not show elements that may be facing away from the screen & visible always shows the elements

  - transition: hover, focus, active, target (pseudo-classes)
  - transition-property: determines which properties will be changed in conjunction with others
  - transition-duration: sets a time value for things like hover
  - transition-timing-function: sets the speed that a transition will move
  - transition-delay: timed value of delay of a transition being executed

  - @keyframes: animation name and breakpoint to set the multiple animations an element should undergo
  - animation-direction: normal, reverse, alternate and alternate-reverse
  - animation-play-state: allows an animation to be played or paused on a page
  - animation-fill-mode: identifies how an animation should be styled before/after the animation is run

  - Fade in: effect of appearing from a blank screen or fading out to a blank screen
  - Change color: animates a color change when an element is hovered over
  - Grow and Shrink: animates an element to increase in size when hovered over and reduce back to original size when not being hovered over or vice versa
  - Rorate element: rotates an element when hovered over
  - Square to circle: rounds the corners of an element when hovered over
  - 3D shadow: adds a shadow box behind an element when hovered over
  - Swing: wiggles an element side to side when hovered over
  - Inset border: adds a border to the inside of the element when hovered over