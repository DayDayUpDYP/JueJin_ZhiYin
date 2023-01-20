
 Front-end technology sharing and exchange.
# use

## Run the project 

```bash
# 安装依赖
$ yarn install

# 开发环境运行 localhost:3000
$ yarn run dev
```

## build
```bash
# 打包项目
yarn run build

# 运行打包后项目
yarn run start
```

## Pm2: project go online using pm2
```bash
# 打包项目
yarn run build

# 运行打包后项目
pm2 start npm --name "myjuejin" -- run "start"
```
