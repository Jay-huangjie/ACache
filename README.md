<h1>ACache</h1><br>
轻量级缓存库,可缓存的数据格式包括jsonObject bitmap Object String drawable byte jsonarray <br>
使用方法
=======
通过`ACache.get(Context context)`获取实例 <br>

`put（）`方法可以存入数据<br>
`getXXX()`方法获取数据<br>
V1.2新增<br>
通过`isExist（you cachekey,dataType）`方法可以判断是否有本地的缓存<br>
for example:`acache.isExist("myCachekey",ACache.STRING)`可以获取是否有此key的本地String缓存
