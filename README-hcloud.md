# 管理后台UI

## 概述

用于管理HCloud平台本身的管理后台的UI，主要功能如下：

- 用户管理：维护使用本平台进行软件研发的人员，注意不是管理使用接入到本平台的应用的用户。
- 组织管理：想将应用接入到本平台，需要先创建组织。
- 团队管理：组织下可以创建团队。
- 应用管理：定义应用。
- 租户管理：定义应用的租户，包括租户可使用的应用模块。
- 平台统计：用户活动，团队统计，应用统计等。

## 开发说明

使用 [LayUI](https://www.layui.com/) 作为前端框架，并使用 [Fetch API](https://developer.mozilla.org/zh-CN/docs/Web/API/Fetch_API) 与后端接口交互。

或使用 [element-ui](https://element.eleme.cn/2.0/#/zh-CN/component/installation) 和 [axios](https://cn.vuejs.org/v2/cookbook/using-axios-to-consume-apis.html) ！

考虑在应用定义时支持拖拽操作，使用 [hammer.js](http://hammerjs.github.io/) 实现。
