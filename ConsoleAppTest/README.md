# DMS.EntityFramewokCore  
一、基于EntityFramewokCore框架扩展的基础组件，目前以泛型的方式实现添删改查等操作，其中包扩展分页查询，分组，排序等方法，目前还在完善中

二、实例操作  
1、Get查询  
//FirstOrDefault查询  
var entity = service.FirstOrDefault(q=>q.JobLogId==8);  

//First查询  
entiry=