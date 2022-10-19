# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

#### Text

- Very dark desaturated blue: hsl(238, 29%, 16%)
- Soft red: hsl(14, 88%, 65%)

#### Gradient

Background gradient:

- Soft violet: hsl(273, 75%, 66%)
- Soft blue: hsl(240, 73%, 65%)

### Neutral

#### Text

- Very dark grayish blue: hsl(237, 12%, 33%)
- Dark grayish blue: hsl(240, 6%, 50%)

#### Dividers

- Light grayish blue: hsl(240, 5%, 91%)

## Typography

### Body Copy

- Font size: 12px

### Font

- Family: [Kumbh Sans](https://fonts.google.com/specimen/Kumbh+Sans)
- Weights: 400, 700



<!-- my planning -->

I will need a good approach on how to do this even though it might not work.

Functionalities

---- Image functionalities

1. On desktop: The image has a bottom card image. It is not as close maybe some gap.
2. Also on the image, there is an  @ box at the left side; just a tiny bit inside the main container.
3. On top of the image, some two spirals are behind the image. They go all the way to the top. 

1. On mobile: We have the image and the bottom holding it pushed to an almost perfect 50% of the main image --- done

----- Faq functionality

1. The faq expands while increasing the height of the container. 
2. When open, the text in summary becomes bold
3. When closed there is a downward arrow, when open the arrow becomes upward. 
4. There is a <hr> line separating all the faq questions. 

---- My plan

1. start with mobile andset the image. -- done
2. deal with the size of the summary inside the detail so that the width doesn't change as the questions are opened. 
3. Go to desktop and deal with the 4 images 😆
4. When the summary text is hovered, change it to the color of the svg arrows. 


---- Tips

```
details[open]{

}

details[open] summary{

}
```

setting it to open by default 

<details open>
...

</details>

Maybe using bootstrap and customzing it

https://getbootstrap.com/docs/5.2/components/accordion/
