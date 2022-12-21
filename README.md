# Face-Mask-Detection (FasterRCNN)
The program detects the status of each person's mask in the given image

# Result:
## Label annotation
It will return 3 results:
  1. with mask
  2. without mask
  3. mask weared incorrect
## Output image:
![image](https://user-images.githubusercontent.com/106876168/208924386-6f1d4f01-4470-4457-990b-27fbce8421e5.png)
![image](https://user-images.githubusercontent.com/106876168/208924432-5c62fc99-27bf-4e33-b6f0-0dd3b8b48f32.png)


# In details

## Source Code:
  file FasterRCNN.ipynb
  
## Annotations Folder
  The folder is used for training the model

## Images Folder
  The folder contains the images that need to detect
  
# Things to Note:
- Copyright belongs to Daniel and the origin code: https://www.kaggle.com/code/daniel601/pytorch-fasterrcnn/notebook
- I just editted something:
  + Correct some errors to be able to run in my machine
  + Display the label for each object
  + Plot the predict image, additionally
