# gobang
网络五子棋游戏项目
# 项目简介
本项目为网络五子棋游戏，能够实现用户之间两两联网对战，也可以进行人机对战，对战中可以聊天，非对战用户可以在房间观战，并可以发送聊天信息，非联网状态下可以进行单机人机对战。
# 主要功能
## 网络模式
用户注册
用户登录
选择房间进行对战
聊天功能
人人对战
人机对战
设置游戏界面风格
## 单机模式
人机对战
设置游戏界面风格
# 功能描述
## 用户的注册和登录
### 用户注册
用户名
密码/确认密码(md5)
昵称
出生日期(用于找回账号密码)
### 用户登录
用户名
密码(md5)
记住密码(用户名和密码md5存储在setting.ini)
忘记密码(找回用户密码)
## 用户信息和在线用户
### 用户信息
用户名
昵称
等级
积分
用户头像
### 在线用户列表
用户昵称
等级
所在房间(大厅/房间)
游戏状态(无/对战/观战/电脑对战)
## 聊天功能
聊天信息，只能在相同位置的用户能够接收到。
可以发送@用户昵称 消息，进行私聊
发送表情
### 聊天字体设置
    字体样式
    字体大小
    粗体
    斜体
    字体颜色
## 用户大厅
用户登录后首先进入游戏大厅
选择房间进行对战
    房间左侧
    房间右侧
    观战
点击快速游戏，自动匹配房间
与电脑对战
创建房间
设置
## 游戏房间
### 人人对战
显示对战双方昵称
对战双方状态(未准备/准备/黑棋/白棋)
游戏用时，20秒倒计时，局累计用时
棋盘，棋子信息
底部功能按钮(开始游戏，悔棋，认输，返回大厅)
### 人机对战
用户和电脑信息
棋盘棋子信息
底部功能按钮(开始游戏)
# 运行环境
Python3.5,第三方库PyQt5==5.10.1
建议用pip3 install pyqt5==5.10.1 ,方法安装pyqt5,否则可能出现import错误
MySQL5.7.22

# 项目成员
李大伟 胡庆焱 李琨 何任杰 王慧 乌琼 林丽君

