# <CENTER>`Bootstrap`</CENTER> 

**<span style="color:red; font-size:19px;">Bootstrap is the combination of Html css and javascript , it is a framework for frontend developer.</span>**

**<span style="font-size:15px;">Bootstrap 5 is open to use</span>**

***In bootstrap 5 Jquery is completely removed and now bootstrap 5 will work according to javascript that makes bootstrap simple to use,Bootstrap currently use Vanila javascript***


## Breakpoint
<div style="color:yellow; font-size:15px">

```
1.**x-small None <576 for mobile**<br>
2.**small sm  >=576**<br>
3.**medium md >=768px**<br>
4.**Large lg >=992px**<br>
5.**Extra-large xl >=1200px**<br>
```
mostly our website use 1170px
</div>

## Container Classes


<div style="color:tomato;font-size:15px;">

1. mobile screen .container  width =100%
2. 

</div>

## container example

![Alt text](ffv.JPG)

<hr color="red" size="10px">

## Grid Options
```1. Extra small (xs)
2. Small (s)
3. Medium (md)
4. Large (lg)
5. Extra large (xl)
6. Extra extra large (xxl)
```

![Alt text](image.png)

<hr color="red">

**Bootstrap kisi bhi div ko 12 columns me divide kar deta hai**

***.col,.col-sm,.col-md,.col-lg,.col-xl,.col-xsl<br>
every div will get 12
classes*** 

```
<div class="container-fluid">
            <div class="container">
               
                <div class="row">
                    <div class="col-lg-3 col-md-6 col-6">Hello </div>
                    <div class="col-lg-3 col-md-6 col-6">Hello 2</div>
                    <div class="col-lg-3 col-md-6 col-6">Hello 3</div>
                    <div class="col-lg-3 col-md-6 col-6">Hello 3</div>
                </div>
            </div>
    </div>
```
## Auto Column layout

```<div class="container">
    <div class="row">
        <div class="col-lg col col-md">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sequi eius perferendis distinctio ad neque voluptatum nulla accusantium nobis maiores fuga omnis similique doloremque quas quae consequuntur, harum rem explicabo voluptate.</div>
        <div class="col-lg col-12 col-md">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sequi eius perferendis distinctio ad neque voluptatum nulla accusantium nobis maiores fuga omnis similique doloremque quas quae consequuntur, harum rem explicabo voluptate</div>
        <div class="col-lg col-md">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sequi eius perferendis distinctio ad neque voluptatum nulla accusantium nobis maiores fuga omnis similique doloremque quas quae consequuntur, harum rem explicabo voluptate</div>
    </div>
</div> 
```



**IS type ke column ke liye 
use hoge vaha 12 colums ke according adjust nahi kar sakte**

<hr color="yellow">

## `Row columns`



***AUTO Column automatic 10 div ko ek line me leke aayege <br>agar mujhe ek hi line me char column chaiye then we use Row column layout***


```<div class="container">
    <div class="row row-cols-2 row-cols-lg-4 row-cols-md-3">
        <div class="col">hello</div>
        <div class="col">hello</div>
        <div class="col">hello</div>
        <div class="col">hello</div>
        <div class="col">hello</div>
        <div class="col">hello</div>
        <div class="col">hello</div>
        <div class="col">hello</div>
        <div class="col">hello</div>
        <div class="col">hello</div>

    </div>
 </div>
 ```

<hr color="blue">

## GUTTER CLASSES

**gutter classes column ke bech me padding and margin dene ka kam karti he <br> left or right padding dega <br> top and bottom me margin dega <br> g prefix he <br> 1rem =16px <br> yaha par jo
g-x (0-5) tak hogi**

> defalut padding 12 px from left and right
* gx-1 uses .25rem matlab 4px mtlb 2px padding from left and right
* gx-2 uses .5 rem matlab 8px 
4px left and 4px right
* gx-3 uses 1rem matlab 16px 
8px left and 8px from right
* gx-4 uses 1.5rem matlab 24px 
12left and 12 right 
* gx-5 uses 3 rem matlab 48px
24px left padding and 24 px right padding

```for desktop gx-lg-1
for tablet gx-md-2
for mobile gx-sm-2
```



```<div class="container">
    <div class="row gx-lg-5 gy-4">
        <div class="col-lg col-md col">hello</div>
        <div class="col-lg col-md col">how </div>
        <div class="col-lg col-md">are</div>
        <div class="col-md col-md">you</div>
    </div>
 </div>
 ```
 
<hr color="white">

## Text Related Class

***There ae some classes of text that will help to do work in less time some of these are***
- ## `center`
     - `text-start` and desktop `text-lg-start` 
     - `text-center` and
     tablet `text-md-center`
     - `text-end` and mobile `text-sm-end`
 
- ## `text-break`
     + to break a big text

- ## `text-uppercase`
     + all letters will be upper class
- ## `text-capitaliza`
     + every word first letter capitalize

- ## `Font size`
     + `fs-1` means 2.5 rem
     + `fs-2` means 2 rem
     + `fs-3` means 1.7 5rem
     + `fs-4` means 1.5rem
     + `fs-5` means 1 rem

- ## `Font Weight and Italics`
     + `fw-bold` 
     + `fw-bolder`
     + `fw-normal`
     + `fw-lighter`
     + `fst-italic`
     + `fst-normal`

<hr size="10" color="green">

*example*

```<div class="container">
    <div class="row">
        <div class="col-12 text-center text-lg-start text-md-end">
            <p class="fs-2 fw-bolder">
                WElcome to my new channel
            </p>
        </div>
    </div>
</div>
```


## UTILITY CLASSES `(SPACING)`


***•m - for classes that set margin<br>
•p - for classes that set padding***

- **`t` - for classes that set margin-top or padding-top**
- **`b` - for classes that set margin-bottom or padding-bottom**
- **`s` - (start) for classes that set margin-left or padding-left in LTR, margin-right or padding-right in RTL**
- **`e` - (end) for classes that set margin-right or padding-right in LTR, margin-left or padding-left in RTL**
- **`x` - for classes that set both `*-left` and * `-right`**
- **`y` - for classes that set both `*-top` and * `-bottom`**


## About size

- ***`p-1 .25 rem 4px`***
- ***`p-2 .25 rem 8px`***
- ***`p-3 .25 rem 16px`***
- ***`p-4 .25 rem 24px`***
- ***`p-5 .25 rem 48px`***


>example
```
<div class="container">
    <div class="row row-cols-1">
        <div class="m-1 p-3"style="background-color: tomato;">
            <p class="text-break">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Facere numquam itaque consequatur magnam rem laudantium nobis labore fuga amet, assumenda reprehenderit at ratione culpa, aut eos, placeat optio in ipsum quo sed! Voluptate nobis iste veniam eligendi neque corporis facere, veritatis inventore minima ea tenetur adipisci iure tempora quos obcaecati!
            </p>
        </div>
    </div>
</div>
```

<hr color="yellow">

## `BACKGROUNDS AND GRADIENTS`

+ `bg-primary`--> blue
+ `bg-secondary`-->greenish
+ `bg-success`
+ `bg-warning` --> yellow color
+ `bg-info` --> blue color
+ `bg-danger` --> red color
+ `bg-light` --> white color
+ `bg-dark` --> black color
+ `bg-white` --> white
+ `bg-transparent` -->

<hr color="BLUE">

## BORDER AND RADIUS

+ **border**
+ **border-top**
+ **border-start**
+ **border-end**
+ **border-bottom**
* *border-bottom-0*
* *border-top-0*

### `border colors`

+ **border-primary**
+ **danger**
+ **info**

## border size

+ **border-1** 1px border
+ **border-2** 2px border
+ **border-3** 3px border

## Border-RADIUS

+ **rounded**  0.25rem 4px from all sides
+ **rounded-top**
+ **rounded-end**
+ **rounded-bottom**
+ **rounded-start**
+ **rounded-circle** if width and height of box is `equal` 
+ **rounded-pill**

 ## size increase

 + **rounded-0** less circulatr
 + **rounded-1**
 + **rounded-2**
 + **rounded-3** more circular

 <hr color="white size="10"/>

## TEXT COLOR CLASSES

* `text-primary`
* `text-secondary`
* `text-success`
* `text-danger`
* `text-warning`
* `text-info`
* `text-dark`
* `text-white`

<hr color="blue" size="10">

## RESPOINSIVE IMAGE DESIGN CLASS


### `img-fluid`
    * work only when big image is there and div is small 

### `img-thumbnail`
    * to make image responsive and in any frame

<hr color="white">

## Clear and Font Classes

**Used to float left and right in content**

  * `float-start` --> to align in left side 
  * `float-end` -> right side
  * `float-lg-start`
  * `float-col-start`
  * `float-md-end`
  * `float-none` --> to remove the direction of float
  *create new `div` and apply
      * `clear-fix`
    
**we also need to clear the direction fo float**
<hr color="white">

## BUTTON CLASSES

**Here are some example**
  
 * `btn`
 * `btn btn-primary`
 * `btn btn-secondary`
 * `btn btn-success`
 * `btn btn-danger`
 * `btn btn-dark`
 * `btn btn-warning`
 * `btn btn-info`
 * `btn btn-light`
 * **OUTLINE TYPE BUTTON**
 * `btn btn-outline-primary`
 * `btn btn-outline-secondary`
 * `btn btn-outline-dark`
 * `btn btn-outline-light`
 * `btn btn-outline-danger`

 ***If want to covert `anchor` tag in button***

 example

 `<a href=" " class="btn btn-primary">hello </a>`

 **For large button**

 * `btn btn-lg`
 * `btn btn-sm`
 <hr color="white">

 ## CARD AND CARD LAYOUT



 ## HIDING ELEMENTS

  * `d-none`--> hide in all devices
  * `d-none d-sm-block` --> hide in below sm means hide in mobile devices

  * `d-none d-md-block`
  * `d-none d-lg-block`
  * `d-block ` --> display on all
  * `d-none d-lg-block` -->hide on all devices but display only on desktop devices

<hr color="yellow" size="20">






