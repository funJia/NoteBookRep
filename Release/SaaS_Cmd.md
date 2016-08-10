# SaaS 开发环境\(Debug\)Jenkins配置

### 1.MS发布

### 2.复制各模块页面文件

[viewCode](/command/SAAS_CMD/CopyView.md)
注意：
  1.复制指定后缀页面

### 3.复制资源文件

[viewCode](/command/SAAS_CMD/CopyStatic.md)
注意：
  1.包括 js,css,img
  2.系统配置信息

### 4.复制动态库文件

[viewCode](/command/SAAS_CMD/CopyDll.md)

注意：

1.包括 系统动态库和第三方动态库
 2.需排除指定后缀的文件

### 5.替换开发环境的布局页面

[viewCode](/command/SAAS_CMD/CopyDevLayout.md)

注意：
 1.项目中可能有多个布局页

2.项目中可能有未使用布局页的页面如 ’登录页面‘

### 6.通过Fis3进行前端工程构建

[viewCode](/command/SAAS_CMD/Fis3Build.md)

注意：
     1.构建时分 debug 和 release 版本

### 7.通过控制台程序复写 fis3的构造结果

[viewCode](/command/SAAS_CMD/ConsoleOverwrite.md)

注意：
   1.主要是layout里 requrie.js的引用位置问题

