Alfred 2 的 Workflows
=====================

Mac 用户对 Alfred 都不陌生，如果不知道的，建议到 [官方网址] 进行了解

如果你是开发者，推荐关注 [这个 Github Repo][willfarrell]


Workflows
-------------

### GoAgentX - [Download](https://raw.github.com/lwr/AlfredWorkflows/master/Workflows/GoAgentX.alfredworkflow)

Fast proxy mode switch for [GoAgentX](https://github.com/ohdarling/GoAgentX)

使用说明

* 输入 `gx` 或 `gax` 关键字触发进入
* 输入 `gxp`， `gxg`， `gxs` 或 `gaxp`， `gaxg`， `gaxs`  
  然后回车可以直接切换到【PAC】,【全局】,【独立】模式

TODO

* 关键字输入后能立刻查询到当前的代理状态

**Commands Included:** `gx`, `gax`

![alt text](https://raw.github.com/lwr/AlfredWorkflows/master/Screenshots/GoAgentX.png)

### 节奏大师新版计算器 - [Download](https://raw.github.com/lwr/AlfredWorkflows/master/Workflows/RhythmMaster.alfredworkflow)

纯属娱乐，就不多说明了，直接看后面的截图吧

* 输入 `rm <combo 数量>` 触发

TODO

* 输入歌名和难度比如 4KH 直接查询

**Commands Included:** `rm`

![alt text](https://raw.github.com/lwr/AlfredWorkflows/master/Screenshots/RhythmMaster.png)

### Youdao Translate - [Download](https://raw.github.com/lwr/AlfredWorkflows/master/Workflows/Youdao Translate.alfredworkflow)
by [@Aether](http://aetherwu.com)

使用有道词典快速查找中英文单词，并可以直接回车从浏览器中查看详细结果

修改历史

  * 添加自定义快捷键，当在任意地方选好单词按下 `CMD+Shift+Y` 后即调出词有道翻译
  * *2013-12-03* 修正查找中文单词使用浏览器打开会出现乱码的问题 by [@lwr]
  * *2013-12-03* 添加使用【爱词霸】打开选项，通过 ALT 键触发 by [@lwr]

**Commands Included:** `yd {query}`

![alt text](https://raw.github.com/lwr/AlfredWorkflows/master/Screenshots/Youdao Translate.png)


### [Dash](https://github.com/willfarrell/alfred-dash-workflow) ([Download](https://raw.github.com/willfarrell/alfred-dash-workflow/master/Dash.alfredworkflow))
by [@willfarrell](https://github.com/willfarrell)

[Dash](http://kapeli.com/) comes with default Alfred 2 Workflow. This is an extension to that by shortening the keyword filters for each language. Does not require online connection.

**Commands Included:** `dash {query}` (default), `html {query}`, `css {query}`, `js {query}`, `jquery {query}`, `angularjs {query}`, `bootstrap {query}`, `svg {query}`, `nodejs {query}`, `php {query}`, `redis {query}`, `mysql {query}`, `cpp {query}`, `backbone {query}`, `underscore {query}`, `sass {query}`, `compass {query}`, `wordpress {query}`, `drupal {query}`

![alt text][dash]


### [Kill Process](https://github.com/nathangreenstein/alfred-process-killer) ([Download](https://github.com/nathangreenstein/alfred-process-killer/raw/master/Kill%20Process.alfredworkflow))
by [@nathangreenstein](https://github.com/nathangreenstein)

`kill {query}`

![alt text][kill]

### [Encode / Decode](https://github.com/willfarrell/alfred-encode-decode-workflow) ([Download](https://raw.github.com/willfarrell/alfred-encode-decode-workflow/master/encode-decode.alfredworkflow))
by [@willfarrell](https://github.com/willfarrell)

Using the keywords `encode {query}` or `decode {query}`, will transform your query strings through *base64*, *html*, *url*, and *utf-8* encode/decode. Pressing enter will copy the encoded/decoded string to the clipboard.

![alt text][encode]

Links
-------
* [Alfred 官方网址][官方网址]
* [开发者使用的 Workflow][willfarrell]
* [87年的脚本](http://loveb.in/?s=alfred) - [失效的连接](http://v2ex.me/alfred-workflow-share)
* [AlfredWorkflow.com](http://www.alfredworkflow.com/) - [Github](https://github.com/hzlzh/AlfredWorkflow.com)

[官方网址]:    http://alfredapp.com "Alfred 官方网址"
[willfarrell]: https://github.com/willfarrell/alfred-workflows "Alfred Workflows for Developers"
[@lwr]:        https://github.com/lwr

[dash]: https://raw.github.com/willfarrell/alfred-dash-workflow/master/screenshots/dash.png  "Sample result"
[kill]: https://github.com/nathangreenstein/alfred-process-killer/raw/master/screenshot1.png "Sample kill result"
[encode]: https://raw.github.com/willfarrell/alfred-encode-decode-workflow/master/screenshots/encode.png  "Sample result"
