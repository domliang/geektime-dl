# geektime-dl
此工具为下载极客时间已购课程方便离线观看

### 环境要求
```
node >= 8.0
已安装 ffmpeg
```

### 安装
```
npm i geektime-dl -g
```
### 使用

#### 1.创建下载目录
```
mkdir geektimedownvideoloader
cd geektimedownvideoloader
```

#### 2.创建配置文件
```
vim conf.json
```
配置文件示例
```
{
	"courseId": "168",
	"cookie": "_ga=GA1.2.1688418439.1544448404; _gid=GA1.2.327097483.1544448404; GCID=44skdfhksdhfjshgjshdgfjhsgdfhjsgdfhjsghjsgssjhd"
}
```
##### courseId获取
浏览器打开并登录极客时间打开某一课程
```
https://time.geekbang.org/course/detail/168-68568
```
其中168是courseId

##### cookie获取
自行google获取浏览器cookie方法.

#### 3.执行下载
```
  geektime-dl
```

### havefun