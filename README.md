# Employee Monitoring Registration (Face Recognition and Detection)
    This is a complete face recognition project with a few clicks the application has the capability to collect
    datasets using a webcam, train itself and do predictions in real-time.

#### Techstack Selected:
    
    Programming language: Python 3.6
    Deep Learning Framework: MXNET, Keras
    Desktop App: Tkinter
    Image Processing: OpenCV
    Face Detection Algorithm: MTCNN
    Face Recognition Algorithm: Arcface


#### How tO Execute the Code:

    Step 1 : open your anaconda prompt (for windows user search inside start menu )
                                   (for Ubuntu and Mac user you can open your terminal)

    Step 2 : Create a new environment
                command : conda create -n facerecognition python==3.6.9
                
    Step 3 : activate your environment
                conda activate facerecognition
                
    Step 4 : Install requirements.txt in the newly created environment
            a). Navigate to your folder location on anaconda prompt/teminal
                    for me ( /PycharmProjects/FaceRecogAcademy )
                    for your folderName
                    
            b). Check if we have requirements.txt or not in the current directory

                    command : for windows (dir)
                              for Mac/Ubuntu(ls)
                    datasets,  How to run.txt,  requirements.txt,  src

                    you should see the above mentioned name of files.

                    if yes:
                        Your are good to go
                    elif No:
                        Please check the steps again you must have missed something

    Step 5 : Installation and setup is done:
         a).  cd src
         b). python app.py

         Yor are good to go !!

#### Results: 

The GUI created using Tkinter will look like below:

    Step 1: Click on Take Imgeas to collect the dataset usign Webcam (Default = 50 Images).
    
    Step 2: Click on Train Images for Training.
    
    Step 3: Click on Predict to do real-time Face Recoognition. 

The GUI will look like :

![Screenshot (335)](https://user-images.githubusercontent.com/55132850/155834095-fd7b29ac-ae67-422a-bbb6-b7839d5936a6.png)

Video Showing real time face recognition : 

https://user-images.githubusercontent.com/55132850/155834218-38d3ed3b-221b-4a85-aedf-ff67f8de3984.mp4



