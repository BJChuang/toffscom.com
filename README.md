# toffscom.com
模板网站
可以，不错，有几点完善下就可以了：

1. 产品名字修改成：Toffs Note (所有地方) （页脚copyright就是公司名正确，不用修改哦）(比如Google LLC, 是公司名，Google Keep, Google Drive就是产品名)
2. logo修改成别的，所有地方。google 搜一下 free logo design, 随便选个改改logo上的文字为 Toffs Note。比如：https://editor.freelogodesign.org/?category=4 
3. / 路径下的 电脑屏幕图片 和 手机屏幕图片 左上角的logo和 Boostnote 用它那块的背景色抹掉。比如mac自带的图片查看工具就可以。
4. /template/all.html 路径下的，左上角产品名点击后应该跳回首页
5. /template/all.html 路径下的，Tutorial Videos 模块去掉，不应该跳到别的产品宣传号里
6. /template/integrations.html，左上角产品名点击后应该跳回首页
7. /template/pricing.html，左上角产品名点击后应该跳回首页
8. /template/pricing.html，️ We are rolling out on 17th January, 2022， 这个去掉，我们的产品已经推出了
9. /template/pricing.html，Learn more → 按钮去掉，不应该跳到别的产品里
10. /template/signin.html，获取验证码功能很好，Signin点击后发个请求/api/signin，不捕获异常，然后alert('Code is invalid')，不跳转页面。
11. /template/signin.html，左上角产品名点击后应该跳回首页
12. /template/signup.html，获取验证码功能很好，Signin点击后发个请求/api/signup，不捕获异常，然后alert('Code is invalid')，不跳转页面。