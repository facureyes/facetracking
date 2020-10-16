This project was developed by Facundo Reyes and Julian Alvarez under the supervision of Ph. Gonzalo Sad in Universidad Nacional de Rosario. 

It is made in C++, using Qt framework, OpenCV 4.3.0 and ALGlib 3.16.0. 

This project proposes the study, development and implementation of a computer software tool, which, through a video input that show a person's face in the foreground, you can follow the movement and expressions of the same and thus be able to extract a series of parameters that are of interest in different fields of study, such as speech therapy, neurology, among others.

For this, advanced digital image processing techniques are combined based on artificial vision and numerical minimization methods. Combining these techniques, facial points of interest were tracked throughout the video and estimation of parameters of the face model used. In this way, it is carried out a tracking of 2D points and they are estimated in a 3D model with the shape of the face of the person under analysis, allowing to obtain quantitative measurements of it. Once processing is completed, the results obtained will be displayed in different interactive graphics and it will be allowed to export them.

To test the correct operation of the program, several videos were used test in different lighting conditions and environment, in which they were analyzed people with partial facial paralysis and healthy people. It was observed that the program is consisting of the results obtained and that the parameters measured in a person they do not vary from video to video. It should be noted that, in the test videos of people with partial facial paralysis, the results obtained for each side of the face  correspond with their partial facial paralysis. The efficiency of the proposed method was evaluated perceptually.

