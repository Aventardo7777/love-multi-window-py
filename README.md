# Python Tkinter 多窗口表白程序
## 项目概述
基于Python内置Tkinter GUI库+多线程threading开发的表白特效程序。
运行后自动弹出全屏粉色爱心主窗口，同时批量生成100个随机位置弹窗，弹窗内显示「我喜欢你」文字，适合告白趣味小工具。
仅使用Python自带标准库，无需pip安装第三方包，Windows/Mac/Linux均可运行。

## 核心功能特性
- ❤ 全屏居中超大爱心主窗口，粉色字体视觉突出
- 💬 批量生成100个随机屏幕位置弹窗，互不阻塞
- 🔄 多线程并行运行，窗口同步弹出不卡顿
- 🖥 自动获取本机屏幕宽高，自适应任意分辨率显示器
- 🧩 零第三方依赖，原生tkinter、random、threading、time库

## 运行环境要求
Python 3.x 版本
- Windows系统：默认自带tkinter，直接运行
- Mac系统：需提前安装tk（brew install python-tk）
- Linux系统：sudo apt install python3-tk

## 本地启动步骤
1. 克隆仓库到本地
git clone https://github.com/Aventardo7777/love-multi-window-py.git
2. 进入项目文件夹，执行脚本
python 多窗口.py
3. 运行后立刻弹出全屏爱心窗口，间隔 0.1 秒依次弹出 100 个表白弹窗

## 项目文件结构
<img width="684" height="168" alt="image" src="https://github.com/user-attachments/assets/639174b7-7bd3-47a4-9c37-6e15150b7144" />

## 代码可自定义修改点
1.range(100)：修改数字调整弹窗总数量
2.ti.sleep(0.1)：修改数值调整弹窗弹出间隔，数字越小弹出越快
3.text='我喜欢你'：替换文字自定义表白内容
4.字体、窗口大小、背景颜色均可自行修改参数

## 开源协议
本项目采用 MIT 开源协议，允许自由学习、修改、二次分发使用。
