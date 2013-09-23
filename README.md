![](images/0.jpg?raw=true)

# Bootstrap Workshop with Hyper Island

- [Download this project](https://github.com/javve/bootstrap-workshop/archive/master.zip) to get started.
- Open index.html in your favorite editor ([Sublime Text](http://www.sublimetext.com/) is awesome and free)
- What are you wating for?

Each assignment contains a couple of images that shows the desired result. I've decided to no include CSS editing in this workshop, but feel free to add margins under some elements to make it look better.

Questions? Grab me or [ping @javve at Twitter](https://twitter.com/javve).

#### Extra

* Tips: Like the kittens? Use [PlaceKitten](http://placekitten.com/) ex  `<img src="http://placekitten.com/400/300" class="img-responsive">` (change 400/300 to get other pictures)
* Tips 2: Think kittens are boring? Use [PlaceSheen](http://placesheen.com/) ex  `<img src="http://placesheen.com/400/300" class="img-responsive">` (change 400/300 to get other pictures)
* Note: See `class="img-responsive"`? [Read more at getbootstrap.com](http://getbootstrap.com/css/#overview-responsive-images)

#### Errors?

If you find any errors (spelling or whatever), please make a __pull request__ (I know Daniel have taught you) or at least [post an issue](https://github.com/javve/bootstrap-workshop/issues/new).


## Assignment 1: Grid

Create a grid that has four columns, independent of screen size. Then put images inside them. [Read more at getbootstrap.com](http://getbootstrap.com/css/#grid)

#### Large
![](images/1-1.png?raw=true)

#### Small
![](images/1-2.png?raw=true)


## Assignment 2: Responsive grid

Improve the grid. It should have four columns for desktop, two for tablets and one in mobile. [Read more at getbootstrap.com](http://getbootstrap.com/css/#grid)

#### Large
![](images/2-1.png?raw=true)

#### Medium
![](images/2-2.png?raw=true)

#### Small
![](images/2-3.png?raw=true)



## Assignment 3: Navbar

Add a responsive menu (navbar) to your site. [Read more at getbootstrap.com](http://getbootstrap.com/components/#navbar). It should container a name (brand)
four items.

#### Large
![](images/3-1.png?raw=true)

#### Small 1
![](images/3-2.png?raw=true)

#### Small 2
![](images/3-3.png?raw=true)



## Assignment 4: Form

Add a creat account form with a large create button. _Remember that Bootstrap supports nested grids._ [Read more at getbootstrap.com](http://getbootstrap.com/css/#forms)

![](images/4-1.png?raw=true)


## Assignment 5: Tooltips and popovers

Javascript!

Time to name your images/kittens. Add [tooltips](http://getbootstrap.com/javascript/#tooltips) that tells the name of the image/kitten
and then add [popovers](http://getbootstrap.com/javascript/#popovers) that show some information about the image you click on.

To do this tasks you'll need to use Javascript. Add all code into `<script></script>` at the bottom of `index.html`, just before `</body>`.

__Tips__: Easiest is probably to use `$('img').tooltip();` & `$('img').popover();` and then use `data-` attributes.

![](images/5-1.png?raw=true)


## Assignment 6: Modal

Add a "read more" link beside "Create account" that launches a modal with more info. [Read more at getbootstrap.com](http://getbootstrap.com/javascript/#modals)

![](images/6-1.png?raw=true)
![](images/6-2.png?raw=true)


## Assignment 7: Styling with LESS CSS (hardcore)

1. Go to [http://incident57.com/less/](http://incident57.com/less/), download `less.app` then open it.
2. Add the files in `/less` by clicking the + button.  
    ![](images/7-1.png?raw=true)
3. Make sure only `bootstrap.less` is checked.  
    ![](images/7-2.png?raw=true)
4. Go to `index.html` and change `<link href="css/bootstrap.css" rel="stylesheet" media="screen">` to `<link href="less/bootstrap.css" rel="stylesheet" media="screen">`
5. Open `less/variables.less` and try change some variables. Maybe `@body-bg: #fff;` to `@body-bg: #ff228a;`?
6. Go to Less.app, click `Compiler` and then `Compile all`.  
    ![](images/7-3.png?raw=true)
    ![](images/7-4.png?raw=true)
7. Reload your browser. Voila!
8. Go to step 5, and start make your site beautiful!

![](images/7-5.png?raw=true)

I guess that's it. Awesome work! Feel free to show me your site :)