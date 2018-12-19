### Jacman
百度分析：
将 /layout/_partial/head.ejs 中删除倒数第二行 <%- partial('baidu_analytics') %> 删除掉，解决源代码中出现 2 个分析的代码

其对应的文件为手动添加的代码 /layout/_partial/baidu_analytics.ejs