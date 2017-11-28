# Changes to the original Wordpress Theme

- Colour scheme
- Fonts
- Favicon
- Nav Bar
- CSS

Before & After

![theme](https://raw.githubusercontent.com/CallumLovekin28/CreativeCollaboration/master/Images/Theme.jpg)

The top image is the theme before I did any changes to it, the bottom image is the final website with all the changes we made. We changed the colour scheme a few times before actually choosing one and we went through several images before picking one for the splash screen.

## CSS Code
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

## Sizes 
We wanted to change the sizing of the Logo's on the website so everything looked in preportion so we added some more CSS for that.

~~~~

#header_inner h1.sitename_logo, #header_inner #logo {
	width:400px;
}

#header_inner h2, #header_inner h1.sitename_logo a {
	font-size:20px;
}
~~~~

## Search Toggle
We reviewd the site after the changes we made and realised there was 2 options to search on the fron page and we didnt need them. Instead of removing it entirely we used CSS to hide it so if we wanted to use it at a later date we could.

~~~~
#search_toggle{
	display : none
}
