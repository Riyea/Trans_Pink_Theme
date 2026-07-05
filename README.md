# Trans Pink Theme for JetBrains IDEs  
# JetBrains IDE 跨旗粉主题

A soft trans-flag pink Islands-style theme for JetBrains IDEs.  
一款柔和的跨性别旗帜粉色 JetBrains IDE 主题，适合 IDEA、PyCharm、WebStorm 等 JetBrains IDE 使用。

The theme includes two variants:  
本主题包含两套配色：

- **Trans Pink Light**
- **Trans Pink Dark**

The main accent color is based on the transgender flag pink: `#F5A9B8`.  
主题强调色使用跨性别旗帜粉色：`#F5A9B8`。

---

## Preview / 预览

You can add screenshots here.  
你可以在这里添加主题截图。

```md
![Trans Pink Dark Preview](screenshots/dark-preview.png)
![Trans Pink Light Preview](screenshots/light-preview.png)
```

---

## Installation / 安装方法

1. Download `Trans_Pink_Theme.jar` from the Releases page.  
   从 Releases 页面下载 `Trans_Pink_Theme.jar`。

2. Open your JetBrains IDE.  
   打开你的 JetBrains IDE。

3. Go to:  
   进入：

```text
Settings / Preferences → Plugins
```

4. Click the gear icon and choose:  
   点击齿轮图标，选择：

```text
Install Plugin from Disk...
```

5. Select `Trans_Pink_Theme.jar`.  
   选择 `Trans_Pink_Theme.jar`。

6. Restart the IDE.  
   重启 IDE。

7. Go to:  
   进入：

```text
Settings / Preferences → Appearance & Behavior → Appearance → Theme
```

8. Select one of the following themes:  
   选择以下主题之一：

```text
Trans Pink Light
Trans Pink Dark
```

---

## Theme Design / 主题设计说明

This theme is designed around a soft gray-pink Islands-style UI.  
本主题围绕柔和的灰粉色岛状 UI 设计。

The dark version uses a calm deep-gray editor surface with lighter gray gaps around panels.  
深色版本使用冷静的深灰代码区，并用较浅灰色作为分区之间的底层背景。

The light version keeps the editor, project header, and tab area clean and white.  
浅色版本让代码区、项目标题区和标签栏保持统一的干净白色。

The pink accent is used only for focus, tabs, borders, selection highlights, and important UI states.  
粉色强调色只用于焦点、标签、边框、选中状态和重要 UI 状态，避免大面积粉色影响阅读。

---

## Color Variables / 代码颜色变量说明

The theme source uses semantic color names.  
主题代码使用语义化颜色变量名。

Each variable means “where this color is used,” not just “what the color looks like.”  
每个变量名表示“这个颜色用在哪里”，而不只是“这个颜色长什么样”。

### Shared Colors / 共用颜色

| Variable / 变量名 | HEX | RGB | Meaning / 含义 |
|---|---:|---:|---|
| `PINK` | `#F5A9B8` | `rgb(245, 169, 184)` | Main accent color. Used for focused borders, active tabs, caret, highlights, and selected UI states. 主强调色，用于焦点边框、活动标签、光标、高亮和选中状态。 |
| `BLUE` | `#5BCEFA` | `rgb(91, 206, 250)` | Link and secondary accent color from the transgender flag blue. 用作链接色和辅助强调色，来自跨旗蓝色。 |

---

## Dark Theme Colors / 深色主题颜色

### Dark Color Variables / 深色变量说明

| Variable / 变量名 | HEX | RGB | Meaning / 含义 |
|---|---:|---:|---|
| `DARK_OUTER` | `#303033` | `rgb(48, 48, 51)` | The outermost background and gaps around Islands panels. It is the gray visible between rounded sections. 最底层背景和岛状分区之间的缝隙颜色，也就是圆角分区外面看到的灰色。 |
| `DARK_SURFACE` | `#242528` | `rgb(36, 37, 40)` | Main working surface. Used for editor body, project body, run console body, project header, and active editor tab area. 主工作区颜色，用于代码区、项目区 body、运行控制台 body、“项目”标题区域和 `Main.java` 标签区域。 |
| `DARK_ROW` | `#303033` | `rgb(48, 48, 51)` | Current line / caret row color in the editor. It is slightly different from the editor body so the active line is visible. 当前行颜色，用于代码区光标所在行，让选中行和普通背景有一点区分。 |
| `DARK_CARD` | `#38383B` | `rgb(56, 56, 59)` | Card-like controls such as buttons, input fields, combo boxes, menus, and popups. 卡片控件颜色，用于按钮、输入框、下拉框、菜单和弹窗。 |
| `DARK_BORDER` | `#50464B` | `rgb(80, 70, 75)` | Borders for cards, inputs, popups, inactive tabs, and subtle dividers. 边框颜色，用于卡片、输入框、弹窗、非活动标签和细分割线。 |
| `DARK_TEXT` | `#F7EEF2` | `rgb(247, 238, 242)` | Main text color on dark backgrounds. 深色背景上的主要文字颜色。 |

### Dark Theme Usage / 深色主题使用位置

| UI Area / 界面区域 | Color / 颜色 |
|---|---|
| Outermost window background / 最底层窗口背景 | `DARK_OUTER` / `#303033` |
| Island gaps / 岛状分区之间的缝隙 | `DARK_OUTER` / `#303033` |
| Editor body / 代码区主体 | `DARK_SURFACE` / `#242528` |
| Project tree body / 项目树主体 | `DARK_SURFACE` / `#242528` |
| Run console body / 运行控制台主体 | `DARK_SURFACE` / `#242528` |
| Project header “项目” / 项目标题区域 | `DARK_SURFACE` / `#242528` |
| Editor tab area such as `Main.java` / 编辑器标签区域 | `DARK_SURFACE` / `#242528` |
| Current editor line / 当前代码行 | `DARK_ROW` / `#303033` |
| Buttons and input fields / 按钮和输入框 | `DARK_CARD` / `#38383B` |
| Focused borders and active highlights / 焦点边框和活动高亮 | `PINK` / `#F5A9B8` |
| Links / 链接 | `BLUE` / `#5BCEFA` |

---

## Light Theme Colors / 浅色主题颜色

### Light Color Variables / 浅色变量说明

| Variable / 变量名 | HEX | RGB | Meaning / 含义 |
|---|---:|---:|---|
| `LIGHT_OUTER` | `#F0E6EB` | `rgb(240, 230, 235)` | Outer background around Islands panels. Used for the soft page-like base outside main sections. 岛状分区外面的底层背景色，用于主要分区外的柔和页面底色。 |
| `LIGHT_SURFACE` | `#FFFBFC` | `rgb(255, 251, 252)` | Main working surface. Used for editor body, project body, run console body, project header, and active editor tab area. 浅色主工作区颜色，用于代码区、项目区 body、运行控制台 body、“项目”标题区域和 `Main.java` 标签区域。 |
| `LIGHT_ROW` | `#FFF1F5` | `rgb(255, 241, 245)` | Current line, hover, and soft selected-row background. 当前行、悬停和柔和选中行背景。 |
| `LIGHT_CARD` | `#FFFFFF` | `rgb(255, 255, 255)` | Card-like controls such as buttons, input fields, combo boxes, menus, and popups. 卡片控件颜色，用于按钮、输入框、下拉框、菜单和弹窗。 |
| `LIGHT_BORDER` | `#E8D5DB` | `rgb(232, 213, 219)` | Borders for cards, inputs, popups, inactive tabs, and subtle dividers. 边框颜色，用于卡片、输入框、弹窗、非活动标签和细分割线。 |
| `LIGHT_TEXT` | `#2B2528` | `rgb(43, 37, 40)` | Main text color on light backgrounds. 浅色背景上的主要文字颜色。 |

### Light Theme Usage / 浅色主题使用位置

| UI Area / 界面区域 | Color / 颜色 |
|---|---|
| Outermost window background / 最底层窗口背景 | `LIGHT_OUTER` / `#F0E6EB` |
| Editor body / 代码区主体 | `LIGHT_SURFACE` / `#FFFBFC` |
| Project tree body / 项目树主体 | `LIGHT_SURFACE` / `#FFFBFC` |
| Run console body / 运行控制台主体 | `LIGHT_SURFACE` / `#FFFBFC` |
| Project header “项目” / 项目标题区域 | `LIGHT_SURFACE` / `#FFFBFC` |
| Editor tab area such as `Main.java` / 编辑器标签区域 | `LIGHT_SURFACE` / `#FFFBFC` |
| Current editor line / 当前代码行 | `LIGHT_ROW` / `#FFF1F5` |
| Buttons and input fields / 按钮和输入框 | `LIGHT_CARD` / `#FFFFFF` |
| Focused borders and active highlights / 焦点边框和活动高亮 | `PINK` / `#F5A9B8` |
| Links / 链接 | `BLUE` / `#5BCEFA` |

---

## Important UI Keys / 重要 UI 配置项说明

These keys are used in the theme JSON files.  
这些配置项写在主题的 JSON 文件中。

### Islands UI / 岛状 UI

| Key / 配置项 | Meaning / 含义 |
|---|---|
| `parentTheme: "Islands Dark"` | Makes the dark theme inherit JetBrains Islands-style rounded panels. 让深色主题继承 JetBrains 的岛状圆角分区风格。 |
| `parentTheme: "Islands Light"` | Makes the light theme inherit JetBrains Islands-style rounded panels. 让浅色主题继承 JetBrains 的岛状圆角分区风格。 |
| `Island.arc` | Controls the roundness of Islands panels. 控制岛状分区的圆角大小。 |
| `Island.borderWidth` | Controls spacing between Islands panels. 控制岛状分区之间的间距。 |
| `Island.borderColor` | Controls the color visible between Islands panels. 控制岛状分区缝隙处显示的颜色。 |
| `Island.inactiveAlpha` | Controls the transparency of inactive Islands panels. This theme sets it to `1.0` to keep panels opaque. 控制非活动分区透明度。本主题设为 `1.0`，让分区保持不透明。 |

### Main Window / 主窗口

| Key / 配置项 | Meaning / 含义 |
|---|---|
| `MainWindow.background` | The outermost IDE window background. IDE 最底层窗口背景。 |
| `MainToolbar.background` | Top toolbar background. 顶部工具栏背景。 |
| `ToolWindow.Stripe.background` | Side tool-window stripe background. 侧边工具栏背景。 |
| `StatusBar.background` | Bottom status bar background. 底部状态栏背景。 |

### Project / Tool Window / 项目区与工具窗口

| Key / 配置项 | Meaning / 含义 |
|---|---|
| `ToolWindow.background` | Main tool window body background, such as the Project panel. 工具窗口主体背景，例如项目面板。 |
| `ToolWindow.Header.background` | Tool window header background, such as the “项目” title area. 工具窗口标题栏背景，例如“项目”区域。 |
| `ToolWindow.Content.background` | Tool window content background. 工具窗口内容区域背景。 |
| `ToolWindow.LeftToolbar.background` | Left-side toolbar inside tool windows, such as the Run panel toolbar. 工具窗口内部左侧工具栏背景，例如运行窗口左侧按钮栏。 |
| `Tree.background` | Project file tree background. 项目文件树背景。 |

### Editor / 编辑器

| Key / 配置项 | Meaning / 含义 |
|---|---|
| `Editor.background` | Main editor background. 主代码编辑区背景。 |
| `EditorPane.background` | Editor pane container background. 编辑器容器背景。 |
| `Editor.gutter.background` | Gutter background beside line numbers. 行号旁边 gutter 区域背景。 |
| `Editor.caretRowBackground` | Current line background. 当前代码行背景。 |
| `EditorTabs.background` | Editor tab bar background. 编辑器标签栏背景。 |
| `EditorTabs.selectedBackground` | Active editor tab background. 当前打开标签页背景。 |
| `EditorTabs.underlineColor` | Active tab underline color. 当前标签页下划线颜色。 |

### Run Console / 运行控制台

| Key / 配置项 | Meaning / 含义 |
|---|---|
| `RunToolbar.background` | Run tool window toolbar background. 运行窗口工具栏背景。 |
| `RunWidget.background` | Run widget background. 运行控件背景。 |
| `Console.background` | Console background. 控制台背景。 |
| `ConsoleView.background` | Console view background. 控制台显示区域背景。 |
| `CONSOLE_BACKGROUND` | Console background in the editor color scheme. 颜色方案中的控制台背景。 |
| `CONSOLE_NORMAL_OUTPUT` | Normal console output text style. 普通控制台输出文字样式。 |
| `CONSOLE_SYSTEM_OUTPUT` | System console output text style, often used for messages like “Process finished with exit code 0”. 系统控制台输出文字样式，常用于“进程已结束，退出代码为 0”这类提示。 |
| `CONSOLE_USER_INPUT` | User input text style in console. 控制台用户输入文字样式。 |
| `CONSOLE_ERROR_OUTPUT` | Error output text style in console. 控制台错误输出文字样式。 |

---

## Full Color Palette / 完整颜色表

| Name / 名称 | HEX | RGB |
|---|---:|---:|
| Trans Pink Accent / 跨旗粉强调色 | `#F5A9B8` | `rgb(245, 169, 184)` |
| Trans Blue Link / 跨旗蓝链接色 | `#5BCEFA` | `rgb(91, 206, 250)` |
| Dark Outer Gray / 深色底层灰 | `#303033` | `rgb(48, 48, 51)` |
| Dark Surface Gray / 深色主工作区灰 | `#242528` | `rgb(36, 37, 40)` |
| Dark Card Gray / 深色卡片灰 | `#38383B` | `rgb(56, 56, 59)` |
| Dark Border Gray Pink / 深色灰粉边框 | `#50464B` | `rgb(80, 70, 75)` |
| Dark Text Pink White / 深色文字粉白 | `#F7EEF2` | `rgb(247, 238, 242)` |
| Light Outer Pink Gray / 浅色底层粉灰 | `#F0E6EB` | `rgb(240, 230, 235)` |
| Light Surface White / 浅色主工作区白 | `#FFFBFC` | `rgb(255, 251, 252)` |
| Light Soft Pink Row / 浅色当前行粉 | `#FFF1F5` | `rgb(255, 241, 245)` |
| Light Card White / 浅色卡片白 | `#FFFFFF` | `rgb(255, 255, 255)` |
| Light Border Pink Gray / 浅色粉灰边框 | `#E8D5DB` | `rgb(232, 213, 219)` |
| Light Text / 浅色文字 | `#2B2528` | `rgb(43, 37, 40)` |

---

## Repository Structure / 仓库结构

Recommended repository structure:  
推荐仓库结构：

```text
Trans_Pink_Theme/
├─ README.md
├─ LICENSE
└─ Trans_Pink_Theme.jar
```

You can also upload `Trans_Pink_Theme.jar` to GitHub Releases instead of putting it directly in the repository.  
也可以把 `Trans_Pink_Theme.jar` 上传到 GitHub Releases，而不是直接放在仓库根目录。

---

## Compatibility / 兼容性

This theme is designed for JetBrains IDEs that support custom theme plugins.  
本主题适用于支持自定义主题插件的 JetBrains IDE。

The Islands-style rounded panels work best on newer JetBrains IDE versions with Islands Theme support.  
岛状圆角分区效果在支持 Islands Theme 的新版 JetBrains IDE 中效果最好。

---

## License / 许可证

MIT License
