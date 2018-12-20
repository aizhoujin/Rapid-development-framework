




#### 使用方式
1.html引入
```
axios、vue、element-ui相关依赖也要引入
avue-cdn:https://gitee.com/smallweigit/avue/raw/master/lib/avue.js
<script src="https://cdn.bootcss.com/axios/0.18.0/axios.js"></script>
<script type="text/javascript" src="https://cdn.bootcss.com/vue/2.5.17-beta.0/vue.js"></script>
<script type="text/javascript" src="https://cdn.bootcss.com/element-ui/2.3.4/index.js"></script>
<script type="text/javascript" src="https://gitee.com/smallweigit/avue/raw/master/lib/avue.js"></script>
```
2.npm引入
```
npm install avue-cli

import Avue from 'avue-cli/packages/index.js';

```

#### 功能结构
```
- 全局错误日志记录
- vuex持久化存储
- 主题色切换
- 锁屏
- SSR渲染页面
- 数据展示
- 登录/注销
 - 用户名登录
 - 验证码登录
- 权限验证
- 第三方网站嵌套
- CRUD(增删改查)
- FORM(动态生成)
- 阿里巴巴图标库(在线调用)
- 环境变量
- 表格树
- 引导页
- 数据持久化
- 剪切板
- 系统管理
 - 用户管理
 - 角色管理
 - 菜单管理
- 高级路由
 - 动态路由
 - 参数路由
- 更多功能开在开发
```



# 进入项目
cd avue

# 安装依赖
npm install --registry=https://registry.npm.taobao.org

# 启动服务
npm run dev
```

#### 调试与发布
```bash
# 构建测试环境
npm run dev

# 构建生成环境
npm run build

# 构建SSR渲染页面
npm run start

```

#### 其它
```bash
# 代码检测
npm run lint

# 单元测试
npm run karma

# 构建SSR客户端代码
npm run build:client

# 构建SSR服务端端代码
npm run build:server
```

