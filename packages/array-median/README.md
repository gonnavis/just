## just-median

Part of a [library](https://anguscroll.com/just) of zero-dependency npm modules that do just do one thing.
Guilt-free utilities for every occasion.

[`🍦 Try it`](https://anguscroll.com/just/just-median)

```shell
npm install just-median
```
```shell
yarn add just-median
```

Return the median value of an array of numbers

```js
import median from 'just-median';

median([1, 2, 3, 4, 5]); // 3
median([3, -1, 2]); // 2
median([9, 14, 14, 200, 15]); // 14
median(1, 2, 4, 3); // 2.5
median(['3', 2, 1]); // throws
median(); // throws
```
