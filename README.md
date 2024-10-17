# Flux 批量生图小工具

## 项目简介

基于网页的应用程序,利用硅基流动提供的 API 服务批量生成 AI 图像。
可以在[这里](https://lazyracket.github.io/flux-image-generator/by_siliconflow.html)快速预览。

## 使用的模型

black-forest-labs/FLUX.1-schnell - 由 Black Forest Labs 开发的文本到图像生成模型。
硅基流动通过 SiliconCloud 平台提供 API 访问。

## 主要特性

- 批量输入提示词
- 智能/手动分配生成次数
- 自定义图片尺寸和种子值
- 实时进度和配额显示（模拟）
- 暂停/继续/重启等功能
- 图片预览和批量下载
- 错误处理和自动重试
- 深色模式

## 使用说明

1. 输入 API 密钥
2. 输入提示词
3. 选择设置
4. 点击"生成"
5. 预览和下载图像
6. 借助其他工具批量下载

## 注意事项

- API 使用限额(免费用户):
  - IPM(每分钟图像数) = 2
  - IPD(每天图像数) = 400
- 需要更高限额可升级账户，请查阅文末的平台链接。
- 使用 API 请遵守平台规则，创作内容请遵守法律法规。

## 致谢

感谢 [硅基流动](https://www.siliconflow.com/) 提供 API 服务,以及 [Black Forest Labs](https://blackforestlabs.ai/) 开发 FLUX.1-schnell 模型。
