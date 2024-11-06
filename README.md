# Jingjin-Gao_jgao0258-Yifan-Chang_ycha0151-Jiachen-Yang_jyan0918-Roxy-Yu_xiyu0397


---

# README

## Section 1 – Research and Inspiration

1. **Inspiration**  
   - In the process of creating the "Apple Tree," the "Tree of Life" from the *Avatar* movie (Figure 1) inspired our work, incorporating dreamy, technological elements to adjust the picture and add depth, breaking the flatness of the original work.

2. **Maintaining Original Elements**  
   - Since the original artwork primarily uses geometric shapes, we preserved its colors, dots, lines, and surface patterns. This allowed us to create a second abstract version without deviating from the main form of the original piece.

3. **Tree Canopy Design**  
   - **Inspiration Source**: Positive and negative shapes, and transparency (Figure 2).
   - **Implementation**: The canopy was designed by layering transparent geometric shapes, adding spatial depth to the image. Apples were depicted through circles of varying sizes, transparencies, and colors, creating intersections to enrich the canopy’s visual complexity.

4. **Vine Design**  
   - **Inspiration Source**: Firefly glow (Figure 3).
   - **Implementation**: We introduced a mysterious, dreamy feel by incorporating yellow dots and line elements of different transparencies, representing the vines and glowing lights. This maintained the geometric feel of the original work while adding a sense of spirituality.

5. **Background Options**  
   - **Option 1**: A solid dark background, highlighting the “Apple Tree’s” complex form and accentuating the colorful vines and fluorescent lights.
   - **Option 2**: Texture using the random walker technique, adding a unique, textured effect to the background.

Figure 1

![Figure 1](/readimage/Figure%201.png)

Figure 2

![Figure 2](/readimage/Figure%202%20.png)

Figure 3

![Figure 3](/readimage/Figure%203.png)





































## Section 4 – Technical Overview

### 1. Comprehensive Overview
This code is used to create a visual art canvas containing circles and lines of various colors, presenting a dynamic layout. The code utilizes the p5.js library and employs the `setup()` and `drawElements()` functions to draw elements and adjust the scale according to the window size.

### 2. Code Snippets and Explanation

#### 2.1 Initialization Settings
**Explanation**: The `setup()` function initializes the size of the canvas, sets the background color, and calls `drawElements()` to draw the elements. The scale factor `scaleFactor` is used to dynamically adjust the size of the elements.



#### 2.2 Circle Class
**Explanation**: The `Circle` class defines the properties of a circle (position, radius, color) and the `draw()` method, which is used to draw circles on the canvas.

#### 2.3 Line Class
**Explanation**: The `Line` class defines the properties of a line (start and end positions, color, line thickness) and the `draw()` method, which is used to draw lines on the canvas.

#### 2.4 `function windowResized()`
**Function**: Dynamically adjusts the canvas size. When the browser window size changes, the canvas automatically resizes and redraws all elements.

### 3. Code Flowchart
*To be added as an image or diagram illustrating the code execution flow.*

---

