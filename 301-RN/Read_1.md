# Responsive Web Design
![img](https://quintagroup.com/services/web-design/responsive-website-design.png)

> *Responsive web design is the practice of building a website suitable to work on every device and every screen size, no matter how large or small, mobile or desktop.*

- **Responsive web design is focused around providing an intuitive and gratifying experience for everyone.**
![img](https://learn.shayhowe.com/assets/images/courses/advanced-html-css/responsive-web-design/food-sense.png)

![img](https://learn.shayhowe.com/assets/images/courses/advanced-html-css/responsive-web-design/food-sense.png)


## Responsive vs. Adaptive vs. Mobile
> 1. Responsive and adaptive web design are closely related, and often transposed as one in the same. Responsive generally means to react quickly and positively to any change, while adaptive means to be easily modified for a new purpose or situation, such as change.


> 2. Mobile, on the other hand, generally means to build a separate website commonly on a new domain solely for mobile users. While this does occasionally have its place, it normally isn’t a great idea.


## Flexible Layouts
> Flexible layouts do not advocate the use of fixed measurement units, such as pixels or inches. Reason being, the viewport height and width continually change from device to device. Website layouts need to adapt to this change and fixed values have too many constraints.


### Flexible Grid
- html
```
<div class="container">
  <section>...</section>
  <aside>...</aside>
</div>
```

- css 
```
.container {
  width: 538px;
}
section,
aside {
  margin: 10px;
}
section {
  float: left;
  width: 340px;
}
aside {
  float: right;
  width: 158px;
}
section,
aside {
  margin: 1.858736059%; /*  10px ÷ 538px = .018587361 */
}
section {
  float: left;
  width: 63.197026%;    /* 340px ÷ 538px = .63197026 */   
}
aside {
  float: right;
  width: 29.3680297%;  /* 158px ÷ 538px = .293680297 */
}
```

## Media Queries 

> *Media queries were built as an extension to media types commonly found when targeting and including styles. Media queries provide the ability to specify different styles for individual browser and device circumstances, the width of the viewport or device orientation.*

```
@media all and (max-width: 1024px) {...}

/* @import Rule */
@import url(styles.css) all and (max-width: 1024px) {...}
```



# All About Floats
![img](https://i1.wp.com/css-tricks.com/wp-content/csstricks-uploads/print-layout.png?resize=540%2C270&ssl=1)

> *Float is a CSS positioning property. To understand its purpose and origin, we can look to print design. In a print layout, images may be set into the page such that text wraps around them as needed. This is commonly and appropriately called “text wrap”.*

![img](https://i1.wp.com/css-tricks.com/wp-content/csstricks-uploads/web-text-wrap.png?resize=540%2C270&ssl=1)

> *In web design, page elements with the CSS float property applied to them are just like the images in the print layout where the text flows around them.*
**Floated elements remain a part of the flow of the web page.**

```
.class{
    float: left;
}
```

## What are floats used for? 
1. **floats can be used to create entire web layouts.**
2. **Floats are also helpful for layout in smaller instances.**


## Clearing the Float
> *Float’s sister property is clear. An element that has the clear property set on it will not move up adjacent to the float like the float desires, but will move itself down past the float.*
![img](https://i1.wp.com/css-tricks.com/wp-content/csstricks-uploads/directionalclearing.png?resize=540%2C226&ssl=1)

## The Great Collapse 
> *If this parent element contained nothing but floated elements, the height of it would literally collapse to nothing.*
![img](https://i0.wp.com/css-tricks.com/wp-content/csstricks-uploads/collapse.png?resize=540%2C182)

![img](https://i0.wp.com/css-tricks.com/wp-content/csstricks-uploads/grid-blocks-cleared.png?resize=540%2C329)



## Problems with Floats

1. **Pushdown**

2. **Double Margin Bug**

3. **The 3px Jog**

4. **Bottom Margin Bug**

![img](https://i1.wp.com/css-tricks.com/wp-content/csstricks-uploads/pushdown2.png?resize=540%2C198&ssl=1)

> *to cut off excess use `overflow: hidden;`*

