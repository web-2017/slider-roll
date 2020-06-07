# What is this

This is a perfect slider before and after author Mario Magomedov

# Installation

Using npm:

`npm i sliderBeforeAfter --save`

Using yarn:

`yarn add sliderBeforeAfter`

In any js file

```
import { sliderBeforeAfter } from './index'

let slider = new sliderBeforeAfter({
  class_name: 'slider',
  width: '600px',
  height: '350px',
  border_width: '2px',
  border_color: 'red',
  showMoreOptionsLog: true,
})

slider.start()
```

## What inside? look at console

```
- _showMoreOptionsLog_ - set true (Default to false)
```

## Options

shadowizard supports 8 options, all of which are optional:

- _class_name_ - set your class name (Default to 'slider')
- _width_ - set width (Default to '500px')
- _height_ - set height (Default to 'slider')
- _src_ - set first img source (Default to 'https://picsum.photos/id/10/500/350')
- _src2_ - set second img source (Default to 'https://picsum.photos/id/1050/500/350')
- _border_width_ - set borderWidth (Default to '2px')
- _border_color_ - set borderColor (Default to '#fff')
- _showMoreOptionsLog_ - set your class (Default to 'slider')
