# echart_map
# echart 地图省市县三级下钻+指定区域随机散点

### 如果出现右击文件用浏览器直接打开时图表并没有渲染出来，这是因为使用异步请求加载数据时，由于cors跨域资源共享问题导致的不能读取json数据；

### 解决方案： 在本地启动一个http服务，使用http://127.0.0.1:8080的方式访问，即可解决上述问题，推荐使用Http-Server
### 安装 http-server，打开终端，输入以下命令：npm install http-server -g
### 打开cmd，切换到当前echarts项目文件夹，在当前项目根路径下输入以下命令即可：http-server [path] [options] 常用命令：http-server -c-1
### 作用： 开启http服务器，并禁止浏览器缓存；注意：如果 public 文件夹存在，[path]默认为 ./public，否则为根目录 ./
