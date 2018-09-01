## 如何使用Sublime Text 3作为Markdown编辑器
###1安装Markdown Preview 插件
输入 Shift + Ctrl + P，输入pcip（也可以点击 Preferences --> 选择 Package Control: ，然后输入install），然后在插件库中分别选择安装Markdown Preview；
###2自定义快捷键

直接在浏览器中预览效果的话，可以自定义快捷键：点击 Preferences --> 选择 Key Bindings User，输入：

{ "keys": ["alt+m"], "command": "markdown_preview", "args": {"target": "browser", "parser":"markdown"} },

保存后，直接输入快捷键：Alt + M 就可以直接在浏览器中预览生成的HTML文件了。