# MUSTACHE and FLEXBOX

# Javascript Templating Language 
![img](https://miro.medium.com/max/700/1*YpdR22sjaflf8VWppz-y3g.png)

> *Javascript templating is a fast and efficient technique to render client-side view templates with Javascript by using a JSON data source. The template is HTML markup, with added templating tags that will either insert variables or run programming logic.*


## Mustache 
![img](https://miro.medium.com/max/700/1*P9q0tkeaRY2l1JOXaVKAig.png)

> *Mustache is a logic-less template syntax. It can be used for HTML, config files, source code — anything. It works by expanding tags in a template using values provided in a hash or object.*
> *It is often referred to as “logic-less” because there are no if statements, else clauses, or for loops.*

![img](https://miro.medium.com/max/700/1*LbqYj87xlazySm6wE0Q2lA.png)

**Mustache-Express**
`$ yarn add mustache-express`

```
var nameObject = {"name": "Sherlynn"}
res.render('hello', nameObject)
```
![img](https://miro.medium.com/max/700/1*YaJ1vtsuwRMhfi8parlHOA.png)

# Flexbox properties

- **display:** This defines a flex container; inline or block depending on the given value.
- **order:** By default, flex items are laid out in the source order.
![img](https://css-tricks.com/wp-content/uploads/2018/10/order.svg)
- **flex-direction: **This establishes the main-axis, thus defining the direction flex items are placed in the flex container.
![img](https://css-tricks.com/wp-content/uploads/2018/10/flex-grow.svg)
- **flex-grow:** This defines the ability for a flex item to grow if necessary. It accepts a unitless value that serves as a proportion.
![img](https://css-tricks.com/wp-content/uploads/2018/10/flex-grow.svg)
- **flex-wrap:** allow the items to wrap as needed with this property.
![img](https://css-tricks.com/wp-content/uploads/2018/10/flex-wrap.svg)
- **flex-shrink:**This defines the ability for a flex item to shrink if necessary.
- **flex-basis:** This defines the default size of an element before the remaining space is distributed.
- **flex-flow:** This is a shorthand for the `flex-direction` and `flex-wrap` properties.
- **flex:** This is the shorthand for `flex-grow`, `flex-shrink` and `flex-basis` combined.
- **align-self:** This allows the default alignment (specified by `align-items`) to be overridden for individual flex items.
![img](https://css-tricks.com/wp-content/uploads/2018/10/align-self.svg)
- **justify-content:** This defines the alignment along the main axis.
![img](https://css-tricks.com/wp-content/uploads/2018/10/justify-content.svg)
- **align-items:** This defines the default behavior for how flex items are laid out along the cross axis on the current line.
![img](https://css-tricks.com/wp-content/uploads/2018/10/align-items.svg)
- **align-content:** similar to how `justify-content` aligns individual items within the main-axis.
![img](https://css-tricks.com/wp-content/uploads/2018/10/align-content.svg)


# FLEXBOX FROGGY
> *All done.*