# Forkawesome intergration: A Plugin for Pelican

Makes it easy to integrate forkawesome icons in Pelican content.

**This is still a work in progress**

## Usage

If you use a lot of icons to make your Pelican website content prettier, a lot of times you'll end up writing HTML in Markdown, which can't be said to be very elegant.

This plugin parses your content and replaces :
```markdown
## $$gimp$$ My super title about Gimp

The rest of my paragraph about gimp goes here.
```

with :

```markdown
## <i class='fa fa-gimp'> My super title about Gimp

The rest of my paragraph about gimp goes here.
```

allowing you to put your [Forkawesome](https://forkaweso.me/) icons easily into text.

**Notes**
* Adding the forkawesome library to your theme is up to you : the CSS library has to be available to your browser some way, whether you use a CDN or download the lib yourself.
* This happens _after_ HTML generation, meaning other operations of find-and-replace on markdown take place before.
