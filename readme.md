
<h1 align="center"><sub>awesome-tools</sub></h1>

<br />
<br />
<h2 align="center">node.js</h2>

- [tj/commander.js](https://github.com/tj/commander.js) - 命令行接口全面的解决方案，灵感来自于 [Ruby's commander](https://github.com/commander-rb/commander)可以自动的解析命令和参数，合并多选项，处理短参等等，功能强大，上手简单。
- [yargs/yargs](https://github.com/yargs/yargs) - Yargs帮助您构建交互式命令行工具，通过解析命令行参数并创建一个优雅的用户界面。(https://github.com/commander-rb/commander)可以自动的解析命令和参数，合并多选项，处理短参等等，功能强大，上手简单。
- [jprichardson/node-fs-extra](https://github.com/jprichardson/node-fs-extra) - 在 Node.js 的 fs 基础上增加了一些新的方法，更好用，还可以拷贝模板。
- [chalk/chalk](https://github.com/chalk/chalk) - 可以用于控制终端输出字符串的样式。
- [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) - Node.js 命令行交互工具，通用的命令行用户界面集合，可以和用户进行交互。
- [terkelg/prompts](https://github.com/terkelg/prompts) - Node.js 命令行交互工具，轻量级的，漂亮的和用户友好的交互式提示。
- [sindresorhus/ora](https://github.com/sindresorhus/ora) - 实现加载中的状态是一个 Loading 加前面转起来的小圈圈，成功了是一个 Success 加前面一个小钩钩。
- [SBoudrias/mem-fs-editor](https://github.com/SBoudrias/mem-fs-editor) - 提供一系列 API，方便操作模板文件。
- [shelljs/shelljs](https://github.com/shelljs/shelljs) - ShellJS 是 Node.js 扩展，用于实现 Unix shell 命令执行。
- [lerna/lerna](https://github.com/lerna/lerna) - Lerna 是一个用来优化托管在 git/npm 上的多 package 代码库的工作流的一个管理工具，可以让你在主项目下管理多个子项目，从而解决了多个包互相依赖，导致发布时需要手动维护多个包的问题。
- [fb55/htmlparser2](https://github.com/fb55/htmlparser2) - 一个 HTML/XML/RSS 解析器
- [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) - 快速、灵活、精简的jQuery核心部分，专为服务器实现的解析html的库

<br />
<br />
<h2 align="center">抹平多端差异的开发框架</h2>

- [NervJS/taro](https://github.com/NervJS/taro) - 多端统一开发框架，支持用 React 的开发方式编写一次代码，生成能运行在微信小程序/百度智能小程序/支付宝小程序、H5、React Native 等的应用
- [RubyLouvre/anu/packages/cli](https://github.com/RubyLouvre/anu/tree/master/packages/cli) - 这只是[anu](https://github.com/RubyLouvre/anu)的一个扩展，通过实现不同的render，以支持在微信小程序，百度小程序，支付宝小程，快应用，H5， hybird上运行。
- [Youjingyu/vue-hap-tools](https://github.com/Youjingyu/vue-hap-tools) - 一个抹平vue.js与快应用差异性的工具
- [dcloudio/uni-app](https://github.com/dcloudio/uni-app) - 使用 Vue.js 开发跨平台应用的前端框架。开发者通过编写 Vue.js 代码，uni-app 将其编译到 iOS、Android、微信小程序、H5等多个平台，保证其正确运行并达到优秀体验。

<br />
<br />
<h2 align="center">Babel 插件库</h2>

- [@babel/parser](https://github.com/babel/babel/tree/master/packages/babel-parser) - 之前的babel/babylon， Babel的解析器，用来解析JavaScript
- [@babel/traverse](https://github.com/babel/babel/tree/master/packages/babel-traverse) - Babel Traverse（遍历）模块维护了整棵树的状态，并且负责替换、移除和添加节点。
- [@babel/types](https://github.com/babel/babel/tree/master/packages/babel-types) - Babel Types模块是一个用于 AST 节点的 Lodash 式工具库， 它包含了构造、验证以及变换 AST 节点的方法。 该工具库包含考虑周到的工具方法，对编写处理AST逻辑非常有用。
- [@babel/generator](https://github.com/babel/babel/tree/master/packages/babel-generator) - 是 Babel 的代码生成器，它读取AST并将其转换为代码和源码映射（sourcemaps）。
- [@babel/template](https://github.com/babel/babel/tree/master/packages/babel-template) - 从一个字符串模板生成AST。是另一个虽然很小但却非常有用的模块。 它能让你编写字符串形式且带有占位符的代码来代替手动编码， 尤其是生成的大规模 AST的时候。 在计算机科学中，这种能力被称为准引用（quasiquotes）。
