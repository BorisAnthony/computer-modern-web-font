# computer-modern-web-font
The Computer Modern LaTeX font for the web

This is a fork of [Dreampulse](https://github.com/BorisAnthony/computer-modern-web-font)'s excellent and much appreciated repo. I've added WOFF2 files and moved some things around.

## To do
* Make a fancy samples page.
* Add "Serif Roman Bold Nonextended" and "Typewriter Text Oblique."

## Example
Take a look at this [example.html](https://cdn.rawgit.com/BorisAnthony/computer-modern-web-font/master/example.html).

## Usage

Insert the `https://cdn.rawgit.com/BorisAnthony/computer-modern-web-font/master/fonts.css` css-stylesheet into your html header.

```html
<head>
  <!-- ... -->

  <link rel="stylesheet" type="text/css" href="https://cdn.rawgit.com/BorisAnthony/computer-modern-web-font/master/fonts.css">
  <style>
    body {
      font-family: "Computer Modern Sans", sans-serif;
    }
  </style>
</head>
```

## Fonts

The folowing font-familys are avaiable:

* `'Computer Modern Bright'`
* `'Computer Modern Concrete'`
* `'Computer Modern Sans'`
* `'Computer Modern Serif'`
* `'Computer Modern Typewriter'`

## Performance

You can use the font for production websites with any amount of traffic. Files are served via MaxCDN's super fast global CDN.
There is no traffic limits or throttling.
