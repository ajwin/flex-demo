# flex-demo

## 弹性布局小demo
```css
.page-body{
            display: flex;
            flex-direction: row;
            justify-content: space-around;
            align-items: flex-start;
            font-size: 5vw;
            flex-wrap: wrap;
        }
        .page-item{
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .page-item img{
            width: 9em;
            height: 9em;
        }
```
### vw vh em rem 几个值得区分

rem ：针对视口左上角进行排列
xx em 父亲容器的样式大小的XX倍数
xx  vw  (viewportwidth ） 设备视口宽度大小的百分之xx 
xx  vh  (viewportheight ） 设备视口高度大小的百分之xx 

