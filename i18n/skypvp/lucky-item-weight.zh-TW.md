---
group: 功能
---

# 幸运物品权重

:::info{title=信息}
此部分仅限想知道原理的。\
其实只需要知道权重越大抽中的概率越大即可。
:::

## 幸运方块开启时是怎么抽取物品的？

幸运方块开启流程如下：

1. 先将同种品质的所有物品的权重相加。
2. 从 0 到 相加的权重 中取任意值。
3. 判断此值属于哪个物品的区间。

其实由此就能看出，权重越大，被抽中的概率越大。

## GUI 中显示的概率是怎么计算的？

其实如果你看懂了上面的内容，就不难理解。

概率就是用该物品的权重除以所有同品质的物品的权重总和，所得到的百分比。
