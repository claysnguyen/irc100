# irc100

## Deploy

Action: `Contract6vU3ZWL57jQeFpbuqUxQfL5PGeFJekWrDG2WVGjWqrKx/deploy` `[tick, total, lmt]`

## Mint

Action: `Contract6vU3ZWL57jQeFpbuqUxQfL5PGeFJekWrDG2WVGjWqrKx/mint` `[tick, lmt]`

## Transfer

Action: `Contract6vU3ZWL57jQeFpbuqUxQfL5PGeFJekWrDG2WVGjWqrKx/transfer` `[tick, id, to]`

## List

Action: `Contract6vU3ZWL57jQeFpbuqUxQfL5PGeFJekWrDG2WVGjWqrKx/list` `[tick, id, price]`

## Unlist

Action: `Contract6vU3ZWL57jQeFpbuqUxQfL5PGeFJekWrDG2WVGjWqrKx/unlist` `[tick, id]`

## Buy

Action: `Contract6vU3ZWL57jQeFpbuqUxQfL5PGeFJekWrDG2WVGjWqrKx/buy` `[tick, id]`

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
