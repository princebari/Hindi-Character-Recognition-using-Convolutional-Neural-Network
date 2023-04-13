# Hindi-Character-Recognition-using-Convolutional-Neural-Network
This repository contains the code and resources for a deep learning project that aims to accurately recognize Hindi characters from input images using Convolutional Neural Network (CNN). 

![image](https://user-images.githubusercontent.com/115543070/231707993-d9ebf678-85ac-448a-af5c-6e541b9ddfaa.png)

<h2>Description</h2>
Handwritten character recognition is an important area in image processing and pattern recognition field. It is a wide field that covers all sort of character recognition via machine in various application domains. The goal of this area of pattern recognition is to translate human readable characters to machine readable characters. Today, we have automatic character recognizers that help humans in variety of practical and commercial applications

<h2>About Dataset</h2>
Devanagari is an Indic script used in India and Nepal, and our dataset contains 36 characters and 10 digits. It is differentiable from many other written languages by the lack of capitalization and the horizontal bar aligned along the top of the script. Below are some examples of input used for this project. These are handwritten symbols from the training dataset used to train our model. Note that each of the following is different characters, although some of them appear quite similar - this is the problem that our model will attempt to resolve. Since these are handwritten characters, some amount of error can be attributed to sloppy or perhaps illegible writing - it might not be possible for even a human subject-matter to expect to achieve 100% accuracy.


Our training dataset contains 2000 examples of each character, for a total of 92,000 images. Each image consists of 32x32 pixels and 3 color channels. The test set consists of 13800 total images (300 for each character) and the training set consists of 78200 images (1700 per character). This accounts for an 85/15 split.

<h2>Inspiration</h2>
Character recognition (for any language) is important to transcribe the written text into digital representations. For many difficult-to-read handwritten instances of lettering, human intervention is required via methods such as Captcha, Gamification, or manual annotation. This process is often labor and cost-expensive. However, for many character sets, deep learning models can accurately transcribe handwriting to digital encoding

<h2>Problem Statement</h2>
The objective of this deep learning project is to create an efficient and accurate system for recognizing Hindi characters using Convolutional Neural Network (CNN). The system should be able to accurately identify and classify handwritten hindi characters. By leveraging the power of deep learning techniques, this project aims to develop a reliable Hindi character recognition system that can have practical applications in various fields.
