# admin-antd-vue

## Demo

**注意：Demo 用的是在线mock服务，不稳定，若在线登录不了pull到本地可直接运行查看demo**

| **[http://demo.admin-antd-vue.liqingsong.cc](http://demo.admin-antd-vue.liqingsong.cc/)**             |
:-------------------------:
| ![Home](https://gitee.com/lqsong/public/raw/master/admin-antd-vue/home.png)  |
| ![Home](https://gitee.com/lqsong/public/raw/master/admin-antd-vue/home2.png)  |



## 使用文档

 - [http://admin-antd-vue.liqingsong.cc](http://admin-antd-vue.liqingsong.cc/)
 - [Github](https://github.com/lqsong/admin-antd-vue) 
 - [Gitee](https://gitee.com/lqsong/admin-antd-vue)

## 功能

```
- 登录 / 注销 / 注册

- 权限验证
  - 页面权限
  - 按钮操作
  - 权限配置

- 全局功能
  - 国际化多语言
  - 动态顶级菜单（支持设置是否启用）
  - 动态侧边栏（支持多级路由嵌套）
  - 动态面包屑（支持自定义配置）
  - Svg Sprite 图标
  - Mock 数据

- 综合实例
  - 引导页
  - 组件示例
    - 编辑器
      - CKEditor
      - tui-editor
    - 图标
      - IconSvg
      - IconFont
  - 页面示例
    - 列表页面
      - 标准列表
      - 表格列表
      - 高度自适应表格
      - 搜索列表
    - 表单页面
      - 基础表单
      - 高级表单      
    - 详情页面
      - 基础详情
      - 模块详情
      - 表格详情
  - 权限验证
```


## 自定义配置

### **(建议)** 本地或开发模式下，不要直接修改 '.env.development'
复制 '.env.development' 重命名为 ' .env.development.local' , 修改对应的参数.

### **(建议)** 生产模式下，不要直接修改 '.env.production'
复制 '.env.production' 重命名为 ' .env.production.local' , 修改对应的参数.


## 项目设置

### 一、Install dependencies,

```bash
$ yarn
```

or

```
$ npm install
```

> 推荐使用 yarn , **[yarn安装与常用命令](http://liqingsong.cc/article/detail/9)** 。

### 二、Compiles and hot-reloads for development

```bash
$ yarn serve
```

or

```
$ npm run serve
```


### 三、Compiles and minifies for production

```bash
$ yarn build
```
or

```
$ npm run build
```

### 四、精简 svg icon

```
$ yarn svgo
```

or

```
$ npm run svgo
```

### 五、Run your unit tests
```
yarn test:unit

#

npm run test:unit
```

### 六、Lints and fixes files
```
yarn lint

#

npm run lint
```


## 捐赠

如果你觉得这个项目帮助到了你，请帮助点击 Star，你也可以请作者喝咖啡表示鼓励.

**ALIPAY**             |  **WECHAT**
:-------------------------:|:-------------------------:
![Alipay](https://gitee.com/lqsong/public/raw/master/common/Alipay.png)  |  ![Wechat](https://gitee.com/lqsong/public/raw/master/common/Wechat.png)

