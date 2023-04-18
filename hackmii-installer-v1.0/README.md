# 使用 HackMii Installer v1.0


## 一、启动界面

HackMii Installer 启动之后会出现以下的界面：

![](./hmiv1.0-startup.png)

正常情况下，等待 30 秒之后，界面下方就会出现提示语，按遥控器手柄的按键 [1] 继续：

![](./hmiv1.0-press-1-to-continue.png)


## 二、测试结果界面

![](./hmiv1.0-bootmii-as-ios-only.png)

上图为测试结果界面，它显示了以下三项测试结果：

1. Using IOS versions 后面的数字可能是 37，也可能是其他数字，代表了 Homebrew Channel 安装完成之后会使用哪个 IOS 运行；

2. The Homebrew Channel 后面总是 Can be installed；

3. 市面上绝大部分机型的 BootMii 检测结果都是 Can only be installed as an IOS。

早期的日版主机存在一个漏洞，姑且将其称为 boot2 漏洞，通过这个漏洞，我们可以使用 BootMii 在 Wii 上面安装（欧美日韩）任意一区，任意版本的系统，而且可以 100% 防砖。民间将这种机型的 Wii 称为：神机。

神机的测试结果界面是这样的：

![](./hmiv1.0-bootmii-as-boot2.png)

测试结果界面没有其他操作入口，按遥控器手柄的 [A] 键继续。


## 三、安装 Homebrew Channel 1.1.0

1. 先通过遥控器手柄的方向键，选择 Install The Homebrew Channel，然后按 [A] 键：
  ![](./hmiv1.0-install-hbc.png)

2. 选择 Yes, continue，按 [A] 键：
  ![](./hmiv1.0-yes-continue.png)

3. 等待安装结束，按 [A] 键：
  ![](./hmiv1.0-install-hbc-success.png)

4. 选择 Exit，按 [A] 键，退出 HackMii Installer 之后会自动进入 HBC：
  ![](./hmiv1.0-exit.png)

5. 在 HBC 界面按遥控器手柄的 [HOME] 键，可以在画面的右上角看到 HBC 的版本号为 1.1.0：
  ![](./hmiv1.0-hbc-1.1.0.png)


后面我们还会把 HBC 升级到 1.1.2，到时再一起安装 BootMii。