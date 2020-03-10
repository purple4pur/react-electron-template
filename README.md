# react-electron-templete

简单易用的基于 React 的 Electron 应用模板。

开发和调试过程可完全使用 React，开发完成后一键打包 (使用 electron-packager)，并尽可能地减小文件体积。

## 使用说明

### 本地搭建

1. clone 模板至本地
   ```
   git clone git@github.com:purple4pur/react-electron-templete.git
   cd ./react-electron-templete
   ```
2. 安装依赖库
   ```
   npm i
   ```
3. 安装 electron-packager
   ```
   # 全局安装（推荐）
   npm i -S electron-packager -g

   # 仅安装在此项目
   npm i -S electron-packager
   ```

### 可用脚本

#### `npm run start`

在浏览器启动本地调试，实时响应更新，与 React 一样。

#### `npm run preview`

预览桌面应用，不会实时更新。

#### `npm run pack-win`

打包为 windows x86 桌面应用，生成在 `release-builds` 文件夹内。

#### `npm run prepreview` 及 `npm run prepack-win`

与 React 的 build 脚本一致，仅用作预览和打包的先行步骤，一般无需手动执行。

## 鸣谢

感谢由 Wolfgang Schmidt 提供的 [切实可行的灵感](https://javascript-conference.com/blog/write-once-run-everywhere-building-desktop-apps-with-react-and-electron/) 。
