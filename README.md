# fetch_baidu_index

目的：本项目主要是用来抓取百度指数的值。因为百度指数为了防止抓取，将数字转成了图片。

# 运行步骤:
1.修改baidu_index/config.ini要启用的浏览器driver, 因为有些人PhantomJS配置可能有问题，默认使用Firefox(容易配置).
  具体参考selenium的浏览器环境配置。讨论区里面，jxlwqq这位朋友说用selenium的2.53.6版本，安装firefox 45 版本，并禁止浏览器自动升级。

2.修改baidu_index/config.ini里面的百度账号跟密码

3.修改baidu_index/config.ini中的start_date和end_date，如果不配置可以查询到这个关键词数据的最大区间

4. 可自主修改baidu_index/config.ini中的其他配置,
   如: num_of_threads,file_name_encoding,index_type_list,area_list

5. 修改task.txt，这是关键词的任务列表，一行一个。

6.执行 python main.py

# 如果对你有帮助，请点个赞吧，真心求赞!有什么意见或者问题也请反馈，我在这里会经常维护的。
