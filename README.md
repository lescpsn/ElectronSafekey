# ElectronSafekey

## 下载工程
```
git clone https://github.com/lescpsn/ElectronSafekey.git
```

## 安装node
```
一路回车傻瓜氏安装，安装完成后设置下npm包的镜像

设置npm的数据为淘宝镜像
npm config set registry "https://registry.npm.taobao.org/"
npm install -g cnpm --registry=https://registry.npm.taobao.org

cnpm与npm两命令一样了
```

## 安装electron环境
```
方法1: 工程内部独立安装electron
    cd Client; npm install

方法2: 系统全局安装electron
    cnpm install -g electron
```

## 运行工程
### 客户端
```
cd Client; npm start
```