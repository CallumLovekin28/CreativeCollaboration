# Changes to the original Wordpress Theme

- Colour scheme
- Fonts
- Favicon
- Nav Bar
- CSS

Before & After

![theme](https://raw.githubusercontent.com/CallumLovekin28/CreativeCollaboration/master/Images/Theme.jpg)

The top image is the theme before I did any changes to it, the bottom image is the final website with all the changes we made. We changed the colour scheme a few times before actually choosing one and we went through several images before picking one for the splash screen.

## Colours - CSS
So after choosing a colour scheme and realising we wanted to change the colours of the background and nav bars. 

~~~~
#menu_wrap {
	background-color: rgba(0,0,0,0.75);
}

#menu_wrap a {
    color: white;
}

a {
    color: #a8d34a;
}
~~~~

## Sizes - CSS
We wanted to change the sizing of the Logo's on the website so everything looked in preportion so we added some more CSS for that.

~~~~

#header_inner h1.sitename_logo, #header_inner #logo {
	width:400px;
}

#header_inner h2, #header_inner h1.sitename_logo a {
	font-size:20px;
}
~~~~

## Search Toggle - CSS
We reviewed the site after the changes we made and realised there were 2 options to search on the front page and we didn't need them. Instead of removing it entirely we used CSS to hide it so if we wanted to use it at a later date we could.

~~~~
#search_toggle{
	display : none
}
~~~~

## Nav Bar
We saw the original nav bar and knew we wanted to change it so we could use it as the main hub for finding images. We added terms and conditions and a page where they can learn about the photographers.
![nav](https://raw.githubusercontent.com/CallumLovekin28/CreativeCollaboration/master/Images/nav.jpg)

## Final Layouts vs Old Layouts
![beforeandafter](https://raw.githubusercontent.com/CallumLovekin28/CreativeCollaboration/master/Images/beforeandafter.jpg)
From the above image, you can see the drastic changes we made from the initial web design to the final one. When we had the old design we liked it but after gathering feedback we looked at the site in a different light and made it more modern.

As you have seen we have changed the nav bar and colours to make the site seem sleeker and not like something out of the 1990's. The image pages themselves now have the pricing depending on the license you want and all completed with tags which you can use to filter images of similar kind. 
