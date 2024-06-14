# Markdown Extension Examples

This page demonstrates some of the built-in markdown extensions provided by VitePress.

## Syntax Highlighting

VitePress provides Syntax Highlighting powered by [Shiki](https://github.com/shikijs/shiki), with additional features like line-highlighting:

**Input**

````md
```js{4}
export default {
  data () {
    return {
      msg: 'Highlighted!'
    }
  }
}
```
````

**Output**

```js{4}
export default {
  data () {
    return {
      msg: 'Highlighted!'
    }
  }
}
```

## Custom Containers

**Input**

```md
::: info
This is an info box.
:::

::: tip
This is a tip.
:::

::: warning
This is a warning.
:::

::: danger
This is a dangerous warning.
:::

::: details
This is a details block.
:::
```

**Output**

::: info
This is an info box.
:::

::: tip
This is a tip.
:::

::: warning
This is a warning.
:::

::: danger
This is a dangerous warning.
:::

::: details
This is a details block.
:::

## More

Check out the documentation for the [full list of markdown extensions](https://vitepress.dev/guide/markdown).

## Unicode Emoji

| **图标** | **描述** | **图标** | **描述** | **图标** | **描述** |
| --- | --- | --- | --- | --- | --- |
| 📌 | 圆形图钉 | 📍 | 圆形目标 | 📎 | 回形针 |
| 🔗 | 链接符号 | 📏 | 直尺 | 📐 | 三角尺 |
| ✂️ | 剪刀 | 🖌️ | 画笔 | 🖋️ | 钢笔 |
| 🗂️ | 索引卡 | 🗒️ | 螺旋笔记本 | 📓 | 彩色笔记本 |
| 📔 | 封皮笔记本 | 📕 | 闭合的书籍 | 📖 | 打开的书 |
| 📚 | 书本堆 | 🔍 | 放大镜（放大） | 🔎 | 放大镜（缩小） |
| 💡 | 电灯泡 | 🔑 | 钥匙 | 🗝️ | 钥匙孔 |
| 🔐 | 锁 | 🌐 | 地球 | 🌙 | 新月 |
| 🌟 | 闪亮的星星 | 🌠 | 流星 | 🌈 | 彩虹 |
| 📱 | 手机 | 💻 | 笔记本电脑 | 🎓 | 学位帽 |
| 🎨 | 调色板 | 🎧 | 耳机 | 🎤 | 麦克风 |
| 🎼 | 音乐谱号 | 🎵 | 音乐笔记 | 🎶 | 多个音乐笔记 |
| 📞 | 电话 | 🚀 | 火箭 | 🛸 | 飞碟 |
| 💼 | 公文包 | 📦 | 箱子 | 📱 | 手机2 |
| 🔋 | 电池 | 🔌 | 电源插头 | 💻 | 笔记本电脑2 |
| 🖥️ | 桌面电脑 | 📱 | 手机3 | 📱 | 手机4 |
| 🔧 | 扳手 | 🛠️ | 锤子 | 🔩 | 螺母 |
| 🔨 | 锤子2 | 🪓 | 剪刀2 | 🧱 | 砖块 |
| 🏗️ | 建筑工地 | 🏢 | 办公大楼 | 🏗️ | 建筑工地2 |
| 🚪 | 门 | 🪟 | 窗户 | 🛏️ | 床 |
| 🛋️ | 沙发 | 🖇️ | 回形针2 | 🔑 | 钥匙2 |
| 🗅 | 圆环 | 🔗 | 链接符号2 | 📌 | 图钉2 |
| 📏 | 直尺2 | 📐 | 三角尺2 | 🖇️ | 回形针3 |
| 🎓 | 学位帽2 | 🎨 | 调色板2 | 🎧 | 耳机2 |
| 🎤 | 麦克风2 | 🎼 | 音乐谱号2 | 🎵 | 音乐笔记2 |
| 🎶 | 多个音乐笔记2 | 📞 | 电话2 | 🚀 | 火箭2 |
| 🛸 | 飞碟2 | 🏞 | 国家公园 | 🏝️ | 无人岛 |
| 🌄 | 日出 | 🌅 | 日落 | 🌃 | 夜晚的城市 |
| 🌆 | 城市天际线 | 🌇 | 夕阳下的天际线 | 🌉 | 夜晚的桥 |
| ⛰️ | 山 | 🏕️ | 露营 | 🏞️ | 国家公园2 |
| 🌈 | 彩虹2 | 🎡 | 摩天轮 | 🎢 | 过山车 |
| 🏗️ | 建筑起重机 | 🏰 | 城堡 | 💒 | 婚礼教堂 |
| 🗽 | 自由女神像 | 🗼 | 埃菲尔铁塔 | 🏰 | 城堡2 |
