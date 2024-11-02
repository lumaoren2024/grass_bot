获取 id 教程：
### Get UserID
#### https://app.getgrass.io/dashboard (login).
#### F12 / Inspect.
#### Go to Console.
#### Type: localStorage.getItem('userId') and press Enter.
#### Replace 'your_user_id_here' in run.py with your UserID.

### 获取用户 ID
#### https://app.getgrass.io/dashboard (登录)。
#### F12 / 检查。
#### 转到控制台。
#### 键入：localStorage.getItem('userId') 并按 Enter。
#### 将 run.py 中的“your_user_id_here”替换为您的用户 ID。

视频教程获取：
https://www.youtube.com/watch?v=AX61w4Ve3B8

修改 user_ids.txt，一行一个 id

修改 proxy_list.txt，单 ip 这个不用修改

开始运行：

1、安装 virtualenv
```bash
pip3 install virtualenv -i https://pypi.tuna.tsinghua.edu.cn/simple/
mkdir myenv
source myenv/bin/activate
```
2、安装组件
```bash
bash pip3.sh
```
3、运行
```bash
python3 grass.py
```
或者
```bash
python3 noproxy_grass.py
```
就是这么简单


