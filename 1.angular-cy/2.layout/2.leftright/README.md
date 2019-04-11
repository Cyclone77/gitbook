# 左右布局组件

## 如何使用

``` typescript
<cy-left-right [leftwidth]="260">
    <ng-template let-scope="psnData" #left>
        <h3>左右布局</h3>
    </ng-template>
    <ng-template #right>
        <div>内容</div>                
    </ng-template>
</cy-left-right>
```

## 配置项

参数|说明|类型|默认值
-|-|-|-
[leftwidth]|左边宽度|number|0

## 属性
参数|说明|类型|默认值
-|-|-|-
left|左边部分内容|ElementRef|-
right|右边部分内容|ElementRef|-
