![MxiDev](https://mxidev.com/assets/svg/mxidev-blue.svg "MxiDev")
# SSR_subscribe-For-WHMCS

***

SSR subscribe是一款基于WHMCS开发的SSR订阅链接生成插件，支持LegendSock与Shadowsocks For WHMCS，同时支持surge配置托管

### 更新日志:

#### 4.2 (2019-04-14)

  - 新增 一键删除过期产品订阅地址功能
  - 新增 在产品被删除时自动删除订阅地址的功能
  - 新增 API模式
  - 新增 只获取正常端口节点的模式，只需把订阅地址中的ssr改为multiport即可
  - 新增 自定义单端口多用户节点名称中的提示符功能
  - 修复 存在单端口节点时，Clash配置托管无法使用的问题
  - 修复 Clash配置文件编写错误的问题
  - 改善 Clash配置文件 {$proxies} 变量默认去除"[]"符号，方便自行添加urltest模式

***

#### 4.1 (2019-02-02)

  - 新增 Clash配置托管链接生成
  - 新增 自定义获取订阅的域名
  - 新增 与ZCat LegendSock Templates的联动，自动生成带有单端口多用户的订阅地址

***

#### 4.0 (2018-07-26)

  - 全新重构，提高可靠性与性能
  - 后台可一键导出所有用户的订阅信息
  - 预留单端口多用户二次开发接口，自带一种单端口多用户解决方案
  - 全新设计的授权系统，可靠性更高
  - 引入升级提示系统，新版本更新时更快获知

***

+ #### 升级注意事项:

+ 4.0版本为全新重构，建议将原先版本的SSR_subscribe插件文件夹删去(文件夹目录: modules/addons/SSR_subscribe/)

***

#### 3.3 

  - 新增 Surge配置下载
  - 新增 服务开通时自动生成订阅地址
  - 全新前台模板主题

***

#### 3.0 

  - 新增 Surge配置托管

***

#### 2.0 

  - 新增 Shadowsocks For WHMCS销售模块支持
  - 新增 安全认证，防止暴力破解

***

#### 1.0 

  - 初始版本



Copyright © MxiDev.com All Rights Reserved.
