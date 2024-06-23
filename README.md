# Serv00 和 ct8 - 控制面板自动登录脚本
为了支持ct8， 在原版修改后不能只有数字，要全域名
## 使用方法
　　在 GitHub 仓库中，进入右上角`Settings`，在侧边栏找到`Secrets and variables`，点击展开选择`Actions`，点击`New repository secret`，然后创建一个名为`ACCOUNTS_JSON`的`Secret`，将 JSON 格式的账号密码字符串作为它的值，如下格式：  
```
[  
  { "username": "qinshihuang", "password": "linux.do", "panelnum": "panel*.serv00.com" },  
  { "username": "zhaogao", "password": "daqinzhonggong", "panelnum": "panel*.ct8.pl" },  
  { "username": "heiheihei", "password": "shaibopengke", "panelnum": "panel*.serv00.com" }  
]
```
> 其中`panelnum`参数为面板~编号~地址，即为你所收到注册邮件的`panel*.serv00.com`中的`*`数值。

## 贡献
|姓名|主页|内容|
| :------------: | :------------: | :------------: |
|linzjian666|https://github.com/linzjian666|增加多面板支持|

## 参考信息
|  名称 |来源|地址|
| :------------: | :------------: | :------------: |
|Limkon|Github|https://github.com/Limkon|
