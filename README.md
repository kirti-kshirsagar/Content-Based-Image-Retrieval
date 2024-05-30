# README
Name - **KIRTI KSHIRSAGAR** 
- Using Windows 10, VScode, CMake,OpenCV 4.9(recent one) and C++.
- Not using any Time Travel Days
- Professor has invoked the **Stuff-Happens** clause for this assignment.

## This is a Readme file for duck.cpp file and this includes all the details that are necessary to execute various tasks in  the program.

### Task-1
- This is just the baseline task and so in order to run this task, the command used is : 
./two D:\PRCV\two\olympus\pic.1016.jpg D:\PRCV\two\olympus baseline sum_of_squared_difference 3

#### We can see that all the commands needed to run the tasks should be 5. First argument corresponds to the target image path, second argument corresponds to the database path or the csv file path, third argument is the feature type, fourth is the distance metric we use and fifth is the number of matching images we want.

## Task-2
- This is a task of Histogram Matching, in order to run the task the command used is:  ./two D:\PRCV\two\olympus\pic.0164.jpg D:\PRCV\two\olympus histogram histogram_intersection 3 
- Here histogram is the feature type and histogram_intersection is the distance metric used.

## Task-3
- This is a task of Multi-histogram Matching, command to run this is:  ./two D:\PRCV\two\olympus\pic.0274.jpg D:\PRCV\two\olympus Multi-Histogram histogram_intersection 3
- Here Multi-Histogram is the feature type and histogram_intersection is the distance metric used.

## Task-4
- This is a task of texture and color Matching, command to execute this task is:  ./two D:\PRCV\two\olympus\pic.0535.jpg D:\PRCV\two\olympus color_texture equal_weighting 3 
- Here color_texture is the feature type and equal_weighting is the distance metric used.

## Task-5
- This is a task of Deep Network Embeddings, command to execute this task is:  ./two D:\PRCV\two\olympus\pic.0893.jpg D:\PRCV\two\ResNet18_olym.csv csv cosine 3 
- Here, D:\PRCV\two\ResNet18_olym.csv is the path to the csv file, csv is the feature type and cosine is the distance metric used.

## Task-6
- This task is just the comparison and is included in the report.

## Task-7
- This is a task, the purpose is retrieval of images that have something small red coloured things in it.
- ./two D:\PRCV\two\olympus\pic.0983.jpg D:\PRCV\two\olympus task7 custom 5
- Above is the command to execute this task, wherein, task7 is the feature type and custom is the distance metric used.

## Extension:
- For extension, I tried to integrate different features together and different distance metric together to be used for task-7.