# Flock-AI-Fish-Unreal-VR

一个基于虚幻4的鱼群AI的VR demo  
A fish flock AI VR demo for Unreal Engine 4 

![github_fish_flock_ai.png](https://ooo.0o0.ooo/2016/10/18/58060a188d281.png)

## Relevant Links 
* Watch the [Video Preview](http://v.youku.com/v_show/id_XMTc2NTM4MjkyMA==.html)
* Download [MyFish.exe (Win64)](http://pan.baidu.com/s/1qYbBrHU)
* [My Blog](http://blog.csdn.net/nosix)


## Unreal Engine Version
4.13.0

## Instructions For The Game 
#####*VR* : 
*(My Device is HTC Vive)*

* Motion Controller FaceButton1 => Move forward
	* 手柄圆盘上键                  => 往前移动
* KeyBoard Arrow UP and Down    => Move faster or slower
	* 电脑键盘的上下箭头键          =>  调整移动速度
* Motion Controller Trigger     => Attract fishes
	* 手柄扳机键                    => 吸引鱼群

#####*PC* :

* R                  =>  Toggle Pawn Rotation Switch   
	* R键                =>  切换是否角色的上下转动视角开关   
* WASD and EQ        =>  Basic movement 
	* WASD 和 EQ  键     =>  基本的移动指令 
* Left Mouse Button  =>  Attract fishes
	* 鼠标左键           =>  吸引鱼群
* Arrow UP and Down  =>  Move faster or slower
	* 上下箭头键         =>  调整移动速度




## About This Demo
* Read [The Post on My Blog (not finished yet)]()  for the details 
	* 查看 [我的博客 (还没写完)]() 探究细节
* This project implements a new flocking Ai algorithm, with 2 components **算法简要** : 
	* Separation : every fish will try to steer away from their neighbors 
		* 分离性 ：每条鱼都会与周围的鱼保持距离 
	* Following the leader : every fish will try to follow its leader
		* 跟随一个领头者 ： 每条鱼都会跟随一个领头者
* Other features **其他特性**:
	* avoiding enemies.
		* 躲避敌人
	* can run **1200+** fishes at the same time
		* 可以同时运行 **1200+** 条鱼儿

