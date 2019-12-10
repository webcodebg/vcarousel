# Installation

via npm

`npm install v-carousel`

via cdn

`<script src="https://cdn.jsdelivr.net/gh/webcodebg/vue-skeleton-loader/dist/vcarousel.min.js"></script>`

clone repo

`git clone https://github.com/webcodebg/vcarousel.git`

# Usage
## Importing the repo
### Global usage
```javascript
import vCarousel from 'v-carousel'
import Vue from 'vue'

Vue.use(vCarousel)
```
### Local usage
```javascript
import { vCarousel } from 'v-carousel'
export default {
  components: {
     vCarousel
  }
}
```

## Props / options

## Examples
```html
<v-carousel v-model="currentSlide" :pagination="true" :controls="true" :autoplay="true" interval="3000">
    
    <!-- You can place your own image tag inside v-carousel-slide -->
    <!-- If you use image property it will automatically make image responsive -->
    <v-carousel-slide v-for="slide in [1, 2, 3, 4, 5]" image="https://www.gettyimages.pt/gi-resources/images/Homepage/Hero/PT/PT_hero_42_153645159.jpg">
        
        <!-- Create custom layout in the slide -->
        <div class="title">Sea image # {{ slide }}</div>
    </v-carousel-slide>
</v-carousel>
```


# Issues and contributions
If you want to report issue/improvements [create issue here](https://github.com/webcodebg/vcarousel/issues)

For contributions read the guidelines in [CONTRIBUTING.md here](https://github.com/webcodebg/vcarousel/blob/master/CONTRIBUTING.md)

# Licence
MIT License

Copyright (c) 2019 Webcode