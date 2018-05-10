# meetup-lewagon-css
Meetup about css and html in Le Wagon Sao Paulo

## Where to know more
http://jsfiddle.net/nick_craver/ntr5b/
https://www.w3schools.com

## Find nice personal icons
* You can pick your icons on [IconStore](https://iconstore.co/), [The Noun Project](https://thenounproject.com/) or [NucleoApp](https://nucleoapp.com/premium-icons/) (they have a free pack).
* **Tips:** Also stay tuned checking [icon resources on Product Hunt](https://www.producthunt.com/search?q=icons)

## Find Images
[Get random images](https://unsplash.it/1300/600?random)

## Doubts
### Id vs Class
* Id refers to an unique element
* Class refers to a recurrent element
https://css-tricks.com/the-difference-between-id-and-class/

### Order import linking to CSS?
Yes, the last one is more in important

## CSS
### Bootstrap
https://getbootstrap.com/

## Grid is important
### Start a grid using container
```html
<div class="container">
	<!-- Create a container with grids -->
</div>
```
### Using rows inside container
```html
<div class="container">
	
	<!-- Create a container with 12 grids -->

	<div class="row">
		<!-- First Row -->
	</div>

	<div class="row">
		<!-- Second Row -->
	</div>

</div>
```
### Responsive matters
Use **vw** instead of **px** on element sizes to fit in mobile and desktop

Static
```css
#banner h1 {
  color: white;
  font-size: 20px;
}
```

Responsive
```css
#banner h1 {
  color: white;
  font-size: 4vw;
}
```