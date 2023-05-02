Download Link: https://assignmentchef.com/product/solved-cpsc1021-assignment-2-turning-image-upside-down
<br>
In this assignment you will use the following skills:

<ol>

 <li>Use of classes and classes containing objects as members.</li>

 <li>Use of a container class (vector) to keep track of data.</li>

 <li>Use of file I/O streams.</li>

 <li>Use of makefiles</li>

</ol>

<strong>Part I – Problem at hand.  </strong>

This project is done in C++ in <em>teams of 2 (and no more than 2), or individually</em>. Your teammate should be from the same lecture section of the class, since you have done the bulk of the work together already and will use assignment1 files as a start up for asg2. You are NOT allowed to discuss your solution or share your asg1 or asg2 files with other teams/students, except your own partner (if you have one). Only one person from each  team should submit the files, and all files (except makefile) should have author/s names in the comments on top of the file.

You will work with .ppm and .pgm files again, but this time you will only use the P2 and P3 files in ASCII format. You can use the same image files as you used for asg1, or find other ones you like. Your program will read data from a .ppm (or .pgm) file and produce an upside-down copy of the original. This copy will not look like a mirror image of the original. It will look like an image that was turned 180 degrees. You will have to devise a clever way to achieve this.




<h1>Part II – Implementation Requirements</h1>

<strong> </strong>

<ol>

 <li>You can use the same classes you have created for asg1: ColorPixel (<em>h</em>) that will contain the red, green, and blue values of each color pixel, and class GrayPixel</li>

</ol>

(<em>grayPixel.h</em>) to contain values of the gray pixel. Again, provide parameterized constructors, destructors, and getter methods for each class. If you have a parameterized constructor, you will not need setter methods to save the pixel values, as the only time you will need to set values of the pixel is when you are creating an instance of that pixel. This will be a very small class with most, if not all functions inlined. (Same as in asg1).




<ol start="2">

 <li>You will create a class Ppm and a class Pgm. Each class will have a header file (named <em>h</em> and <em>pgm.h</em>) and an implementation file (<em>ppm.cpp</em> and <em>pgm.cpp</em>). You will need member variables for storing magic number, height, width, max_value for each pixel, (other members, if needed), and a vector of ColorPixel or GrayPixel objects, correspondingly.</li>

</ol>




1




<ol start="3">

 <li>Create a main function that will drive the processing. Your file should be called upsideDown.cpp. Your executable will take two command line parameters – the original image file and the output image file.</li>

</ol>




<ol start="4">

 <li>Create a makefile and provide the functionality to remove object files (<em>clean</em>).</li>

</ol>




<ol start="5">

 <li>Create a tarball containing all the source code and the makefile, but <em>not</em> the object code. Please run <em>clean</em> before creating a tarball. You do not need to submit image files. Graders will use their own image files to test your program.</li>

</ol>




<ol start="6">

 <li>Submit to canvas before the deadline: <strong>April 16<sup>th</sup> before 5pm</strong>.</li>

</ol>




<strong>           </strong><strong>NOTE: If you submit the archive that cannot be open, or is corrupt, you will not be given             the opportunity to redo the work and resubmit. You have one shot to get it right.  </strong>







<h1>How to create your own .ppm and .pgm files in GIMP (so you can use them to test your program)</h1>

<strong> </strong>

Two <em>.ppm</em> and two <em>.pgm</em> files (ASCII and raw format) are provided for you. They can be found in Canvas under the assignment1 link: chips.ppm, chips.pgm, potatochips.ppm, potatochips.pgm. BUT if you would like to test your program with some more interesting/exciting files, you can convert your favorite image to <em>.ppm</em> or <em>.pgm</em> format in GIMP. Open you image in GIMP, then click on  Files-&gt; Export As, give it a name on the very top, then on the bottom click on Select File Type (by Extension), scroll down, select .ppm (or .pgm). After that it will bring up a box with options to save in ASCII or raw format. Select format and save it.




<h1>Part III. Where to Get Help</h1>

<strong> </strong>

<ol>

 <li>First of all, try to use textbook, online sources and search engine of your choice to look at code examples, programming concepts explanation, etc. You need to learn to be independent and to be able to use available resources to help yourself.</li>

</ol>




<ol start="2">

 <li>You can also get help with this assignment from the course teacher or TAs. Though TAs may not be familiar with the details of the assignment or design requirements, they can help you with programming questions and debugging.</li>

</ol>




<ol start="3">

 <li>Many questions can be answered in e-mail. Please do not e-mail code unless you were asked to do so. Do this ahead of time, not at the last moment. You are still responsible for submitting your assignment on time, whether you got your question answered or not at the last moment.</li>

</ol>




<strong>Most importantly</strong>: make a plan A and a plan B. You should always have a plan A and a plan B!! Unexpected circumstances happen, and it is better to be safe, than sorry. Start working right away, DO NOT WAIT TILL THE LAST MOMENT. Make frequent backups!!!!


