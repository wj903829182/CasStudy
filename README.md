# CasStudy
CAS自定义开发

 
一 CAS服务端开发

1，采用maven的overlays方式覆盖war包的文件方式自定义开发，存在相同文件则覆盖
2，修改cas.properties文件，修改默认的采用语言，默认的登入用户名和密码

#默认使用中文配置文件

locale.default=zh_CN #en

#默认的用户名和密码

accept.authn.users=jack::123456
