# Dynamicwallpaper

项目名称：
    下载dynamicwallpaper.club网站的全部动态壁纸

环境要求：
    -python3
    -科学上网

项目简介：
    -项目中用到的python模块，如网络请求（requests）以及文本解析（etree）皆为python源码自带的模块，无需配置更多环境
    -本项目爬取的网站（https://dynamicwallpaper.club）由于服务器在国外，因此全程需要科学上网进行使用

爬取思路：
    -使用浏览器的开发者工具，捕捉到真实的壁纸下载链接
    -分析真实的下载链接的url参数（共有三个）
    -分步获取各个参数
    -访问壁纸链接，保存其返回的二进制文本至本地文件

改进：
    -此网站有不同类型的壁纸可选，可制作GUI图形界面，让用户以下拉框选择的形式，自行选择下载哪一个类型的壁纸

更多：
    -此网站所有的壁纸链接分享：http://billie52707.cn/true_heic_urls.html

    
