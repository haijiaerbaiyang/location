## 问题分析： 
实现函数 ToLowerCase()，该函数接收一个字符串参数 str，并将该字符串中的大写字母转换成小写字母，之后返回新的字符串。
## 代码实现
```c
class Solution {
public:
    string toLowerCase(string str) {
        
      for(int i=0;i<str.size();i++){
        if(65<=str[i]&&str[i]<=90){str[i]=str[i]+32;}  
      }
        return str;
    }
};
```
## 总结：
大写字母ASCII码位于65~90，小写字母位于97~122，当字母为大写字母时，将该字母加上32即可。
      
      
      