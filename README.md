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

<p  align="center"><img  src="https://github.com/breatheco-de/exercise-instagram-post/blob/master/preview.png?raw=true"  height="300" /></p>

 - [ ] Create the HTML and CSS files in the code editor. If you are using Visual Studio Code, inside the html-hello folder, you can create both HTML and CSS files by clicking on the “New File…” button as follows:

![Creating first files](https://i.imgur.com/bVhCZs2.png)
![Files created](https://i.imgur.com/ISoPVl7.png)

 - [ ] Add the basic HTML structure to you HTML file. If you are using Visual Studio Code, you can type `!` + Enter and that would do the work

![HTML structure 1](https://i.imgur.com/mnB0hER.jpg)
![HTML structure 2](https://i.imgur.com/8PBtZdT.jpg)

 - [ ] Change the `<title>` inside the `<head>` tag to “Instagram Post” and add the **styles.css** file as a stylesheet inside the `<head>` as follows:

![HTML structure 3](https://i.imgur.com/5v7kuvU.jpg)

This project uses a Roboto-type font from Google Fonts and icons from Font Awesome, to import the Roboto-type font from Google Fonts to your code we proceed as follows:

 - [ ] Go to [https://fonts.google.com/](https://fonts.google.com/), type Roboto on the search bar and select the Roboto font below as follows:
 
![Google Fonts 1](https://i.imgur.com/zjVBN8f.jpg)

 - [ ] Once you are in the Roboto font page, scroll down to find the Styles section and select one of the styles by clicking on the + button at the right side of the style, in this occasion, we will select the “Regular 400” Style:

![Google Fonts 2](https://i.imgur.com/Ir51P9o.png)

 - [ ] After selecting the style, click the “View selected families” button at the top-right corner where the “Selected Family” window will display at the right. Here you will copy the code to then paste it into your HTML file `<head>` tags as follows:

![Google Fonts 3](https://i.imgur.com/xhUJetI.jpg)
![Google Fonts 4](https://i.imgur.com/GU8bqQ0.png)

![Google Fonts 5](https://i.imgur.com/b4FZ2qJ.png)

Now, let’s import the Font Awesome Icons into our code (https://fontawesome.com/), 

 - [ ] Go to https://fontawesome.com/ and create an account.
 - [ ] Once you have the account created, you need to go to your account profile page and create a new kit here https://fontawesome.com/kits
 - [ ] Once you create your kit, you need to enter the kit and copy the following code into your HTML `<head>` tags:

![Icons 1](https://i.imgur.com/YhYcFhU.jpg)

![Icons 2](https://i.imgur.com/ejlnj6H.png)

Now that we have our HTML and CSS files all set up, we proceed to make our strategy in the next section.
  

## Strategy

Let’s start by identifying which html tags you can use for the website, like `<div>`, `<p>`, etc. Here is the strategy that we will follow in the next instructions:

![Strategy for instagram post](https://github.com/breatheco-de/exercise-instagram-post/blob/master/strategy.gif?raw=true)

 - [ ] Let’s start by creating the first `<div>`, it is highly recommended that any first `<div>` in your code to be a container, where all of the other `<div>` will be contained. So, the first `<div>` will be the container, and we will write it as follows `<div class=”container”>`:

![Container](https://i.imgur.com/UCT8efS.jpg)

 - [ ] As we see in the GIF, the background color is black, so our container needs to cover all of our website screen, to do this we need to go to our CSS file and add a `margin: 0` to our whole body using the `*` as a selector as follows:

![Container 2](https://i.imgur.com/C8X3gNe.jpg)

 - [ ] Then we need to add the styles to our container, adding the background color, the width and height to cover our whole website screen as follows:

![Container 3](https://i.imgur.com/6yTO2a0.jpg)

Now, as we see in the GIF, we have a post `<div>` (the green one) that contains 3 main `<div>` (the red ones), that are header, photo and footer. 

 - [ ] Add the post `<div>` (the green one in the GIF) and the 3 main `<div>` (the red ones in the GIF) contained in the post  `<div>` into the html file as follows:

![Main Divs](https://i.imgur.com/TkSqQRx.jpg)

- [ ] Add the necessary styles into the CSS file to make the post `<div>` a centered white rectangle as follows:

**TIP: Try to work with flexbox in this exercise**

![Post 2](https://i.imgur.com/o3VCPsL.jpg)

 - [ ] Add the 3 `<div>` into our HTML file according to the GIF (make sure to add them inside our header `<div>`), that will contain the logo, the title/username of the photo and the 3 dot icon, let's use `id` as a selector for these 3 `<div>`. To help us in this process, we can add a red solid border of 1px to help us visualize how the `<div>` are being distributed in our post rectangle as follows:

![Header 1](https://i.imgur.com/ng5lrcW.jpg)

![Main Divs 3](https://i.imgur.com/YepRjDf.jpg)


 - [ ] Add the corresponding information (HTML logo, post title and 3 dot icon) into the correct `<div>` into our HTML file, as well as the corresponding styles into our CSS file to finish the header. The header should look like this:
 
![Header 19](https://i.imgur.com/g2eSZQa.jpg)

**TIP: To use Fontawesome Icons, you can follow the next steps:**

 - Go to https://fontawesome.com/icons and search for the desired logo, once you've found it, click on the logo and copy the following code into our HTML file (inside the logo `<div>`):

![Header 4](https://i.imgur.com/Z3ZoqNA.png)
![Header 5](https://i.imgur.com/cmKQR8Z.png)


 - You can change the Fontawesome icon size adding this code `fa-2x`, which corresponds to a literal sizing statement for font awesome icons (to learn more about font awesome icons sizing, you can visit https://fontawesome.com/docs/web/style/size) , into the icon's class as follows:

![Header 8](https://i.imgur.com/uHu3aJ5.png)

 - Here is another example using the 3 dot icon:

![Header 15](https://i.imgur.com/cbFDU6n.png)



 - [ ] Let's now add the image into our photo `<div>` (HTML file), you can add any image writing the `<img>` tag alongside the image source as follows:

![Photo 1](https://i.imgur.com/DF6cKsT.png)

![Photo 2](https://i.imgur.com/wEUujXZ.jpg)

 - [ ] Add the styles to fit the image in our photo `<div>` in our CSS file to look like this:

![Photo 4](https://i.imgur.com/zzMHV81.jpg)

 - [ ] Let's add the 3 `<div>` contained in our footer where the "icons", "likes" and "description" (the purple rectangles in the GIF) will be into our HTML file as follows (let's use the id selector again for these `<div>`):

![Photo 5](https://i.imgur.com/BEh7s4I.png)

![Photo 7](https://i.imgur.com/CZ8Skb4.jpg)

 - [ ] Now let's add the 4  `<div>`  into our HTML file according to the GIF (make sure to add them inside our icons  `<div>`), that will contain the heart, comment, send and save icons, let’s use  `id`  as a selector for these 4  `<div>`:

![Icon 1](https://i.imgur.com/4PdnJXY.png)

 - [ ] Let's add the icons using Font Awesome, go to [https://fontawesome.com/icons](https://fontawesome.com/icons) and search "heart" for the heart icon, "comment" for the comment icon, "paper-plane" for the send icon and "bookmark" for the save icon, copy the icon codes and paste them into their corresponding `<div>`, let's also add the sizing, use `fa-2xl` for this occasion:

![Icon 2](https://i.imgur.com/6CzCbt3.png)

 - [ ] Add the corresponding styles to these icons into our CSS file. The icons should look like this:

![Text 1](https://i.imgur.com/T2CIyfS.jpg)

 - [ ] Now for the final part, let's add the text into our HTML file corresponding to the likes and description sections, remember to use the `<strong>` tag whenever is needed. You can also type `lorem` + enter in the description section to auto-fill that text:

![Text 2](https://i.imgur.com/MeXk4PI.png)

![Text 3](https://i.imgur.com/dMtIpUQ.jpg)

 - [ ] We just need to add the styles into our CSS file corresponding to the likes and description section. Add the Roboto-type font, add some padding, remove the remaining boxes and we are good to go

![Text 5](https://i.imgur.com/d8Bkuh2.jpg)

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
