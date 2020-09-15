## panogram-package

项目打包相关配置。

### 环境说明

使用的是 `electron 9.2.0 ` 与  `electron-builder` 。

### 打包步骤

1. clone 本项目。
   ```bash
   $ git clone git@code.aliyun.com:smileyan/panogram-electron.git 
   ```

2. 首先把前端相关文件复制到 `www` 目录下。
   ```bash
   $ cd panogram-electron
   $ git clone git@code.aliyun.com:smileyan/another-panogram.git www
   ```

3. 安装依赖，打包。
   ```bash
   # 安装依赖
   $ cnpm install
   # 打包 windows
   $ npm run pack:win
   # 打包 mac(必须在mac上打包)
   $ npm run pack:mac
   # 打包 linux
   $ npm run pack:linux
   ```



> Smileyan
>
> 2020.8.20

