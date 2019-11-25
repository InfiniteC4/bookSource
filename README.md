# bookSource
开源阅读软件的自制书源


以下是一个标准单个书源的各个参数的简单解

'''
{
    "bookSourceUrl": "",//书源的地址（一般是网站首页）
    "bookSourceName": "",//书源的名称
    "bookSourceGroup": "",//书源的分组（可空）
    "loginUrl": "",//登录网址（少数需登录站点可能会用到）
    "ruleFindUrl": "",//发现功能（编辑发现按钮进入）
    "ruleFindList": "",//发现列表，某分类或榜单列表类似于搜索结果列表
    "ruleFindName": "",//发现书名，
    "ruleFindAuthor": "",//发现作者，
    "ruleFindKind": "",//发现分类，
    "ruleFindIntroduce": "",//发现简介，
    "ruleFindLastChapter": "",//发现最新章节，
    "ruleFindCoverUrl": "",//发现封面
    "ruleFindNoteUrl": "",//发现跳转书籍页链接
    "ruleSearchUrl": "",//书源的搜索地址
    "ruleSearchList": "",//搜索结果页的书籍显示样式
    "ruleSearchName": "",//搜索结果页的书名
    "ruleSearchAuthor": "",//搜索结果页的作者
    "ruleSearchKind": "",//搜索结果页的书籍分类
    "ruleSearchLastChapter": "",//搜索结果页的最新章节
    "ruleSearchIntroduce": "",//搜索结果页的书籍简介
    "ruleSearchCoverUrl": "",//搜索结果页的书封面
    "ruleSearchNoteUrl": "",//书籍页跳转链接
    "ruleBookUrlPattern": "",//书籍页书名样式正则
    "ruleBookInfoInit": "",//书籍页预处理
    "ruleBookName": "",//书籍介绍页的书名
    "ruleBookAuthor": "",//书籍介绍页的作者
    "ruleCoverUrl": "",//书籍页封面
    "ruleIntroduce": "",//书籍页书籍介绍
    "ruleBookKind": "",//书籍页分类
    "ruleBookLastChapter": "",//书籍页的最新章节
    "ruleChapterUrl": "",//书籍页跳转目录页地址
    "ruleChapterUrlNext": "",//目录页翻页地址（列表有分页）
    "ruleChapterList": "",//目录列表（章节列表）
    "ruleChapterName": "",//章节名称（单章）
    "ruleContentUrl": "",//章节地址（单章）
    "ruleContentUrlNext": "",//章节内容翻页地址
    "ruleBookContent": "",//章节内容正文
    "httpUserAgent": "",//浏览器标识，一般用不到
    "enable": true,//是否启用书源
    "serialNumber": //书源排序，默认即可
    "weight": ,//权重，搜索优先级，默认即可
}
'''


书源制作教程
-https://gedoor.github.io/MyBookshelf/sourcerule.html

第三方书源制作教程
-https://www.52pojie.cn/thread-758541-1-1.html


语法测试
-jsoup语法测试 https://try.jsoup.org
-JSonPath语法测试 http://jsonpath.herokuapp.com
