# AstrBot_Plugins_Collection

AstrBot Plugin 插件集合站，用于在 AstrBot 仪表盘-插件页中作为插件市场显示。

## 提交插件

1. Fork 本仓库
2. 修改 `plugins.json` 文件，添加你的插件信息
   1. key 为你的插件名
   2. value 为插件信息，必须包括 `repo`, `desc`, `author` 等字段。
   3. 例子：
      ```json
      "astrbot_plugin_essential": {
        "desc": "随机动漫图片、以图搜番、Minecraft服务器、一言、今天吃什么、群早晚安记录、EPIC喜加一。帮助：https://github.com/Soulter/astrbot_plugin_essential",
        "author": "Soulter",
        "repo": "https://github.com/Soulter/astrbot_plugin_essential"
      }
      ```