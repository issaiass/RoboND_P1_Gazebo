# Udacity Robotics Nanodegree - Project 1



<details open>
<summary> <b>Brief Review<b></summary>

This project includes all necessary files reproduce the first project of the Udacity Robotics Software Engineer Nanodegree.  It contains a gazebo world with a mimic of my home (non standard dimensions) and two instantiated dummy robots.


NOTE:
- for launching correctly you must export the gazebo plugins path (explained later)

Below a few image examples of the outcome.

<p align="center">
<img src = "doc/imgs/world.PNG?raw=true" width="65%"/>
<img src = "doc/imgs/plugin.PNG?raw=true" width="55%"/>
<img src = "doc/imgs/model.PNG?raw=true" width="45%"/>
</p>

The project tree:

<p align="center">
<img src = "doc/imgs/tree.PNG?raw=true" width="65%"/>
</p>

The project is now divided in several folders and now you can easily excecute effectively each file.

</details>

<details open>
<summary> <b>Using this repository<b></summary>

NOTE:  By default, all models has the same structure as the default suggested project.

- Clone this repository and navigate to the project itself.
~~~
    git clone https://github.com/issaiass/RoboND_P1_Gazebo
    cd RoboND_P1_Gazebo
~~~
- Inside the *RoboND_P1_Gazebo* folder create a `build` directory and compile the model, this will generate a gazebo plugin:
~~~
    mkdir built
    cd build
    cmake ../
    make
~~~
- Important!, you must export the  `GAZEBO_PLUGIN_PATH` for obvious reasons like if you do not do that the plugin will not be loaded:
~~~
    export tGAZEBO_PLUGIN_PATH=${GAZEBO_PLUGIN_PATH}:~/workspace/RoboND_P1_Gazebo/build
~~~
- Now navigate to the folder of your world file and execute it:
~~~ 
    cd ~/workspace/RoboND_P1_Gazebo/world
    gazebo phtrinidad.world
~~~
- You must  see a world of a home, a person, some stuff and two dummy robots in the floor


Finally, on `~/.gazebo/gui.ini` on `filenames` are exposed the address used from the models of the robot and building.


<details open>
<summary> <b>Issues<b></summary>

- Currently no issues

</details>

<details open>
<summary> <b>Future Work<b></summary>

Not in this project but:
- Plan to use the step or stl model of the jetbot.

</details>

<details open>
<summary> <b>Contributing<b></summary>

Your contributions are always welcome! Please feel free to fork and modify the content but remember to finally do a pull request.

</details>

<details open>
<summary> :iphone: <b>Having Problems?<b></summary>

<p align = "center">

[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/riawa)
[<img src="https://img.shields.io/badge/telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white"/>](https://t.me/issaiass)
[<img src="https://img.shields.io/badge/instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white">](https://www.instagram.com/daqsyspty/)
[<img src="https://img.shields.io/badge/twitter-%231DA1F2.svg?&style=for-the-badge&logo=twitter&logoColor=white" />](https://twitter.com/daqsyspty) 
[<img src ="https://img.shields.io/badge/facebook-%233b5998.svg?&style=for-the-badge&logo=facebook&logoColor=white%22">](https://www.facebook.com/daqsyspty)
[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/riawe)
[<img src="https://img.shields.io/badge/tiktok-%23000000.svg?&style=for-the-badge&logo=tiktok&logoColor=white" />](https://www.linkedin.com/in/riawe)
[<img src="https://img.shields.io/badge/whatsapp-%23075e54.svg?&style=for-the-badge&logo=whatsapp&logoColor=white" />](https://wa.me/50766168542?text=Hello%20Rangel)
[<img src="https://img.shields.io/badge/hotmail-%23ffbb00.svg?&style=for-the-badge&logo=hotmail&logoColor=white" />](mailto:issaiass@hotmail.com)
[<img src="https://img.shields.io/badge/gmail-%23D14836.svg?&style=for-the-badge&logo=gmail&logoColor=white" />](mailto:riawalles@gmail.com)

</p

</details>

<details open>
<summary> <b>License<b></summary>
<p align = "center">
<img src= "https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg" />
</p>
</details>