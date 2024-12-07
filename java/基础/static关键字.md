[# Java基础—static关键字（包括static内存原理)](https://blog.csdn.net/weixin_54555405/article/details/142077598?ops_request_misc=%257B%2522request%255Fid%2522%253A%25227728164c778d2dc7b56e0ddca20d23ae%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fblog.%2522%257D&request_id=7728164c778d2dc7b56e0ddca20d23ae&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~blog~first_rank_ecpm_v1~rank_v31_ecpm-1-142077598-null-null.nonecase&utm_term=static&spm=1018.2226.3001.4450)

### static静态变量

## 特点
- 被该类所有的对象共享
- 不属于对象，属于类
- 使用的现象：如果一个static静态成员变量被读个对象引用，当值被修改，所有对象的值都会被修改；
## 内存图

![[Pasted image 20241207095119.png]]
![[Pasted image 20241207095048.png]]