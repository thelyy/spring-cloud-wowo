Eureka注册中心
	在服务治理框架中，通常都会构建一个注册中心，每个服务单元都向注册中心登记自己提供的服务，包括服务的主机ip和端口、服务的版本号、通信协议等一些附加信息
	注册中心按照服务名称分类组织服务清单，同时需要以心跳的机制检查清单中的服务是否可用，若不可用则需要从服务清单中移除，已达到排除故障服务器的效果。
	
搭建步骤：
	1、导包
	2、创建配置文件
	