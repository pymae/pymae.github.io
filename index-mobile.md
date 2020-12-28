<span id="yesno"></span>

<script>
window.mobilecheck = function() {
      var check = false;
      if(window.innerWidth<768){
          check=true;
      }
      return check;
    }

if(window.mobilecheck()){
      document.getElementById("yesno").innerHTML = <center><a href="https://pymae.github.io">Home</a> | 
      <a href="https://pymae.github.io/buy.html">Purchasing</a> | 
      <a href="https://pymae.github.io/sample.html">Chapter 5 Sample</a> |
      <a href="https://pymae.github.io/about.html">About</a> | 
      <a href="https://pymae.github.io/emaillist.html">Mailing List</a></center>;
}

</script> 

<!--<center><a href="https://pymae.github.io">Home</a> | 
<a href="https://pymae.github.io/buy.html">Purchasing</a> | 
<a href="https://pymae.github.io/sample.html">Chapter 5 Sample</a> |
<a href="https://pymae.github.io/about.html">About</a> | 
<a href="https://pymae.github.io/emaillist.html">Mailing List</a></center>-->
<br>

# Python for Mechanical and Aerospace Engineering
by [Alex Kenan](https://pymae.github.io/about.html)
 

<center>
<img src="https://raw.githubusercontent.com/pymae/pymae.github.io/master/files/cover_page_low.jpeg" alt="Python for Mechanical and Aerospace Engineering cover page" 
     width="170px" height="220px">
</center><br><br>


## What is this book about?
The traditional computer science courses for engineering focus on the fundamentals of programming without demonstrating the wide array of practical applications for fields outside of computer science. As a result, engineers know (or, at least, learned) the principles of inheritance and object-oriented programming, but the courses fail to link these concepts to actual engineering applications. Thus, the mindset of “Java/Python is for computer science people or programmers, and MATLAB is for engineering” develops. MATLAB tends to dominate the engineering space because it is viewed as a batteries-included software kit that is focused on functional programming. Everything in MATLAB is some sort of array, and it lends itself to engineering integration with its toolkits like Simulink and other add-ins. The downside of MATLAB is that it is proprietary software, the license is expensive to purchase, and it is more limited than Python for doing tasks besides calculating or data capturing. 

This book is about the Python programming language. Specifically, it is about Python in the context of mechanical and aerospace engineering. Did you know that Python can be used to model a satellite orbiting the Earth? Or, that Python can be used to graph airfoil coordinates? This book assumes a college junior level of mechanical/aerospace engineering understanding. It will use examples like

* Thrust available and thrust required for an aircraft
* Dynamic pressure and how it changes with altitude and velocity
* Plotting different airfoils
* Orbital mechanics and orbital parameters
* Mechanical properties of different aluminum alloys

to show the reader how Python is better than MATLAB for anything that does not require Simulink. Don’t be scared if you don't understand all of those topics; they are just being used to provide concrete examples for how Python can be used for engineering.

In total, there are 10 chapters:

1.	Intro chapter on how to download Python via Anaconda distribution and getting started with Python syntax
1.  A very small problem and solution to demonstrate a basic Python program
2.	Graphing thrust required and thrust available for an Airbus A321 at three different altitudes with **Matplotlib**
3.	Graphing dynamic pressure as a function of time for a rocket launch with **Matplotlib** 
4.	Getting and plotting airfoil coordinates with **Requests** and **Matplotlib**
5.	Modeling a satellite’s orbit around Earth with **PyAstronomy** and **Matplotlib**
8.	Creating a GUI to convert units with **Tkinter** and **Pint**
6.	Introduction to web scraping (**Requests** and **BeautifulSoup4**) and exporting data to Excel (**Openpyxl**)
7.	Modeling camera shutter effect on an aircraft’s propeller with **Tkinter** and **Numpy**
9.	Making pdf reports of Python code with **Pweave**

You can find the completed programs and a very helpful 595 page NSA Python tutorial [at the book's GitHub page here](https://github.com/alexkenan/pymae).

## Where to buy this book

Click [here](https://pymae.github.io/buy.html) for purchasing information.


## Sample Chapter
Take a test drive of this book by previewing some of Chapter 5: Modeling a 2-body orbit in two and three dimensions [here](https://pymae.github.io/sample.html).

## Mailing List

Get on the mailing list to be the first to know if I publish more books or create a second edition! Click [here](https://pymae.github.io/emaillist.html) to learn more.

<center><a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a></center><p>Python for Mechanical and Aerospace Engineering and its associated materials are licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.</p>
