## Welcome to Udacity's Self-Driving Car Simulator 
##欢迎来到Udacity的自动驾驶汽车模拟器
这个模拟器是为Udacity的自动驾驶汽车纳米学位开发的，用来教学生如何训练汽车如何使用深度学习来驾驶道路课程。查看更多项目细节。
这个存储库中的所有资产都需要统一。请按照下面的说明进行完整的设置。
可验证的游戏构建(模拟器的预编译构建)
说明:下载zip文件，提取并运行可执行文件。
This simulator was built for [Udacity's Self-Driving Car Nanodegree](https://udacity.com/drive), to teach students how to train cars how to navigate road courses using deep learning. See more [project details here](https://github.com/udacity/CarND-Behavioral-Cloning-P3).

All the assets in this repository require Unity. Please follow the instructions below for the full setup.

### Avaliable Game Builds (Precompiled builds of the simulator)

Instructions: Download the zip file, extract it and run the executable file.

Version 2, 2/07/17

[Linux](https://d17h27t6h515a5.cloudfront.net/topher/2017/February/58983558_beta-simulator-linux/beta-simulator-linux.zip)
[Mac](https://d17h27t6h515a5.cloudfront.net/topher/2017/February/58983385_beta-simulator-mac/beta-simulator-mac.zip)
[Windows](https://d17h27t6h515a5.cloudfront.net/topher/2017/February/58983318_beta-simulator-windows/beta-simulator-windows.zip)

Version 1, 12/09/16

[Linux](https://d17h27t6h515a5.cloudfront.net/topher/2016/November/5831f0f7_simulator-linux/simulator-linux.zip)
[Mac](https://d17h27t6h515a5.cloudfront.net/topher/2016/November/5831f290_simulator-macos/simulator-macos.zip)
[Windows 32](https://d17h27t6h515a5.cloudfront.net/topher/2016/November/5831f4b6_simulator-windows-32/simulator-windows-32.zip)
[Windows 64](https://d17h27t6h515a5.cloudfront.net/topher/2016/November/5831f3a4_simulator-windows-64/simulator-windows-64.zip)

### Unity Simulator User Instructions
版本2,2/07/17
Linux Mac Windows
版本1,12/09/16
Linux Mac Windows 32 Windows 64
## 统一模拟器用户指令
将存储库克隆到本地目录，请确保使用Git LFS正确地拉出大型纹理和模型资产。
安装免费游戏制作引擎统一，如果你没有它。统一是加载所有资产的必要条件。
加载统一，选择加载退出项目，选择自驱动-汽车-sim文件夹。
通过在左下角的Project选项卡加载场景，并导航到文件夹Assets/1_SelfDrivingCar/场景。要加载其中一个场景，例如LakeTrack，双击文件LakeTrackTraining.unity。一旦场景被加载，你可以通过按住鼠标右键点击，鼠标滚动到缩放来在场景查看窗口中飞行。
扮演一个场景。只要点击查看窗口上方的play按钮箭头，就可以随时进入游戏模式。
视图脚本。脚本使模拟器的所有不同机制工作，它们位于两个不同的目录中，第一个是Assets/1_SelfDrivingCar/脚本，它们主要与UI和套接字连接相关。脚本的第二个目录是Assets/Standard Assets/Vehicle/Car/ scripts并且它们控制与Car的所有不同交互。
建立一个新的轨道。通过使用位于Assets/RoadKit/ prefabs中的预先构建的道路预制板，您可以轻松地构建一个新的赛道，单击并将道路预制件拖拽到编辑器上，您可以通过按住“v”并将道路件拖拽到另一个块上，轻松地将道路块拼接在一起。
1. Clone the repository to your local directory, please make sure to use [Git LFS](https://git-lfs.github.com) to properly pull over large texture and model assets. 

2. Install the free game making engine [Unity](https://unity3d.com), if you dont already have it. Unity is necessary to load all the assets.

3. Load Unity, Pick load exiting project and choice the `self-driving-car-sim` folder.

4. Load up scenes by going to Project tab in the bottom left, and navigating to the folder Assets/1_SelfDrivingCar/Scenes. To load up one of the scenes, for example the Lake Track, double click the file LakeTrackTraining.unity. Once the scene is loaded up you can fly around it in the scene viewing window by holding mouse right click to turn, and mouse scroll to zoom.

5. Play a scene. Jump into game mode anytime by simply clicking the top play button arrow right above the viewing window.

6. View Scripts. Scripts are what make all the different mechanics of the simulator work and they are located in two different directories, the first is Assets/1_SelfDrivingCar/Scripts which mostly relate to the UI and socket connections. The second directory for scripts is Assets/Standard Assets/Vehicle/Car/Scripts and they control all the different interactions with the car.

7. Building a new track. You can easily build a new track by using the prebuilt road prefabs located in Assets/RoadKit/Prefabs click and drag the road prefab pieces onto the editor, you can snap road pieces together easily by using vertex snapping by holding down "v" and dragging a road piece close to another piece.

![Self-Driving Car Simulator](./sim_image.png)
