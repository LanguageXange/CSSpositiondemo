## View live demo at https://languagexange.github.io/CSSpositiondemo/
CSS position:
- static, relative, absolute, fixed ( I didn't include sticky position in this demo)

1. The container with grey background is the parent with relative position (class="parent")
2. Parent has absolute children (the purple box) and relative children (notice the overflow of the relative children)
3. Static children are set to float:right for better visibility
4. Fixed position is outside the parent section (the yellow box that says "fixed when scroll")
5. As you scroll, you'll notice the orange progress bar at the top of the screen (the position is also set to fixed)
6. The JS code for the progress bar is from Eloquent JavaScript Ch.15 (Handling Events)
 - Key concepts: scrollHeight, innerHeight, pageYOffset
