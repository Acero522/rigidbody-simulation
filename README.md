## rigid-body-simulation
刚体模拟2D或3D实现  

## 库依赖:
2D   
[matter.js](https://www.npmjs.com/package/matter-js)  
[matter-attractors](https://www.npmjs.com/package/matter-attractors)  
[p5.js](https://www.npmjs.com/package/p5)  
3D      
[FleX](https://github.com/NVIDIAGameWorks/FleX)    

## 项目描述

**完成项目：**  
刚体模拟  

**2D实现：**    
使用JavaScript，利用matter.js 2D刚体物理引擎，matter-attractors引力模拟库，实现2D小球刚体及box刚体碰撞模拟。  

**使用：**        
index.html运行，可以设置刚体数量，刚体最大体积，刚体最小体积。     
随机生成刚体数量个在最大体积和最小体积之间随机大小的刚体，鼠标点按或拖拽都可模拟2D刚体碰撞。  

**示例：** 

![avatar](/pic/1.png)  
![avatar](/pic/2.gif)  

**3D实现**  
[NVIDIA FleX](https://github.com/NVIDIAGameWorks/FleX) Flex是一个基于粒子的实时模拟库。

 **使用：**   

FleX文件夹解压，run_cuda.bat使用cuda运行或run_dx.bat使用dx11或dx12运行。

**3D示例**

![avatar](/pic/3.gif)

![avatar](/pic/4.gif)

  ![avatar](/pic/5.gif)

## 参考:
- [NVIDIAGameWorks/FleX](https://github.com/NVIDIAGameWorks/FleX)  
- [metaball-fluid-simulation](https://github.com/mx0c/metaball-fluid-simulation)
