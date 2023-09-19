# Grid-Structure

## [Live Website Link!]https://rajakhan017.github.io/Grid-Structure/

### Structure of the web page

img src="./webpage.png" width="700px" alt="structure of the webpage" 

#### \*

| Property     | Value        | Description                                                                                                                            |
| ------------ | ------------ | -------------------------------------------------------------------------------------------------------------------------------------- |
| `margin`     | `0`          | Set the margin for all elements to 0.                                                                                                  |
| `padding`    | `0`          | Set the padding for all elements to 0.                                                                                                 |
| `box-sizing` | `border-box` | Specify the box-sizing model as "border-box," which includes padding and borders in the element's total width and height calculations. |

**Selector Explanation:** The `*` selector targets all elements on the page.

#### .container

| Property                | Value                                                      | Description                                                       |
| ----------------------- | ---------------------------------------------------------- | ----------------------------------------------------------------- |
| `display`               | `grid`                                                     | Set the element with the class "container" to use a grid layout.  |
| `grid-template-rows`    | `repeat(6, 6rem)`                                          | Define the grid rows to repeat 6 times with a height of 6rem.     |
| `grid-template-columns` | `repeat(16, 6.25%)`                                        | Define the grid columns to repeat 16 times with a width of 6.25%. |
| `grid-template-areas`   | Specifies the placement of grid items in named grid areas. |

**Selector Explanation:** The `.container` selector targets elements with the class "container."

#### .container > img

| Property  | Value            | Description                                                                                                 |
| --------- | ---------------- | ----------------------------------------------------------------------------------------------------------- |
| `padding` | `3px`            | Add padding of 3px to all direct child `img` elements within elements with the class "container."           |
| `border`  | `3px solid #000` | Add a 3px solid black border to all direct child `img` elements within elements with the class "container." |

**Selector Explanation:** The `.container > img` selector targets `img` elements that are direct children of elements with the class "container."

#### .navbar

| Property          | Value            | Description                                                            |
| ----------------- | ---------------- | ---------------------------------------------------------------------- |
| `grid-area`       | `nav`            | Define the grid area named "nav" for elements with the class "navbar." |
| `border`          | `3px solid #000` | Add a 3px solid black border to elements with the class "navbar."      |
| `margin-top`      | `1px`            | Add a 1px margin to the top of elements with the class "navbar."       |
| `display`         | `grid`           | Set the element with the class "navbar" to use a grid layout.          |
| `grid-auto-flow`  | `column`         | Automatically place grid items in columns.                             |
| `justify-content` | `center`         | Center-align content horizontally within the grid container.           |
| `align-items`     | `center`         | Center-align content vertically within the grid container.             |
| `gap`             | `8rem`           | Define the gap between grid items in the grid container.               |

**Selector Explanation:** The `.navbar` selector targets elements with the class "navbar."
![image](https://github.com/rajakhan017/Grid-Structure/assets/135150598/945d9ad7-31cf-4641-a2cc-074846850f8d)


#### .one, .two, .three, .four, .five, .six, .seven, .eight, .nine

| Property    | Value                                                                    | Description |
| ----------- | ------------------------------------------------------------------------ | ----------- |
| `grid-area` | Specifies the grid area in which elements with these classes are placed. |

**Selector Explanation:** The `.one`, `.two`, `.three`, `.four`, `.five`, `.six`, `.seven`, `.eight`, and `.nine` selectors target elements with these specific classes.
![image](https://github.com/rajakhan017/Grid-Structure/assets/135150598/208c4ce1-a3ce-4012-aaf9-809c220cd348)

#### img

| Property | Value  | Description                                                            |
| -------- | ------ | ---------------------------------------------------------------------- |
| `width`  | `100%` | Set the width of all `img` elements to 100% of their parent's width.   |
| `height` | `100%` | Set the height of all `img` elements to 100% of their parent's height. |

**Selector Explanation:** The `img` selector targets all `img` elements on the page.
![image](https://github.com/rajakhan017/Grid-Structure/assets/135150598/b69a6323-80ce-4beb-8a07-c390ecdbbe10)

#### .navbar img

| Property | Value  | Description                                                                       |
| -------- | ------ | --------------------------------------------------------------------------------- |
| `width`  | `80px` | Set the width of `img` elements within elements with the class "navbar" to 80px.  |
| `height` | `80px` | Set the height of `img` elements within elements with the class "navbar" to 80px. |

**Selector Explanation:** The `.navbar img` selector targets `img` elements that are descendants of elements with the class "navbar."

#### button

| Property           | Value         | Description                                                                                      |
| ------------------ | ------------- | ------------------------------------------------------------------------------------------------ |
| `background-color` | `#000`        | Set the background color of `button` elements to black.                                          |
| `color`            | `#fff`        | Set the text color of `button` elements to white.                                                |
| `padding`          | `0.1rem 1rem` | Add padding to the top and bottom (0.1rem) and left and right (1rem) sides of `button` elements. |
| `border-radius`    | `8px`         | Add rounded corners (8px) to `button` elements.                                                  |

**Selector Explanation:** The `button` selector targets `button` elements.
![image](https://github.com/rajakhan017/Grid-Structure/assets/135150598/e2a10d1d-3db9-4edb-a648-7e79a8376230)
