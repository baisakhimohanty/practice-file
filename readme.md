HTML  -it stands for hyper text markeup language
we use html for creating str of the website.
we called html as a markeup lanuage bcz it cntain seliton of the web page.
all html are written in tag line
hr -horizontal line
p -paragraph
br - brake
src,height,width,alt are the attributeof the image tag.
href-hyper referance (referance to the another page/element )
 hTML Formating
 _____________________
<b>-bold text
<i>-italic
<em>-emphasized text
<ins>-inserted text
<del>-deletion text
<sub>-subscripted text
<sup>-super subscriped text
       HTML TABLE
       .............
 HTML table gives us a table like structure where we can insert our data in row and column format
<table>-main tag
<tr>-table row
<th>-table heading
<td>-table data
  HTML LIST
  -----------------------
  1-unordered list <ul>
  2-ordered list   <ol>
  HTML block level element
  --------------------------
  html contain 2 types of block level element to specify the structure of a web pages
  1-<p>-paragraph
  2<div>-division
  HTML FORMS
  ------------------------
  HTML forms provids a form like structure so that we can give our data by use of these forms.q
  <input type="">url
  <input type="search">
  <input type="week">
  <input type="email">
  <input type="image">
  <input type ="month">
  <input type="range">
  <input type="file">
  <input type="tel">
  <input type="number">
      CSS
      ----------------
  _css stands for cascading stylish sheet
  _we used css for designing and stylint the web pages
  syntax___h1{  selector
   (property)     color:red-value)


  }
  __basically css are3 types
  1 )inline css
  2)internal css
  3)external css
  inline css
  -----------
  <body>
     <h1 style="color:red"> today is thusday</h1>
     <pstyle="backgroundcolor:yellow">today we started css</p>
  </body>     
2)internal css
**************
<head>
   <style>
      h1{
        color:red;
      }
      p{
        background_color:blue;
      }
    </style>
 </head>

 3)external css
 ******************
 it is a linkage to the outer css file to our main HTML elemante

 index__HTML                                  style.css
                                        h1{
                                          color:red;
                                        }

<head>
   <link rel="stylesheet" 
   href="style.css">
</head>
<body>
 <h1>today is a buteful day<h1>
 </body>   

CSS selector
*****************
CSS selector are of 5 types
1.ID selector
2.class selector
3.universal slector
4.group selector
5.element selector
__selector means selecting a elemante which we have to designed.
Id selector
............
ID selector are those selector which unique design / we select only one element in HTML file.

ex
----
<html>
  <head>
     <link rel="stylesheet"
       href="style.css">
   </head>
   <body> 
    <h1 id="TAT">today is tuesday</h1>
    <h1>we learn css</h1>
    <h1>we write code</h1>
  </body>
</html>


style.scc
..........
#TAT{
  color:green;
}
h1{
  color:red;
}


class selector
................
1.we used to class selector for repeating the similar design in multiple times.
2."."property we used to specify the class selector in our css file.
3. class denoted by"."


universal selector
*****************
we used universal selector to design whole html page in a single design 
2."*"property we used to specify the universal selector in our css file
*{
  color:red;
  text-align;
}


GROUP selector
**************
1.we used group selector to create one design in which we have selected the tags
2.group selector we used by creating the group

h1,p{
  color:red;
  text-align:center;
}


ELEMENT selector
*******************
1.by selecting one single single element we have to design is called the element selector.


h2{
  background-color:aqua;
}



version control system :-
->git and github are those open source version control system
->we used version contril system to store our code,share our code collaborate our projects with each other
->example of VCS is-git,github,gitlab....




