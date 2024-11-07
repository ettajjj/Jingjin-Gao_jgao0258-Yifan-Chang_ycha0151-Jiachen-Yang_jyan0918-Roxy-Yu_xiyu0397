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



## Section 3 – Implementation

1. **Initial Rendering**  
   - We chose to render an apple tree inspired by the *Avatar* film's "Tree of Life." Through five iterations, we refined the design before finalizing the code. The first design generation (Figure 9) didn't fully capture the "Tree of Life" inspiration, so we decided to incorporate more subtle elements to enhance the tree’s complexity.

2. **Second Generation**  
   - In the second iteration, we added dense circular elements to represent branches and fruits (Figure 10). However, this version felt disproportionate, especially in the lower half, making the overall appearance less aesthetically pleasing.

3. **Third Generation**  
   - Building on the first two versions, we refined the tree's body by adding vertical line elements, focusing on creating a sense of randomness and freedom. We introduced dynamic, free-floating line elements in the background. However, the final outcome appeared overly chaotic (Figure 11), as the lines were too freely distributed.

4. **Fourth Generation**  
   - To reduce background clutter, we removed the excessive lines and introduced uniformly colored circles of varying sizes in the main tree body (Figure 12). This step helped to refine the design while maintaining a structured randomness.

5. **Final Generation**  
   - In the last iteration, we agreed that the background should be minimalistic to emphasize the apple tree’s main body. We removed the circles from the top half, retaining the final apple tree structure, which was then coded into the final design.


**Figure 9**

![Figure 9](/readimage/Figure%209.png)

**Figure 10**

![Figure 10](/readimage/Figure%2010.png)

**Figure 11**

![Figure 11](/readimage/Figure%2011.png)

**Figure 12**
 
![Figure 12](/readimage/Figure%2012.png)

**Figure --**
 
![Figure --](/readimage/WechatIMG1414.jpg)




## Section 4 – Technical Overview

### 1. Comprehensive Overview
This code is used to create a visual art canvas containing circles and lines of various colors, presenting a dynamic layout. The code utilizes the p5.js library and employs the `setup()` and `drawElements()` functions to draw elements and adjust the scale according to the window size.

### 2. Code Snippets and Explanation

#### 2.1 Initialization Settings
**Explanation**: The `setup()` function initializes the size of the canvas, sets the background color, and calls `drawElements()` to draw the elements. The scale factor `scaleFactor` is used to dynamically adjust the size of the elements (Figure 13).

**Figure 13**

![Figure 13](/readimage/Figure%2013.png)

#### 2.2 Circle Class
**Explanation**: The `Circle` class defines the properties of a circle (position, radius, color) and the `draw()` method, which is used to draw circles on the canvas (Figure 14).

**Figure 14**

![Figure 14](/readimage/Figure%2014.png)

#### 2.3 Line Class
**Explanation**: The `Line` class defines the properties of a line (start and end positions, color, line thickness) and the `draw()` method, which is used to draw lines on the canvas (Figure 15).

**Figure 15**

![Figure 15](/readimage/Figure%2015.png)

#### 2.4 `function windowResized()`
**Function**: Dynamically adjusts the canvas size. When the browser window size changes, the canvas automatically resizes and redraws all elements (Figure 16).

**Figure 16**

![Figure 16](/readimage/Figure%2016.png)

### 3. Code Flowchart

**Figure 17**

![Figure 17](/readimage/Figure%2017.png)





## References

1. Gonzalez, N. (2023). *Avatar wallpaper. Avatar collage by Natalia* [Photograph]. Retrieved from [Pinterest](https://pin.it/NeuZLTn7H)

2. Pizana, N. (2015, March 16). *EVA EUN-SIL HAN’S TEXTURED COLLAGES UTILIZE GEOMETRIC PATTERNS*. Retrieved from [Hi-Fructose](https://hifructose.com/2015/03/16/eva-eun-sil-hans-textured-collages-utilize-geometric-patterns/)

3. @Agencja Promocyjna. (n.d.). *BACKBONE OF THE WIND: Photo* [Photograph]. Retrieved from [Pinterest](https://pin.it/3h606ua34)

4. Reas, C. (2023). *Metavasarely*. Retrieved from [reas.com](https://reas.com/metavasarely/)

5. Vyacheslav K. (2018). *Renaissance*. Retrieved from [Saatchi Art](https://www.saatchiart.com/en-au/art/Painting-July-Evening/1102578/4359240/view)

6. Vyacheslav K. (2018). *July Evening*. Retrieved from [Saatchi Art](https://www.saatchiart.com/en-au/art/Painting-July-Evening/1102578/4359240/view)

7. O’Keeffe, G. (1936). *Jimson Weed*. Retrieved from [Georgia O’Keeffe Art Collection](https://www.georgiaokeeffe.net/jimson-weed.jsp#google_vignette)

8. O’Keeffe, G. (1941). *Pedernal*. Retrieved from [Google Arts & Culture](https://artsandculture.google.com/asset/pedernal/ZQFZYRmomxV-iw?hl=en-GB)






