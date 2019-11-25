# bookSource
开源阅读软件的自制书源

* 以下是一个标准单个书源的各个参数的简单介绍

{
1.    "bookSourceUrl": "",//书源的地址（一般是网站首页）
2.    "bookSourceName": "",//书源的名称
3.    "bookSourceGroup": "",//书源的分组（可空）
4.    "loginUrl": "",//登录网址（少数需登录站点可能会用到）
5.    "ruleFindUrl": "",//发现功能（编辑发现按钮进入）
6.    "ruleFindList": "",//发现列表，某分类或榜单列表类似于搜索结果列表
7.    "ruleFindName": "",//发现书名，
8.    "ruleFindAuthor": "",//发现作者，
9.    "ruleFindKind": "",//发现分类，
10.    "ruleFindIntroduce": "",//发现简介，
11.    "ruleFindLastChapter": "",//发现最新章节，
12.    "ruleFindCoverUrl": "",//发现封面
13.    "ruleFindNoteUrl": "",//发现跳转书籍页链接
14.    "ruleSearchUrl": "",//书源的搜索地址
15.    "ruleSearchList": "",//搜索结果页的书籍显示样式
16.    "ruleSearchName": "",//搜索结果页的书名
17.    "ruleSearchAuthor": "",//搜索结果页的作者
18.    "ruleSearchKind": "",//搜索结果页的书籍分类
19.    "ruleSearchLastChapter": "",//搜索结果页的最新章节
20.    "ruleSearchIntroduce": "",//搜索结果页的书籍简介
21.    "ruleSearchCoverUrl": "",//搜索结果页的书封面
22.    "ruleSearchNoteUrl": "",//书籍页跳转链接
23.    "ruleBookUrlPattern": "",//书籍页书名样式正则
24.    "ruleBookUrlPattern": "",//书籍页书名样式正则
25.    "ruleBookInfoInit": "",//书籍页预处理
26.    "ruleBookName": "",//书籍介绍页的书名
27.    "ruleBookAuthor": "",//书籍介绍页的作者
28.    "ruleCoverUrl": "",//书籍页封面
29.    "ruleIntroduce": "",//书籍页书籍介绍
30.    "ruleBookKind": "",//书籍页分类
31.    "ruleBookLastChapter": "",//书籍页的最新章节
32.    "ruleChapterUrl": "",//书籍页跳转目录页地址
33.    "ruleChapterUrlNext": "",//目录页翻页地址（列表有分页）
34.    "ruleChapterList": "",//目录列表（章节列表）
35.    "ruleChapterName": "",//章节名称（单章）
36.    "ruleContentUrl": "",//章节地址（单章）
37.    "ruleContentUrlNext": "",//章节内容翻页地址
38.    "ruleBookContent": "",//章节内容正文
39.    "httpUserAgent": "",//浏览器标识，一般用不到
40.    "enable": true,//是否启用书源
41.    "serialNumber":4 //书源排序，默认即可
42.    "weight":1 ,//权重，搜索优先级，默认即可


}


* 书源制作教程
- https://gedoor.github.io/MyBookshelf/sourcerule.html

* 第三方书源制作教程
- https://www.52pojie.cn/thread-758541-1-1.html

* 语法测试
- jsoup语法测试 https://try.jsoup.org
- JSonPath语法测试 http://jsonpath.herokuapp.com
