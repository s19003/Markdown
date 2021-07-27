# 目次
1. [見出し](#見出し1)
1. [リスト](#リスト)
1. [表](#表)
1. [pre記法](#pre記法)
1. [code記法](#code記法)
1. [引用](#引用)

# 見出し1
## 見出し2
### 見出し3
#### 見出し4
##### 見出し5
###### 見出し6

```
# 見出し1
## 見出し2
### 見出し3
#### 見出し4
##### 見出し5
###### 見出し6
```
 
## リスト
- A
  - A_B
    - A_B_C

```
- A
  - A_B
    - A_B_C
```

1. A
    1. A_B
        1. A_B_C

```
1. A
    1. A_B
        1. A_B_C
```

## 表
| HeaderA | HeaderB | HeaderC |
| :-- | :--: | --: |
| 左寄せ | 中央寄せ | 右寄せ |
| A | B | C |

```
| HeaderA | HeaderB | HeaderC |
| :-- | :--: | --: |
| 左寄せ | 中央寄せ | 右寄せ |
| A | B | C |
```

## pre記法
```Java
class Hello {
    public static void main(String[] args) {
        System.out.println("Hello World");        
    }
}
```

~~~
```Java
class Hello {
    public static void main(String[] args) {
        System.out.println("Hello World");        
    }
}
```
~~~

## code記法
インストール方法 : `install markdown`

```
インストール方法 : `install markdown`
```

## 引用
> Google  
> https://www.google.co.jp/
>> Youtube  
>> https://www.youtube.com/

```
> Google  
> https://www.google.co.jp/
>> Youtube  
>> https://www.youtube.com/
```

## リンク
https://www.google.co.jp/  
[Google](https://www.google.co.jp/)  

```
https://www.google.co.jp/  
[Google](https://www.google.co.jp/)  
```

## 折りたたみ
<details>
  <summary>Openrec</summary>
  https://www.openrec.tv/
</details>

```
<details>
  <summary>Openrec</summary>
  https://www.openrec.tv/
</details>
```

*123 abc* _斜体で強調される_  
**123 abc** __太字で強調される__  
***123 abc*** ___斜体と太字で強調される___  
~~取り消し線~~  

```
*123 abc* _斜体で強調される_  
**123 abc あかさ** __太字で強調される(日本語含む)__  
***123 abc*** ___斜体と太字で強調される___  
~~取り消し線~~  
```


