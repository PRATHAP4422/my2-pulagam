# saiprathap reddy pulagam
Myself saipratha ,i completed my ug in computer science and i have prior experience  as devops enginner , my hobbies are playing cricket and online games .

my image inserted
![my image](MicrosoftTeams-image.png) 

------------------------------------
# Sports Section
We are creating a table for students to try in a different sports 
| name of a sport | reason for recommendation | Hrs in a week |
| --------------  | ------------------------- | ------------- |
| Cricket         | My favrt sport            |    7          |
| Base ball       | Fun                       |    5          |
| Football        | Trilling sport            |    5          |
| Tennis          | running                   |    6          |

-------------------------------------------------------------
# Scientist Section
> "The more I learn, the more I realize how much I don't know." - *Isaac Newton*

> "The only source of knowledge is experience." - *Albert Einstein*

--------------------------------------------------
# Code fencing section
> SVG patterns scaling the way pattern is not cut off
Link of the svg circle pattern
[Svg](https://stackoverflow.com/questions/61179458/svg-patterns-scaling-the-way-pattern-is-not-cut-off)

```<svg width="100%" height="100%">
  
  <!-- Create mask that we'll use to define a slight gradient -->
  <mask maskUnits="userSpaceOnUse" id="fade">
    <!-- Here's that slight gradient -->
     	<linearGradient id="gradient" x1="0" y1="0" x2="0" y2="100%">
      <stop offset="0" style="stop-color: #FFFFFF"></stop>
      <stop offset="1" style="stop-color: #000000"></stop>
    </linearGradient>
    <!-- The canvas for our mask -->
    <rect fill="url(#gradient)" width="100%" height="100%"></rect>
  </mask>
    
  <!-- Let's define the pattern -->
  <!-- The width and height should be double the circle radius we plan to use -->
  <pattern id="pattern-circles" x="0" y="0" width="40" height="40" patternUnits="userSpaceOnUse">
    <!-- Now let's draw the circle -->
    <!-- We're going to define the `fill` in the CSS for flexible use -->
    <circle mask="url(#fade)" cx="20" cy="20" r="20"></circle>
  </pattern>
  <!-- The canvas with our applied pattern -->
  <rect x="0" y="0" width="100%" height="100%" fill="url(#pattern-circles)"></rect>
  
</svg>
```

[Snippet from css ](https://css-tricks.com/snippets/svg/svg-patterns/)