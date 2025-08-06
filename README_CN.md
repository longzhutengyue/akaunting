# Akaunting™



[![Release](README_CN/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f762f72656c656173652f616b61756e74696e672f616b61756e74696e673f6c6162656c3d72656c65617365.svg+xml)](https://github.com/akaunting/akaunting/releases) [![Downloads](README_CN/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f646f776e6c6f6164732f616b61756e74696e672f616b61756e74696e672f746f74616c3f6c6162656c3d646f776e6c6f616473.svg+xml)](https://camo.githubusercontent.com/1e1b6355513179257f3b015666620324e1cddb171bdb9edc92d029b2a364ba9c/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f646f776e6c6f6164732f616b61756e74696e672f616b61756e74696e672f746f74616c3f6c6162656c3d646f776e6c6f616473) [![Translations](README_CN/68747470733a2f2f6261646765732e63726f7764696e2e6e65742f616b61756e74696e672f6c6f63616c697a65642e737667.svg+xml)](https://crowdin.com/project/akaunting) [![Tests](README_CN/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f616374696f6e732f776f726b666c6f772f7374617475732f616b61756e74696e672f616b61756e74696e672f74657374732e796d6c3f6c6162656c3d7465737473.svg+xml)](https://github.com/akaunting/akaunting/actions)

专为小型企业和自由职业者设计的在线会计软件。Akaunting 采用 Laravel、VueJS、Tailwind、RESTful API 等现代技术构建。得益于其模块化结构，Akaunting 为用户和开发者提供了强大的应用商店。

- [首页 ](https://akaunting.com/)- Akaunting 之家
- [论坛 ](https://akaunting.com/forum)- 寻求支持
- [文档 ](https://akaunting.com/hc/docs)- 了解如何使用
- [开发者门户 ](https://developer.akaunting.com/)- 产生被动收入
- [App Store](https://akaunting.com/apps) - 扩展您的 Akaunting
- [翻译 ](https://crowdin.com/project/akaunting)- 帮助我们翻译 Akaunting

## 要求



- PHP 8.1 或更高版本
- 数据库（例如：MariaDB、MySQL、PostgreSQL、SQLite）
- Web 服务器（例如：Apache、Nginx、IIS）
- [其他库](https://akaunting.com/hc/docs/on-premise/requirements/)

## 框架



Akaunting 采用现存最好的 PHP 框架 [Laravel](http://laravel.com/) 作为应用程序的基础框架和[模块](https://github.com/akaunting/module)包。

## 安装



- 安装 [Composer](https://getcomposer.org/download) 和 [Npm](https://nodejs.org/en/download)
- 克隆存储库： `git clone https://github.com/akaunting/akaunting.git`
- 安装依赖项： `composer install ; npm install ; npm run dev`
- 安装 Akaunting：

```
php artisan install --db-name="akaunting" --db-username="root" --db-password="pass" --admin-email="admin@company.com" --admin-password="123456"
```



- 创建示例数据（可选）： `php artisan sample-data:seed`

## 贡献



请非常清楚地说明您的提交消息和 Pull 请求，空的 Pull 请求消息可能会被无故拒绝。

向 Akaunting 贡献代码时，必须遵循 PSR 编码规范。黄金法则是：模仿现有的 Akaunting 代码。

请注意，本项目已发布[贡献者行为准则 ](https://akaunting.com/conduct)。 *参与本项目即表示您同意遵守其条款* 。

## 翻译



如果您想贡献翻译，请查看我们的 [Crowdin](https://crowdin.com/project/akaunting) 项目。

## 变更日志



请参阅[发布](https://github.com/longzhutengyue/akaunting/releases)以获取有关最近发生的变化的更多信息。

## 安全



请查看[我们的安全政策 ](https://github.com/akaunting/akaunting/security/policy)，了解如何报告安全漏洞。

## 致谢



- [丹尼斯·杜利奇](https://github.com/denisdulici)
- [库内特·森图尔克](https://github.com/cuneytsenturk)
- [所有贡献者](https://github.com/longzhutengyue/akaunting/contributors)

## 执照



Akaunting 是在 [BSL 许可](https://github.com/longzhutengyue/akaunting/blob/master/LICENSE.txt)下发布的。