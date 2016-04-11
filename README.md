# state_grid
某项目气候可视化
===========================

###环境依赖

node
//安装node运行环境   
安装看这里: https://nodejs.org/

###部署步骤
1. 添加数据目录（csv文件）  
``` 
/my-app/data
```
2. Setup   
```
# cd ./(当前目录)  
# start the server and watch (localhost:8080)    
node server.js
```
3. 在浏览器地址栏输入localhost:8080 


###目录结构描述
```
├── my-app                      // 应用  
│   ├── images                  // 图片资源  
│   ├── scripts                 // 脚本文件  
│   ├── styles                  // 样式文件  
│   ├── index.html              // 预测模型入口
├── .gitignore                  // 忽略文件配置  
├── Readme.md                   // help info  
├── server.js                   // 启动应用服务文件  
```

###代码说明
#### 依赖库
1. jQuery（不多说）
2. [C3.js](http://c3js.org)
c3是一个基于D3-based可重用的图表库,使图表的更深层次的整合到web应用程序中。  
更多信息:https://d3js.org/、http://c3js.org。




























