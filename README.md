# cervical-spine-detection

## Abstract:

Worked on dicom format data, images Fractural images were given in dicom format. Moreover, Fractures can be more difficult to detect on imaging due to superimposed degenerative disease and osteoporosis. I designed a CNN classifierto identify fractures based on the CT Scan images of Cervical Spine (neck).Used Tiling to partition the images into mini-batches to detect small fractures. Used Transfer Learning to Fine-tune an Efficient-Netb07 model, achieving 0.54 on the Log Loss metric. Ranked Top 8% in Kaggle Competition.


## DataSet:
worked on 343 GBytes Dataset consists of medical Images. Here is the Link of the data:
https://www.kaggle.com/competitions/rsna-2022-cervical-spine-fracture-detection/data

## Classification:
Challenge was to detect the Cervical Spine of the humans, there were 7 classes to detect: C1,C2...C7. Some Patients have more than 4 cervical fractures but 80% of the Patients had 2-1 Cervical fractures.


## Efficient-Netb07:
Used Transfer Learning to Fine-tuned an Efficient-Netb07 Model. Just changed the last layer of the model according to my own dataset classes.

