、#Linux Shell Output

1. 使用echo打印彩色输出
 ``` 
     RED='\033[0;31m'
     NC='\033[0m' # No Color
     printf "${RED} This is red text ${NC}" 
  or echo -e "${RED} This is red text ${NC}" 
```

