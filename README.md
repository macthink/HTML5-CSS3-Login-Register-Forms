# HTML5/CSS3 Login/Register Forms

These are some beatiful Login/Register Forms built with HTML5 & CSS3. 

## Usage

The forms are made up of both HTML5 and CSS3. The first part involves inserting the HTML found in index.html. Specifically the form that you'd like, be it the register form or the login form. You then need to include the CSS from forms.css.

There are several different color themes you can have:

* Default (blue)
* Red
* Green
* Orange
* Yellow
* Black

To use one, all you need to do is add a color class to the form, like `green` or `red`. Here's an example of what the form part of the HTML would look like to make it orange:

```
<form class="login orange">
```

You can also enable 'labels' for each part of the form. Simply find the label part in `forms.css` and add a `display: block;` style to it. Like so:

```
.register label,
.login label {
	display: block;
}
```
		
There is also a lock symbol included by default. This can easily be removed by getting rid of the `<img` HTML that inserts it, or changing the CSS for it like so:

```
.register .secure,
.login .secure {
	display: none;
}
```
		
There are also several different HTML layouts included in this download. Please take note of some of them, such as the background image ones, which require a little bit extra CSS that is included in the <head> part of the HTML. You should copy this to your forms.css file or wherever you CSS is.

With the background image templates, to change the background, just replace the file in the images folder named `bg.jpg` with your own image with the same file name, or change the filename in the CSS for the background to your new file name.