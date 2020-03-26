# 这是一个演示如何使用github actions持续集成的实例
- 使用 actions/checkout@v2 切换分支
- 使用 actions/upload-artifact@v1 上传构件文件
- 使用 actions/create-release@latest 进行打包操作
- 使用 actions/upload-release-asset@v1 给打包添加附件
