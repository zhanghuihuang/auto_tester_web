# auto_tester_web

## 安装项目依赖
```
npm install
```

### 编译热启动开发环境
```
npm run serve
```

### 编译构建生产部署包
```
npm run build
```

### 执行测试用例
```
npm run test
```

### 规则检查并修复文件格式
```
npm run lint
```

### 文件结构
├── public                     // 公共静态资源
│   ├── favicon.ico            // 浏览器页签图标
│   ├── index.html             // 静态首页

├── src                        // 源代码
│   ├── api                    // 所有请求
│   ├── assets                 // 主题 字体等静态资源
│   ├── components             // 全局公用组件
│   ├── config                 // 自定义配置
│   ├── directive              // 全局指令
│   ├── filtres                // 全局 filter
│   ├── icons                  // 项目所有 svg icons
│   ├── lang                   // 国际化 language
│   ├── mock                   // 项目mock 模拟数据
│   ├── router                 // 路由
│   ├── store                  // 全局 store管理
│   ├── styles                 // 全局样式
│   ├── utils                  // 全局公用方法
│   ├── vendor                 // 公用vendor
│   ├── views                  // view
│   ├── App.vue                // 入口页面
│   ├── main.js                // 入口 加载组件 初始化等
