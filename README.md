# Emotion-recognition-in-images

This programm uses the deepface library (https://github.com/serengil/deepface) to detect emotions in images. 
The code can detect the following emotions from a persons face:
1. anger
2. disgust
3. fear
4. happiness 
5. sadness
6. surprise
7. neutral

The emotion "disgust" is not working as intended as of now. I havent found a single image which met the requirements to classify "disgust" as the dominant emotion.

To run ths file the following requirements are needed:
1. "pip install deepface"
2. "pip install opencv" (if you are facing an error when installing this library use "pip install opencv-contrib-python" and then "pip install opencv-python"
3. Have some images ready and save them in the "images" folder within the same repository
4. Run the code and get visual representations of the results!


For better visual representation of not dominant emotions use log = "true" when plotting the bar chart.
