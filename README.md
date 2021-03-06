# RTH
### ☢Study on optimal path of operation under radioactive source

![](https://raw.githubusercontent.com/ckjbug/xiaokui/master/split.png)

## A，放射源下作业最优路径的研究

<div align="center">
    <img src="https://i.imgur.com/3xwLNLi.png">
    <br>
</div>


#### 使用场景：

  在磁场、电场、电磁波（WiFi）、辐射场等中预算人员在一些平面或空间的位置移动的最优路径，减少对辐射的吸收。

#### 待解决问题：
	
- 放射源的位置节点P（平面和空间）
	
- 标准的参考，最小辐射量和最短路径（缩短作业工期）
	
- 热图原理，如地图视图中的热图和叠加图
	
- 所受辐射标准（最大值）
	
- 不同作业（工业、军工）的不同解决方案
	
- 通过软件生成的方式热力图，计算得到最优作业路径



#### 已知变量：

- 放射源位置（二维/三维）（单源、多源节点）

- 放射源强度tmp

- 所能承受最大辐射量标准

- 活动作业的范围（面积/空间）


#### 应用载体（软件选型）：

- Asp.Net Core（Web App）

- Xarmain 移动端

- 嵌入式设备（Qt）

![](https://raw.githubusercontent.com/ckjbug/xiaokui/master/split.png)

## B，基于原有的热图/密度图分析最优路径的研究与应用

#### 概念：

   将热图或密度图导入软件系统进行分析，提取图片中的数据，计算规划出最优路径的解决方案。
   
#### 前提：

   热力图已经通过其他数据建模生成出来（支持各种数据格式），我们只分析图片上的数据，通过软件分析出途中最优的路径并标注出来。

#### 应用方向：

- 交通路线图中，选中最畅通的路线上班

- 传统军工行业中，如核电站现在作业，单兵作战路线分析


Key Word：

    Heat map、The optimal path、Radiation


