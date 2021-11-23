
#### 演示图
<table>
<tr>
  <td><img src="https://images.gitee.com/uploads/images/2020/1208/180453_252f5e9f_5469596.png"/></td>
  <td><img src="https://images.gitee.com/uploads/images/2020/1208/180630_ee5b4f46_5469596.png"/></td>
</tr>
<tr>
  <td><img src="https://images.gitee.com/uploads/images/2020/1208/180737_9363e283_5469596.png"/></td>
  <td><img src="https://images.gitee.com/uploads/images/2020/1208/180802_aefb78f4_5469596.png"/></td>
</tr>
<tr>
  <td><img src="https://images.gitee.com/uploads/images/2020/1208/180821_30fc7aaf_5469596.png")"/></td>
  <td><img src="https://images.gitee.com/uploads/images/2020/1208/180844_01ebd7d2_5469596.png")"/></td>
</tr>
<tr>
  <td><img src="https://images.gitee.com/uploads/images/2020/1208/180902_02c8d838_5469596.png"/></td>
  <td><img src="https://images.gitee.com/uploads/images/2020/1208/180918_ff1f7ff5_5469596.png"/></td>
</tr>
<tr>
  <td><img src="https://images.gitee.com/uploads/images/2020/1208/180938_86b39645_5469596.png"/></td>
  <td><img src="https://images.gitee.com/uploads/images/2020/1208/180956_69e25a9c_5469596.png"/></td>
</tr>
<tr>
  <td><img src="https://images.gitee.com/uploads/images/2020/1208/181013_791d92f0_5469596.png"/></td>
  <td><img src="https://images.gitee.com/uploads/images/2020/1208/181032_9f0dbbee_5469596.png"/></td>
</tr>
<tr>
  <td><img src="https://images.gitee.com/uploads/images/2020/1208/181049_099d0169_5469596.png"/></td>
  <td><img src="https://images.gitee.com/uploads/images/2020/1208/181104_914c457a_5469596.png"/></td>
</tr>
</table>


#### 技术体系
- 前端：Vue + Vue-Router + Vuex + ViewUI + vue-enum
- 后端：SpringBoot2 + Mybatis-plus + jwt + druid + mysql
- 前端代码规范smart-front-standard -guide（大力推荐）
- 基于阿里规范之上的后端规范smart-backend-standard-guide（大力推荐）

#### 前端特点
- 高质量的代码、代码结构、和代码注释
- 漂亮的UI，菜单栏、标签页，体验、交互更好用的员工、部门、角色、菜单管理等等
- 优化基于Keepalive的标签页，做到标签页该缓存的时候缓存，比如左右切换等，不该缓存的时候不缓存，比如新建，表单提交结束等
- 前端常量维护: vue-enum，拒绝出现魔法数字，代码不可维护的现象
- 全新的基于前端的权限设计（忘掉传统的权限设计吧，已经不适合这个前端时代）
- 基于websocket的在线人数
- 支持一级、二级、三级菜单，四级菜单以及搜索功能
- 其他功能：邮件、富文本、消息、系统配置等等
- 写不完了，太多好的细节需要你的发现......

#### 后端特点
- 高质量的Java代码、分包结构、和代码注释
- 业内独创的请求返回码维护，非常值得一看
- 基于一个注解和controller的权限设计放弃更复杂的shiro，以及一套数据权限支持
- 四层架构（controller, service, manager, dao）
- 代码阅读性强、扩展性极高的员工、部门、角色、菜单管理
- 基于LRU策略的内存级权限缓存
- 配合前端vue-enum的swagger文档注解
- 心跳服务，让你发现有哪些机器再跑，哪些人在偷偷的跑你的Job
- 自定义的quartz job添加和修改，方便测试人员测试
- smart-reload，为系统预留钩子，动态加载，在不重启程序前提下执行一些代码，你懂的
- 以上只是一些举例，更多灿若繁星的惊喜和细节，等待着你的发现！

#### 前端代码规范
- 文件、文件夹、目录结构、组建、变量等等怎么命名
- html、css、less等如何规范
- vue项目目录结构如何划分
- router和store该怎么划分扩展性更好
- vue组件规范该选择哪些
- 以及更多，数不胜数让你觉得实用，同时身心愉悦的规范

#### 后端代码规范
- 四层架构（controller, service, manager, dao） 是什么，为什么要有四层
- 各个层的代码该怎么写才能让团队配合默契，高度一致
- vo, bo, dto, entity ，各种javabean 怎么区分和使用
- spring的 @Transactional 你用对了吗
- 方法参数个数、注释、todo这些也要有规范，你遵守过吗
- 以上举例，只是沧海一粟，更多的细节等待你的发现！

