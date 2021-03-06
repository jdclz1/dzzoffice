
### DzzOffice2.0 程序简介   

   Dzzoffice是一套开源办公套件，适用于企业、团队搭建自己的 类似“Google企业应用套件”、“微软Office365”的企业协同办公平台。套件由多个工具组成，包含但不限于如：

**网盘:**  企业、团队文件集中管理。主要体现的功能是支持企业部门的组织架构建立共享目录，也支持组的方式灵活建立共享目录。支持文件标签，多版本，评论，详细的目录权限等协作功能。

**文档:**  在线 Word 文档协作工具。前端做了一套模板管理，用于企业添加自己的常用文档模板，如空白合同。后端支持 office online server，onlyoffice，collaboraoffice 来实现文档预览与协同编辑。

**表格:**  在线 Excel 协作工具。同上

**演示文稿:**  在线 PPT 文档浏览、编辑工具。同上

**记录:** 多人参与协作的记录本，主要体现协作记录内容。

**新闻:** 文章系统，可用于企业新闻，通知等用途

**通讯录:** 企业人员联系方式查询

**文集:** 通过树形目录有序管理文档。支持 Markdown 编辑，支持导入导出 txt，epub、mobi、azw3

**相册：** 企业，团队图片管理

**任务板:** 任务管理、团队协作

**讨论板:** 内部论坛设置

**表单:** 表单，问卷工具

   企业根据需要可以只使用一款工具，也可以多款工具组合使用。例如团队需要一个任务管理工具，可以只安装一个任务板，登陆系统会直接进入任务板工具，没有其他工具的干扰。如果多个工具组合使用，可以设置默认登陆到哪个工具里。


### DzzOffice的下载及技术支持

1. 官方网站：   http://www.dzzoffice.com
2. github地址：https://github.com/zyx0814/dzzoffice
3. 码云地址：   https://gitee.com/zyx0814/dzzoffice


### DzzOffice安装方法

1. 上传文件到服务器。

2. 设置目录属性（windows 服务器可忽略这一步）
	以下这些目录需要可读写权限
	./config
	./data 含子目录

3. 执行安装脚本 /install/
   请在浏览器中运行 install 程序，即访问 http://您的域名/install/

4. 参照页面提示，进行安装，直至安装完毕。

5. 在开始面板中打开“管理”“系统工具”应用，更新系统缓存。

### DzzOffice首次安装配置说明

 1. 程序安装后，默认会进入管理应用，先打开系统工具 更新系统缓存。

 2. 打开 应用市场 ，在线安装所需应用，安装完成后在已安装里面启用需要的应用。

 3. 进入 管理 -> 系统设置内，设置默认首页，平台名称、平台logo等。

 4. 点击导航头部右侧 开始菜单，查看各个应用是否正常。
