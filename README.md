LemonChat协议
===
本文档用于定义LemonChat开放聊天工具的协议



## 基本类型说明

| 类型名称 | 类型长度 | 描述 | 备注 |      |
| -------- | -------- | ---- | ---- | ---- |
| u8       | 1        |      |      |      |
| i8       | 1        |      |      |      |
| u16      | 2        |      |      |      |
| i16      | 2        |      |      |      |
| u32      | 4        |      |      |      |
| i32      | 4        |      |      |      |
| u64      | 8        |      |      |      |
| i64      | 8        |      |      |      |
| f32      | 4        |      |      |      |
| f64      | 8        |      |      |      |
| string   | var      |      |      |      |
| list     | var      |      |      |      |
|          |          |      |      |      |
|          |          |      |      |      |
|          |          |      |      |      |



## Packet

### Ping

| Packet ID | Bound To |
| --------- | -------- |
| 0x01      | Server   |



| Field Name | Field Type | Description |
| ---------- | ---------- | ----------- |
| Payload    | u32        |             |

