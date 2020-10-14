# yaojianjuruishu
药监局瑞数反爬学习

---

* 贴逆向好的js代码..剩下靠你们自己了

* 需要返回cookie,否则无限跳转,文件夹中带有nginx静态服务配置

* 启动nginx后,并在hosts中添加一行app1.nmpa.gov.cn [你nginx服务器的ip],浏览器访问http://app1.nmpa.gov.cn/data_nmpa/face3/base.jsp 即可调试js

---

### 增加2020年10月14号的逆向学习代码
* 1.对代码格式
* 2.处理控制流平坦化,减少对键盘伤害
* 3.对加密方法名解密,减少对鼠标伤害


#### 备注:base.jsp为删除多余代码并格式化后的代码,base.jsp.eval.js为处理后代码

#### 快速阅读:
* base.jsp 搜索call快速找到eval的入口
* base.jsp.eval.js	搜索"_$B7[0]"这里是控制流平坦化代码的开始,搜索"console.log(cookie);"这里是更新cookie的地方

---

白嫖邮箱:2605326000@qq.com

