# Arctic Fuse 2 Touch

Arctic Fuse 2 的界面，叠一层适合手机 / 平板的触控。

基于 [jurialmunkey / Arctic Fuse 2](https://github.com/jurialmunkey/skin.arctic.fuse.2) `2.12.12`，许可证 CC BY-NC-SA 4.0。

插件 id 仍是 `skin.arctic.fuse.2`：从 zip 安装会覆盖原版，皮肤设置和小部件会保留。显示名为 **Arctic Fuse 2 Touch**，版本 `2.12.12.1`。

## 下载

到 [Releases](https://github.com/xiaojiu885210-arch/skin.arctic.fuse.2.touch/releases) 下这两个文件：

| 文件 | 用途 |
| --- | --- |
| `skin.arctic.fuse.2-2.12.12.touch.zip` | **唯一能在 Kodi 里从 zip 安装的包（约 64MB）。** |
| `AF2-Touch-XML-overlay.zip` | 手工覆盖用的 XML。**不能从 zip 安装**，Kodi 会提示无法安装。 |

## 安装完整包

1. 把 `skin.arctic.fuse.2-2.12.12.touch.zip` 拷到手机 / 平板 / 盒子
2. Kodi → 插件 → 从 zip 文件安装
3. 装完把皮肤切到 **Arctic Fuse 2 Touch**
4. 依赖和原版一样：TMDb Helper、Skin Variables、TextureMaker

## 这版动了什么

**没动的（界面还是 AF2）：** 配色、字体、组件、小部件排版、主页侧栏展开动画、播放 OSD 按钮造型。遥控照常用。

**加上的（Estouchy 的操控逻辑）：**

- 底部触控条：返回 / 主页 / 侧栏 / 更多 / 搜索 / 视图（用 AF2 自己的圆形图标，放在底部本来空着的位置）
- 主页侧栏可点开（原版要遥控先聚焦才显示）
- 分类标签可点（原版把点击区域设成了 0）
- 全屏播放可拖进度；左上主页、右上关闭

只用遥控：皮肤设置里打开「隐藏触控条」。

## 仓库里是什么

Git 里只有改过的 XML / 语言文件（`xml-overlay/`），没有 19MB 贴图。完整可安装包在 Release 附件里。
