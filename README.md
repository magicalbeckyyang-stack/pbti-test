# PBTI · 拼多多消费者人格测试

纯静态单页应用(单文件 `index.html`),20 道荒诞情景题 → 28 种「下单 × 售后」双重人格,纯前端计算 + canvas 物种卡,无后端、无依赖。

## 部署到 EdgeOne Pages

这是纯静态站,**无需 build**。

- 构建命令:**留空**
- 输出目录 / 根目录:`./`(当前目录)
- 框架预设:`无 / Static`

### 方式一:控制台直接上传(最快,无需 Git)
1. 进入 EdgeOne 控制台 → Pages → 新建项目 → 「直接上传」
2. 把本目录(含 `index.html`)拖进去
3. 部署完成,拿到 `*.edgeone.app` 域名

### 方式二:连接 Git 仓库(自动部署)
1. 把本目录推到 GitHub / Gitee
2. EdgeOne Pages → 新建项目 → 选择该仓库
3. 构建命令留空,输出目录填 `./`,部署

### 方式三:EdgeOne CLI(需先装 Node)
```bash
npm i -g edgeone
edgeone pages deploy ./ -n pbti
```
