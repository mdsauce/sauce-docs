---
id: backtrace-test
title: A Backtrace Test Page
sidebar_label: Test Page
---

import useBaseUrl from '@docusaurus/useBaseUrl';
import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

## Header 2 Example
Some Text, a [link](https://google.com)

### Header 3

Some Image:
<img src={useBaseUrl('img/live-testing/device-vitals.png')} alt="Device Vitals" width="450"/>
<Tabs
    defaultValue="Java"
    values={[
    {label: 'Java', value: 'java'},
    {label: 'Python', value: 'python'},
    {label: 'Ruby', value: 'ruby'},
]}>

<TabItem value="java">

```java
bash
```

</TabItem>


<TabItem value="python">

```python
$$
```

</TabItem>

<TabItem value="ruby">

```ruby
rspec
```

</TabItem>
</Tabs>