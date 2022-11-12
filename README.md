### 无限循环用于运行一组永无休止的重复指令。

## Bash无限While循环
无限while循环示例：
-----------------
#!/usr/bin/env bash

while :
do
echo "Press [CTRL+C] to exit this loop..."
# Add more instructions here
sleep 2
done
-----------------
## 语法示例:while循环的Unix true命令,true命令的while循环语法示例:
-----------------
#!/usr/bin/env bash

while true
do
echo "Press [CTRL+C] to exit this loop..."
# Add more instructions here
sleep 2
done
-----------------
## 满足特定条件，中断无限循环语法示例:
-----------------
#!/usr/bin/env bash

while true
do
echo "Press [CTRL+C] to exit this loop..."
# Add more instructions here
sleep 2

if [ condition ]
then
break
fi
done
在上面的循环中添加一个if语句以中断匹配条件。
-----------------



