





http://qd-visual.jd.com:8080/platform/access/:site-detail/h5/:PJV7R/site-detail/h5/PJV7R/pages#/router1/router2/router3?param1=1&param2=:2&p=3&e=3

https://task-test.hanghuicloud.com/work/web/oauth/login?redirect_uri=http://task-pc.hanghuicloud.com 授权登录链接

岗位描述：
1.负责奇点埋点项目前端研发和敏捷迭代
2.负责搜索推荐前端项目开发与维护
3.负责参与奇点埋点标准化、规范化制定，推动各业务团队奇点的接入和治理
4.负责奇点日常维护，解决业务部门提出的问题，并持续改进

任职要求：
1.3年以上前端开发经验，熟练掌握HTML5、CSS3、JS等技能，参与过中大型项目的开发
2.熟练掌握vue或react，能熟练使用vue或react组件库开发项目，比如 Element UI、Vuetify、Ant design 等
3.熟悉前端工程化与模块化开发，能熟练使用 webpack 或 vite 构建前端项目
4.熟练使用echart、G2或G6等生成图表
5.具有良好的分析和解决问题能力，能独立承担任务、按时保质保量完成任务
6.热爱前端技术，注重代码质量
7.有团队精神、善于沟通、责任心强、执行能力强


问题：
1、选择通讯录，没有回显已选择的人，前端处理，已完成
2、选择不同的任务类型，显示不同的模板，前端处理
3、负责人可结束/拒绝/重启流程，需增加一字段，前后端处理，是否需要，不需要
4、接口task/list需要返回附件和图片加起来总数，需要返回负责人名字和头像，后端返回
5、草稿任务编辑时，切换来切换去，本地缓存数据部分会丢失，前端处理，已完成
6、任务详情页优化调整，前端
7、我的切换tab标签时，滚动条没有滑到最上边，已完成
8、搜索功能没做
9、选择地图账号替换
10、云存储改为动态从后端获取加密信息
11、编辑时，如果上一个页面是草稿列表页，则先删除缓存的编辑字段，已完成
12、我的列表和待办，过滤掉草稿类型，后端处理
13、加载上次有些小bug，需调整优化


H5页面录入规范要求

1、如果选择包含关系，录入的页面至少包含一级path路径，不允许只录入域名，然后选择包含关系，比如：msc.jd.com，是不允许的
2、页面pageId自定义时，不能包含特殊字符，只能是数字加字母组合
3、页面URL给出引导提示：
   1. 请确保URL在当前站点内唯一
   2. 建议精确匹配或URL动态匹配录入，告知用户这样能100%正确上报pageId
   3. 选择URL包含匹配时，包含只能是除去参数外的URL，不能是通过截取URL部分作为页面URL
   4. 录入URL时，会校验之前已录入的URL，如发现类似URL，给出提示，比如用户录入了 msc.jd.com/path1，再录入 msc.jd.com/:path1时给出提示，具体
      a：path长度一样，一个为动态URL匹配，另一个为精确或包含匹配
      b：同一个url，一个录入了带参数的，另一个没有录入参数
      c：同一个url，参数录入的顺序不一致
4、统一站点下存在重复的URL，立峰帮推动改掉
