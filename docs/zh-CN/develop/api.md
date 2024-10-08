# API List

NapCatQQ 实现了 [OneBot 11](https://11.onebot.dev/) 以及 [go-cqhttp](https://docs.go-cqhttp.org/api) 的大部分 API，对于 API 的详细说明请自行点击相关链接查看。

## 连接方式支持情况

| 连接方式           | 可用  |
| ------------------ | :---: |
| HTTP 接口调用      |   ✔   |
| HTTP POST 事件上报 |   ✔   |
| HTTP POST 快速操作 |   ✔   |
| 正向 WS 连接       |   ✔   |
| 反向 WS 连接       |   ✔   |

## API 支持情况

::: details OneBot 11 API

| 功能                 | Api                     | 可用  | 备注                   |
| -------------------- | ----------------------- | :---: | ---------------------- |
| 获取 bot 账号信息    | get_login_info          |   ✔   |                        |
| 发送消息             | send_msg                |   ✔   |                        |
| 发送群聊消息         | send_group_msg          |   ✔   |                        |
| 发送好友消息         | send_private_msg        |   ✔   | 不支持主动临时消息         |
| 获取消息详情         | get_msg                 |   ✔   |                        |
| 撤回消息             | delete_msg              |   ✔   |                        |
| 点赞                 | send_like               |   ✔   |                       |
| 获取好友列表         | get_friend_list         |   ✔   |                        |
| 处理好友请求         | set_friend_add_request  |   ✔   |                        |
| 获取群列表           | get_group_list          |   ✔   |                        |
| 获取群信息           | get_group_info          |   ✔   |                        |
| 获取群成员列表       | get_group_member_list   |   ✔   |                        |
| 获取群成员信息       | get_group_member_info   |   ✔   |                        |
| 获取群荣誉信息       | get_group_honor_info    |   ✔   |                        |
| 设置群组专属头衔     | set_group_special_title |   ❌   |                        |
| 群匿名禁言           | set_group_anonymous_ban |   ❌   |                        |
| 开关群匿名           | set_group_anonymous     |   ❌   |                        |
| 处理加群请求         | set_group_add_request   |   ✔   |                        |
| 退群                 | set_group_leave         |   ✔   |                        |
| 群踢人               | set_group_kick          |   ✔   |                        |
| 群禁言               | set_group_ban           |   ✔   |                        |
| 全群禁言             | set_group_whole_ban     |   ✔   |                        |
| 设置管理员           | set_group_admin         |   ✔   |                        |
| 设置群名片           | set_group_card          |   ✔   |                        |
| 设置群名             | set_group_name          |   ✔   |                        |
| 获取陌生人信息       | get_stranger_info       |   ✔   |                         |
| 获取版本信息         | get_version_info        |   ✔   |                        |
| 获取状态             | get_status              |   ✔   |                        |
| 检查能否发送图片     | can_send_image          |   ✔   |                        |
| 检查能否发送语音     | can_send_record         |   ✔   |                        |
| 获取图片详情         | get_image               |   ✔   |                        |
| 获取语音文件         | get_record              |   ✔   |                        |
| 获取文件详情         | get_file                |   ✔   |                        |
| 获取 Cookies         | get_cookies             |   ✔   |                        |
| 获取 CSRF Token      | get_csrf_token          |   ❌   |                        |
| 获取 QQ 相关接口凭证 | get_credentials         |   ❌   |                        |
| 重启 OneBot 实现     | set_restart             |   ✔   |                        |
| 清理缓存             | clean_cache             |   ✔   |                        |

:::

::: details go-cqhttp API

| Api                      | 可用  |
| ------------------------ | :---: |
| send_forward_msg         |   ✔   |
| send_private_forward_msg |   ✔   |
| send_group_forward_msg   |   ✔   |
| get_forward_msg          |   ✔   |
| upload_group_file        |   ✔   |
| download_file            |   ✔   |
| get_essence_msg_list     |   ✔   |
| _get_group_notice        |   ✔   |
| _send_group_notice       |   ✔   |
| _del_group_notice        |   ✔   |
| get_group_system_msg     |   ✔   |
| ocr_image                |   ✔   |
| get_online_clients       |   ✔   |

:::

## 接口文档
[完整参考文档](./NapCat.md)
