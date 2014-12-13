使用 Gradle 构建 Mult-projects

目的：

够用就行，意味着：

1. 够用的 plugins
2. 够用的常用配置（sourceCompatibility，repositories 等）
3. 够用到项目分层（common, api, web，该分层参考：[iRomin][blog-1]），同时有 jar，war。
4. 够用的依赖（比如 spring，junit，slf4j 等）


附：使用 [gvm][website-1]

查看当前使用的 gradle: `gvm current gradle`

查看可用的 gradle 版本：`gvm list gradle`

安装新版本的 gradle `gvm install gradle 2.2`

设置默认版本：`gvm default gradle 2.2`



<!-- 参考： -->
[blog-1]:http://rominirani.com/2014/07/29/gradle-tutorial-part-3-multiple-java-projects/
[website-1]:http://gvmtool.net/