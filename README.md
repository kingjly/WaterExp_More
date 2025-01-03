
![30x30](https://user-images.githubusercontent.com/96420060/179494641-89ede898-38fb-42dd-b0e2-d36d643dd847.jpg)


# WaterExp：一款面向安服仔的扫描报告模板 和 碰瓷工具 
█ 打工人新时代的摸鱼解决方案，安抚仔挖不到洞的最后一丝欢颜！
  
    （不产生实际攻击）  
    （不会getshell）  
    （面向水报告）  
什么红队蓝队的，要什么shell，老夫日站就是看响应头缺啥一把梭，只要看得过去就能过！

# MoreWater：比原来更水的版本！

## 致谢
感谢原作者 [@linshaoSec](https://github.com/linshaoSec) 的 [WaterExp](https://github.com/linshaoSec/WaterExp) 项目！
本项目在原项目基础上进行了功能增强和扩展。

原本以为已经够水了？惊喜来了！
这次我们带来了更多的"水分"，让你的报告更有技术深度！

## 这波更新有啥亮点？

### 响应头检测
在原有基础上，我们新增了更全面的检测：
- HSTS
- X-Content-Type-Options
- X-XSS-Protection
- Referrer-Policy
- X-Permitted-Cross-Domain-Policies

一个不少，一个不落，让你的报告更加全面！

### HTTP方法检测
不仅仅是TRACE，现在PUT、DELETE、PATCH都纳入检测范围
每个不安全方法都能被精准捕获，报告内容更加丰富~

### 报错信息检测
PHP版本泄露也逃不过我们的法眼
把潜在的信息泄露风险一网打尽！

## 使用方式还是那么简单
```bash
py3 WaterExp.py -u http://www.target.com
py3 WaterExp.py -f urls.txt
```

## 最后说两句
- 发现新的检测点？欢迎分享~
- 一起让安全检测更加精准！

记住：不是每个安服仔都需要getshell，但每个安服仔都要会写报告！


# 配合《专业水报告漏洞模板.docx》食用更舒服
# 使用方式：
    py3 WaterExp.py -u http://www.target.com
    py3 WaterExp.py -f urls.txt

    扫描完毕复制漏洞名称
    打开模板文档
    ctrl+a打开微信截图，
    圈上对应响应头
    粘贴上文字
    粘贴到模板文档对应位置
    复制到新文档
    好了，可以出报告了
#渗透模板
![image](https://user-images.githubusercontent.com/96420060/179387550-4ed2491b-1ccd-4849-8387-2d9e57148f6d.png)

# 运行截图

![image](https://user-images.githubusercontent.com/96420060/189296502-106c8c34-8982-4f6d-a60a-61ddd1f8c7ac.png)

扫描结果
![image](https://user-images.githubusercontent.com/96420060/179387420-0bc4d65c-5d74-4ea4-a476-23b6409c8c48.png)

# 编程，免杀，工具开发 深入交流小圈子
绕过您有更多的好检测的洞请告诉我添加进去哦~
互相帮助才能打更好的工，摸更漂亮的鱼过期加拉哦

![image](https://user-images.githubusercontent.com/96420060/189295166-8e2a46f4-b9b0-4339-9e5d-7389334dca7a.png)

![image](https://user-images.githubusercontent.com/96420060/195889411-34b82fd4-8f22-416c-b781-d3b256a00d2b.png)


# Star
[![Stargazers over time](https://starchart.cc/linshaoSec/WaterExp.svg)](https://starchart.cc/linshaoSec/WaterExp)
