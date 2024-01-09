# CSS
css: cascading style sheets
cascading: jhorna --> ager jotoi ex thakuk, last partner ei take pabe.. ager gula bad.


#### layers
=> A typical webpages has three layers

==> most important part: Content Layer --> HTML

==> Ruposhi: Presentation layer --> css
==> nora-chora: Behavior layer --> javaScript

--> Html is basically a document that will be displayed as  a webpage when opened with the browser

--> HTML tells the browser what the structure of the webpage will be.


## types of css
1. inline css ==> at starting tag
2. internal css --> embaded(attached) ==> at head tag
3. external css --> linked ==> css file



### Selector
1. element => tagname{
    --> all that tagname's element
}
2. id => #id{
    --> specific
    --> only one element with same name
}
3. class => .class{
    --> can be many element with single name
}
4. Universal => *{
    --> select all of element
}
5. grouping selector & attribute selectors => input[type="typeName"]{
    --> just typeName er input k select korbe.
}


=> Parent tag er cheye,,, child tag er priority beshi. Also j pore ashbe,, tar priority beshi.


## inline: style attribute
style="style-rule: value;"
or,
style="property: value;"



## CSS Units
=> There are two types of length units: absolute and relative
--> A whitespace cannot appear between the number and the unit.


## border margin padding
border: width style color; ---> by default color black
border-radius: width;
border-radius: top-left top-right bottom-right bottom-left;

margin: top right bottom left;
margin: top-bottom right-left;
margin: top right-left bottom
margin: all-side;
padding: as it is like margin

=> margin: extra space outside the container
=> padding: inside the box space between border and content


## text-align
justify: chardike mishbe
center: majhe
right: right side a mishbe
left: left side a mishbe


### extra shortcut: habi-jabi
1. alt + (l + o) --> live server open
==> after each change, it reload the page automatically



## Box Model
=> mainly 4 ta part ase
1. content
2. border
3. margin
4. padding
another part can be
5. width, height



## text-decoration
-> overline, underline, ...


## display
=> display: none; --> er ostitto muche jabe. space o thakbe nah
--> element hide

=> display: block; --> block element er moto behave korbe

=> display: inline; --> inline element er moto behave korbe
--> inline element a height kaj kore nah.
--> inline element a margin top-bottom a kaj kore nah.

=> display: inline-block; --> inline a thekei block er moto achoron korbe


## visibility
=> visibility: hidden; --> just erase hobe. but space theke jabe.
--> just content hide


## box-shadow
--> margin use kora lagbe
box-shadow: x y spread color;
=> box-shadow: h-offset v-offset blur spread color;


## font
font-family: font-type;



## background-image

=> background-image: url(...);
--> aita onek bar repeat hote pare or only kichu part show korte pare

=> background-repeat: no-repeat;
=> background-repeat: repeat-x; / repeat-y;

=> background-size: cover;
--> height same thakbe
--> puro width cover korbe. image k tene width borabon cover kore.

=> background-size: contain;
--> no-repeat deya jabe nah
--> image ratio change hoy nah
--> width borabor jototuku complete hobe, tar porer part a image repeat or image er kichu part boshbe jeno puro width cover kore.

=> background-size: 200px;
--> image ratio device-width onujayi change hote thake.
--> width and height both 200px hoye jabe, bakita contain er moto


## background-position
- left-top, top, right-top
- left, center, right
- left-bottom, bottom, right-bottom


# id VS class
id --> each element can have only one id
class --> you can use same class on multiple elements

id --> an id selector is name preceded by a hash character("#")
class --> a class name is a name preceded by a full stop(".")


### multiple class name of an element

class = "moon mkm"
- we can use both .moon or .mkm
