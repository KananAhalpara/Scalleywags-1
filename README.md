# Scalleywags-1
Web Design Assignment-Saclleywags - Algonquin College

Your site is ready to be published at https://kananahalpara.github.io/Scalleywags-1/.
(ALERT:If you click the link above you might get the fonts different in visual than the psd but if you have the pasifico font installed on
your device,than you will get the corretc font family when you download the file.)

<br><br>
Assignment 3: Scalleywags!
 

Goal : Re-create the Photoshop Mock-up as closely as possible!
Starter HTML: scalleyway-starter.zip
Original PSD file: scalleywag-psd.zip
 

Guidelines

All visual assets are accounted for in the /images folder
All font sizes, line heights, margins and padding are accounted for in the Photoshop file
All colours are also given to you in the swatch in the PSD (use the Eyedropper Tool in Photoshop to isolate pixels). Please note, you do not need to include the color swatch in the actual HTML, it is for reference only.
Setting the Basic Styles

reset.css has been set, so all sizes are “100%” and margins/padding is “0”
Use the wrapper element to set basic widths, margins, padding for all the child elements
(you do not have to set a width for every element inside the wrapper, they will “flow” and fill it)
The text content can be set exactly in place using only Padding on the <section> area
(avoid having to set left & right margins on every element...just pad the containing element!)
You can set up the CSS using Em’s, %’s or Pixels (px)
Floating the Logo

First, set <header> to have “relative” positioning: header { position: relative; }
Set the logo <div> to have “absolute” positioning: .logo { position: absolute; top: 0; right: -140px; }
Setting the Backgrounds

You will use css to “target” the elements that need backgrounds 
(specifically: <body>, <header>,<section>, and <footer>)
Use a combination of background-image, background-repeat, and background-position to set the backgrounds and make them repeat and tile to re-create the same effect as in the Photoshop file
The Navigation

You are going to set up a “standard” navigation menu using the Unordered List <ul> element
There are two navigation menus, one in <nav> and one in <footer>. You will have to style both of these using compound styles (e.g. nav ul li a vs. footer ul li a) 
The <ul> has list-style: none; The <li> has display: inline; and the <a> has display: block; float: left; 
Remember to “clear” the first non-floating element that follows the floating elements (e.g. <section>) 
