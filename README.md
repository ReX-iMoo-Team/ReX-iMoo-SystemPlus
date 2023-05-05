# ReX-iMoo-SystemPlus
- 小天才系统优化模块(ReX-iMoo-SystemPlus)由chalk与ReX Wear论坛的面向小天才破解的组织ReX iMoo Team研发

# 作用
 - 通过userdebug解除非法安装限制；
 - 修复运行库还原Android原生功能：
   - 系统级恢复旋屏功能；
   - 黑暗模式；
   - 剪贴板；
   - aosp原生应用；
   - 系统级圆形图标
   
# 构建
  - 为了适配不同的机型，该模块的构建较为复杂，因此我们为Unix用户以及WindowsNT(暂时不支持（因为懒得修改测试））用户提供了构建工具。
  - **☠：该模块在Z8使用会导致桌面无法启动，无限第二屏桌面循环，请Z8用户不要使用该模块！**
  1. 在项目根目录下启动命令行终端；
  2. Unix用户输入`bash make.sh 机型`（经测试，sh不可使用，建议使用bash），WindowsNT用户输入`./make.bat 机型`，回车，支持的机型：
      - z6dfb
      - z7
      - z7a
      - ~~z8~~（Z8使用异常）
      - z8snb
  3. ⚠：实验性功能 如果有使用aosp系统应用的需求，请在命令最后加上`-apps`，如对于z8少年版用户为`bash make.sh z8snb -apps`。
    - 官方不会提供带有aosp系统应用版本的模块，请自行构建。
  4. 打开项目的`./build`目录/文件夹，即可找到build.zip的magisk模块包，可用于刷入。

### 需获取更多详细信息请登录：[ReX Wear](https://wear.rexwe.net/)查看详情。​
