# 定时自动打卡脚本

 - 可定时，默认为每天8点30分开始执行（基于Github Actions执行，免费版任务排队可能会有较大的延时）
 - 默认每次提交上次所提交的内容（只有时间部分更新）
 - 系统表单如有更新，在当天自行手机打卡，后面会自动按照你更新后的选项继续打卡
 - 使用Github Actions完成自动化任务
 - 添加了保活脚本，请自行添加Github Token

 项目用于学习交流，仅用于各项无异常时打卡，如有身体不适等情况还请自行如实打卡~


> 感谢[Tishacy](https://github.com/Tishacy)同学的项目 https://github.com/Tishacy/ZJU-nCov-Hitcarder

## Usage

1. Fork 本项目
2. 添加 Secrets，完成参数配置
3. 开启 Actions
4. 设置自动保活（可选）

可以参阅[教程](https://www.zwya.top/posts/21107/)

## LICENSE

Copyright (c) 2021 Zwysun.

Licensed under the [MIT License](https://github.com/Zwysun/HealthCheckin/blob/main/LICENSE)



