# Step 3: 安装 cIOS236  {#step3}


## 一、关于 IOS36 和 cIOS236

进行安装 IOS、安装系统菜单、安装/删除系统频道、安装 Priiloader 之类的操作，通常需要有较高的权限才能完成。IOS36 正好具备这样的高级权限。

cIOS236 是官方 IOS36 的补丁版本，它能够为自制 APP 提供稳定的高级权限。比如使用 cIOS236 来安装 .wad 文件，极少会出现安装失败的情况。其他推荐优先使用 cIOS236 的 APP 还有：

- Any Region Changer: 改区 APP；
- AnyTitle Deleter MOD: 删除系统频道；
- Priiloader: 防砖 APP。 


## 二、相关文件

| 文件 | 出处 |
| --- | --- |
| Multi-Mod Manager（以下简称 MMM） | <https://gbatemp.net/download/multi-mod-manager.13015> |
| IOS15-64-v257.wad | 通过 NUS Downloader 下载 |
| IOS15-64-v1032.wad | 通过 NUS Downloader 下载 |
| IOS36-64-v3608.wad | 通过 NUS Downloader 下载，MMM 将基于它制作出 cIOS236 |
| cIOS236[36-v3351]-v65535.wad | <https://modmii.github.io> <br/>cIOS236 的安装文件，基于 IOS36-64-v3351 制作 |


## 三、注意事项

- 在 HBC 运行 MMM，如果你的 Wii 和下图一样，-> Load another IOS 后面显示为 IOS236，说明你的 Wii 已经安装过 cIOS236，可以略过本文余下的内容，跳转到[《Step 4: 安装 IOS58》](@ref step4)继续操作：<br/>
  ![](./mmm-cios236-loaded.png)

- 以下三种安装 cIOS236 的方法：
  - 方法 A 只能支持 SD 卡，使用的 IOS36 版本比较新；
  - 方法 B 和方法 C 可以选择 SD 卡或 USB 设备，使用的 IOS36 版本稍微老一丢丢。


## 四、安装方法 A：使用 MMM 安装 cIOS236 

1. 在 HBC 运行 MMM ：<br/>
  ![](./multi-mod-manager.png)

2. 先按遥控器手柄的方向键，使 -> 指向 Load another IOS，然后按 [A] 键：<br/>
  ![](./mmm-load-another-ios.png)

3. 先选中 249，然后按 [A] 键：<br/>
  ![](./mmm-select-cios249.png)

4. 先按方向键，使 -> 指向 Install & Patch IOS36，然后按 [A] 键：<br/>
  ![](./mmm-cios249-loaded.png)

5. 先确认 --> 指向 Express mode，然后按 [A] 键：<br/>
  ![](./mmm-express-mode.png)

6. 耐心等待安装结束：<br/>
  ![](./mmm-install-cios236.png)

7. 按任意键回到 MMM 的主界面，可以看到当前使用的 IOS 为 IOS236:<br/>
  ![](./mmm-cios236-loaded.png)


有了 cIOS236 的加持，我们使用 MMM 的 WAD Manager 或者 Some YAWMM Mod 来安装 .wad 文件，不会再因为权限不足而失败了。正如上文第 6 步最后的提示信息所言：

> You can use it to install anything now.


## 五、安装方法 B：使用 YAWM ModMii Edition 安装 cIOS236

使用 YAWM ModMii Edition 来安装 `wad` 文件夹里的 cIOS236[36-v3351]-v65535.wad，可参考[《Step 2: 安装 USB Loader 使用的 cIOS》](@ref step2)中的操作步骤：

![](./yawmME-select-cios236.png)


## 六、安装方法 C：使用 Some YAWMM Mod 安装 cIOS236

使用 Some YAWMM Mod 来安装 `wad` 文件夹里的 cIOS236[36-v3351]-v65535.wad，可参考[《安装 USB Loader 使用的 cIOS（2022 版）》](@ref some-yawmm-mod)中的操作步骤：

![](./yawmm-select-cios236.png)
