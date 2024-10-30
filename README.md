[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/swKMSSMl)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=16850966&assignment_repo_type=AssignmentRepo)
# Computer Graphics Booting Up

## Let's start with ModernGL

This lab stands to prepare the moderngl development environment. Below the steps and requirements for initial coding tasks. Please make sure to edit the python provided files; for dependencies, you can add the files you need.

1. Install moderngl and its dependencies
2. Make sure that the following programs run
    - [`01_hello_world.py`](./01_hello_world.py)
    - [`06_multiple_objects.py`](./06_multiple_objects.py)
    - [`09_models_and_images.py`](./09_models_and_images.py)
        - _Modify this program to change the box's texture to a correctly aligned TEC logo_
3. Document how to execute the 3 programs in the section below.

* For documentation and missing dependencies, follow these links:
    - https://github.com/moderngl/moderngl
    - https://moderngl.readthedocs.io/

## How to run your program

```
First you will need to open the github repository in visual studios. Afer opening you need to make sure that you have installed python in your computer, if you have not, you will need to install it in the micrsoft store or in the offical python site:
https://www.python.org/downloads/

After making sure that you have python installed you need to follow the following steps on each of the programs in order to run them.

Program 1:
Open the terminal and execute the commands:
-pip install moderngl
-pip install pygame
After executing these commands you can execute the program and it will work :D

Program 2:
Open the terminal and execute the following commands:
-pip install PyGLM
-pip install numpy
After executing this commands you will be able to run the program :D

-Program 3:
Open the terminal and execute the following commands:
-pip install objloader
-pip install Pillow

After executing the commands you need to download the following files and put them in the same folder of the program:
-An image of the Tec logo
-crate.obj (that you can finnd it in the github repository)
-lowpoly_toy_car.obj(that also can be found in the github repository)
 Once you have download those files you will need to change the paths where those files are stored.

By doing all this steps you will be able to run the program correctly :D



# Update this section with instructions on how to run your programs. 

# Consider that these instructions will be executed 
in a completely new linux-based machine (Ubuntu 22.04),
so, instructions for dependencies installation must be added.

# It's highly recommended to use python virtual envs. 
You may take a look on:
https://docs.python.org/3/library/venv.html
```

## Grading Policy

- 25% - `01_hello_world.py` is running with no errors
- 25% - `06_multiple_objects.py` is running with no errors
- 25% - `09_models_and_images.py` is running with the requested change (TEC logo texture)
- 25% - Documentation on how to run your programs