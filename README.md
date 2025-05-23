# Face_Detection
based on pyimagesearch tutorials
first we need to take some pictures keep them in seperated folders
then we need some libraries like opencv, libd, face_recognition
after that just we need to locate the face in the pictures do as said in pyimagesearch
then just calculate the border of face in the image this will done by pretrained models like resnet but we dont need to do that because face_recognition library does this for us
finally turn the camera on using opencv and manage the frames. in the frames face_recognition find the place of faces and compare them with our photos.
As we create a dictionary at first in the code and assign the names to photo's addresses we have the name for each photo
then when the match found we show the matched photos name
Thats it.
