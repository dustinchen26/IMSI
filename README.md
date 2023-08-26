# IMSI 工具
online calculate: https://dustinchen26.github.io/IMSI

## Example
```
【1】IMSI 解析
请输入 IMSI (ex: 466660000055241)： 466660000055241
 解析
Mobile Country Code (MCC): 466
Mobile Network Code (MNC): 66
MSIN: 0000055241
Byte = { 0x49, 0x66, 0x66, 0x00, 0x00, 0x50, 0x25, 0x14 }

【2】Byte 反向提取为 IMSI
请输入 Byte (ex: 0x49, 0x66, 0x66, 0x00, 0x00, 0x50, 0x25, 0x14)： 0x49, 0x66, 0x66, 0x00, 0x00, 0x50, 0x25, 0x14
 提取
IMSI: 466660000055241
Mobile Country Code (MCC): 466
Mobile Network Code (MNC): 66
MSIN: 0000055241
```