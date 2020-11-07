# code_refactor_1

##HTML

**body**
First of all, it is always important to do *FORMAT DOCUMENT* 
to find out structure of documentaion.
this HTML document fitures NAV bar with links at the Top 
MAIN image element, SECTION-CONTAINER element with 3 SECTIONS inside , ASIDE element with 4 divs and FOOTER element at bottom of document.
Change to semantic tags not just use " div

**nav element**

- Change  *title* element revised to *Horiseon* which indicates for Horiseon websites.

- Change tag name to *nav* from div.
- line-15 inside *nav* remove unnecessay div tag.
- line-17 add *class="navbar-menu"* on *ul* tag.

**main element**

- Change to tag name to *main*.

**div class="section-container" element**

- Change tag name to "section" inside 'div *class="section-container"*.
- add *alt="image name"*  attributes on all *img* tags. 
- add *class="section-contents"* on all  *h2* tag to define CSS class. 

**aside element**

- Change tag name to *aside*.
- add *alt="image name"*  attributes on all *img* tags. 
- add *class="benefit-contents"* on all "h3"tag to define CSS class. 

**footer element**

- Change tag name to *footer*.

**File Path**

File path for CSS and images are revised in order to view on gitHub pages. such as *Develop/Develop/assets/css/style.css*

##CSS

- All repeated class has been consolidated once by adding class name in HTML 
or  change tag name. 

- change class name as class name added and changed. 

- add :root  for colors easier to change colors later on. 

**media queries**

*media and screen(max-width:764px)*
-when screen size reduced,

- change *navBar* 
- all links are placed in vertical.
- reduced size of main image and font-sizes 
- all sections and asides elements shows in rows . 
- **responsive view**
 <img width="489" alt="Screen Shot 2020-11-06 at 4 23 12 PM" src="https://user-images.githubusercontent.com/70460020/98417881-c3896a00-204f-11eb-8633-f5795068db9b.png">
<img width="534" alt="Screen Shot 2020-11-07 at 3 34 09 PM" src="https://user-images.githubusercontent.com/70460020/98451093-aff20800-2110-11eb-8f3f-e7d1744a52e9.png">
<img width="534" alt="Screen Shot 2020-11-07 at 3 34 25 PM" src="https://user-images.githubusercontent.com/70460020/98451095-b2546200-2110-11eb-8a34-06d393e20def.png">
<img width="535" alt="Screen Shot 2020-11-07 at 3 34 36 PM" src="https://user-images.githubusercontent.com/70460020/98451098-b41e2580-2110-11eb-93ca-3c360a128527.png">

