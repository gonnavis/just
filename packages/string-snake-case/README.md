## just-snake-case

Part of a [library](https://anguscroll.com/just) of zero-dependency npm modules that do just do one thing.
Guilt-free utilities for every occasion.

[`🍦 Try it`](https://anguscroll.com/just/just-snake-case)

```shell
npm install just-snake-case
```
```shell
yarn add just-snake-case
```

Convert a string to snake case

```js
  import snakeCase from 'just-snake-case';

  snakeCase('the quick brown fox'); // 'the_quick_brown_fox'
  snakeCase('the-quick-brown-fox'); // 'the_quick_brown_fox'
  snakeCase('the_quick_brown_fox'); // 'the_quick_brown_fox'
  snakeCase('theQuickBrownFox'); // 'the_quick_brown_fox'
  snakeCase('thequickbrownfox'); // 'thequickbrownfox'
  snakeCase('the - quick * brown# fox'); // 'the_quick_brown_fox'
  snakeCase('theQUICKBrownFox'); // 'the_q_u_i_c_k_brown_fox'
```
