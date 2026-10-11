# ChatGPT Stickers 🐉

**一个可下载、复用、持续扩展的 ChatGPT 主题表情包仓库。**
A community-friendly collection of ChatGPT-inspired stickers and emotes.

> 非 OpenAI 官方项目（Unofficial fan-made project）。本仓库的「知微」是一位原创的白发龙娘虚拟角色。

## 已发布：知微 / Weiwei · White Dragon Girl

银白长发、浅紫色眼睛、白色龙角、小龙翼与龙尾，白紫配色。

| 预览 | 表情 | 场景 | 高清版本 |
|---|---|---|---|
| ![在吗？](stickers/01-zaima.png) | 在吗？ | 打招呼 | [1254 px](originals/01-zaima.png) |
| ![收到！](stickers/02-shoudao.png) | 收到！ | 接收任务 | [1254 px](originals/02-shoudao.png) |
| ![让我想想](stickers/03-xiangxiang.png) | 让我想想 | 思考 | [1254 px](originals/03-xiangxiang.png) |
| ![哼！](stickers/04-heng.png) | 哼！ | 气鼓鼓 | [1254 px](originals/04-heng.png) |
| ![搞定啦](stickers/05-gaoding.png) | 搞定啦 | 完成任务 | [1254 px](originals/05-gaoding.png) |
| ![怎么又是 Excel 啊](stickers/06-excel.png) | 怎么又是 Excel 啊 | 表格崩溃 | [1254 px](originals/06-excel.png) |

## 直接使用 / Usage

打开任意 PNG 保存后，添加到微信、QQ、Discord 等支持自定义表情的软件。
- `stickers/`：透明 PNG 聊天版（512×512）
- `originals/`：高分辨率 PNG（1254×1254，经过调色板压缩优化，非未处理的生成源文件）
- `index.json`：可机读的表情索引，包含 ID、文字和相对路径

直接引用示例：

```text
https://raw.githubusercontent.com/Zhangwier/chatgpt-stickers/main/stickers/01-zaima.png
```

访问 `index.json`，根据 `base_url + stickers[].file` 获取完整图片 URL。GitHub 原始图片链接需联网；聊天客户端是否支持外链内嵌，由客户端决定。

## 自由使用与贡献 / Contributing

欢迎下载并用于个人日常聊天，也欢迎通过 Issue 提交新表情点子、修图反馈或建议。仓库计划继续扩展其他 ChatGPT/AI 主题角色和表情系列。

目前没有为素材指定完整的商用或再分发授权许可证；请勿将此仓库视为 OpenAI 官方素材库，商业或批量再发布使用请联系仓库所有者确认。

本仓库保留已有稳定文件名和 URL；扩展新系列时优先使用 `packs/<series>/`，并更新 `index.json`。
