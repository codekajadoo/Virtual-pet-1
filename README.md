# Virtual-Pet-1
34th HomeWork project at whitehatjr .

# Table of contents

## How to play this?

## How to create this?



# How to play this?

Press the UP ARROW to feed the dog some food



# How to create this?

1.Create a folder for your project and create a folder as images

2.You can download the images from my repository and place them inside the folder .

3.Create the index.html file and start open it with VS-CODE or any editor you prefer .

4.In the <head> tag , paste this code :

```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/0.9.0/p5.min.js"></script>
      <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/0.9.0/addons/p5.dom.min.js"></script>
      <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/0.9.0/addons/p5.sound.min.js"></script>
      <script src="p5.play.js"></script>
```

This is defining the p5.min.js library, the p5.dom.min.js library, the p5.sound.min.js library using the cdn , and the p5.play.js library inserted in the folder itself . You can download it from my repository .

5.Next, you can use bootstrap and JQuery to style your project easily .

```html
<!-- Latest compiled and minified CSS -->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">

<!-- jQuery library -->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>

<!-- Latest compiled JavaScript -->
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>

```

6.Now, you should start with adding firebase . Create a firebase project , a web app in it and a database with a json node name of Food and assign it a value of 20

7.Then add the firebase config like the one I have added:

```html
 <script src="https://www.gstatic.com/firebasejs/8.0.1/firebase-app.js"></script><script src="https://www.gstatic.com/firebasejs/7.17.1/firebase-database.js"></script>
      <script src="https://www.gstatic.com/firebasejs/7.17.1/firebase-database.js"></script>


<!-- TODO: Add SDKs for Firebase products that you want to use
     https://firebase.google.com/docs/web/setup#available-libraries -->

<script>
  // Your web app's Firebase configuration
  var firebaseConfig = {
    apiKey: "AIzaSyD_h9PXMxSiicReA6PYiBZynUJlX2nSgag",
    authDomain: "virtual-pet-1-bf501.firebaseapp.com",
    databaseURL: "https://virtual-pet-1-bf501.firebaseio.com",
    projectId: "virtual-pet-1-bf501",
    storageBucket: "virtual-pet-1-bf501.appspot.com",
    messagingSenderId: "185988396216",
    appId: "1:185988396216:web:6d6353f404a7ebbf01704d"
  };
  // Initialize Firebase
  firebase.initializeApp(firebaseConfig);
</script>
```

8.Start with the <body> tag after ending the head tag and place the following in it:

```html
 <script src="sketch.js"></script>
```

Here we are adding the sketch.js so that we can style the canvas easily .

9.Javascript code is not defined because I downloaded it from 

[HERE]: https://github.com/priyapandey2020/Virtual-Pet--1/archive/master.zip

10.Style the canvas and body either by the <style> tag or external css and the code which goes there is:

```css
html, body {
  margin: 0;
  padding: 0;
  text-align: center;
}
canvas{
  border: 2px solid black;
  margin-top: 10%;
}

```

Here, we are giving the html and body a margin, padding of 0 and text-align:center . The canvas is placed beautifully in the middle and a border which makes it non-blurry .

YAY! YOU MADE IT!!!!!

