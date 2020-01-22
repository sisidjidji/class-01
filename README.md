# class-01

# Quizz:
1. What does HTML use to structure a web page ?
2. what's HTML stand for ?
3. what is the dIfference between *HTML* and *HTML5* ?
4. What is a *site map* ?
5. How the old browsers reconize HTML5?


# 1.HTML STRUCTURE AND MARKDOWN :
HTML defines the content of every web page on the Internet. by using tags we can structure the web page , the following are an exemple of the most used tags

< html>
  < head>
    < title> the titel of the web page < /title>
  < /head>
 < body>
 < header> 

    <h1>heading message </h1>
    <p> for adding paragraphs</p>
    <nav> 
     <ul>
      <li> < a href= ' the link'>Home</a> </li>
     </ul>    
    </nav>
 < /header>
 < main>
   < img src='path to the picture' >
 < /main>
 < footer> < /footer>
< /body>
< /html>

# 2. HTML5:
HTML5 introduce a new set of element that allow you to devide up the parts of a pages .The most interesting new HTML5 elements are: 

- New semantic elements like < header>, < footer>, < article>, and 
< section>.

- New attributes of form elements like number, date, time, calendar, and range.

- New graphic elements: < svg> and < canvas>.

- New multimedia elements: < audio> and < video>.


# 3. PROCESS AND DESIGN :
the following are the steps to create your new web site :

* Understand who your target is and what information your web site is for 

* Map your web site 

* Wireframe to organize the information that will need to go on each page 

* Design it by using size ,color,style . use grouping and similarity to help simplify the information 

# Answer to the quizz:

1. HTML USE ELEMENTS TO STRUCTURE A WEB PAGE.

2. HTML IS FOR : The Hypertext Markup Language.

3. HTML5 introduce a new set of element that allow you to divide up the parts of a pages.

4. Its a Diagram that help structure the page.

5. First we have to include the css that states which element should rendered as block-level element

      header,section,footer,aside,nav,article,figure,figurecaption {
     display:block;}
 

Then we will insert this javascript code :

       [if lt IE 9]
       < script src=" http://html5shiv.googlecode/snv/trunk/html5.js "> 
       < script>
       [ endif]
