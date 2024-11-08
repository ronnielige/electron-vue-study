参考：https://blog.csdn.net/2301_76692187/article/details/143327644
# 本项目主要记录electron-vue项目的创建和运行过程，作为后续参考。

# 项目初始化
1. npm create @quick-start/electron electron-vue-study
	√ Select a framework: » vue
	√ Add TypeScript? ... No / Yes
	√ Add Electron updater plugin? ... No / Yes
	√ Enable Electron download mirror proxy? ... No / Yes
2. cd electron-vue-study
3. 设置npm淘宝镜像，加速npm包下载过程：
   npm config edit
   在打开的配置文件中，添加以下镜像源配置：
   electron_mirror=https://cdn.npmmirror.com/binaries/electron/ electron_builder_binaries_mirror=https://npmmirror.com/mirrors/electron-builder-binaries/
4. npm i electron -D

# 运行项目
1. npm run dev

# 打包exe
1. 下载打包工具 npm install electron-builder --save-dev