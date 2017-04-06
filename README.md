# 移动端应用脚手架


## 1、环境准备


版本（全局安装）：

NODE ：6.9 +

NPM ：3 +

webpack ：1.13 +

## 2、源

由于 npm 安装源太慢，建议安装成淘宝 cnpm 
```bash
npm install -g cnpm --registry=https://registry.npm.taobao.org
```


## 3、使用脚手架

```bash
npm install -g vue-cli
vue init whkfzyx/cli my-project
cd my-project
cnpm install
cnpm run dev

```

如果8080端口已经被使用了，则需要修改 `/config/index.js`端口. 然后重新输入命令 `npm run dev` 
