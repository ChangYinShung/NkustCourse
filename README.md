# 2020-03-03 Note
### 基本
- nodejs
- angular cli  
- ionic cli

### 安裝 Nrwl 
以 Angular CLI 為基礎，能夠協助開發者產生樣板的工具
``` cmd
npm install -g @nrwl/cli
npm install -g @nrwl/schematics
```
### 安裝 @nstudio/xplat
整合 nrwl 與 ionic cli 的樣板(專案建立後)
``` cmd
npm install --save-dev @nstudio/xplat
```
### 建立專案
``` cmd
npx create-nx-workspace nkustworkspace
(選Empty 和 Nx) 
cd nkustworkspace
npm install --save-dev @nstudio/xplat
nx generate app
選 ionic 、angular
``` cmd
一個Nx 樣板會建立成功並用 @nstudio/xplat 提供的樣板將 ionic 加入


