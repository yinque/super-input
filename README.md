# super-input
超级输入，Windows下的快捷输入工具（待初始化）
# 介绍
快速输入文本，从剪切板记录，预设文本
# 开发计划
## 剪切板
- [ ] 剪切板记录
- [ ] 文本处理，比如复制了一个词组"news section"，自动处理为指定的代码命名风格（snake_case：news_section）、（CamelCase：NewsSection）
## 选区
- [ ] 交换  
交换选区中两个特定的词语，常用于mermaid的时序图中，例如：  
```mermind
sequenceDiagram
  用户->>数据库: 获得数据  
  数据库->>用户: 返回数据  
```
如果使用该功能即可快速交换“用户”与“数据库”  
## 原始文本储存
- [ ] 原始文本
- [ ] 原始文本集合
## 渲染文本
- [ ] 几种常见的格式转换，例如 


空格分隔：
text1  text2  text3 text4  text5  
 

行分隔：  
text1  
text2  
text3  
text4  
text5  


js数组：['text1', 'text2', 'text3', 'text4', 'text5'] 

python字典（2个数组）：{  
'key1':'value1',  
'key2':'value2',  
'key3':'value3',  
'key4':'value4',  
'key5':'value5',  
}

sqlite行数据（n个数组）：  
INSERT INTO Tab (c1, c2, c3, c4, c5) VALUES  
('c1r1', 'c1r2', 'c1r3', 'c1r4', 'c1r5')  
('c2r1', 'c2r2', 'c2r3', 'c2r4', 'c2r5')  
('c3r1', 'c3r2', 'c3r3', 'c3r4', 'c3r5')  
('c4r1', 'c4r2', 'c4r3', 'c4r4', 'c4r5')  
('c5r1', 'c5r2', 'c5r3', 'c5r4', 'c5r5');



## 环境
- [ ] 工作环境切换
