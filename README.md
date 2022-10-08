# vw-fit-screen

vw的大屏适配方案，使用scss预处理器。

##### view

```
1: pnpm install
2: pnpm run serve
```

##### default

默认宽度为`1920 * 1080` 位于文件`styles/unitll.scss`

```scss
$designWidth: 1920;
$designHeight: 1080;
```

##### use

```scss
.{
	width: vw(300);// 300 -> Width of your design drawing
	height: vh(400);// 400 -> Height of your design drawing
}
```



<img src="https://typora-picture-hai.oss-cn-chengdu.aliyuncs.com/img/image-20221008105930919.png" alt="image-20221008105930919" style="zoom:50%;" />



<img src="https://typora-picture-hai.oss-cn-chengdu.aliyuncs.com/img/image-20221008110012292.png" alt="image-20221008110012292" style="zoom:50%;" />

## <img src="https://typora-picture-hai.oss-cn-chengdu.aliyuncs.com/img/image-20221008110103593.png" alt="image-20221008110103593" style="zoom:50%;" />

