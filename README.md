# godotPrebuildApks
专门编译用于Godot导出的预编译apk资源包。

@GenOuka

**请为本仓库点个Star吧！**

## 对于用户的使用方法

**推荐在手机上使用Godot导出助手（开发者GenOuka），自动完成以下所有过程，现在正在积极开发中。**

目前软件可以在QQ群获取：517549773

1. 从[本项目 Releases](https://github.com/Genouka/godotPrebuildApks/releases)下载对于你Godot项目创建的版本的apk。
2. 使用MT管理器、APK编辑器、apk-signer或同类应用，把你的项目直接复制进apk中的assets文件夹。
3. 在上述应用中修改应用信息、签名、可能还需要对齐后即可分享给别人使用。

## 使用本项目编译预编译包的方法
一般无需自行编译，直接从本项目的Release中获取相关包即可。如果确实需要，请查看以下步骤：

1. fork本项目，启用Github Action功能。
2. 发布Release包，tag填写Godot相应版本的名称即可。（详见[Godot Release库](https://github.com/godotengine/godot-builds/releases/)），与其tag保持一致即可。
3. 等待10分钟以内，Github Action会自动生成预编译包，并发布到Release。
4. 如果生成失败，请前往Github Action查看详细信息。如果你可以解决，记得回来为本项目提交pr和issue，感激不尽！

## 开源许可证
见LICENSE文件。
