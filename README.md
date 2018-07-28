# tianti-tool
本Project持续提供常见应用的包装类，目前包括：redis、kafka、mysql数据库读写分离操作、swagger的demo使用等等。该Project目前都是基于Spring Boot来构建，后续会持续更多的应用操作。<br>

1、tianti-kafka。<br>
  ![image](https://raw.githubusercontent.com/xujeff/tianti-tool/master/screenshots/tianti-kafka.png)  
 （1）、KafkaApplication.java------kafka启动类。<br>
 （2）、package com.jeff.tianti.tool.kafka.config------kafka生产者和消费者配置类。<br>
 （3）、package com.jeff.tianti.tool.kafka.controller------kafkad的Producer端控制器层。<br>
 （4）、package com.jeff.tianti.tool.kafka.dto------kafka传输的消息对象封装层。<br>
 （5）、package com.jeff.tianti.tool.kafka.enums------kafka主题枚举层。<br>
 （6）、package com.jeff.tianti.tool.kafka.listener------kafka监听器层。<br>
 （7）、package com.jeff.tianti.tool.kafka.service------kafkad服务层。<br>
 （8）、src/main/resources------kafka配置文件层。<br>

2、tianti-readwrite。<br>
  ![image](https://raw.githubusercontent.com/xujeff/tianti-tool/master/screenshots/tianti-readwrite.png)  
 （1）、ReadWriteApplication.java------读写分离启动类。<br>
 （2）、package com.jeff.tianti.tool.readwrite.annotation------注解层。<br>
 （3）、package com.jeff.tianti.tool.readwrite.aop------aop层。<br>
 （4）、package com.jeff.tianti.tool.readwrite.config.dbconfig------配置层。<br>
 （5）、package com.jeff.tianti.tool.readwrite.controller------控制层。<br>
 （6）、package com.jeff.tianti.tool.readwrite.dao------dao层。<br>
 （7）、package com.jeff.tianti.tool.readwrite.module------module层。<br>
 （8）、package com.jeff.tianti.tool.readwrite.service------service层。<br>
 （9）、src/main/resources------tianti-swagger配置文件层。<br>

3、tianti-redis。<br>
  ![image](https://raw.githubusercontent.com/xujeff/tianti-tool/master/screenshots/tianti-redis.png)  
 （1）、RedisApplication.java------redis启动类。<br>
 （2）、package com.jeff.tianti.tool.redis.config------配置层。<br>
 （3）、package com.jeff.tianti.tool.redis.controller------控制层。<br>
 （4）、package com.jeff.tianti.tool.redis.dto------dto层。<br>
 （5）、package com.jeff.tianti.tool.redis.service------service层。<br>
 （6）、src/main/resources------tianti-redis配置文件层。<br>

4、tianti-swagger。<br>
  ![image](https://raw.githubusercontent.com/xujeff/tianti-tool/master/screenshots/tianti-swagger.png) <br>
 （1）、SwaggerApplication.java------swagger启动类。<br>
 （2）、package com.jeff.tianti.tool.swagger.config------配置层。<br>
 （3）、package com.jeff.tianti.tool.swagger.controller------控制层。<br>
 （4）、package com.jeff.tianti.tool.swagger.model------module层。<br>
 （5）、src/main/resources------tianti-swagger配置文件层。<br>
