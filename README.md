# Bootsrap Pagecopy
## by Jacob Blampied

### Description 
The aim of this code is to generate a webpage based of an example page (<https://www.volumenetwork.com>) and try to replicate its components. The code was written in Atom version 1.27.2 using languages HTML and CSS. The majority of elements were made using Bootstrap and customised using CSS.

### Tech Used
The code was written in Atom version 1.27.2 using languages HTML and CSS. The majority of elements were made using Bootstrap and customised using CSS.

Document setup:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Volume Network Copy</title>
  <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.3.1/css/all.css" integrity="sha384-mzrmE5qonljUremFsqc01SB46JvROS7bZs3IO2EmfFsd15uHvIt+Y8vEf7N7fWAU" crossorigin="anonymous">


  <script
  src="https://code.jquery.com/jquery-3.3.1.min.js"
  integrity="sha256-FgpCb/KJQlLNfOu91ta32o/NMZxltwRo8QtmkMRdAu8="
  crossorigin="anonymous"></script>
  <!-- Bootstrap Files -->
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">
  <link rel="stylesheet" href="main.css">
  <!-- JavaScript Files -->
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>
</head>
```

### Challenges
Due to the complexity of some of the components on the example page, the basic Bootstrap elements needed to be altered to meet the requirements. The biggest challenge would have to be the carousel, but the basic divs needed to be resized. 

```css

.CaroBoundary {
  height: 250px;
  border: 3px solid black;
}

.CarouselContainer {
  margin-top: 50px;
  height: 150px;
  border: 3px solid black;
}

.left-carousel-control {
  border: 2px solid black;
  width: 100px;
  height: 100px;
  margin-top: -10px;
  margin-left: -10px;
}

.right-carousel-control {
  border: 2px solid black;
  width: 100px;
  height: 100px;
  margin-top: 10px;
  margin-left: 10px;
}

``` 
### Takeaways

* Gained more experience using html to structure more complex pages.  
* Have a greater understanding of CSS and how to use it to override the Bootsrap CSS.
* Should be able to make a webpage now.

### Link to Repository
<https://jacobblampied.github.io/sparta-bootsrap-pagecopy/>

#### How to download:
Type this command in your terminal to clone the repository: git clone git@github.com:JacobBlampied/sparta-bootsrap-pagecopy.git