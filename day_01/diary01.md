第一章 Odoo之初见<br>
1、Odoo<br>
1.1 Odoo概念：<br>
一种能够满足客户各种需求的用来开发EPR系统和电子商务系统的开源的框架，能直观展示商品从被生产到被消费之间的过程；模块化结构，像搭积木一样快速开发系统。
其目的是减少企业在管理上投入的精力。

1.2语言:<br>
前后端分离，前端Javascript，后端Python，使用werkzeug库处理http协议(未用其他web 框架)，前后端通信json-rpc，数据库采用开源的PostgreSQL。</br>

1.3 Odoo常见功能模块： <br>
    财务Accounting<br>
    客户关系管理CRM(Customer Relationship Management) <br>
    仓库管理Warehouse Management<br>
    制造资源计划MRP(Manufacturing Resource Planning) <br>
    采购管理Purchase Management<br>
    项目/服务管理Project/Service Management<br>
    人力资源管理HRM(Human Resource Management) <br>
    内容管理CMS(Content Management System) <br>
    文档管理Document Management<br>
    车辆管理Fleet Management<br>
    门店零售POS(Point of Sale) <br>
    供应链管理SCM(Supply Chain Management)  <br>

2、PostgreSQL<br>
2.1 PostgreSQL概念:  <br>
PostgreSQL支持大部分 SQL标准并且提供了许多其他现代特性：复杂查询、外键、触发器、视图、事务完整性、MVCC。<br>
PostgreSQL强壮的一个原因源于它的架构。和商业数据库一样，PostgreSQL可以用于C/S(客户/服务器)环境。这对于用户和开发人员有很多好处。<br>
PostgreSQL安装核心是数据库服务端进程。它允许在一个独立服务器上。需要访问存储在数据库中的数据的应用程序必须通过数据库进程。这些客户端程序无法直接访问数据，即使它们和服务程序在同一台机器上。<br>
--百度百科

3、Werkzeug<br>
3.1 Werkzeug概念:<br>
Werkzeug是Python的WSGI规范的实用函数库。<br>
--百度百科

4、json-rpc<br>
4.1json-rpc概念:<br>
JSON-RPC，是一个无状态且轻量级的远程过程调用（RPC）传送协议，其传递内容透过 JSON 为主。相较于一般的 REST 透过网址（如 GET /user）调用远程服务器，JSON-RPC 直接在内容中定义了欲调用的函数名称（如 {"method": "getUser"}），这也令开发者不会陷于该使用 PUT 或者 PATCH 的问题之中。 本规范主要定义了一些数据结构及其相关的处理规则。它允许运行在基于 Socket、HTTP 等诸多不同消息传输环境的同一进程中。其使用 JSON（RFC 4627）作为数据格式。<br>
--百度百科
