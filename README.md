# irc100

## Deploy

Action: `Contract6vU3ZWL57jQeFpbuqUxQfL5PGeFJekWrDG2WVGjWqrKx/deploy` `[tick, total, lim]`

- `tick`: 名称
- `total`: 总量
- `lim`: mint限额

## Mint

Action: `Contract6vU3ZWL57jQeFpbuqUxQfL5PGeFJekWrDG2WVGjWqrKx/mint` `[tick, lim]`

- `tick`: 名称
- `lim`: mint数量

## Transfer

Action: `Contract6vU3ZWL57jQeFpbuqUxQfL5PGeFJekWrDG2WVGjWqrKx/transfer` `[tick, id, to]`

- `tick`: 名称
- `id`: irc-100的id
- `to`: 接受者

## List

Action: `Contract6vU3ZWL57jQeFpbuqUxQfL5PGeFJekWrDG2WVGjWqrKx/list` `[tick, id, price]`

- `tick`: 名称
- `id`: irc-100的id
- `price`: 出售价格

## Unlist

Action: `Contract6vU3ZWL57jQeFpbuqUxQfL5PGeFJekWrDG2WVGjWqrKx/unlist` `[tick, id]`

- `tick`: 名称
- `id`: irc-100的id

## Buy

Action: `Contract6vU3ZWL57jQeFpbuqUxQfL5PGeFJekWrDG2WVGjWqrKx/buy` `[tick, id]`

- `tick`: 名称
- `id`: irc-100的id

## 监听

获取transaction的tx_receipt

### deploy

`{op: "deploy", tick: "IOSI", max: "880000000", lim: "1000" }`

### mint

`{op: "mint", tick: "IOSI", amt: "1000", id: "1" }`

### transfer

`{op: "transfer", tick: "IOSI", id: "1", lim: "1000", from: "abc", to: "def" }`

### list

`{op: "list", tick: "IOSI", id: "1", owner: "abc", price: "100" }`

### unlist

`{op: "unlist", tick: "IOSI", id: "1", owner: "abc" }`

### buy

`{op: "buy", tick: "IOSI", id: "1", owner: "abc", price: "100", buyer: "abc", seller: "def" }`
