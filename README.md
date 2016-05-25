# ACLUIS——智能空调使用微软认知服务LUIS接口实现语义理解样例
# 项目说明
该项目是智能空调使用微软认知服务LUIS接口实现语义理解样例，帮助开发者理解在JAVA环境下使用LUIS API的调用。
## 部署说明

###Step1. 开发环境就绪 
* 本地开发环境Eclipse
* LUIS应用导入
###Step2. Run Demo

* Dowload Picture Transfer.zip file and unzip it, open it in Visual Studio
* Debug->Start Debugging or F5
* VS will launch Word or PowerPoint and Add-ins will run in office, Add-ins will give you a 2D image code
* Using your mobilephone to scan this 2D image code
* Then you can select your photes on mobile need transfer to Office, Click upload
* Your Word or PowerPoint Add-in pane will display your selected photoes
* Now, you can insert them into your Word file or PowerPoint


###Step3. Notes

This deme use Document.setSelectedDataAsync method in Office.js, it can snych string/array/html/image etc. you can reference https://dev.office.com/reference/add-ins/shared/document.setselecteddataasync get detail.

