# Credit Card OCR :- 
Performing Optical Character Recognition (OCR) using template matching via OpenCV and Python to get 16 digit credit card numbers.
The OCR-A font was designed in the late 1960s such that both (1) OCR algorithms at that time and (2) humans could easily recognize the characters.The font is backed by standards organizations including ANSI and ISO among others.
Despite the fact that modern OCR systems don’t need specialized fonts such as OCR-A, it is still widely used on ID cards, statements, and credit cards.

# OCR-A DIGITS :- 
<img src="https://github.com/kishanpython/OCR-Projects/blob/master/Credit%20Card%20OCR/images/ref.png"></img>

# STEPS :- 
<ul>
  <li>Detecting the four groups of four numbers on the credit card via various image processing techniques, including morphological operations, thresholding, and contour extraction.</li>
  <li>Extracting each of the individual digits from the four groupings, leading to 16 digits that need to be classified.</li>
  <li>Applying template matching to each digit by comparing it to the OCR-A font to obtain our digit classification.</li>
</ul>

# Useful Link :- 
<ul>
  <li><a src="https://en.wikipedia.org/wiki/Top-hat_transform">Top-hat Transform </a></li>
  <li><a src="https://en.wikipedia.org/wiki/Sobel_operator">Sobel operator</a></li>
  <li><a src="https://en.wikipedia.org/wiki/Otsu%27s_method">Otsu's method</a></li>
  <li><a src="https://www.pyimagesearch.com/2015/04/20/sorting-contours-using-python-and-opencv/">Sorting Contours</a></li>
</ul>
