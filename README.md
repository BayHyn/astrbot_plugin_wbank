
<div align="center">

![:name](https://count.getloli.com/@astrbot_plugin_wbank?name=astrbot_plugin_wbank&theme=minecraft&padding=6&offset=0&align=top&scale=1&pixelated=1&darkmode=auto)

# astrbot_plugin_wbank

_✨ [astrbot](https://github.com/AstrBotDevs/AstrBot) 词库插件 ✨_  

[![License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Python 3.10+](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org/)
[![AstrBot](https://img.shields.io/badge/AstrBot-3.4%2B-orange.svg)](https://github.com/Soulter/AstrBot)
[![GitHub](https://img.shields.io/badge/作者-Zhalslar-blue)](https://github.com/Zhalslar)

</div>

## 🤝 介绍

动态词库，自定义回复词

## 📦 安装

- 可以直接在astrbot的插件市场搜索astrbot_plugin_wbank，点击安装，耐心等待安装完成即可
- 若是安装失败，可以尝试直接克隆源码：

```bash
# 克隆仓库到插件目录
cd /AstrBot/data/plugins
git clone https://github.com/Zhalslar/astrbot_plugin_wbank

# 控制台重启AstrBot
```

## ⌨️ 使用说明

### 命令表

| 命令             | 功能说明                                       |
|------------------|------------------------------------------------|
| 添加词条 关键词 内容     | 向指定关键词添加一个新的词条（回复内容）                 |
| 删除词条 关键词 序号     | 删除某个关键词下指定序号的词条                          |
| 删除关键词 关键词1 关键词2 | 删除整个关键词及其所有词条                            |
| 设置别名 关键词 别名1 别名2 | 为某个关键词设置别名，可用于触发相同回复                 |
| 启用关键词 关键词 群1 群2  | 启用某关键词在指定群聊中可触发                         |
| 禁用关键词 关键词 群1 群2 | 禁用某关键词在指定群聊中触发                          |
| 查看词条 关键词         | 查看某个关键词下的所有词条、别名和启用的群聊             |
| 查看所有关键词           | 查看当前存在的所有关键词（别名 `查看所有词条` 也可触发） |


### 示例图

![13bfe1bb4cca835fff78beef843ef0a](https://github.com/user-attachments/assets/552c12ab-812a-4235-a543-2d20f73ff3db)


### 直接编辑词库

词库存储在“data\plugin_data\astrbot_plugin_wbank\default_word_bank.json”，可直接打开编辑（建议用编程软件编辑，不要用记事本）

## 👥 贡献指南

- 🌟 Star 这个项目！（点右上角的星星，感谢支持！）
- 🐛 提交 Issue 报告问题
- 💡 提出新功能建议
- 🔧 提交 Pull Request 改进代码

## 📌 注意事项

- 想第一时间得到反馈的可以来作者的插件反馈群（QQ群）：460973561（不点star不给进）
