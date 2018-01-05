##### ACache(修改自杨福海的ACache)
### 超轻量级缓存库，轻量到只有一个类，可缓存的数据格式包括：

* JsonObject 
* Bitmap 
* Object
* String 
* Drawable 
* Byte 
* JsonArray
------
#### 使用方法
#### 通过`ACache.get(Context context)`获取实例
#### `put（）`方法可以存入数据
#### `getXXX()`方法获取数据
#### __V1.2新增__
#### 通过`isExist（you cachekey,dataType）`方法可以判断是否有本地的缓存

**for example:**
   ````java
   acache.isExist("myCachekey",ACache.STRING)  //可以获取是否有此key的本地String缓存
   ````
