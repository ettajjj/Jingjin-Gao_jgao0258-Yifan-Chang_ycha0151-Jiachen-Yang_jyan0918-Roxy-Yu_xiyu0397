# Jingjin-Gao_jgao0258-Yifan-Chang_ycha0151-Jiachen-Yang_jyan0918-Roxy-Yu_xiyu0397


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

**Figure 1**

![Figure 1](/readimage/Figure%201.png)

**Figure 2**

![Figure 2](/readimage/Figure%202%20.png)

**Figure 3**

![Figure 3](/readimage/Figure%203.png)





## Section 2 – Technical Planning

1. **Project Inspiration**  
   - This creation is inspired by an exploration of the cycle of life, the relationship between humanity and nature, and the use of coding technologies to generate artwork. Influenced by artist Casey Reas, we aim to express the rhythm of life of the apple tree through geometric layering and dynamic transformations, blending nature's unpredictability with the precision of digital programming (Figure 4). This combination allows the audience to experience nature in a way that feels both familiar and strangely new.

2. **Generative Art and Coding as Visual Language**  
   - Reas's concept of generative art reveals that code is not merely a tool but a new visual language. Through coding techniques, we intend to let the branches and leaves of the apple tree "grow" within the program, simulating the natural expansion and transformation of plants in the real world. Using Perlin noise, we will give the apple tree a subtle sense of randomness and organic quality. Interactive elements will allow the audience to experience the tree's growth through direct engagement. This generative process not only recreates the physical appearance of the apple tree but also expresses its inner vitality, as though the audience is witnessing the tree's seasonal cycles and growth year after year (Figures 5 & 6).

3. **Abstract Expression of Nature’s Rhythm**  
   - Vyacheslav Kulikov's works inspire us to convey nature's rhythm from an abstract perspective. In this piece, we incorporated interactive elements that allow the apple tree’s growth and color to change in response to audience behavior. For instance, when the audience taps the keyboard, the color and transparency of the leaves change, and the branches adjust their growth speed in response to external influence. This interactive mechanism goes beyond mere "participation" in the artwork; it also serves as a metaphor for the human-nature relationship, illustrating how our actions affect the balance and evolution of ecosystems.

4. **Seasonal Color Shifts**  
   - The seasonal color shifts of the apple tree are inspired by the work of Impressionist painter Georgia O’Keeffe. Known for her adept use of color to convey the impact and beauty of natural landscapes, we draw from her color choices and presentation to create an evolving work. Through the screen, the audience can visually experience the life cycle of the apple tree and, in turn, feel the passage of time (Figures 7 & 8).


**Figure 4**

![Figure 4](/readimage/Figure%204.png)

**Figure 5**

![Figure 5](/readimage/Figure%205.png)

**Figure 6**

![Figure 6](/readimage/Figure%206.png)

**Figure 7**
 
![Figure 7](/readimage/Figure%207.png)

**Figure 8**

![Figure 8](/readimage/Figure%208.png)




































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

