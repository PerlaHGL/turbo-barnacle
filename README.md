

## 简介
 街机游戏克隆项目


## 如何在服务器上运行
  如已有服务器，可以把源码直接拷贝至目录下，浏览器输入相应地址即可；如果没有可通过如下python去搭建简单的Http 服务器。
* 打开命令行（Windows）。
* 通过 `cd` 进入到你保存 HTML 文件的目录。例如，`cd ~/Documents/mysite/`。
* 输入 `python --version`,查看当前安装的版本。
* 如果你安装的是 **Python 2**，输入 `python -m SimpleHTTPServer 8000`；如果你安装的是 **Python3**，输入`python -m http.server 8000`。
* 在你的浏览器中访问 `http://localhost:8000/`。如果在你的目录中存在一个名为`index.html`的文件，它将自动显示。如果不存在，你应该能看到该目录下的文件。点击 HTML 文件并加载。


## 游戏相关规则

* 玩家在移动时，需要避开虫子，碰到虫子则回到起始位置，生命数`-1`，玩家初始生命数有`3`条，为`0`时，则通关失败；
* 当玩家成功到达对岸，即可通过当前关卡，分数`+10`；
* 当玩家通过关卡 `>5`，且分数`>=50`,即可获得游戏胜利
* 当玩家升级后，会出现石头，玩家需要绕过石头


## 操作

* 通过方向键上下左右控制玩家移动
* 游戏通关胜利或失败，按 `Enter`键可重新游戏


## 版权