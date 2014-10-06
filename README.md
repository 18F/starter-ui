18F Starter UI
======================

For when you want to get up and go, and also stay on-brand.

### How to use:
Fork me to use as a foundation for your project, add in your HTML and custom CSS/Sass.
Start creating custom styles, if desired, in ```sass/custom.scss```.

### Install dependencies:
```
$ gem install sass
```

### Compile the CSS (from the project root): 
```
$ sass sass/styles.scss styles.css
```

### In your HTML:

```
<link href='http://fonts.googleapis.com/css?family=Raleway:300,400,600,700|Open+Sans:300,400,600,700' rel='stylesheet' type='text/css'>
<link href="styles.css" rel="stylesheet" type="text/css" />
```

### Included tools:

- [Neat](http://neat.bourbon.io/) for grids
- [Bourbon](http://bourbon.io/) for handy Sass mixins

### Starter Grids:

There are some basic starter grids to give your project a little structure quickly. They are in ```sass/grids```. To include one in your project, import it in ```sass/custom.scss``` using ```@import 'grids/grid-file-name';```

They are made so that you can use them modularly. You can include multiple in your project and by including the correct class names in your HTML, can use different column configurations within the pages of your site.
