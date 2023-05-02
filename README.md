Download Link: https://assignmentchef.com/product/solved-computer-vision-lab-session-no-5
<br>
<h1></h1>

<strong> </strong>




The following items are the steps that you have to do in this lab session:




<h2>NCC-based segmentation</h2>




<ul>

 <li>Select a window around the red car on the street (in the gray scale image “ur_c_s_03a_01_L_0376.png”) and apply the NCC (normalized cross correlation, <em>normxcorr2</em>), in order to find the template in all the 6 images (consider the same images of Lab4). Show the template. Show the position of the maximum of the score map and a box corresponding to the size of the template for all the 6 images (as in Fig.1). Do the same for the dark car that turns on the left.</li>

 <li>Compare the results of this Lab with the ones of Lab4 (color-based segmentation).</li>

 <li>Consider three different sizes of the window (centered around the dark car that turns on the left): discuss the results in terms of computation time and accuracy of detection.</li>

</ul>




<h2>Harris corner detection</h2>




<ul>

 <li>Implement the Harris corner detector. Apply the developed corner detector on the “image i235.png”. Show the partial derivatives of the image and the Gaussian filter. Show the R score map and the corner regions. Show the detected corners overlapped to the image (see Fig.2). Tips: to look at the <em>m </em>available on AulaWeb; threshold for the corner regions 0.3*M, where M is the maximum value of R map; to use <em>regionprops()</em> function to get the centroids of the blobs in the corner regions map.</li>

</ul>







<strong>Notes: </strong>

<ul>

 <li>You have to write a report that describes your work and the obtained results (please include the figures). In the report you must indicate all the surnames of the participants (not other names, e.g. the teachers).</li>

 <li>About the code:

  <ul>

   <li>You have to use relative paths. o You have to write and use functions.</li>

   <li>You have to provide us a main script to test your code.</li>

  </ul></li>

 <li>The code must be uploaded as M-files. All the files (M-files, images, and report) have to be compressed in a single file named “surnames_labxx.zip/tgz” (all the surnames of the participants have to be indicated), and then the compressed file has to be uploaded.</li>

</ul>







detected object                                                                                                                       detected object

200            400            600            800          1000          1200                                 200            400            600            800           1000          1200

Fig.1: Segmentation examples.
















Fig.2: Corner detection example.


