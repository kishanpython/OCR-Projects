
# Text Detection (EAST text detector)

<b>TASK :-</b> Detect text in natural scene images using the OpenCV and EAST text detector.

OpenCV’s EAST text detector is a deep learning model, based on a novel architecture and training pattern. It is capable of (1) running at near real-time at 13 FPS on 720p images and (2) obtains state-of-the-art text detection accuracy.

Due to the proliferation of cheap digital cameras, and not to mention the fact that nearly every smartphone now has a camera, we need to be highly concerned with the conditions the image was captured under — and furthermore, what assumptions we can and cannot make.

# EAST :- 
We call the algorithm “EAST” because it’s an :-  Efficient and Accurate Scene Text detection pipeline.
For more details on EAST, including architecture design and training method <a href="https://arxiv.org/abs/1704.03155">be sure to refer to the publication by the authors.</a>

# Useful Links :- 

<ul>
  <li src="https://arxiv.org/abs/1704.03155"> EAST </li>
  <li src="https://www.pyimagesearch.com/2017/11/06/deep-learning-opencvs-blobfromimage-works/"> OpenCV’s blobFromImage </li>
  <li src="https://www.pyimagesearch.com/2014/11/17/non-maximum-suppression-object-detection-python/">Non-Maximum Suppression</li>
</ul>

# Output :- 
<img src="https://github.com/kishanpython/OCR-Projects/blob/master/Text%20Detection%20using%20OpenCV%20and%20EAST/images/target.jpg"></img>


## Note:-
The EAST text requires that your input image dimensions be multiples of 32, so if you choose to adjust your width and height values, make sure they are multiples of 32!
