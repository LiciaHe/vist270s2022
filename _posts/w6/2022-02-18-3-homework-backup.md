---
layout: post
title:  "W6-3 Homework Set (5) DRAFT"
---
## Overview
The homework set counts for <span style="color:#0000ff;"> 6.5%  </span> of your total grade. Bonus opportunity:   <span style="color:#0000ff;"> ~1% </span>. 
- Part 1, Maya boolean operation:  <span style="color:#0000ff;"> 3%  </span>
- Part 2, Snow Flake Design <span style="color:#0000ff;"> 3.5%  </span>
	- bonus opportunity 1 <span style="color:#0000ff;">  (0.1-1%)  </span>

The peer review of this homework set counts for <span style="color:#0000ff;"> 0.5%  </span>

Useful link:
	- [Maya Python pkg doc](https://help.autodesk.com/view/MAYAUL/2022/ENU/index.html?contextId=COMMANDSPYTHON-INDEX)

**[ANSWER SHEET]()**


https://www.cnn.com/style/article/evolution-of-snowflake-photography/index.html
https://alexey-kljatov.pixels.com/
https://alexey-kljatov.pixels.com/collections/all+snowflakes



## Part 2: Snowflake  Design 

[No two snowflakes are alike.](https://www.thoughtco.com/why-all-snowflakes-are-different-609167#:~:text=Snowflakes%20are%20made%20up%20of,are%20exactly%20the%20same%20size.&text=Each%20snowflake%20is%20exposed%20to,time%20they%20reached%20the%20surface.) 

In this challenge, you will design and implement a snowflake generator using turtle graphics. 





### Task 2.1, sketches <span style="color:#0000ff;"> 1%  </span> 
Sketch ideas of your snowflakes generator. Here are some tips:
- You are not required to create realistically rendered snowflakes. Using snowflake shapes as inspirations for your art system. 
- Think about color. 
- Think about the structure of your snowflake. Are there any symmetry? 
- Because no two snowflakes are alike, think about how your snowflakes vary in shape, structure, and size. 
 

In this task, describe your design visually and verbally. Minimally, you should have 3 sketches illustrating your idea. 

Fill the answer sheet. 


### Task 2.2, turn your sketch into code  <span style="color:#0000ff;"> 2%  </span> 

 You are implementing a function that generates snowflakes according to some given information. 

 
 Create a script `hw5_part2.py` and  `hw5_part2_test.py`.
 
Your generator works for a variety of settings, such as size, location. Therefore, please package your snowflake generator in a function that follow this exact format: 

```

def snowflake_generator(turtle, screen, center_x, center_y, canvas_size):  
    '''  
  
		Produce a snowflake in the designed location using the given turtle and screen. 
 
	 :param turtle: turtle used to perform the drawing 
	 :param screen: turtle screen object 
	 :param center_x: x coordinate associated with the center of the snowflake
	 :param center_y: y coordinate associated with the center of the snowflake
	 :param canvas_size: the width and height of the canvas 
	 :return:  None
 
 '''  
 #TODO

```

**Just like the last homework, you shouldn't call any of these functions directly in this script. Your `hw5_part2.py`  serves as a library.** 


During the implementing process, you will want to test if your snowflake system works. You should conduct all the testing in `hw5_part2_test.py`.

e.g., 
```
#hw4_part2_test.py: used to test my generator

import hw5_part2 as HW5
#TODO 
HW5.snowflake_generator(  
	pixel_function=HW4.my_pixel_system,  
	emoji_option=0 # There are 6 images in the layout library. Set this value to an integer from 0 to 5 to see different layouts  
)


```


**Bonus Opportunity** <span style="color:#0000ff;"> 0.1-0.5%  </span>: If we love your design and implementation, you will get bonus. 


### Task 2.3 Write a paragraph about your design.  <span style="color:#0000ff;"> 0.5%  </span>

In the paragraph, includes  
- The name of your design 
- Description of your design
- Inspiration for your design. 
- Challenges encountered in implementing your design. 

Write the paragraph as a comment in your `hw5_part2.py`, also paste it to the answer sheet. 




-------------END OF PART 2---------------------

## Submission Instruction 
Upload the following files to canvas (without compressing/zipping them)
1. hw5_part1.py
2. hw5_part2.py
3. hw5_answersheet.pdf (you can use File->download-> as PDF to export the pdf version)