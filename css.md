# CSS

### cascading

Styles can be overwritten by other styles.
There's a hierearchy of ways to apply styles: inline styles as the most powerful, and then in order

- inline styles `style={{}}`
- ids `#my-button{}` (can't be shared between elements)
- classes `.my-button{}` (we use this all the time)
- tag name `button{}`


### common style rules

- display
- background or background-color
- margin
- padding
- position
- height / width
- color (text)
- font-size
- font-weight
- border
- border-radius
- z-index: the z direction on the screen, objects can go on top (below) of each other.
           Needs a 'position' rules to work


### units

- px
- %
- vw / vh
- rem (proportional to the font-size of the <html> element)
- calc


### flex

- `display:flex`
- `flex-direction`: row/column/row-reverse/column-reverse
- `align-item`: center, flex-start
- `justify-content`: space-between, space-around, center
- `flex-shrink:0` will make your flex children not shrink


### position

- `relative`: positioned according to the elements around it
- `absolute`: means that the element can be positioned with 'top', 'left', 'right', 'bottom' rules
              (relative to its first parent that has `position:relative;`)

