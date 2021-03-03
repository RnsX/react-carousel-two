# React carousel component

## How to setup project

1. Download repository
2. Run command: npm install
3. Run command: npm start

## Functionality:

1. Must work for mobile and desktop devices - [Yes]
2. Must support swipes - [Yes]
3. Must work for any HTML content - [Yes]
4. Must be animated, finger-following swipes, you can use a multi-picture post in Instagram as a reference.- [Yes]

5. Supports multiple slides on the screen - [Yes]
6. Supports infinite option - [Not completed]
7. Supports scrolling to a selected slide (like go to slide X) - [Yes]

## Change log:

1. carousel now provides easier use for displaying content (either images or html)
2. navigation buttons are now automatically generated based on slide count

## Example of use:

1. Import carousel container

```
import CarouselContainer from './components/carousel-component/carousel-container/carousel-container.component'
```

2. Place your sliders as html elements in carousel component:

```
<CarouselContainer>
  <img draggable={false} src={Image1}/>
  <img draggable={false} src={Image2}/>
  <img draggable={false} src={Image3}/>
  <img draggable={false} src={Image3}/>
</CarouselContainer>
```
