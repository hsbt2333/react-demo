npm start

> "@testing-library/jest-dom": "^5.17.0"

用于在Jest测试中扩展DOM匹配器的库。如果您不打算进行单元测试或集成测试，则可以删除此依赖项。

> "@testing-library/react": "^13.4.0"

提供了一组用于测试React组件的实用程序。同样，如果您不需要进行React组件的测试，则可以删除此依赖项。

> "@testing-library/user-event": "^13.5.0"

模拟用户与浏览器交互的库，用于测试。如果您不需要进行用户交互的测试，则可以删除此依赖项。

> "react": "^18.2.0"
> "react-dom": "^18.2.0"

React的核心库，用于构建用户界面。这些是React项目的核心依赖项

> "react-scripts": "5.0.1"

包含构建、测试和生产环境的脚本。对于使用Create React App创建的项目，这是必要的依赖项

> "web-vitals": "^2.1.4"

用于测量和报告网页的关键性能指标（KPIs）。如果您不需要进行性能测量或报告，则可以删除此依赖项。

browserslist 是一个字段，用于指定项目支持的目标浏览器和版本范围
">0.2%"：全球使用率超过 0.2% 的所有浏览器。
"not dead"：所有非已死的浏览器。
"not op_mini all"：排除所有版本的 Opera Mini 浏览器。

"last 1 chrome version"：最新版本的 Google Chrome 浏览器。
"last 1 firefox version"：最新版本的 Mozilla Firefox 浏览器。
"last 1 safari version"：最新版本的 Safari 浏览器。

> npm install --save-dev @babel/plugin-proposal-private-property-in-object


assets：放置原始资源文件。

components：存放全局组件。

contants：常量文件夹，存放常量。

i18n：i18n国际化，各种语言的翻译。

pages：页面文件夹。

router：路由文件夹。

utils：存放一些常用函数的封装。