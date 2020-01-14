Mini Auto Race Car (MARC) Project
=========
  
![MARC](https://github.com/MARC-Project/doc/blob/master/MARC.png)  
The MARC project is a project aiming at developing a 1/24 scale smart car model as a powerful tool for academic research and education. It lauched since June 2019, and the project is still developing. If you need more information about MARC, contact the director via email tllam@cuhk.edu.cn.

|Author|Huang Tianjian|
|---|--- |
|E-mail|117010099@link.cuhk.edu.cn

****

# Basic components & reference about MARC
MARC consists of smart car hardware, computer hardware, software and simulation platform.  
  
**Smart car hardware:**  
Here is the link where you can buy smart car hardware: 
https://item.taobao.com/item.htm?spm=a1z10.1-c-s.w137644-21484817964.26.59b53e176q7pza&id=602425271926  
Here is all supporting material of the smart car hardware: https://pan.baidu.com/s/1hMAgY1OgKLl4K0E6DjuoVw, password please contact 117010099@link.cuhk.edu.cn or the seller.  
  
**Computer Hardware:**  
Currently we are using Raspberry Pi 3B/3B+. Material and docs of smart car also teaches how to assemble Raspberry Pi and the lower level control board together.  
  
**Software:**  
The OS currently using is Ubuntu Mate 16.04, which is fit for ROS kinetic version.  
Install Ubuntu Mate 16.04 (Reference Only): https://blog.csdn.net/BreederBai/article/details/87865457  
Install ROS Kinetic: http://wiki.ros.org/ROS  
When you have configured Ubuntu and ROS environment, you can create a catkin workspace and compile [navigation_without_movebase package](https://github.com/MARC-Project/navigation_without_movebase) to make the car work. Detailed description is in the corresponding repo.  
  
**Simulation:**  
[MARC_sim](https://github.com/MARC-Project/MARC_sim) is used to do simulation in Gazebo. This package is **not to be used in the smart car computer system**.  







