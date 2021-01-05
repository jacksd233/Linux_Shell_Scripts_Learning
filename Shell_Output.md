、#Linux Shell Output

1. 使用echo打印彩色输出
 ``` 
     RED='\033[0;31m'
     NC='\033[0m' # No Color
     printf "${RED} This is red text ${NC}" 
  or echo -e "${RED} This is red text ${NC}" 
```
  MacOS使用`\x1B`, linux使用`\e`, 全平台使用`\033`.
  常用颜色为`重置=0，黑色=40，红色=41，绿色=42，黄色=43，
蓝色=44，洋红=45，青色=46，白色=47。` 
  同理，<b>背景色</b>输出为`重置=0，黑色=40，红色=41，绿色=42，黄色=43，蓝色=44，洋红=45，青色=46，白色=47`

2. 
