# WaterExp_More：比原来更水的版本！

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

![image](https://user-images.githubusercontent.com/96420060/195889411-34b82fd4-8f22-416c-b781-d3b256a00d2b.png)


# Star
[![Stargazers over time](https://starchart.cc/linshaoSec/WaterExp.svg)](https://starchart.cc/linshaoSec/WaterExp)
