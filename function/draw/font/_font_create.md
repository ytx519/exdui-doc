---
description: 字体_创建自默认字体
---



## 声明

|动态库命令| 返回值类型|库文件名|参数量| 备注|
|:--:|:--:|:--:|:--:|:--:|
| _font_create |  整数型 |  libexdui.dll | 0 | 字体_创建自默认字体，成功返回真(1)，失败返回假(0) |


## 示例

### 易语言

```basic
如果 (_font_create() ＝ 1)
	输出调试文本 (“创建成功”)
 否则
    输出调试文本 (“创建失败”)
```