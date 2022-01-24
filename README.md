# Assistive_Vision
Computer Vision based Assistive Technology for blind and visually impaired people
![image](https://user-images.githubusercontent.com/66831307/150796720-0c5717b5-6879-46fe-9e59-e4614865029e.png)

# Aim of the Project:
Creation a model which will work to assist visually impaired people. This product will detect objects or any other activities and will reflect the same in the form of audio, so that person can easily know about what’s happening in his/her surroundings.

# Motivation behind the work of project:
In a recent survey it is estimated that 285 million people worldwide are visually impaired, among them 246 million have low vision and 39 million are blind. 9 million children are estimated as visually impaired and among them 1.4 million are irreversibly blind. The fact about visual impairment is surprising on one hand, because despite of enormous medical efforts have been made to wipe out the visual impairment, the number is still breath taking. On the other hand, these facts encourage us to develop object recognition-based assistance for visually impaired people.

# Objectives:
◼️ To detect objects and person
◼️ To maintain or improve an individual’s functioning and independence
◼️ To improve visual tracking
◼️ To identify the characteristics of visual impairments

# Now, lets start with working-

Let's see the architecture first-
The overall system comprises of front-end. The back-end framework comprises of three modules:
Camera module, Detection module and Audio module as appeared in Fig.
![Architecture](https://user-images.githubusercontent.com/66831307/150792932-22d62e81-8262-4815-8516-c392cfff86f8.jpg)

Final architecture of our proposed product is to recognize object which is there in front of a person i.e. in front of camera which is shown in the following table-
![Steps of AV](https://user-images.githubusercontent.com/66831307/150793294-3ab26260-b761-4b79-8891-0bf89eec68e5.png)

Steps for implementation-
# Step 1: Capturing Object
In the initial phase, we used to webcam to get the image or object. Python provides various libraries for image and video processing. One of them is OpenCV. OpenCV is a vast library that helps in providing various functions for image and video operations. With OpenCV, we can capture a video from the camera.
![Object_Captured](https://user-images.githubusercontent.com/66831307/150794250-4c2b0acc-ad9d-49ef-be45-95fa82dc8187.jpg)

# Step 2: Reading and shaping images of captured object 
It loads the image from PC and gives it height, weights and number of channels for each pixel. When working with OpenCV Python, images are stored in numpy ndarray. To get the image shape or size, use ndarray.shape to get the dimensions of the image. Then, you can use index on the dimensions variable to get width, height and number of channels for each pixel.

# Step 3: Putting text over detected image of object
In this step we are putting text to our detected object and will display it. cv2.putText() method is used to draw a text string on any image.
![Text_Over_Image](https://user-images.githubusercontent.com/66831307/150794993-60594741-f334-4a74-a51f-e03c51485737.jpg)

# Step 4: Audio output
Here by using python module it converts text into audio form and displays it. For that we have used a module called gTTS, which is text to speech convertor.

# Here is the demonstration of the whole work-
https://user-images.githubusercontent.com/66831307/150790192-bfc8802c-870a-43e6-8391-be46531faf54.mp4

Hope, you have liked it!

Thank you all my readers...!
