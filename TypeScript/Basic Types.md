# typescript基本数据类型

![](images/types.png)
### 1. boolean类型
![](images/boolean.png)
```
let isDone: boolean = false;
```
### 2. number类型

![](images/number.jpg)
```
let decimal: number = 6;
let hex: number = 0xf00d;
let binary: number = 0b1010;
let octal: number = 0o744;
```
### 3. string类型

![](images/string.png)
```
let name: string = "bob";
name = "smith";
```
### 4. Array数组

第一种，可以在元素类型后面接上 []，表示由此类型元素组成的一个数组：
```
let list: number[] = [1, 2, 3];
```

第二种方式是使用数组泛型，Array<元素类型>：
```
let list: Array<number> = [1, 2, 3];
```
### 5. Tuple元组
```
let x: [string, number];
```
### 6. enum枚举
```
enum Color {Red, Green, Blue};
let c: Color = Color.Green;
```
默认情况下，从0开始为元素编号。 你也可以手动的指定成员的数值。
```
enum Color {Red = 0, Green =1, Blue =2};
```

### 7. any任意值
```
let notSure: any = 4;
```

### 8. void空值

它表示没有任何类型。
```
let unusable: void = undefined;
```





#### 参考资料：
> 1. http://www.jikexueyuan.com/course/281_1.html?ss=1
> 2. http://www.tslang.cn/docs/handbook/basic-types.html
> 3. http://www.typescriptlang.org/docs/handbook/basic-types.html

