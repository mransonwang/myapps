# 说明
本项目是一个用于部署微服务应用的Chart，该应用包含若干微服务及依赖的后端服务，所有微服务和后端服务均以子Chart的形式存在
后端服务部署方式多样，其中MySQL通过镜像直接部署，Redis通过初始化CR实例的方式部署，Consul则是以Chart的方式部署

所有子Chart的参数配置均通过顶级目录下的values.yaml进行控制