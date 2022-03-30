# Humankind Style GAN  

Style GAN converting images into the style of the Game [`HUMANKIND™`](https://humankind.game) by Amplitude Studios.
The code and training of the neural network is based on [`AnimeGANv2`](https://github.com/TachibanaYoshino/AnimeGANv2).
   

## Requirements  

I recomend using [`Docker`](https://www.docker.com/) with [`Visual Studio Code`](https://code.visualstudio.com/) + [`Remote-Containers`](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) extension.

The following is only relevant if you want to setup the project by yourself without using docker:
- python 3.6  
- tensorflow-gpu 1.15.0 (GPU 2080Ti, cuda 10.0.130, cudnn 7.6.0)  
- opencv-python 4.5.4.60  
- gradio 2.5.2

## Usage  
Open this repository inside Visual Studio Code. A Pop up tels you that the "Folder contains a Dev Container configuration file. Reopen folder to develop in a container (learn more)." Click on the "Reopen in Container" button. Make sure that you are running docker otherwise you will get an error.
Visual Studio Code is starting the container and connecting to it. This process may take some time. 

In the newly opened Visual Studio Code a terminal should pop up in the bottom of the screen. Run following command inside the terminal:
> `python main.py`

A pop up tells you that: "Your application running on port 7860 is available. See all forwarded ports".
Click the "Open in Browser" button to open the application. 
____  
## Results  

![image info](./example_images.png)

Example results of the differnt GAN versions, V1-V4 from lefft to right (the first image is the original)
  

## License  
Copied from AnimeGANv2 as its based on the code and ideas of this repo: 

"This repo is made freely available to academic and non-academic entities for non-commercial purposes such as academic research, teaching, scientific publications. Permission is granted to use the AnimeGANv2 given that you agree to my license terms. Regarding the request for commercial use, please contact us via email to help you obtain the  authorization letter."
