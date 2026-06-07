### DAY01
- 生成解决方案（.exe）——>开始运行不调试（ctrl+F5） 调试（F10）

- mian函数是函数的入口，C语言默认返回0为正常状态

- ` #include <stdio.h>`:std:标准；i：输入；o：输出
	`include`是C的一条预处理指令

- 常见关键字
`auto、break、case、char、const、continue、default、do、double、else、enum、extern、float、for、goto、if、int、long、register、return、short、signed、sizeof、static、struct、switch、typdef、union、unsigned、void、volatile、while`

- 字符串是特殊的，末尾隐藏一个`\0`,是字符串的结束的标志。

- 转义字符
      `\n`换行
	  `\0`字符串结束
	  `\a`报警
	  `\\`防止\被判断为转义字符
	  `\n`换行符
	  `\t`制表符 
	  `\ddd`表示十进制数字
	  `\xdd`表示十六进制数字
	  转义字符通常也算作strlen中的字符
### DAY02
- 常见的数据类型和变量
     整形(`int`)
     字符型（`char`）
     小数型（`float`）
     布尔（`bool`）
     内置类型
	     数组
	     结构体(`struct`)  	 
	     枚举（`enum`）
	     联合体（`union`）
- `signed`和`unsigned
	`signed表示该类型含正负号
	`unsigned表示该类型不包含正负号，只有0和正数
- 变量
	- 数据类型 变量名
	- 变量在创建的时候赋值，该操作叫做**变量初始化**
	- 变量有全局变量和局部变量，其中局部变量优先
	- 变量创建的本质是在内存中开辟空间
- 内存
	栈区：存放局部变量、函数参数，可以自动申请及释放；空间小
	堆区：存放动态内存，需要手动申请及释放；空间大
	静态区：全局变量、staic变量，程序结束后释放
	常量区：存放游戏额字符串常量
- 常见操作符
	`+-*/%`双目操作符
	`++ --`单目操作符（后置++，先使用，再加1；前置++，先加1，再使用）
### DAY03
-  函数
	函数声明
	函数调用
	函数定义
