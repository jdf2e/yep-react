---
order: 0
title: 基础用法
description:
---

```js
import React from 'react';
import {Stepper} from '@jdcfe/yep-react';

class Demo extends React.PureComponent {
  render() {
    return (
      <div>
        <Stepper
          onChange={n => {
            console.log(n);
          }}
        />
      </div>
    );
  }
}

ReactDOM.render(<Demo />, mountNode);
```