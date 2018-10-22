# Auerbach CMDB系统产品文档
------
## 简介
系统专门为运维人员打造的配置管理数据库（CMDB）平台，它由一个面向用户的WEB系统和一个面向应用程序的接口系统组成，提供了丰富的接口API。  
## 术语定义
1. **模型**    
模型定义的是一类资产，也可以形象的类比为数据库中的一张表，里面你可以定义需要存储的字段。
2. **模型关系**    
模型关系定义的是模型与模型之间存在的关系，模型关系约束了当前模型资产与其他模型资产的关系。
3. **仓库**    
仓库是具体存放资产数据的资源池。
4. **资产**    
资产是存放了某个模型的具体数据。
5. **资产关系**    
资产关系描述的是具体的某个资产与其他资产的关系。

## 功能介绍
- 简洁、灵活的配置模型
- 多样化的API接口
- Excel批量导入导入资产
- 简单的定时任务管理
- 图形化的相关数据展示     

## 操作指南     
1. **模型管理**      
1.1. [新建/编辑模型](newmodel.md)   
1.2. [编辑模型关系](modelRelation.md)     
2. **资产管理**      
2.1. [新建编辑资产](newProperty.md)      
2.2. [编辑资产关系](PropertyRelation.md)  
2.3. [资产导入](PropertyImport.md)  
2.4. [资产搜索](PropertySearch.md)     
  
## API接口  

1. **模型操作相关API**    
1.1. [模型获取](modelAPI1.md)      
1.2. [模型关系获取](modelAPI2.md)      
1.3. [模型新增](modelAPI3.md)      
1.4. [模型更新](modelAPI4.md)     
1.5. [模型删除](modelAPI5.md)      
1.6. [模型关系新增](modelAPI6.md)     
1.7. [模型关系更新](modelAPI7.md)     
1.8. [模型关系删除](modelAPI8.md)     
2. **资产操作相关API**   
2.1. [资产获取](PropertyAPI1.md)      
2.2. [资产关系获取](PropertyAPI2.md)   
2.3. [资产搜索](PropertyAPI3.md)   
2.4. [资产新增](PropertyAPI4.md)   
2.5. [资产更新](PropertyAPI5.md)   
2.6. [资产删除](PropertyAPI6.md)   
2.7. [资产关系新增](PropertyAPI7.md)   
2.8. [资产关系删除](PropertyAPI8.md)   
