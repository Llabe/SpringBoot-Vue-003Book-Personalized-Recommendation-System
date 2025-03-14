# springboot003图书个性化推荐系统 / Book Personalized Recommendation System

![SpringBoot](https://img.shields.io/badge/SpringBoot-2.x-brightgreen)
![MyBatisPlus](https://img.shields.io/badge/MyBatisPlus-2.3-orange)
![Shiro](https://img.shields.io/badge/Shiro-1.3.2-blue)
![Vue](https://img.shields.io/badge/Vue-2.x-4fc08d)

# 项目简介  
基于 SpringBoot + MyBatis-Plus + Shiro 的图书推荐管理系统，集成百度AI算法实现个性化推荐，包含图书评论、消息通知、多端界面适配等功能模块。

# 特征介绍  
- ​**智能推荐**：整合百度AI SDK 实现用户画像分析与图书推荐算法。  
- ​**权限管理**：Shiro 实现动态权限控制，支持基于注解的接口鉴权。  
- ​**高效开发**：MyBatis-Plus 增强 ORM 操作，内置分页插件与代码生成模板。  
- ​**多端适配**：独立配置前端（Layui）与后台（Vue）界面，支持响应式布局。  
- ​**文件管理**：集成 Commons-IO 实现文件上传/下载，支持图片格式校验。  

# 代码结构 
src/
├── main/
│   ├── java/
│   │   ├── com/
│   │   │   ├── annotation/          # 鉴权注解
│   │   │   ├── config/              # Shiro/MyBatis配置
│   │   │   ├── controller/          # 接口层
│   │   │   ├── dao/                 # 数据访问接口
│   │   │   ├── entity/              # 数据库实体
│   │   │   │   ├── model/           # 业务模型
│   │   │   │   ├── view/            # 视图对象
│   │   │   ├── interceptor/         # 请求拦截器
│   │   │   ├── service/             # 服务层
│   │   │   ├── utils/               # 百度AI工具类
│   ├── resources/
│   │   ├── mapper/                  # XML映射文件
│   │   ├── application.yml          # 多环境配置
│   │   ├── admin/                   # Vue后台模板
│   │   ├── front/                   # Layui前台模板

# 使用说明
**推荐浏览器**：谷歌浏览器  
**后台地址**：http://localhost:8080/springbootxs5o6/admin/dist/index.html  
**管理员账号**：abo / abo  
**前台地址**：http://localhost:8080/springbootxs5o6/front/index.html  
**数据库配置**：修改 application.yml 中的 JDBC 连接信息

# 技术文档
* 核心框架：[Spring Boot](https://spring.io/projects/spring-boot)
* 持久层框架：[MyBatis-Plus](https://baomidou.com)
* 权限认证：[Apache Shiro](https://shiro.apache.org)
* 前端框架: [Vue.js](https://vuejs.org) + [Layui](https://layui.dev)
* AI服务：[百度AI SDK](https://ai.baidu.com/ai-doc)
* 工具库：[Hutool](https://hutool.cn) + [Fastjson](https://github.com/alibaba/fastjson)

# 捐赠
> 博主将持续更新Java全栈开发项目，包含ssm，springboot，前后端分离系统等项目。
> 此外如果您够宽裕，请博主喝杯咖啡吧！捐赠将用于服务器维护与开源社区建设，感谢您的认可！
> 如需更多Java相关项目毕设3000+，sql文件可联系博主v:xq-lucky311
![输入图片说明](%E7%91%9E%E5%B9%B8%EF%BC%81%E7%91%9E%E5%B9%B8%EF%BC%81.png)