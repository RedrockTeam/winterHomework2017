# 2017-2018 WEB研发部寒假大作业

- 1前端 + 1后端 组队完成 自行组队, 两人一组
- 组完队队伍负责人把 你们的信息, 发到 `web@redrock.team`
 
 如: 后端李立平和前端李丽萍在一起了, 负责人李立平, 发邮件到 `web@redrock.team`
 
```
标题: 
   李立平-李丽萍-知乎
内容: 
   前端: 李丽萍, 后端: 李立平
   项目: 知乎
```

- 如果没有找到队友的, 做下面的 **单人作业** , 邮箱发送格式如下:

```
标题: 
   李立平-知乎
内容: 
   项目: 知乎 (单人)
```


- 旨在让你们从实战角度提升能力, 善用搜索, 感受WEB的强大
- 作业提交时间为:`开学第一周周末, 第二学期第一节课之前` 
- 作业提交形式: GitHub, (到时候通知) 并在第一节课检查作业时向大家介绍你们的作品，希望到时候能看到你
- 没完成并提交的自动退出, 希望你们珍惜寒假的时间:)
- **禁止**互相推锅，**沟通**很重要，我知道肯定会发生队友坑了的情况, 给你几条路: 

    1. 你也跟着坑
    2. 自己顶上去
    3. 只做前端/后端, 会给你适当打分, 

- 到时候不准说是队友的问题，我只会认为你们没沟通好。这是一个提升能力的过程，禁止抄袭（后果很严重）。
- 有任何问题的，除了在群里问，也可以发起issue
- 寒假有问题的, 私聊或者@管理员 (群主肯定在打麻将

### 双人套作业

##### 基本说明

- 以下可选题目任选其一
- 页面不崩是基本要求，最新版chrome能看
- 前端界面美观, 有后端管理界面, 有基本的CRUD功能
- 后端开发全部面向对象

##### 加分项

- 有自己的域名, 服务器
- https
- 输入验证
- 前端语义化, 使用HTML5标签
- 使用CSS3制作前端动画
- 考虑安全性 (比如前端xss,后端sql注入)
- 考虑性能因素
- 考虑缓存

##### 须知

- 前端 **不可以使用** 任何库或者框架
- 后端 不知道

#### 知乎

1. 首页
2. 问题列表页面和详情页面(可以回答问题, 对回复进行评论, 删除自己的问题和答案)
3. 个人资料页面(登录, 修改个人资料, 上传头像)
4. 后台管理页面(可以对问题进行管理)
5. 其他功能: 赞同/踩问题, 收藏, 搜索
6. \[选做\]分享到微博贴吧空间
7. \[选做\]搜索

#### 博客

1. 至少要有主页、文章内容页、后台管理
2. 主页有文章的链接
3. 文章内容页要有评论功能
4. 后台管理需要登陆，能够分别对文章和评论进行增删改查
5. \[选做\]: 搜索
6. \[选做\]相册: 对缩略图的处理, 图片上传
7. \[选做\]日志分类/标签
8. \[选做\]日历，在日历上显示自己今天是否有博文，点击当天日期后可跳转至当天博文列表, 后台删除
9. \[选做\]时间轴，把所有的日志显示在一条轴上，实在不懂就百度。

#### B站

1. 用户登录注册
2. 视频文件上传
3. 视频播放/评论
4. 视频分类
5. 搜索:视频根据视频标签和标题进行搜索
6. 后台管理系统:视频管理 用户管理
7. \[选做\]**弹幕功能**
    + 可以做用户等级, 自己想等级制度, 等级越高, 发的弹幕越大
    + 比如说一级的时候弹幕是h5标签, 二级的时候弹幕是h4标签
8. \[选做\]浏览历史, 收藏功能


### 单人作业

> 后端应该都会有伙伴, 下面三个必做

+ 切图 [下载psd](https://hongyan.cqupt.edu.cn/files/mentum.psd)
    - 页面布局不要崩
    - 把 `Ajax` 封装好供下面用，**考核题第 7 题**
    - 轮播要写出来, 图片用这个地址 `http://123.207.89.151/jrtt/carousel` (到时候图可能有点丑，不要在意)
    - 上面轮播地址是用 `Ajax` 来请求渲染
    - 能用 iconfont 的用 iconfont, 也可以尝试用 CSS  Sprite

+ 用 `canvas` 做一个画板
+ 写一个非自慰版的弹幕
    - 用 `CSS3` 做动画
    - 有输入验证，防止 xss
    - 可选字体大小、 颜色等
    - 用 `localStorage/sessionStorage` 存取数据 
    - [进阶] 自学 [Node.js](https://nodejs.org/en/) , 把上一条改成存数据库
    - [进阶] 封装成一个弹幕类
    - [其他] 靠自己脑洞添加功能，比如: 视频弹幕存入时间等，视频到了某一时间显示相应时间弹幕...

### 其他

#### 前端必备的技能

+ HTML
    - 语义化
    - HTML5

+ CSS
    - 阅读代码的技能
    - CSS 布局技能
    - 盒模型技能
    - CSS3
        + transtion
        + transfrom
        + animate

    - CSS选择器

+ JS
    - 数组(重点)
        + pop
        + map
        + forEach ...

    - 对象(重点)
        + 原型
        + 原型链

    - 函数(重点)
        + 作用域链
        + call, apply, bind
        + 回调
        + 闭包
        + 高阶函数
        + 柯里化

    - 正则表达式（可选掌握， 可暂时不要求）
    - AJAX (重点中的重点)
    - Window API
        + `setTimeout, setInterval` 基本用法
        + `location`对象
        + `navigator`对象

    - DOM API （重点）

        + 啥是DOM树
        + 删除节点， 创建节点， 节点类型
        + 获取元素属性
        + CSS 操作`(style, getComputedStyle)`
        + `querySelector, querySelectorAll `的选择器

    - 事件 (重点)

        + 冒泡和捕捉
        + 基本浏览器事件`（load, click, mouseover, mouseout, blur ...）`
        + 如何阻止事件冒泡
        + addEventListener

    - canvas

    - localStorage/sessionStorage

    - CSS3 动画

    - 响应式布局

    - JavaScript高级程序设计

    - [阮一峰的 es6](es6.ruanyifeng.com)

    - Node.js
