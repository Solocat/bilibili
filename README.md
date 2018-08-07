# bilibili
在家自学完了JavaEE部分，总要有一个做项目的机会。网上找了一圈，如某某商场、某某系统。觉得这种项目太无聊了。恰好在一个博客上有基于ssm框架的哔哩哔哩项目。
于是乎把源码下了下来看了一遍。有的变量甚至有拼写错误、使用拼音等。。很尴尬。
正好我需要练手，所以重构了整个后端的代码，源码并没有很好的进行分层，这里我根据业务模块分了一下层次。
源码里项目里对数据库的操作使用的是JdbcTemplate，我则采取mapper接口映射xml方式对数据库进行读写。由于下载的压缩包里没有资源文件，所以我根据entity实体类建了六张数据库单表。
本项目基于Spring、Springmvc、mybatis框架开发，数据库使用MySQL。前台Jsp、Js、jquerry、Ajax。
后端代码全部由我自己编写，页面上的都是用的源码的源文件，我非原创，也是一个新手，只是通过这种方式将自己所学的知识点做一个总结，期间遇到很多的代码报错，自行百度解决，受益良多。
