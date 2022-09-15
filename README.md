<!-- hide -->
# The Instagram Post
<!-- endhide -->
Instagram is one of the most popular user interfaces in the world, this is the first of three exercises that will make you replicate the most important and difficult parts of Instagram.com

In this case, we are starting with a single post.

## 🌱  How to start this project

Do not clone this repository.

a) If using Gitpod (recommended) you can clone the boilerplate by [clicking here](https://gitpod.io#https://github.com/4GeeksAcademy/html-hello).

b) If working locally type the following command from your command line: 

```
$ git clone https://github.com/4GeeksAcademy/html-hello
```

💡 Important: Remember to create a new repository, update the remote (`git remote set-url origin <your new url>`), and upload the code to your new repository using `add`, `commit` and `push`.


## Instructions

We are going to replicate [this exact same picture](https://github.com/breatheco-de/exercise-instagram-post/blob/master/preview.png?raw=true). Let's set up our project as follows:

<p align="center"><img src="https://github.com/breatheco-de/exercise-instagram-post/blob/master/preview.png?raw=true" height="300" /></p>

 - [ ] Create the HTML and CSS files in the code editor. If you are using Visual Studio Code, inside the folder where you want to save this project, you can create both HTML and CSS files by clicking on the “New File…” button as follows:

<p  align="center"><img src="https://i.imgur.com/xfn0zgi.jpg" width="450" /></p>
<p  align="center"><img src="https://i.imgur.com/oMu4HS3.jpg" width="400" /></p>

 - [ ] Add the basic HTML structure to you HTML file. If you are using Visual Studio Code, you can type `!` + Enter and that would do the work

<p  align="center"><img src="https://i.imgur.com/mnB0hER.jpg" width="500" /></p>
<p  align="center"><img src="https://i.imgur.com/8PBtZdT.jpg" width="600" /></p>

 - [ ] Change the `<title>` inside the `<head>` tag to “Instagram Post” and add the **styles.css** file as a stylesheet inside the `<head>` as follows:

<p  align="center"><img src="https://i.imgur.com/5v7kuvU.jpg" width="600" /></p>

This project uses a Roboto-type font from Google Fonts and icons from Font Awesome, to import the Roboto-type font from Google Fonts to your code we proceed as follows:

 - [ ] Go to [https://fonts.google.com/](https://fonts.google.com/), type Roboto on the search bar and select the Roboto font below as follows:
 
<p  align="center"><img src="https://i.imgur.com/zjVBN8f.jpg" width="600" /></p>

 - [ ] Once you are in the Roboto font page, scroll down to find the Styles section and select one of the styles by clicking on the + button at the right side of the style, in this occasion, we will select the “Regular 400” Style:

<p  align="center"><img src="https://i.imgur.com/Ir51P9o.png" width="800"/></p>

 - [ ] After selecting the style, click the “View selected families” button at the top-right corner where the “Selected Family” window will display at the right. Here you will copy the code to then paste it into your HTML file `<head>` tags as follows:

<p  align="center"><img src="https://i.imgur.com/xhUJetI.jpg" width="500" /></p>
<p  align="center"><img src="https://i.imgur.com/GU8bqQ0.png" width="400" /></p>
<p  align="center"><img src="https://i.imgur.com/b4FZ2qJ.png" width="800" /></p>


Now, let’s import the Font Awesome Icons into our code (https://fontawesome.com/), 

 - [ ] Go to https://fontawesome.com/ and create an account.
 - [ ] Once you have the account created, you need to go to your account profile page and create a new kit here https://fontawesome.com/kits
 - [ ] Once you create your kit, you need to enter the kit and copy the following code into your HTML `<head>` tags:

<p align="center"><img src="https://i.imgur.com/YhYcFhU.jpg" width="800" /></p>
<p  align="center"><img src="https://i.imgur.com/ejlnj6H.png" width="800" /></p>

Now that we have our HTML and CSS files all set up, we proceed to make our strategy in the next section.
  

## Strategy

Let’s start by identifying which html tags you can use for the website, like `<div>`, `<p>`, etc. Here is the strategy that we will follow in the next instructions:

![Strategy for instagram post](https://github.com/breatheco-de/exercise-instagram-post/blob/master/strategy.gif?raw=true)

 - [ ] Let’s start by creating the first `<div>`, it is highly recommended that any first `<div>` in your code to be a container, where all of the other `<div>` will be contained. So, the first `<div>` will be the container, and we will write it as follows `<div class=”container”>`:

<p  align="center"><img src="https://i.imgur.com/UCT8efS.jpg" width="300" /></p>

 - [ ] As we see in the GIF, the background color is black, so our container needs to cover all of our website screen, to do this we need to go to our CSS file and add a `margin: 0` to our whole body using the `*` as a selector as follows:

<p  align="center"><img src="https://i.imgur.com/C8X3gNe.jpg" width="300" /></p>

 - [ ] Then we need to add the styles to our container, adding the background color, the width and height to cover our whole website screen as follows:

<p  align="center"><img src="https://i.imgur.com/6yTO2a0.jpg" width="350" /></p>

Now, as we see in the GIF, we have a post `<div>` (the green one) that contains 3 main `<div>` (the red ones), that are header, photo and footer. Let's first proceed to make our post frame (the white rectangle) and center it in our website screen as follows:

 - [ ] We need to make our container `display: flex` and align the post rectangle adding `align-items:  center` and `justify-content:  center` to our container class in our CSS file
 - [ ] We need to add the size of our post rectangle using `width` and `height` into the post class in our CSS file. The result should look like this:

<p  align="center"><img src="https://i.imgur.com/Gyw5Oeo.jpg" width="300" /></p>
<p  align="center"><img src="https://i.imgur.com/o3VCPsL.jpg" width="600" /></p>

Let's now create the 3 main `<div>` (the red ones) contained in our post `<div>`, that are header, photo and footer as follows:

 - [ ] Add the 3 main `<div>`  into our HTML file (be sure to add them inside the post `<div>`:

<p  align="center"><img src="https://i.imgur.com/TkSqQRx.jpg" width="350" /></p>

 - [ ] Add the header, photo and footer classes into our CSS file with their width and height, make sure to add the sizes according to your post size (you can use a width of 100% in these 3 classes since the height will be the only value that will vary in size). To help us in this process, we can add a red solid border of 1px to help us visualize how the `<div>` are being distributed in our post rectangle as follows:

<p  align="center"><img src="https://i.imgur.com/JXu8Pon.jpg" width="300" /></p>
<p  align="center"><img src="https://i.imgur.com/YepRjDf.jpg" width="600" /></p>


See that the sum of heights of our header, photo and footer `<div>` is equal to our post `<div>` height. Let's now work on our header `<div>`:

 - [ ] Add the 3 `<div>` into our HTML file according to the GIF (make sure to add them inside our header `<div>`), that will contain the logo, the title/username of the photo and the 3 dot icon, let's use `id` as a selector for these 3 `<div>`

<p  align="center"><img src="https://i.imgur.com/ng5lrcW.jpg" title="source: imgur.com" /></p>

 - [ ] Add the styles into our CSS file corresponding to these 3 `<div>` using the `#` selector since we are working with `id` instead of `class`. Let's add width, height and a solid orange border as a reference for our 3 `<div>` as follows:

<p  align="center"><img src="https://i.imgur.com/mncYgR9.jpg" width="300" /></p>
<p  align="center"><img src="https://i.imgur.com/2o93exX.jpg" width="600" /></p>

 - [ ] Let's now add the HTML5 logo using Font Awesome, go to https://fontawesome.com/icons and search for the HTML5 logo, once you've found it, click on the logo and copy the following code into our HTML file (inside the logo `<div>`):

<p  align="center"><img src="https://i.imgur.com/Z3ZoqNA.png" width="700"/></p>
<p  align="center"><img src="https://i.imgur.com/cmKQR8Z.png" width="450"/></p>
<p  align="center"><img src="https://i.imgur.com/mZsVakk.png" width="600" /></p>

 - [ ] Now that we have the HTML5 logo, we need to add the styles for it. First, center the logo in its `<div>` using flexbox adding the following code into the logo selector in our CSS file:

<p  align="center"><img src="https://i.imgur.com/dBUj02y.png" width="300" /></p>

 - [ ] Change the HTML5 logo size adding this code `fa-2x`, which corresponds to a literal sizing statement for font awesome icons (to learn more about font awesome icons sizing, you can visit https://fontawesome.com/docs/web/style/size) , into the icon's class as follows:

<p  align="center"><img src="https://i.imgur.com/uHu3aJ5.png" width="450"/></p>
<p  align="center"><img src="https://i.imgur.com/PfZKrO8.jpg" width="450" /></p>

 - [ ] Add the username text into the username `<div>` (HTML file), note that the word `HTML5` is in strong font, so you need to wrap it in `<strong>` tags. You need to also add a line break `<br>` at `Rigoberto`

<p  align="center"><img src="https://i.imgur.com/xk2p1fM.png" width="450" /></p>
<p  align="center"><img src="https://i.imgur.com/cICmzAv.jpg" width="500"/></p>

 - [ ] Add the styles to align the username text and to change the font to the Roboto-type font into our CSS file as follows:

<p  align="center"><img src="https://i.imgur.com/6iXjBJk.png" /></p>
<p  align="center"><img src="https://i.imgur.com/Car9VpN.jpg" width="500" /></p>

**Note**: You can copy the Roboto-type font style from [https://fonts.google.com/](https://fonts.google.com/). Go to the selected families and copy the following code:

<p  align="center"><img src="https://i.imgur.com/ozfVhNn.png" width="400" /></p>

 - [ ] Add the 3 dot icon into the right side of our header using Font Awesome, go to https://fontawesome.com/icons and search "ellipsis-vertical", once you've found it, click on the desired icon and copy the following code into our HTML file (inside the otherOptions `<div>`), you can also add the sizing right away (`fa-2x`):

<p  align="center"><img src="https://i.imgur.com/cbFDU6n.png" width="600" /></p>
<p  align="center"><img src="https://i.imgur.com/A8BG0S1.png" width="500" /></p>

 - [ ] Add the styles into our CSS file corresponding to the 3 dot icon to move it to the right corner of our post and also center it as follows:

<p  align="center"><img src="https://i.imgur.com/wFPztit.png" /></p>
<p  align="center"><img src="https://i.imgur.com/lAdfesP.jpg" width="500" /></p>

 - [ ] Remove all the borders in our post header (CSS file) and see the results:

<p  align="center"><img src="https://i.imgur.com/g2eSZQa.jpg" width="500"/></p>

 - [ ] Let's now add the image into our photo `<div>` (HTML file), you can add any image writing the `<img>` tag alongside the image source as follows:

<p  align="center"><img src="https://i.imgur.com/DF6cKsT.png" width="900"/></p>
<p  align="center"><img src="https://i.imgur.com/wEUujXZ.jpg" width="700" /></p>

 - [ ] Add the styles to fit the image in our photo `<div>` in our CSS file. Set the width and height to `100%` and add the `object-fit:  cover` style so our photo does not get distorted as follows:

<p  align="center"><img src="https://i.imgur.com/7rkZ3yH.jpg" width="250" /></p>

  - [ ] Remove the border in our post photo `<div>` (CSS file) and see the results:

<p  align="center"><img src="https://i.imgur.com/zzMHV81.jpg" width="500" /></p>

 - [ ] Let's add the 3 `<div>` contained in our footer where the "icons", "likes" and "description" will be into our HTML file as follows (let's use the id selector again for these `<div>`):

<p  align="center"><img src="https://i.imgur.com/BEh7s4I.png" width="900" /></p>

 - [ ] Add the styles into our CSS file corresponding to these 3 `<div>` using the `#` selector since we are working with `id` instead of `class`. Let's add width, height and a solid purple border as a reference for our 3 `<div>` as follows:

<p  align="center"><img src="https://i.imgur.com/evTy2qP.jpg" width="300" /></p>
<p  align="center"><img src="https://i.imgur.com/CZ8Skb4.jpg" width="500" /></p>

 - [ ] Now let's add the 4  `<div>`  into our HTML file according to the GIF (make sure to add them inside our icons  `<div>`), that will contain the heart, comment, send and save icons, let’s use  `id`  as a selector for these 4  `<div>`:

<p  align="center"><img src="https://i.imgur.com/4PdnJXY.png" width="900" /></p>

 - [ ] Let's add the icons using Font Awesome, go to [https://fontawesome.com/icons](https://fontawesome.com/icons) and search "heart" for the heart icon, "comment" for the comment icon, "paper-plane" for the send icon and "bookmark" for the save icon, copy the icon codes and paste them into their corresponding `<div>`, let's also add the sizing, use `fa-2xl` for this occasion:

<p  align="center"><img src="https://i.imgur.com/6CzCbt3.png" width="900" /></p>

 - [ ] Add the following styles into our CSS files so we can draw the orange boxes as reference to our icons positions:

<p  align="center"><img src="https://i.imgur.com/ezF0dZZ.jpg" /></p>
<p  align="center"><img src="https://i.imgur.com/iJ4UQXN.jpg" width="500" /></p>

 - [ ] Now we need to make our orange boxes `display: flex` and align the items vertically and horizontally. Note that, for the save icon, we will need to change the flex direction to column so we can apply `flex-end` and put it to the right side of our icons section. Apply the following styles into our CSS file:
 
<p  align="center"><img src="https://i.imgur.com/KjMAZAC.jpg" /></p>
<p  align="center"><img src="https://i.imgur.com/jbD8ETF.jpg" width="500"  /></p>

 - [ ] Remove the orange and purple boxes (icons section) from the styles in our CSS file and see the results

<p  align="center"><img src="https://i.imgur.com/T2CIyfS.jpg" width="500"/></p>

 - [ ] Now for the final part, let's add the text into our HTML file corresponding to the likes and description sections, remember to use the `<strong>` tag whenever is needed. You can also type `lorem` + enter in the description section to auto-fill that text:

<p  align="center"><img src="https://i.imgur.com/MeXk4PI.png"/></p>
<p  align="center"><img src="https://i.imgur.com/dMtIpUQ.jpg" width="500" /></p>

 - [ ] We just need to add the styles into our CSS file corresponding to the likes and description section. Add the Roboto-type font, add some padding, remove the remaining boxes and we are good to go

<p  align="center"><img src="https://i.imgur.com/bylcc3i.jpg" /></p>
<p  align="center"><img src="https://i.imgur.com/d8Bkuh2.jpg" width="600" /></p>


## What to do if you are stuck?

Ask the instructor or classmates right away. Do not stay stuck for more than 15 min because this is one of your first exercises and you are not expected to know everything. Ask questions!!!

## Fundamentals
This exercise covers the following fundamentals:

1. Basic structure for every HTML5 website.  
2. The *Link* tag to import CSS Rules.  
3. Using google fonts.  
3. Using the different selectors available in CSS.  
4. Working with boxes: border, padding and margins.  
5. Overflow.  
6. Using Flex vs Position vs Float vs Display.  
7. Using a simple form.  
