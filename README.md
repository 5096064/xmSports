> 小米运动 `bash mimotion.sh $PARAMETER`  

####  Fork本仓库使用AC每天自动运行
进入仓库后点击 `Settings`，右侧栏点击 `Secrets`，点击 `New secret`。添加 `PARAMETER` 的值为脚本支持的参数，间隔符使用空格即可:
| Secrets参数 | 含义 |
| -------- | ----- |
| `18812345678@password@10000-20000` | 账号@密码@随机步数起止点,可多次传入支持多账号 |
| `token@*** chat_id@***` | 为telegram bot通知所需参数，无则不进行信息通知 |