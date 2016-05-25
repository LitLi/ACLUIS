# ACLUIS——智能空调使用微软认知服务LUIS接口实现语义理解样例
# 项目说明
该项目是智能空调使用微软认知服务LUIS接口实现语义理解样例，帮助开发者理解在JAVA环境下使用LUIS API的调用。
## 部署说明

###Step1. 开发环境就绪 
* 本地开发环境Eclipse
* 访问(http://luis.ai) ,将AirCond.json文件导入到LUIS Studio中
* 可以根据需要调整LUIS的Intent/Entity等定义，训练后，选择publish 应用，确认发布
* 发布后可以点击App Settings，如图

![LUIS 应用Publish和App Settings](https://github.com/LitLi/ACLUIS/blob/master/Appsetting%26Publish.PNG)
* 可以查找到AppId与LUIS服务的订阅密钥并复制
* 将oxfordvisitor.zip文件解压，导入Eclipse 工程空间，并将相关的jar下载导入: httpclient.jar/httpcoe.jar/commons-logging.jar/commons-codec.jar/json.jar
* 打开src/main/java/requestBody.json文件，将AppId和订阅密钥修改成刚刚在LUIS应用中复制的
* 根据环境修改buildpath的输出目录等

###Step2. 运行样例

* 编译并运行工程，提示输入需要搜索的语料，输入语料如：明天北京天气怎么样，回车。如下图

![语料输入]( https://github.com/LitLi/ACLUIS/blob/master/start.PNG)

* LUIS就会返回对该语料的理解，给出得分最高的意图，和对应的实例参数，以及完整的消息，如下图

![语义输出]( https://github.com/LitLi/ACLUIS/blob/master/result.PNG)

