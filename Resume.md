<center>
 <h1> 李智健 </h1>
     <div>
         <span>
             <img src="assets/phone-solid.svg" width="18px">
             13261806700
         </span>
         ·
         <span>
             <img src="assets/envelope-solid.svg" width="18px">
             zjli2000@gmail.com
         </span>
           ·
         <span>
             <img src="assets/info-circle-solid.svg" width="18px">
             2000.01.15
         </span>
         <br/>
         <span>
             <img src="assets/Github-brands.svg" width="18px">
             <a href="https://github.com/lizhijian-cn">lizhijian-cn</a>
         </span>
         ·
         <span>
             <img src="assets/rss-solid.svg" width="18px">
             <a href="https://www.yuque.com/zhijian-jli3z/pnxvgg">My Blog</a>
         </span>
     </div>
</center>


## <img src="assets/graduation-cap-solid.svg" width="30px"> 教育经历

- **本科	北京航空航天大学	软件工程**                																										   2018.09~2022.06

## <img src="assets/briefcase-solid.svg" width="30px"> 实习经历

- **美团	闪购技术部	Java工程师** 																																2021.05~2021.09

   我们组负责外卖闪购业务的**API网关服务** ，提供接口给客户端和小程序的闪购频道。
   
   网关服务的比较重视两点：
   
   1. 服务的稳定性。网关是整个服务链路的起始点，需要比较多的服务保障措施。
   2. 吞吐能力和接口耗时。API服务从业务形态上就是一个聚合下游服务的集成服务，其内部的执行逻辑可以抽象成是对一系列逻辑单元的有序执行。为了提高吞吐能力，降低接口耗时，现在的技术方案是将这一系列逻辑单元按照依赖关系编排成有向无环图，异步化执行。

## <img src="assets/tools-solid.svg" width="30px">技能清单

- 对Java并发编程相关的知识有一定了解
- 对CMS GC有一定了解
- 对熔断、限流、降级等服务稳定性手段有一定了解


## <img src="assets/project-diagram-solid.svg" width="30px"> 项目经历

- **品牌金刚落地页**

  背景：用户想要购买品牌商品，需要先进入店铺，然后再寻找，没有品牌商品直接和用户触达的路径，PM希望增加新的落地页，使用户可以浏览附近门店中属于同一品牌的商品

  方案：基于LBS召回门店，算法部门将门店商品实时清洗生成候选的商品集，最后再将商品集按照一定规则过滤，返回展示。

- **IM系统**

  分布式系统大作业，支持单聊, 账户/好友系统, 离线信息存储等功能
  分为两个模块, 模块之间通过 RPC 通信.

  * 用户模块与客户端通过 HTTP 协议连接, 负责登录注册, 添加好友, 离线消息同步等功能. 同时也是整个系统的数据层, 负责持久化数据
  * 聊天模块与客户端通过 TCP 长连接相连, 只负责在用户间转发消息. 如果用户处于未登录状态, 就转发到数据层保存。

## <img src="assets/honor-solid.svg" width="30px"> 校内荣誉

- 2020-2021 学年二等奖学金

