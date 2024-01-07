# Web-App-for-Face-Detection-and-Recognition-
Using OpenCV, DeepFace, FastAPI

This model contains a web app that can be run in two ways-
1) Upload an image and the app draws box around detected face(S) and annotates it with the name of the person in it if the face matches any of those in the database(which contains their name data in the filename itself)


Input:
![Screenshot 2024-01-05 221545](https://github.com/Samsriddhi/Web-App-for-Face-Detection-and-Recognition-/assets/154321347/3b8a2b5a-0640-4f42-935d-41bcb7645e42)


Output:
![Screenshot 2024-01-05 221515](https://github.com/Samsriddhi/Web-App-for-Face-Detection-and-Recognition-/assets/154321347/ac0a2d7c-0086-43f2-bf22-6ae87566660b)






2) Upload a video and the app draws box around detected face(S) and annotates it with the name of the person in it if the face matches any of those in the database(which contains their name data in the filename itself) in every frame

Input: ![Screenshot 2024-01-07 224654](https://github.com/Samsriddhi/Web-App-for-Face-Detection-and-Recognition-/assets/154321347/64468833-067e-4b05-8bc0-79abb294b901)



Output: ![Screenshot 2024-01-07 224721](https://github.com/Samsriddhi/Web-App-for-Face-Detection-and-Recognition-/assets/154321347/94caee50-2090-4115-bc27-da7ed59dd9cd)







Working: the uploaded file is compared to database Celebrity_Faces_Dataset and returns if any matched face is same.
Here, for debugging, I created a subset of Celebrity Faces Dataset, called temp facerec dataset to compare faces.

#How to Use this Model:

1. Download the dataset from the link in Celebrity_Faces_Dataset txt file.
2. Download the static and template files.
3. Copy my code to your Jupyter(/preferred ide with suitable changes) and change filepaths for db in verify function, static, and template, depending on where youve stored them in your system.



   
   
