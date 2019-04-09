---
order: 2
title:
  zh-CN: 文本组件
  en-US: Text Component
---

## zh-CN

内置不同样式的文本。

## en-US

Provides multiple types of text.

```jsx
import { Typography } from 'antd';

const { Text } = Typography;

ReactDOM.render(
  <div>
    <Text>CDesign</Text>
    <br />
    <Text type="secondary">CDesign</Text>
    <br />
    <Text type="warning">CDesign</Text>
    <br />
    <Text type="danger">CDesign</Text>
    <br />
    <Text disabled>CDesign</Text>
    <br />
    <Text mark>CDesign</Text>
    <br />
    <Text code>CDesign</Text>
    <br />
    <Text underline>CDesign</Text>
    <br />
    <Text delete>CDesign</Text>
    <br />
    <Text strong>CDesign</Text>
  </div>,
  mountNode
);
```
