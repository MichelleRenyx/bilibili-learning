# 仿B站前后端分离微服务项目

## 实现了以下功能：
- 视频的上传、查看、点赞、评论、收藏、弹幕（有分片上传与断点续传实现）
- 用户的个人信息查看编辑、关注
- 用户个人主页权限查看修改、个人主页内容获取
- 图形码、手机号、邮箱登录注册
- 一对一实时私聊
- 文生文、文生图、智能PPT
- 关注UP动态、评论点赞私聊消息的生成与推送
- 视频和用户的聚合搜索、关键字补全、关键字高亮

## 项目亮点
- 重复度极低，项目需求都是作者一比一复刻分析b站功能决定的，在企业招聘需求减少招聘要求提高的当下意味着在简历筛选会得到远高于常人的被感兴趣程度（绝大部分Java人都是做的黑马尚硅谷项目或其余较流行项目，项目上的千篇一律导致hr及面试官对简历感兴趣程度较低，相对不愿意细看简历，且由于这些项目网上资料过多过详细容易被面试官判定为难度较小的项目而不能确定Java人是否高水平，以及对使用这些项目的人简历要求提高甚至见到简历写这些项目就直接丢弃）
- 技术栈相当丰富且贴近企业需求：使用了当下企业开发最常用的可以快速开发单体应用的SpringBoot，保证了下限的基础上引用了SpringCloud系列组件搭建微服务提高上限，并使用了流行中间件Redis、RocketMQ、ElasticSearch，完整覆盖所有公司对Java应届生的要求，技术栈达到要求则过筛选率大大提高，且按需引入技术如实时连接Websocket、转码Jave等，体现出相对于大部分Java人更强的解决需求能力，进一步提供过筛选率，同时更广的技术栈代表可供面试官提问的点更多，也是可以自己提前准备主动引导面试官的点更多
- 技术亮点多：一份好的简历需要有足够多能和面试官细聊的地方，本项目亮点相当多，像分片上传、断点续传、数据同步流程、一对一实时私聊、集成大模型功能及全网首发的给出主题生成ppt所有文案实现等都足够和面试官展示军火相当久且可以延伸出足够多八股，将一场面试节奏完全掌握在自己手中
- 有详细完整最快落地的教程：从部署环境到前后端运行到接口调通有相当完整详细的教程，且运行所需包都可直接从作者文件床中获取无需在官网中找省去麻烦从而最快本机跑通项目功能，并附带项目技术栈使用讲解更快理解项目
- 有配套简历话术：配合现成简历话术极快改进简历，省去大量的反复修改简历时间
  ## 项目演示
https://github.com/user-attachments/assets/109a5b6e-c354-46ef-abf2-14ffede8b725

## 技术栈
- springboot：快速开发Java应用程序
- security：具备强大的鉴权授权
- nacos：服务注册与发现
- openfeign：远程调用服务
- gateway：请求入口与路由网关
- redis：跨服务缓存
- elasticsearch：更快的查询与更高的查询匹配度
- rocketmq：异步处理队列
- minio：文件对象存储
- mybatis-plus：便捷执行单表增删改查
- mybatis-plus-join：业务层多表查询
- druid：阿里数据库连接池
- jwt：token实现形式
- swagger：接口文档
- gson：谷歌序列化转换
- hutool：集成众多工具类省去手动实现工具类
- websocket：实时长连接
- 讯飞星火api：集成大模型功能
- jave：视频操作，转码、压缩、截图、去水印等
- xxl-job：分布式可视化定时任务
- zipkin：请求链路追踪信息可视化ui
- slueth：发送请求链路追踪信息
## 相关教程
- [本机部署环境](https://www.nowcoder.com/discuss/640368532730990592?sourceSSR=users)
- [前后端本机运行](https://www.nowcoder.com/discuss/640865638906384384?sourceSSR=users)
- [前后端接口调通运行](https://www.nowcoder.com/discuss/650364579364581376?sourceSSR=users)
- [简历话术](https://www.nowcoder.com/feed/main/detail/787da9e468f343039b50014739030311?sourceSSR=users)
- [需求分析与需求实现思路](https://www.nowcoder.com/discuss/646784094038151168?sourceSSR=users)
- [技术使用之一篇文章快速掌握redis、mp、es、rocketmq使用](https://www.nowcoder.com/discuss/641707654733123584?sourceSSR=users)
- [技术使用之快速掌握websocket、权限框架、远程调用、接口文档使用](https://www.nowcoder.com/discuss/642011355679064064?sourceSSR=users)
- [技术使用之一文迅速掌握minio、xxl-job、jave的使用](https://www.nowcoder.com/discuss/642468459871240192?sourceSSR=users)
- [技术使用之一文快速掌握链路追踪、异步任务、手机号邮箱号登录、大模型调用](https://www.nowcoder.com/discuss/642820288471703552?sourceSSR=users)

## 项目地址

项目地址：[https://labilibili.com](https://labilibili.com)，演示地址：[https://labilibili.com/video/演示.mp4](https://labilibili.com/video/演示.mp4)，欢迎访问项目，给GitHub点个小星星就更好啦

---
