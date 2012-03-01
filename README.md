# Easing Equation for SASS/SCSS

A list of easing cubic-bezier functions derived from [Robert Penner](http://twitter.com/robpenner)'s easing equation. Code was taken from the [LESS-CSS3-Mixins](https://github.com/MatthewWagerfield/LESS-CSS3-Mixins) github repository and then converted from LESS to SASS/SCSS.

## Usage

Assuming you are using [Compass](http://compass-style.org) and have the `easing.scss` and your `site.scss` file:

```scss
// easing.scss
@import 
@import "easing.scss";

.button {
	+transition(400ms $easeInOutQuint);
}
```
