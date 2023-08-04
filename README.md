# FaceMaskDetection
This repo contains neccessary code to develop face mask detection using transfer learning.

# Creating Virtual Environment
Create a virtual environment and install jupyter notebook and all other required modules.

# IMAGE CAPTURE
Run the Image capture.ipynb file from this folder to capture images for your dataset.
create your necessary labels as shown in the picture.
![Image capture part-1](https://github.com/TejashKatuwal/FaceMaskDetection/assets/118622724/dd74d312-9aad-4025-bc0a-974fe526af95)

After creating the labels, capture as many pictures as you want for your dataset. The more the merrier.
![Image capture part-2](https://github.com/TejashKatuwal/FaceMaskDetection/assets/118622724/80fc41db-e36d-4fe9-81c3-d34aeac1f979)

P.S You can skip this if you already have a datset.


# TRAINING AND DETECTION
# TRAINING
First split the images into two folders train and test. Usually keep 80% of data in train folder and rest 20% in test. Label the images using labelimg in pascal/VOC format.
Now create all the neccessary paths and folders to operate and work on them one by one.
Here we are using mobilenet ssd.
![training-1](https://github.com/TejashKatuwal/FaceMaskDetection/assets/118622724/c3d6af5a-9d06-4af9-b031-edf06470c7fd)

![training-2](https://github.com/TejashKatuwal/FaceMaskDetection/assets/118622724/e4dd332b-4590-4623-a062-062973becf71)

Now download the protobuf that fits your version.
![training-3](https://github.com/TejashKatuwal/FaceMaskDetection/assets/118622724/c45176ee-743f-4167-97e5-9504f7362195)

now run the verification script. The script must say ok like shown in the figure for the program to work smoothly.
![training-4](https://github.com/TejashKatuwal/FaceMaskDetection/assets/118622724/e2e1b837-088a-4a25-b20d-0623d356173e)
