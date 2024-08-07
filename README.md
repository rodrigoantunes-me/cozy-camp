# Glam Up My Markup - Cozy Camp

[![dev.to](https://img.shields.io/badge/dev.to-0A0A0A?style=for-the-badge&logo=devdotto&logoColor=white)](https://dev.to/rodrigoantunes/glam-up-my-markup-cozy-camp-149k)

_This is a submission for DEV Challenge v24.03.20, Glam Up My Markup: Camp Activities_

## Demo
[![CodePen](https://img.shields.io/badge/Codepen-000000?style=for-the-badge&logo=codepen&logoColor=white)](https://codepen.io/rodrigoant/pen/rNbmNYe)


## Journey
I started by choosing the colors. I wanted to deliver a cozy and warm vibe, so I used CSS Variables to help me remember them.
```css
:root {
  --color-camp-01: #738d5e; // muted green
  --color-camp-02: #293d31; // rich green
  --color-camp-03: #ffc78a; // warm golden
}
```


Looking at camp inspiration designs, I found strong typography, colorful contrasts and nature-inspired illustrations. Fonts are always hard to choose, so I made up my mind on `Truculenta` and kept moving forward.


![Truculenta from Google Fonts](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ffzdd4dbrr5g2vejw4n7.png)


Ok, time to build the thing.
Since we cannot edit the HTML, with flexbox I manage to achieve something like this.
Looks fine, but there is still some work to be done.

![Form v1](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ppfah6xzww0vpbk45lag.png)


This is more of a mobile-first approach, since on desktop we have more room to work with, I thought about changing the direction of the flex elements. And using the `:after` pseudo element so I could place something inside the `<h1>` tag. 
I used an SVG from game-icons library.

![Camp fire SVG from game-icons](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/c4lbfefu3kbhltvi1hsn.png)


Putting it all together, we have this:

![Form v2](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/mk88ejm3r0slp1itq0v8.png)

Good, we are getting somewhere.
Although, there is something missing 🤔

Getting back at the camp designs inspiration, I found some rough edges designs, and things that give some organic look. So I decide to try some `border-image` css to see how it looks.

![Form v3 - Final](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/rosobag4kq9c65kczk7j.png)


Now, about the feedback when the form is sent?
Since I started this thinking about cozyness, we need some smooth animations:

![Animated Gif of the form submission](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ga2amijron4yb2xngu1h.gif)


At the last minute I decide to increased spacing between elements for improved readability 😊

Thank you Dev.to team for creating this challange. 
