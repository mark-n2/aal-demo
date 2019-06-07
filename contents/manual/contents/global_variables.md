# Global Variables

Lecture の `conf.yaml` 中 `global_variables` で，当該 Lecture 中で有効な変数を定義できます．
日付など，毎年修正する必要のある項目に対して使うことを意図しています．
以下は使用例です．

```
week1: &lt;%= @week1 %&gt;
```

week1: <%= @week1 %>


