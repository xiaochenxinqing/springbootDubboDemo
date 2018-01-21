# springbootDubboDemo

## springboot结合dubbo,整合了mybatis+mvn+freemarker+redis+zeekeeper+avtiviti的简单测试样例

* 启动项目前,需要先启动zk和redis

* 如果需要测试activiti,需要本地启动activiti-explorer来进行部署工作流,或者数据库中已经有相关数据,就可以测试,直接用注解方式(@Autowired)引入工作流的各个service即可

*此项目支持热部署,本地修改或新增java文件不要重启项目,刷新浏览器页面即可体现出效果,具体配置参照博客:http://blog.csdn.net/sdzhangshulong/article/details/79011983
