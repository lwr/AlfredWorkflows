Alfred 2 的 Workflows 分享
=====================

Mac 用户对 Alfred 都不陌生，如果不知道的，建议到 [官方网址] 进行了解

如果你是开发者，推荐关注 [这个 Github Repo][willfarrell]


Workflows
-------------

### [Youdao Translate](Workflows/Youdao Translate.alfredworkflow) [(Download)](https://raw.github.com/lwr/AlfredWorkflows/master/Github.alfredworkflow)
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
* [87年的脚本](http://v2ex.me/alfred-workflow-share])
* [AlfredWorkflow.com](https://github.com/hzlzh/AlfredWorkflow.com)

[官方网址]:    http://alfredapp.com "Alfred 官方网址"
[willfarrell]: https://github.com/willfarrell/alfred-workflows "Alfred Workflows for Developers"
[@lwr]:        https://github.com/lwr

[dash]: https://raw.github.com/willfarrell/alfred-dash-workflow/master/screenshots/dash.png  "Sample result"
[kill]: https://github.com/nathangreenstein/alfred-process-killer/raw/master/screenshot1.png "Sample kill result"
[encode]: https://raw.github.com/willfarrell/alfred-encode-decode-workflow/master/screenshots/encode.png  "Sample result"