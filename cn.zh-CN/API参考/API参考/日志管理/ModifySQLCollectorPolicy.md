# ModifySQLCollectorPolicy {#reference_kb5_r23_12b .reference}

## 描述 {#section_l21_v32_12b .section}

开启或关闭指定RDS实例的SQL采集功能。

## 请求参数 {#section_qzx_w32_12b .section}

|名称|类型|是否必须|描述|
|--|--|----|--|
|Action|String|是|系统规定参数，取值：ModifySQLCollectorPolicy。|
|DBInstanceId|String|是|实例名。|
|SQLCollectorStatus|String|是| -   Enable：SQL采集开启
-   Disabled：SQL采集关闭

 |

## 返回参数 {#section_a5x_zlh_12b .section}

|名称|类型|描述|
|--|--|--|
|<公共返回参数\>| |详见[公共参数](cn.zh-CN/API参考/使用API/公共参数.md#)。|

