Emotion-Detection
=================

This is a project to implement emotion recognition in C++ using dlib.

Emotions
--------

0\. Neutral

1\. Happy

2\. Sad

3\. Anger

4\. Surprise

Requirements
------------

1\. [dlib C++ Library.](http://dlib.net/)

2\. [68-face-landmark
shape\_predictor](http://sourceforge.net/projects/dclib/files/dlib/v18.10/shape_predictor_68_face_landmarks.dat.bz2)

3\. A large image database with atleast 5000 images with images of each
emotions in separate folders.

4\. Tools – Linux,Cmake,g++,make

<span id="anchor-1"></span>Steps for use
----------------------------------------

1\.  Download "shape\_predictor\_68\_face\_landmarks.dat" for landmark
    detection from this link:
    <http://sourceforge.net/projects/dclib/files/dlib/v18.10/shape_predictor_68_face_landmarks.dat.bz2>
    
2\.  Put this file to the "data" folder.

3\.  Download and setup "dlib" on your computer.

4\.  In the programs give proper name to the header
    files(dlib directory).
    
5\.  Download and install cmake to compile.

6\.  For training put images containing happy and sad emotions in
    separate folders.
    
7\.  Run annotate.exe "./annotate.exe (emotion no) (directoy of
    images)/\*" .
    
8\.  Run ./train.exe .

9\.  Run ./emotionDetection.exe (image name) .

References
----------

-   Histograms of Oriented Gradients for Human Detection By Navneet
    Dalal and Bill Triggs CVPR 2005
-   Object Detection with Discriminatively Trained Part Based Models
    by P. Felzenszwalb, R. Girshick, D. McAllester, D. Ramanan IEEE
    Transactions on Pattern Analysis and Machine Intelligence, Vol.
    32, No. 9, Sep. 2010
-   One Millisecond Face Alignment with an Ensemble of Regression Trees
    by Vahid Kazemi and Josephine Sullivan, CVPR 2014

