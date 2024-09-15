 
 mkdir images
 mkdir css
 mkdir js

 mkdir images/ css/ js/

 touch index.html
 touch css/stsyle.css

 touch index.html css/style.css


 cd ~/Documents
 cd myLessons
 cd myTutorials
 cd sugarViaEmmet
 code .


 cd ~/Documents/myLessons/myTutorials/sugarViaEmmet
 code ~/Documents/myLessons/myTutorials/sugarViaEmmet


 ! = <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>

--> div>h3*3{hi} = <div>
                      <h3>hi</h3>
                      <h3>hi</h3>
                      <h3>hi</h3>
                      </div>

-->div>h1{Home}+a[href="about.php"]{About}+a[href="contact.php"]{contact} =                               
                  <div>
                       <h1>Home</h1>
                       <a href="about.php">About</a>
                       <a href="contact.php">Contact</a>
                  </div>

tag = [a, p, div, table ...]
  P{afadfas} = ```<P> aasdfasfda </P> ````
   ````
   div>P{hello ther}= <div>
                        <P>
                      hello there
                        </P>
                     </div>

     + =  parallel | or 

     div>p{hello there}+p{howdy}+p{great work} =                  
                                                  <div>
                                                      <P>
                                                         hello there
                                                      </P>
                                                      <P>
                                                        howdy
                                                      </P>
                                                      <P>
                                                        great work
                                                      </P>
                                                  </div>



```
{} = content
[] = attribute
> = child
+ = sibling

````

     div>a[href="a.html"]{visit a}+ a[href="b.html"]{visit b}+a[href="c.html"]{visit c}   =  <div>
                                                                                                  <a href="a.html">visit a</a>
                                                                                                  <a href="b.html">visit b</a>
                                                                                                  <a href="c.html">visit c</a>
                                                                                              </div>