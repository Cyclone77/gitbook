# 标记组件用法

## 如何使用
```markup
<cy-doc-sign [TempHTML]="TempHTML" [(TempData)]="TempData"></cy-doc-sign>
```
### TempHTML模版数据
```typescript
   this.http.get('assets/1.html', { responseType: 'text' })
      .subscribe(data => this.TempHTML = data);
```
下载 assets/[1.html](./1.html)

### TempData标记数据
<details>
  <summary>测试数据</summary>
  <pre>
    <code>
  TempData = {
    OtherData: [{
      tag: '单位',
      text: '测试单位',
      records: [{
        name: '2019-02-01 交互：',
        content: '测试1',
      },
      {
        name: '2019-02-02 交互：',
        content: '测试2',
      },
      {
        name: '2019-02-03 交互：',
        content: '测试3',
      },
      {
        name: '2019-02-03 交互：',
        content: '测试3',
      },
      {
        name: '2019-02-03 交互：',
        content: '测试3',
      },
      {
        name: '2019-02-03 交互：',
        content: '测试3',
      }]
    }, {
      tag: '时间',
      text: '2019年4月8日 15:04:14',
      records: [{
        name: '2019-02-04 交互：',
        content: '测试1',
      }, {
        name: '2019-02-05 交互：',
        content: '测试2',
      }]
    }],
    TableData: [
      [{
        '招聘单位': '测试单位1',
        '核定岗位总数': 2,
        '实有数': 3,
        '空缺数': 4
      }, {
        '招聘单位': '测试单位2',
        '核定岗位总数': 22,
        '实有数': 33,
        '空缺数': 44
      }, {
        '招聘单位': '测试单位3',
        '核定岗位总数': 222,
        '实有数': 333,
        '空缺数': 444
      }],
      [{
        '招聘单位': '测试单位11',
        '核定岗位总数': 21,
        '实有数': 31,
        '空缺数': 41
      }, {
        '招聘单位': '测试单位22',
        '核定岗位总数': 221,
        '实有数': 331,
        '空缺数': 441
      }]
    ]
  };
    </code>
  </pre>
</details>

## cy-doc-sign 设置

参数 | 说明 | 类型 | 默认值
-|-|-|-
[TempHTML] | 显示的模版文件 | string | -
[TempData] | 标记绑定的值 | EventEmitter:CyTempData | -



