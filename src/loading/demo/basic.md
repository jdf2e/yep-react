---
order: 0
title: 基础用法
description: 基于 apng 实现的京东 9.0 统一 loading 动画。
---

```js
import React from 'react';
import {Loading} from '@jdcfe/yep-react';

class Demo extends React.PureComponent {
  render() {
    return (
      <div>
        <Loading />
      </div>
    );
  }
}

ReactDOM.render(<Demo />, mountNode);
```
