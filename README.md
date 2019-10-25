# 3D Morphological Plant Modelling : From Theory to Practice

Workshop organised by the University of Tokyo.
Dates: 28 and 29 October 2019

## Aim

The aim of this workshop is to stress the importance of 3D plant morphology in plant science, and in particular, to address the challenge of modeling plant morphology under field conditions.

The first day of the workshop will give a general introduction on the modelling of 3D plant architecture and its development. We will present the functional-structural plant models (FSPM), the formalisms behind the representation of plant geometry and topology, methods and tools to reconstruct and analysed plant architecture as well as formalisms to simulate plant form and function. We will also present OpenAlea, the open-source software platform dedicated to multiscale modelling of plants.
During the second day, you will have the opportunity to develop your own model during hands-on tutorials. This will be the opportunity to simulate your plant of interest.


## Install

This workshop will be based on the [OpenAlea](https://openalea.rtfd.io) opensource platform.
*OpenAlea* is a modular platform based on the Python language.

To install OpenAlea, you need first to install the [Conda](https://conda.io) package manager.

### Conda Installation

[Conda](https://conda.io) is a package manager that can be installed on Linux, Windows, and Mac.
If you have not yet installed conda on your computer, follow these instructions:

[Conda Installation](https://conda.io/docs/user-guide/install/index.html). Follow instructions for Miniconda.

[Conda Download](https://conda.io/miniconda.html). Use the Python 2.7 based installation.

#### Windows, Linux, Mac

Create an environment named *openalea*:
Launch a console (See Anaconda Prompt in Start menu on windows)

    conda create -n openalea openalea.plantgl openalea.lpy openalea.mtg pyqglviewer boost=1.66 -c openalea -c anaconda -c openalea/label/unstable

Activate the *openalea* environment:

    conda activate openalea

## Agenda

### Monday 28th October

    09:00 - 09:10     Welcome 
    09:10 - 09:30    Workshop introduction
    09:30 - 10:15    Short presentation of the participants

    10:30 - 11:30    Introduction to 3D shoot and root plant modelling (Christophe Pradal)
    11:30 - 12:00     Discussion

Lunch

    13:30 - 14:00    Short Introduction to OpenAlea
    14:00 - 14:30    3D Analysis and Reconstruction of Plant Architecture
    14:30 - 16:00    Simulation of Plant Architecture using L-Systems

    16:30 - 17:00    Light interception on 3D models

    Installation of OpenAlea (needed for Tuesday)

### Tuesday 29th October

Morning (09:00 - 12:00)
    
    Hands-on tutorials : Simulation of shoot or root architecture
    Basic tutorials
    Simulation of a tree
    Simulation of a root system

Afternoon

    13:30 - 17:00    Open simulation tutorials based on participants feedback
    17:00 - 18:00    Open Discussions and Farewell

