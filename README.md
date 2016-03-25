## 友好速搭地址库

### JSON地址库

address.json为友好速搭的现有地址库，之后更新会同步维护github上的json库。

单个地址行政区域结构说明如下：

Example:
```
//[当前编码,[简体名称,繁体名称],上一级编码（如顶级则为null）]
["110000",["北京","北京"],null]
```
### 开放API地址库接口

在开放API中，包括以下接口：
* [Country](https://docs.youhaosuda.com/app/s/554092400abc3e4e1100005f)
* [Province](https://docs.youhaosuda.com/app/s/55409af10abc3e4ea0000002)
* [City](https://docs.youhaosuda.com/app/s/55409e790abc3e4ea0000008)
* [District](https://docs.youhaosuda.com/app/s/5540a0ed0abc3e4ea0000010)

Example:
```
{
    "district": {
        "code": "440305",
        "full_name": "南山区",
        "id": "440305",
        "name": "南山"
    }
}
```

### JSSDK地址库接口

参考[area的SDK](https://docs.youhaosuda.com/development/s/5574063a0abc3e090c000004)，这个是基于address.json的一个js封装。

