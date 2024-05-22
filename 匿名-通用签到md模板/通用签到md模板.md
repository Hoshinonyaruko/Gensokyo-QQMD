模板名称：通用签到,查询信息模板
使用场景：
用户签到,签到信息查询
----------------------------------------
markdown源码：
![{{.px}}]({{.imageurl}})
# {{.data1}}!
{{.data2}}
{{.data3}}
{{.data4}}
![image #15px #15px]({{.logo1}})![image #15px #15px]
({{.logo2}})![image #15px #15px]({{.logo3}}){{.data5}}
----------------------------------------
使用示例:
![image #640px #640px](https://example.com/ueserhead.png)
# 今日签到成功!
您已连续签到 {{.data2}} 天，获得 {{.data3}} 积分!
本月总积分: {{.data4}}
![image #15px #15px](https://example.com/icon1.png)![image #15px #15px](https://example.com/icon2.png)![image #15px #15px](https://example.com/icon3.png)继续保持，挑战更多奖励!