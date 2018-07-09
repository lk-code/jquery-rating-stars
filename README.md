# jQuery RatingStars

A simple but powerful jQuery plugin for rating stars.

## Informations

you can design the entire UI yourself (CSS and Icons).

## Getting Started

see the examples in the examples-directory.

### jQuery options

```
var ratingOptions = {
    selectors: {
        starsSelector: '.rating-stars',                 // the main container
        starSelector: '.rating-star',                   // the container for a single star
        starActiveClass: 'is--active',                  // the css-class for the active stars
        starHoverClass: 'is--hover',                    // the css-class for the hover stars
        starNoHoverClass: 'is--no-hover',               // the css class for the other stars (only in the hover effect)
        targetFormElementSelector: '.rating-value'      // the selector for the input
    }
};
```