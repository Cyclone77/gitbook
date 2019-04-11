# 上下布局组件

## 如何使用

``` typescript
<cy-up-down>
    <ng-template #top>
        <h1>上下布局</h1>
    </ng-template>
    <ng-template #bottom>
        <div>内容</div>                
    </ng-template>
</cy-up-down>
```

## 配置项

参数|说明|类型|默认值
-|-|-|-
[padding]|上半部边距设置|number|0
[setTop]|是否显示上半部分|boolean| true

## 属性
参数|说明|类型|默认值
-|-|-|-
top|上半部分内容（如果为空则setTop=false）|ElementRef|-
bottom|下半部分内容|ElementRef|-
