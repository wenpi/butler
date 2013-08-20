
通用

自定义返回字段：url?fields=field1,field2,field3

查询某一段数据：url?

查询某个条件数据：url?


### Users

/api/v1/users				GET		读取所有有效的用户

/api/v1/users/<userid>		GET		读取<userid>的用户数据

/api/v1/users				POST	创建用户

/api/v1/users/<userid>		PUT		更新用户信息，如果用户不存在则新建用户

/api/v1/users/<userid>		DELETE	删除用户


### Groups

/api/v1/groups				GET

/api/v1/groups/<groupid>	GET

/api/v1/groups				POST

/api/v1/groups/<groupid>	PUT

/api/v1/groups/<groupid>	DELETE


### Products

/api/v1/products				GET

/api/v1/products/<productid>	GET

/api/v1/products				POST

/api/v1/products/<productid>	PUT

/api/v1/products/<productid>	DELETE


### Devices

/api/v1/devices					GET

/api/v1/devices/<deviceid>		GET

/api/v1/devices					POST

/api/v1/devices/<deviceid>		PUT

/api/v1/devices/<deviceid>		DELETE


### Sensors

/api/v1/devices/<deviceid>/sensors				GET

/api/v1/devices/<deviceid>/sensors/<sensorid>	GET

/api/v1/devices/<deviceid>/sensors				POST

/api/v1/devices/<deviceid>/sensors/<sensorid>	PUT

/api/v1/devices/<deviceid>/sensors/<sensorid>	DELETE


### Datapoints

/api/v1/devices/<deviceid>/sensors/<sensorid>/datapoints                   GET

/api/v1/devices/<deviceid>/sensors/<sensorid>/datapoints/<datapointid>     GET

/api/v1/devices/<deviceid>/sensors/<sensorid>/datapoints                   POST

/api/v1/devices/<deviceid>/sensors/<sensorid>/datapoints/<datapointid>     PUT

/api/v1/devices/<deviceid>/sensors/<sensorid>/datapoints/<datapointid>     DELETE