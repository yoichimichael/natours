Natours
=======
Travel Agency Clone
------
### Animations
Used both types of CSS animation techniques:

1.  Using the `animation` short-hand property in conjunction with `@keyframes` lists.
2. Using the `transition`shorthand property on elements with different styles in different states. 
#### In Header
##### **h1**
- Used `@keyframes` lists and `animation` properties with `opacity` and `translate` for slide/fade-in animation. Restricted use of this technique to `opacity` and `transform` properties for performance reasons.
##### **a (.btn)**
- Used pseudo-classes with `translateY`

### Relative Units
All length and font-sizes are set to `rem` to be relative to the root property value of 10px. This requires fewer changes when declaring media queries.