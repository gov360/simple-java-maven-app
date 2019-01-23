#simple-java-maven-app

这个存储库是为了
[使用Maven构建Java应用程序]（https://jenkins.io/doc/tutorials/build-a-java-app-with-maven/）
[Jenkins用户文档]（https://jenkins.io/doc/）中的教程。

存储库包含一个输出字符串的简单Java应用程序
“你好，世界！” 并附有几个单元测试来检查
主要应用程序按预期工作。 这些测试的结果保存到了
JUnit XML报告。

`jenkins`目录包含`Jenkinsfile`的示例（即Pipeline）
你将在教程和`scripts`子目录中创建自己
包含一个shell脚本，其中包含在Jenkins处理时执行的命令
管道的“交付”阶段。
