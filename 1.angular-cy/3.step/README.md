# 步骤条组件

## 如何使用

``` typescript
<cy-step [(StepSource)]="StepSource" [SelectorStepIndex]="SelectorStepIndex">
    <!-- <ng-template #container let-title="title" let-content="content">
        <div> {{ title }}</div>
        <div> {{ content }}</div>
    </ng-template> -->
</cy-step>
```
``` js
  StepSource = [{
    date: '2019-02-02',
    content: '内容1'
  }, {
    date: '2019-02-04',
    content: '内容2'
  }, {
    date: '2019-02-05',
    content: '内容2'
  }];
```
## 实例
https://stackblitz.com/edit/angular-ng-cy-ui-step


## 配置项

参数|说明|类型|默认值
-|-|-|-
[StepSource]|数据源|{}| 如果不用template模版则必须包含date, content属性
[SelectorStepIndex]|当前步骤|number| -

## 属性
参数|说明|类型|默认值
-|-|-|-
container|自定义内容|ElementRef|-

## 数据类型
参数|说明|类型|默认值
-|-|-|-
date|显示时间|date|-
content|显示内容|string|-
disabled|是否禁用选择时间|boolean| false