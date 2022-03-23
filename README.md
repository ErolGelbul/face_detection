<div id="top"></div>

<div style="text-align:center"><img src="images/cover.jpg" /></div>

<!-- ABOUT THE PROJECT -->
## Description

I used the OpenCV library to load `faces.jpg` image into my project.
After importing the `CascadeClassifier` I converted the image to grayscale.
Then I chose the detectMultiScale2 method. For the threshold I selected 8 for
minNeighbors. For more information on the method parameters, check out the
OpenCV's Cascade Classifier Class [documentation](https://docs.opencv.org/3.4/javadoc/org/opencv/objdetect/CascadeClassifier.html).

<br>

<div style="text-align:center"><img src="images/preview0.gif" /></div>

<br>

Finally I included real-time face detection using a webcam. You may try it yourself!
Just make sure you import the libraries and run `face_detection` function. To stop
the videocapture, press `a`.

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- TECH -->
## Technologies

IDE: [Jupyter Notebook](https://jupyter.org/)

Libraries & Packages: [NumPy](https://numpy.org/), [OpenCV](https://pypi.org/project/opencv-python/)

Download the [Cascade Classifier](https://github.com/opencv/opencv/tree/4.x/data/haarcascades) from OpenCV's GitHub repo.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing

If you would like to add any extra features to the optimisation simulation, feel free to fork and create a pull request. Thank you!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>




<!-- CONTACT -->
## Contact

Erol Gelbul - [Website](http://www.erolgelbul.com) - erolgelbul@gmail.com

Project Link: [Face Detection](https://github.com/ErolGelbul/face_detection)

<p align="right">(<a href="#top">back to top</a>)</p>
