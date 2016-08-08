# A Study of Machine Learning and it's Applications

## Deep Dive

I've found a need to dive deeply and learn comprehensivly about a particular
subject. In my survey of the computer science landscape I find that the
applications of machine learning are a worth while
area of the field to persue in depth. 

## Experiments

Following is an outline of some experiements in the area of machine learning
that I find touch on the topics that I want to learn.

Topics are:

* Recognition of objects in an image
* Learning strategies to achieve goals

### Experiment 1: Recognition - Unique facial recognition

Using a Haar classification in opencv I should be able to locat faces in a
image and identify a bounding box around that face. The outcome is a
smaller image containing a single face. The image can then be passed into a
classification algorithm that can say if it recognizes the face or not and 
if so provide a identfying number. If it doesn't recognize the face it will 
use the image to generate a training set of new imags, again using opencv's
generators, and learn against it.

### Experiment 2: Recognition - Identifying buttons on a page

This is similar to experiement 1 instead of faces, this will detect buttons in a
screenshot of a webpage. Challenge is that there will not be a prebuilt haar
classifier for finding buttons on a page. So one will have rto be built from
scratch. 

Given I have a screenshot I can get a list of button bounding boxes. 

### Experiment 3: Learning - Find paths through an application

Given I have an driver that can perform clicks and take screenshots and I can
identify a goal in a screenshot then I can evaluate a strategy for a sequence of
button presses

