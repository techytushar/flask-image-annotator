# Flask Image Annotator

A simple image annotator made in Flask which outputs the annotations in CSV format.


## Setup

* Clone the repository using:
```
git clone https://github.com/techytushar/flask-image-annotator
```
* Install Flask
```
pip3 install Flask
```

## How to use

* Run the app using `python3 app.py`
* In your browser navigate to `localhost:5000`
* Select the images you want to annotate and click submit
* The image will be displayed on the next page
* Drag on the image, on the part which you want to annotate
* On the left write the name of the annotation and click enter
* If you want to delete an annotation click "-" button beside the annotation
* Click the next button to go to the next image
* Annotate all the images
* At last, download the CSV file

## Format of CSV file

* image: Name of the image file
* id: id number of the annotation
* name: name of the annotation
* xMin: top left of the annotation box
* xMax: bottom right of the annotation box
* yMin: top left of the annotation box
* yMax: bottom right of the annotation box
