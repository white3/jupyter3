# Update/development log(更新/开发日志)

## 简介

根据时间戳记录整体开发进度与更新内容。
## 2020-01-06
1、开发端成功配置SpringBoot并启动成功。
## 2020-01-08
1、Spring Data JPA测试成功。  
2、基于微信实现了微信小程序用户登录接口。  
3、实现WeChatUser用户类，用于辅助微信用户个人资料管理。
## 2020-01-10
1、实现观测适宜度的业务层测试  
2、实现jwt对token的实现，包括jwt工具类，并测试通过。
## 2020-01-11
1、实现jwt对登录服务的链接。  
2、修复登录问题，前后端成功对接。  
3、实现日出日落业务层测试。  
## 2020-01-12
1、实现对question实体类的创立。  
2、增加questionController试题业务层。  

## 2020-01-13
1、实现试题数据库与模块数据库的链接，完成数据的标准化和处理。  
2、实现试题接口API业务层。  
3、完全实现实时数据API接口和服务（近400行代码）。

## 2020-01-14
1、实现分页搜索、模块搜索接口业务层服务层。  
2、实现根据id搜索试题。  
3、实现随机生成试题（基于登录用户）。  
4、实现试题搜索模块。  
5、实现用户答题记录类。  

## 2020-01-15
1、实现用户答题记录添加API。  
2、实现图片映射。  
3、实现数据库总练习数量和正确率排行榜视图。  

##  2020-01-16 
1、实现部署服务器的全面测试。  
2、实现两个排行榜的查询接口。

## 2020-01-17至2020-01-23放了鸽子
1、1718日去了兰考，19日同学聚会。  
2、20日回老家，21日白天和22日上午在研究ES并导入数据，22下午回老家。

## 2020-01-23
1、完成elastic Search的接口和本地链接配置。    
2、实现了ES分布式集群，并成功导入11000余条数据。  
3、成功实现模糊查询接口，目前尚待完善。   
4、0.5后端预览版即将发布，敬请期待。  
同时，服务器配置已经测试成功，备案已经提交。

## 2020-01-24
1、完成恒星查询的接口，至此0.5测试版已经完成。 
V0.5Beta主要功能：  
1、接口包括上一版本所有接口，包括实时数据，试题练习，恒星查询的业务模块。  
2、新版本新增试题的答题记录和恒星查询的高性能搜索引擎检索，以及试题排行榜。

下一阶段主要任务：包括优化观测适宜度评价算法，设计试题推荐算法，设计完善架构和其余边缘业务，设计前端与后台管理演示系统等。

## 2020-01-27  
1、完成八大行星接口，月球月相接口和天象日历接口，至此基本业务完成。  

## 2020-01-29
完成算法逻辑。  （28日完成毕业设计写作提纲）  

## 2020-01-30  
完成算法分词测试和分词筛选。   

## 2020-01-31  
实现微服务体系监控功能，覆盖所有的监控，并集成监控模块。  

## 2020-02-01
实现积分系统内容，包括：  
1、积分的增加，查询；  
2、积分的验证，以及当日积分，总积分，当日各个项目积分的反馈接口。  
3、完成用户资料修改接口，新建试题反馈类并完成反馈提交接口。目前暂缺试题维护添加修改接口和公告板模块。  
## 2020-02-02
1、完成排行榜，包括积分排行和挑战排行。  
2、完成试题的修改和增加接口  
3、完成公告板模块。  