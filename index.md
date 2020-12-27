<script>
window.mobileCheck = function() {
  let check = false;
  (function(a){if(/(android|bb\d+|meego).+mobile|avantgo|bada\/|blackberry|blazer|compal|elaine|fennec|hiptop|iemobile|ip(hone|od)|iris|kindle|lge |maemo|midp|mmp|mobile.+firefox|netfront|opera m(ob|in)i|palm( os)?|phone|p(ixi|re)\/|plucker|pocket|psp|series(4|6)0|symbian|treo|up\.(browser|link)|vodafone|wap|windows ce|xda|xiino/i.test(a)||/1207|6310|6590|3gso|4thp|50[1-6]i|770s|802s|a wa|abac|ac(er|oo|s\-)|ai(ko|rn)|al(av|ca|co)|amoi|an(ex|ny|yw)|aptu|ar(ch|go)|as(te|us)|attw|au(di|\-m|r |s )|avan|be(ck|ll|nq)|bi(lb|rd)|bl(ac|az)|br(e|v)w|bumb|bw\-(n|u)|c55\/|capi|ccwa|cdm\-|cell|chtm|cldc|cmd\-|co(mp|nd)|craw|da(it|ll|ng)|dbte|dc\-s|devi|dica|dmob|do(c|p)o|ds(12|\-d)|el(49|ai)|em(l2|ul)|er(ic|k0)|esl8|ez([4-7]0|os|wa|ze)|fetc|fly(\-|_)|g1 u|g560|gene|gf\-5|g\-mo|go(\.w|od)|gr(ad|un)|haie|hcit|hd\-(m|p|t)|hei\-|hi(pt|ta)|hp( i|ip)|hs\-c|ht(c(\-| |_|a|g|p|s|t)|tp)|hu(aw|tc)|i\-(20|go|ma)|i230|iac( |\-|\/)|ibro|idea|ig01|ikom|im1k|inno|ipaq|iris|ja(t|v)a|jbro|jemu|jigs|kddi|keji|kgt( |\/)|klon|kpt |kwc\-|kyo(c|k)|le(no|xi)|lg( g|\/(k|l|u)|50|54|\-[a-w])|libw|lynx|m1\-w|m3ga|m50\/|ma(te|ui|xo)|mc(01|21|ca)|m\-cr|me(rc|ri)|mi(o8|oa|ts)|mmef|mo(01|02|bi|de|do|t(\-| |o|v)|zz)|mt(50|p1|v )|mwbp|mywa|n10[0-2]|n20[2-3]|n30(0|2)|n50(0|2|5)|n7(0(0|1)|10)|ne((c|m)\-|on|tf|wf|wg|wt)|nok(6|i)|nzph|o2im|op(ti|wv)|oran|owg1|p800|pan(a|d|t)|pdxg|pg(13|\-([1-8]|c))|phil|pire|pl(ay|uc)|pn\-2|po(ck|rt|se)|prox|psio|pt\-g|qa\-a|qc(07|12|21|32|60|\-[2-7]|i\-)|qtek|r380|r600|raks|rim9|ro(ve|zo)|s55\/|sa(ge|ma|mm|ms|ny|va)|sc(01|h\-|oo|p\-)|sdk\/|se(c(\-|0|1)|47|mc|nd|ri)|sgh\-|shar|sie(\-|m)|sk\-0|sl(45|id)|sm(al|ar|b3|it|t5)|so(ft|ny)|sp(01|h\-|v\-|v )|sy(01|mb)|t2(18|50)|t6(00|10|18)|ta(gt|lk)|tcl\-|tdg\-|tel(i|m)|tim\-|t\-mo|to(pl|sh)|ts(70|m\-|m3|m5)|tx\-9|up(\.b|g1|si)|utst|v400|v750|veri|vi(rg|te)|vk(40|5[0-3]|\-v)|vm40|voda|vulc|vx(52|53|60|61|70|80|81|83|85|98)|w3c(\-| )|webc|whit|wi(g |nc|nw)|wmlb|wonu|x700|yas\-|your|zeto|zte\-/i.test(a.substr(0,4))) check = true;})(navigator.userAgent||navigator.vendor||window.opera);
  return check;
};
if(window.mobileCheck){
  document.write("<center><a href="https://pymae.github.io">Home</a> | 
<a href="https://pymae.github.io/buy.html">Purchasing</a> | 
<a href="https://pymae.github.io/sample.html">Chapter 5 Sample</a> |
<a href="https://pymae.github.io/about.html">About</a> | 
<a href="https://pymae.github.io/emaillist.html">Mailing List</a></center>");
}
</script>     


# Python for Mechanical and Aerospace Engineering
by [Alex Kenan](https://pymae.github.io/about.html)

"<center><a href="https://pymae.github.io">Home</a> | 
<a href="https://pymae.github.io/buy.html">Purchasing</a> | 
<a href="https://pymae.github.io/sample.html">Chapter 5 Sample</a> |
<a href="https://pymae.github.io/about.html">About</a> | 
<a href="https://pymae.github.io/emaillist.html">Mailing List</a></center>"

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
