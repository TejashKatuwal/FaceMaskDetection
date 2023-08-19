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

Now run all the codes one by one as shown in the picture.
![training-5](https://github.com/TejashKatuwal/FaceMaskDetection/assets/118622724/62577d0d-5bd1-46c9-aa9f-3d995f8b5a81)
![training-6](https://github.com/TejashKatuwal/FaceMaskDetection/assets/118622724/ca63515a-2a21-4327-b8fe-6211ceafa928)
![training-7](https://github.com/TejashKatuwal/FaceMaskDetection/assets/118622724/e1a45542-4fe3-43a2-a53f-90b2e6f9f67f)
![training-8](https://github.com/TejashKatuwal/FaceMaskDetection/assets/118622724/5ef3bcbb-ced3-45b1-97f0-a8cb4934c127)

Now generate the training command and run it on cmd. Go to the project folder using cd project and run the generated command. This will take time to train if you don't have GPU with GPU it will be a little faster.
![training-9](https://github.com/TejashKatuwal/FaceMaskDetection/assets/118622724/288db2e6-ec78-48f0-92cc-5603ed2723a4)
Now run the evaluation script.
![training-10](https://github.com/TejashKatuwal/FaceMaskDetection/assets/118622724/55f347f4-adf5-4973-a772-c1d5528c0fa0)

# DETECTION
Now run the following code to get your program ready for object detection.
![checkpoint generation](https://github.com/TejashKatuwal/FaceMaskDetection/assets/118622724/859b62b9-6106-4054-9dd8-84e4f2a8ccc7)

Now import labels from the image path as shown in the code below.
![label loading](https://github.com/TejashKatuwal/FaceMaskDetection/assets/118622724/08da951c-395d-428b-8f6d-456a9ff76035)

Now read image from the test file and perform the object detection by running the code below.
![image reading](https://github.com/TejashKatuwal/FaceMaskDetection/assets/118622724/dc0f378b-6f2f-4cef-bc0b-9eef71bb544f)

The following figure shows the output.

![output](https://github.com/TejashKatuwal/FaceMaskDetection/assets/118622724/bea8eb6a-c4cb-450a-8231-016e5c70b541)
