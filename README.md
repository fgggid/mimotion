
| Secrets |  格式  |
| -------- | ----- |
| PMODE |   推送模式,server酱推送:`wx` 新server酱推送:`nwx` tg推送:`tg` 企业微信推送:`qwx` PushPlus推送:`pp` 关闭推送:`off`|
| PKEY |   推送key,详见PKEY参数解释|
| USER |   账号,仅支持手机号|
| PWD |   密码|
| STEP |   步数:0则为1w-2w之间随机,自定义随机范围: `18000-25000`|

| PKEY参数解释 |  格式  |
| -------- | ----- |
| TG推送 |   `token@userid`|
| Server酱推送 |   `填写server酱的推送key`|
| 企业微信推送 |   `推送用户（可@all）-corpid-corpsecret-(agentid 空则为默认1000002)`|
| PushPlus推送 |   `token`|
| 关闭推送 |   `off`|

### 三、多账户(用不上请忽略)

多账户请用 **#** 分割 然后保存到变量 **USER** 和 **PWD**

#### 例如

**13800138000#13800138001** 变量 **USER**

**abc123qwe#abcqwe2** 变量 **PWD**

