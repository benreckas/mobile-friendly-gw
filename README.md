# Day 03

### Display None, Visibility Hidden

`display: none;` will remove the element from the page, and all of the space it 
would normally take up will be removed.
`visibility: hidden;` will visually remove the element from the page, but the
space it would normally take up will remain.

### Bootstrap Components

Bootstrap Components are pieces of reusable code that you can bring in to your project
to augment or add something to your content.

Here's a link to the all of the [Bootstrap Components in 3.3.7][https://getbootstrap.com/docs/3.3/components/]

#### Glyphicons

Similar to Font Awesome, we can use these icons that are included in Bootstrap to
easily bring in a vector icon within a `span` element. Ex: `<span class="glyphicon glyphicon-heart"></span>`

#### Jumbotron

The 'hero' of your page, used to showcase key content on your site. You can alter
the styling of your Jumbotron by overriding the Bootstrap defaults in a custom stylesheet.
You add a Jumbotron by using the `.jumbotron` class.

### Media Queries

Media Queries will put custom styles into place at a given screen size.
Any css property can change within a media query. Queries are not a part of
Bootstrap, they are vanilla CSS.

Ex:
This media query will take effect for any screen size under 768px, and it will put a
red background on all `div` elements.

```
@media screen and (max-width: 768px) {
  div {
    background: red;
  }
}
```
