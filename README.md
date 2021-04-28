# Slider - Javascript  Vanilla

Vanilla javascript slider for an University exercise

## Use

```html
<section id="slider" data-slider="true" data-effect="fade" data-time="4500">
        <ul class="slider__container">
		      <li class="slide">
              <img class="img-carrousel" src="./images/slide1.jpg" alt="Slide">
          </li>
          <li class="slide">
              <img class="img-carrousel" src="./images/slide2.jpg" alt="Slide">
          </li>
          <li class="slide">
              <img class="img-carrousel" src="./images/slide3.jpg" alt="Slide">
          </li>
        </ul>
  </section>
```

### Transition time
Modify the value on "data-time" attribute in html markup and put the time in milliseconds.
Example: data-time="1500", equals to 1.5 seconds between slide and slide.

### Effects
Modify the "data-effect" in the html markup to change the slider effect transition. Possible values are: "fade", "left", "top".
