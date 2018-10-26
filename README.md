"# webpack-demo" 
## 参考文章
``` bash
https://www.webpackjs.com/guides/getting-started/
# webpack只能打包JS文件,但是可以通过 loader 引入任何其他类型的文件

# 预加载数据概念：import Data from './data.xml';
# 在使用 d3 等工具来实现某些数据可视化时，预加载数据会非常有用。
# 我们可以不用再发送 ajax 请求，然后于运行时解析数据，而是在构建过程中将其提前载入并打包到模块中，以便浏览器加载模块后，可以立即从模块中解析数据。

# 每次要编译代码时，手动运行 npm run build 就会变得很麻烦。
# webpack 中有几个不同的选项，可以帮助你在代码发生变化后自动编译代码：
# webpack's Watch Mode
# webpack-dev-server
# webpack-dev-middleware
# 多数场景中，你可能需要使用 webpack-dev-server，但是不妨探讨一下以上的所有选项。

# 模块热替换
# 它允许在运行时更新各种模块，而无需进行完全刷新
``` 
