# `Bootstrap` 

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

**gutter classes column ke bech me padding and margin dene ka kam karti he <br> left or right padding dega <br> top and bottom me margin dega <br> g prefix he** <br>
