# slide-show
html css slideshow
---
#### to make a slider using ` cycle2 ` you need to pass `cycle-slideshow` to class attribute of a div. like this :  
```
<div class="cycle-slideshow">
<img src="image1.png" />
</div>
```
#### if your each slide includes text you have to create a div including img and some text tag and pass the class to its parent by `data-cycle-slides `:  
```
<div class="cycle-slideshow" data-cycle-slides=".slide">
            <div class="slide">
                <img src="images/duck.jpg" alt="">
                <div class="slide-text">
                    <h4>Title1</h4>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam aut1</p>
                </div>
            </div>
```

#### to create previous and next button you can pass `cycle-prev` and `cycle-next` to some span tags to have those buttons automatically.  
```
<span class="cycle-prev">&laquo;</span>
<span class="cycle-next">&raquo;</span>

```

#### how to create a pagger for your slider:
```
<span class="cycle-pager"></span>
```
#### pause slider if user hover mous on slider by `data-cycle-pause-on-hover="true"`:
```
<div class="cycle-slideshow" data-cycle-pause-on-hover="true">...</div>
``` 
