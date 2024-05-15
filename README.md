# Depth Image Processing and Visualization

This repository contains two Python scripts that demonstrate advanced techniques for processing and visualizing depth images. The first script transforms depth values from millimeters to meters and highlights a specific pixel in the image. The second script utilizes Plotly to create an interactive 3D surface plot of the depth data.

## Scripts Description

- **Depth Conversion and Highlighting**: This script loads a grayscale depth image, converts the depth values from millimeters to meters, and highlights a specific pixel. It's useful for applications needing precise depth measurements at specific image locations.

  ![d2d](https://github.com/Husseinhhameed/Depth-image-Processing/blob/main/d2d.png)

- **3D Surface Visualization**: This script creates a 3D surface plot of a depth image using Plotly, allowing for interactive exploration of the depth data. It's ideal for visualizing spatial depth data in applications such as 3D modeling and terrain analysis.

  ![d2d](https://github.com/Husseinhhameed/Depth-image-Processing/blob/main/3d%20representation.gif)


##Depth Conversion and Highlighting

- **Make sure to input the path to your depth image file. You can also adjust the pixel coordinates you wish to query within the script.

- **3D Surface Visualization
Update the image file path to your depth image location. You can interact with the 3D plot in the browser to explore different views of the depth data.

##Dependencies
- **Python 3.x
- **NumPy
- **OpenCV
- **Plotly

##Contributing
**Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

##Contact
hossein.h.hameed@gmail.com

##License
This project is licensed under the MIT License - see the LICENSE file for details.
