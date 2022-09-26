# Second challenge for the UT-Austin Full Stack Development Bootcamp

## Develop a Starter Portfolio page 

Developing a good portfolio will be vital to show people where my coding skills are, were, and will be. So the second module challenge for the Bootcamp is to create a beginning portfolio page using Advanced CSS techniques that we learned in class.

The inspiration for the overall layout and design is from the Challenge Assignment, which was to replicate the given page and functionality as close as possible. To that end, most of the design decisions come directly from the team at the UT-Austin Bootcamp and were replicated in form and function, with some small tweaks here and there. 

![Screenshot of Horiseon Webpage](./assets/images/Advanced%20CSS%20Portfolio%20screenshot.jpg)


___


## Changes Made and Lessons Learned

I used a color theme generator at [coolors.co](https://coolors.co) to get a color theme close to the one listed in the assignment. When building the page, I assigned all the major colors to CSS variables so I could easily change the overall look and feel of the page.  

I quickly realized the advantages to using Flexbox for most of the layout, including sections I didn't think originally needed it, such as the `<li>` elements in the `<header>` and "Contact Me" sections. That made the responsiveness much easier to implement and much nicer to look at. 

Since my previous work was in digital video production, I decided to go ahead and include some of that work in the page as well so the links would actually go to real locations. All of the images were generated by me for those projects and resized for the project. ([The Star Trek ship in the "Constellation" section is a 3D render I made in Blender](https://blenderartists.org/t/remaking-a-star-trek-sovereign-model-bit-by-bit/1208369) using a heavily modified source Blend from [Geblendert](https://sketchfab.com/3d-models/star-trek-sovereign-class-ussgeblendert-30608d0b13984ef9a16512ec65edd566). Just to be clear, this was a fan RPG and not official in anyway. I just really love the way the model turned out.)

The brief for the assignment included a punchy tagline in the hero section. I had been wanting to design a shirt with the short two sentence tagline "Forged by Geekdom. Fueled by Coffee." since one of our community members suggested it for t-shirts a few years ago. It seemed fitting here so I decided to adapt it for this project. I did want to add a little character to it so I used Flexbox justifications and alignments to offset the headers and create the stacking box effect. That took some time to make consistent at all the responsive sizes.

I also took the time to add `transition` attributes to most the elements that would change in order to smooth the transitions from smaller to larger sizes, and vice-versa.


___


## Possible Future Changes

- I included additional variables for accent colors to add later.
- Further optimize image size to improve load times.
- Add additional projects to show Directing experience.
- Continue to refactor CSS and try to simplify styles.css.

___



## Credits

The original visual concept of the page was created by staff of the UT Austin Full Stack Development Bootcamp. Thanks to Leah, Ian, Negin, Diem, and all the students who work with me daily to keep improving. 

The animating background on the navbar and Contact Me section was inspired by [Geoff Graham on CSS Tricks](https://css-tricks.com/having-fun-with-link-hover-effects/).

Background for the Github image is a composite of a personal photo and Photo by [Adi Goldstein](https://unsplash.com/@adigold1?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/s/photos/technology?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)
  
Background image in hero section from Steve Johnson at [Pexels.](https://www.pexels.com/photo/multicolored-lighted-device-1044990/)


___


## License

MIT License

Copyright (c) 2020 Mark Gardner

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.