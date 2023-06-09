# Indian License Plate Detector using Haar Cascade and OpenCV in C++

This project aims to detect and extract Indian license plates from images using the Haar Cascade method in OpenCV and C++. The Haar Cascade method is a popular object detection technique that uses machine learning algorithms to detect objects in images or videos.

# Demo

1.) Test Image: -

![4](https://user-images.githubusercontent.com/98112123/229573315-91d241a3-83e2-4ee7-9d19-f90f24adc494.png)

2.) Extracted Number Plate :-
            
![4](https://user-images.githubusercontent.com/98112123/229573346-2936f5a1-d327-49a1-a06d-17f903243400.png)

3.) Live Working :-


https://user-images.githubusercontent.com/98112123/229589496-4574f375-a106-4409-accd-d0d6b21b381c.mp4



# Requirements

1.) OpenCV (https://github.com/opencv)

2.) C++ Compiler

# Usage

1.) To use the license plate detector, follow these steps:

2.) Clone the repository.

3.) Compile the code using a C++ compiler.

4.) Run the executable file with the path to the image you want to detect the license plate from.

5.) The program will output the detected license plate as a separate image.

# How it Works
The license plate detector using Haar Cascade method uses the following steps to detect and extract license plates:

1.) Load the input image in realtime via webcam.

2.) Load the Haar Cascade classifier for license plate detection.

3.) Detect license plate regions in the image using the classifier.

4.) Filter out the regions based on their size and aspect ratio and create a contour around the region.

5.) Extract the license plate region from the image and saves it in the folder.


# Limitations

The license plate detector using Haar Cascade method may not work well in the following scenarios:

1.) Low-quality images with poor lighting or blurriness.

2.) Non-standard license plate formats, such as personalized or temporary plates.

3.) Obstructed or partially visible license plates.

# Credits

1.) This project is inspired by and based on the OPENCV using C++ Course by Murtaza's Workshop - Robotics and AI (Youtube).




