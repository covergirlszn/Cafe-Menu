# Cafe-Menu
freecodecamp s1 e2
__________________________________________________________________________

so header is semantic, to describe that it's a header, cute
        is there a way of inventing your own tags for html? yessir
    
    <style type="text/css">
    angrydiv { background: red; color: white; display: block; }
    </style>

    <angrydiv>Arrrg!</angrydiv>

AND IT WORKS!!!

CSS STANDARD LAYOUT

element { <!--you can use a .element if you want to incorporate class-->
 property: value;
}
fun fact you can also do, 

element, element, {
    prop:val;
}

which i think is veryyy cool 

okay so what does rel mean, because i know it's for stylesheets but wag1 with it fr??
.....its for relationship!!! so link rel=stylesheet means its the stylesheet for the given html

hmmm--RESPONSIVE TINGS
For the styling of the page to look similar on mobile as it does on a desktop or laptop, you need to add a meta element with a special content attribute. 

Add the following within the head element:

<meta name="viewport" content="width= device-width, initial-scale=1.0" />
SO THE VARIABLE NAME when you check pon the javascripp gives you a humble viewport sef, and then the content, kinda like style is thaat the width of said sontent should be the same width as the device

fka responsive design

and burlywood is #deb887
i think it makes sense to use percentages instead of pixels for sizing inna css as then it translates on the mobile thing....

TO REITERATE
 center a div with margin auto settings

 sorry since when could you use an url to change a background image???


 WHAT DOES SPACEBAR MEAN IN CSS SCHOOL OF PARENTING???
 <!--
 is this code??
 but spacebar means descendant
 i think it means take characteristics of both css classes 

 icl i feel like this was html as opposed to for css but we move

OH SO IF YOU HAVE AN ELEMENT INSIDE OF THE OTHER THEN USE THE FOLLOWING CSS

 -->
 por ejemplo
    div p {
  background-color: yellow;
}
SE IF YOU HAVE A DIV WITH A P INSIDE MAKE THE BG YELLOWWW
https://www.w3schools.com/css/css_combinators.asp
________________________________________________________________

 but anyways i will come back to inline later because this is starting to confuse me ngl

 12.8
 ____________________________________________
inline-block elements only take up the width of their content. so "french vanilla" is like 2cm

in this instance as well, article has class item which is assigned to only paragraphs... and puts both paragraph elements on the same line as opposed to under eachother because they're paragraphs

and apparently putting the set of para elements next to eachother with no space, after doing the inline assignment, meants the extra spaces are deleted, which kinda makes sense

i hope this makes sense later but the reason there was space after the number was not because of the spacebar thing......okay you put it at 48% and so it would have startted at the 48 from the flavour and then theres the space. the element is already like to the edge anyways so the gap is because it's taking up less of the page, then also because apparently that extra space does something in in line

whew
image.png
____________________________________________
16.8
long time smh

The menu text CAMPER CAFE has a different space from the top than the address's space at the bottom of the menu. This is due to the browser having some default top margin for the h1 element.

answer
h1 {
  margin:0px;
  font-size: 40px;
}
bare in mind font size a deya deja
you need to analyse this later

to push it up.....the element
 img elements to pull them up from their current positions. Negative values are created using a - in front of the value. To complete this project, go ahead and use a negative top margin of 25px in the img type selector.

 so margin top beeing negative would mean instead of adding space to the margin top, you remove it so the forehead gap is smaller ygm

 _________________________________________
 apparently this is done, i need to run through and review it because i'm just typing ngl

 __________________________________________________

 so you can put something in a one line say that the paras in lass item have an inline block then make the size different.
 
 so you could make the pricing items touch the opposite ends of the thing. then say that the width ofthe eement they're in is smol and centre it xx

 so apparently floating the text elements is not very sustainable. but you can stilluse it with line breaks and it comes out cute

 otherwise change the width of each element fi 48% and align.
 erm acc ge rid of extra space by removing the spaces so the text is at the edge. then put padding on the whokle thing