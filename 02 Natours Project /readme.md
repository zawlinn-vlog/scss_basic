> I'm Zaw Linn Tun a Frontend Web Developer on [Zaw Linn Tun](https://www.facebook.com/zawlinn.profile). :heart:

<br>

## Languages &mdash;

<!-- ![Screenshot of Project](./s1.png) -->

What I use packages are &mdash;

[![My Skills](https://skillicons.dev/icons?i=html,css,git,github,vscode&perline=3)](https://skillicons.dev)

<br>

## What you will learn in the lecture &mdash;

- The best way to perform a basic reset using the `universal` selector.
- How to set project-wide font definitions.
- How to clip parts of elements using `clip-path`.
- The easiest way to center anything with the `transform`, `top` and `left` properties
- How to create CSS animations using `@keyframes` and the animation property
- What `pseudo-elements` and `pseudo-classes` are:
- How and why to use the `::after` pseudo-element;
- How to create a creative hover animation effect using the `transition` property
- How and why to use `rem` units in our project;
- A great workflow for converting `px` to `rem`.
- How to use the `BEM` method in practice
- `The focus of this project is on using modern CSS properties and techniques`: clips, transforms, animations, background video, etc.
- Even though flexbox and CSS Grid are more modern, `every web developer should still know how float layouts work`
- As a professional developer, `your job will include working with older CSS codebases,` which will contain float layouts.
- Thinking about `components`.
- How and why to use `utility classes`
- How to use `background-clip` property
- How to use `multiple properties` simultaneously
- How to use `outline-offset` property together with `outline`
- How to style elements that are `NOT` hovered while other are;
- How to include and use an `icon font`(linea.io )
- Another way of creating `skew` section design
- How and when to use the `direct child` selector
- How to build `amazing rotating cards`
- How to use `perspective` in CSS
- How to use `backface-visibility` property
- Using` background blend mode`
- How and when to use `box-decoration-break`
- How to make text flow around shapes with `shape-outside` and `float`
- How to apply a `filter` to images
- How to create `background video`covering an entire section
- How to use `the <video> HTML element`.
- How and when to use the `object-fit` property.
- How to implement `solid-color gradients`
- How to general and `adjacent sibling selectors` work and why we need them;
- How to use the `::input-placeholder` pseudo-element;
- How and when to use the `:focus, :invalid, :placeholder-shown` and `:checked` pseudo-classes;
- Techniques to build `custom radio` buttons.
- How to design a simple `website footer`.
- What the `checkbox hack` is and how it works
- How to create custom animation timing functions using `cubic bezier curzes`.
- How to animate `solid-color gradients`.
- How and why to use `transform-origin`
- In general create an amazingly `creative effect`!
- How to build a `nice popup with only CSS`;
- How to use the `:target` pseudo-class:
- How to `create boxes with equal heigh`t using `display: table-cell`:
- How to create `CSS text columns`:
- How to `automatically hyphenate words` using `hypes`

<br />

```scss
//  COLORs

//  light green: #7ed56f
//  Medium Green: #55c57a
//  Dark Green: #28b485;
```

<br />

- `transform` ကို သုံးပြီး `animation` ပြုလုပ်တဲ့အခါ တုန်တဲ့ ပြဿနာတတ် တတ်တယ်. အဲအခါ parent မှာ `backface-visibility: hidden;` လို့ သတ်မှတ်ပေးလိုက်ရင် အဆင်ပြေပြီး

- Animation fill mode `backward` က animation မစခင်မှာ 0% condition ကို Apply လုပ်ပေးတယ်။

### FLUID LAYOUTs

- To allow webpage to adapt to the current viewport width(or even height)
- Use `%`(or `vh/ vw`) unit instead of `px` for elements that shoud adapt to viewport(usually layout)
- Use `max-width` instead of width

<br />

1. FLOAT LAYOUTs &mdash;

The `old way of building layouts` of all sizes, using the float CSS property. Still used, but getting outdated.

- How to architect and build a simple grid system;

- How the attribute selector works:

- How the `:not` pseudo-class works;

- How `calc()` works, and what's the difference between `calc()` and simple Sass operations.

2. FLEXBOX &mdash;

Modern way of laying out elements in a `1-dimensional row` without using floats. Perfect for `component layouts`.

3. CSS GRID &mdash;

For laying out element in a fully-fledged `2-dimensional grid`. Perfect for `page layouts and complex components`.

### RESPONSIVE UNITs

- Use `rem` instead of `px` for most lengths
- To make it easy to scale the entire layout down(or up) automatically

### FLEXIBLE IMAGEs

- By default, images don't scale automatically as we change the viewport, so we need to fix that
- Always use `%` for image dimensions, together with the `max-width` property

### MEDIA QUERIEs

- To change CSS styles on certain viewport widths(called breakpoints)

bennettfeely.com/clippy

## NODE.js

Allows developers to write and run JavaScript applications on the server. Developers started using node.js to also write tools to help them with `local web development`.

## NPM

NPM is a simple command line interface that allows developers to `install and manage packages` on their local computers. There are all kinds of open-source `tools`, `libraries and frameworks` needed for modern development. Modern web developement could simply not exist withouta package manager.

<!-- TODO: Add last video link -->

## Responsive Design Strategies

- Start writing CSS for the desktop large screen;
- Then, media queries shrink design to smaller screens
- Start writing CSS for mobile devices small screen
- Then, media queries expand design to a large desktop screen;
- Forces us to reduce websites and apps to the absolute essentials

```

                max-width(600ox)
Desktop First ----------------------
                (width <= 600px)    \
                                     \
                         0px ------- 600px ------- 900px ------- 1200px -------- ∞
                                       \
                                        \                          min-width(600px)
                                         ------------------------------------------ Mobile First
                                                                   (width >= 600px)


```

### Is Mobile-first Right for you?

| PROS                                                              | CONS                                                                            |
| :---------------------------------------------------------------- | :------------------------------------------------------------------------------ |
| 100% optimised for the mobile experience                          | The desktop version might feel overlay empty and simplistic                     |
| Reduces websites and apps to the absolute essentials              | More difficult and counterintuitive to develop                                  |
| Results in smaller, faster and more efficient products            | Less creative freedom, making it more difficult to create distinctive products  |
| Prioritizes content over aesthetic design, which may be desirable | Clients are used to see a desktop version of the site as a prototype            |
|                                                                   | Do your users even use the mobile internet? What's the purpose of your website? |

### Selecting Our Breakpoints: A Good Approach

- 0 to 600px (Phone Only)
- 600px to 900px (Tablet Portrait)
- 900px to 1200px (Tablet Landscape)
- 1200px to 1600px (Desktop)
- \> 1600px (Big Desktop)

## What you will learn in this lecture

- How to use a `powerful Sass mixing `to wirte all our `media queries`.
- How to use the `@content` and `@if` Sass directives
- Taking advantage of `Chrome Dev Tools for reponsive design`

## What are responsive images anyway?

> The goal of responsive images is to serve the `right image` to the `reight screen size` and device, in order to avoid downloading unnecessary large images on smaller screens.

1. Resolution Switching (Decrease image resolution on smaller screen)
   - Screen Size ပေါ်မူတည်ပြီး ပေးပို့သော images ကွာခြားပါတယ်။
2. Density switching (Half the image resolution on @1x screen)
   - Screen size ပေါ် မူမတည်ဘဲ pixel density ပေါ်မူတည်ပါတယ်။ ၁လက်မ/၁စင်တီမီတာ ပတ်လည်မှာရှိသော pixel အရည်အတွက်ကို ဆိုလိုခြင်းဖြစ်ပါတယ်။
   - 1x pixel design/ x1 screen ဆိုတာ 1 logical pixel == 1 physical pixel နဲ့တူတူဖြစ်ပါတယ်။ ဥပမာ 100px ရှိတဲ့ပုံကို screen မှာဖော်ပြမို့ physical 100px လိုအပ်ပါတယ်။ (normal pc screen - low resolution screen)
   - 2x pixel design/x2 screen ဆိုတာ 1logical pixel == 2 physical pixel လိုအပ်ပါတယ်။ ဥပမာ 100px ရှိတဲ့ပုံကို screen မှာဖော်ပြမို့ physical 200px လိုအပ်ပါတယ်။ ဒါကြောင့် 100px ပုံတစ်ပုံကို ပြပေးမို့ 200px ရှိတဲ့ ပုံဖြစ်မို့ အရေးကြီးပါတယ်။ (retina pc screen/ smart phone - high resolution screen)
3. Art Direction (Different image on smaller screen)
   - ပုံတစ်ပုံတည်းကို resolution လျော့ပေးတာမျိုး မဟုတ်ပါဘူး screen size မတူတဲ့အခါ မတူညီတဲ့ image တစ်ပုံကို ပြပေးတာ ဖြစ်ပါတယ်။ image ထဲက အရေးကြီးတဲ့ အပိုင်းကိုသာ ထားပြီး ကျန်တာတွေကို ဖြတ်ထုတ်ပေးတာ ဖြစ်ပါတယ်။

## What you will learn in this lecture

- How to use the `srcset` attribute on the `<img>` and `<source>` elements, together with density descriptors
- How and why to use the `<picture>` element for art direction.
- How to write `media queries in HTML`.

### Density Switching

```html
<img
  srcset="./assets/img/logo-green-1x.png 1x, ./assets/img/logo-green-2x.png 2x"
  alt="Full Logo"
  class="footer__logo"
/>
```

low resolution မှာ 1x နဲ့ပြပြီး high resolution မှာ 2x နဲ့ ပြပေးမှာ ဖြစ်ပါတယ်။

### Art Direction

```html
<picture class="footer__logo">
  <source
    srcset="
      ./assets/img/logo-green-small-1x.png 1x,
      ./assets/img/logo-green-small-2x.png 2x
    "
    media="(max-width: 37.5em)"
  />

  <!-- Density Switching -->

  <img
    srcset="
      ./assets/img/logo-green-1x.png 1x,
      ./assets/img/logo-green-2x.png 2x
    "
    alt="Full Logo"
    class=""
  />
</picture>
```

## What you will learn in this lecture

- How to allow the browser to decide the best image to download, using the `srcset` attribute, width descriptors, and the `sizes` attribute of the `<img>` element.

## What you will learn in this lecture

- How to implement responsive image in CSS.
- How to use resolution media queries to target high-resolution screens with 2x
- How to combine multiple conditions in media queries

## What you will learn in this lecture

- How to use `@supports` feature queries.
- Implement graceful degradation on selected properties.
- How to use `backdrop-filter`.

📫 Reach me out!

[![Messenger](https://img.shields.io/badge/Messenger-00B2FF?logo=messenger&logoColor=white)](https://m.me/zawlinn.profile)
[![Gamil Badge](https://img.shields.io/badge/-Gmail-c0392b?style=flat&labelColor=c0392b&logo=gmail&logoColor=white)](mailto:zawlinn.profile@gmail.com)

<details>
    <summary>
        My Portfolio
    </summary>
    <br/>

- :earth_asia: I’m currently working at @Mae Sot Market as a sale staff
- :computer: Most used line of code git commit -m "Initial Commit"
- :brain: I’m looking for help with Outstanding Video ideas.
- :mailbox_with_mail: How to reach me: zawlinn.profile@gmail.com.
- :heart: In a relationship with React
</details>
