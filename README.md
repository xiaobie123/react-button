项目名称
简要描述;简介
如何让项目在本地运行
运行短裤
运行测试套件
如何贡献
提交公关的步骤
如何提出问题
链接到行为准则
更改日志
build会告诉巴别塔把所有东西都lib放在build目录中。记得我们如何build/index.js提早进入 那将是溺爱的版本lib/index.js
lint将递归运行我们的linter，lib以确保我们的语法正确。
lint:watch是一个很好的脚本，随时更改linter lib。当我们走的时候，它会帮助我们抓住错误。
prepublish是一个很酷的剧本。当我们运行npm publish并执行它之前，npm会寻找这个。这是确保我们的资产build是最新版本的好方法。稍后我们还将添加一个lint和测试脚本。这有助于我们确保我们不会将破坏的代码发布到npm。
npm
