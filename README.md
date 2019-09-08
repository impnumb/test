# Yandex.Checkout API Go Client Library

https://vk.com/music/album/282414735_76079804

[Russian](https://github.com/yandex-money/yandex-checkout-sdk-python/blob/master/README.ru.md) | English

This product is used for managing payments under [The Yandex.Checkout API](https://kassa.yandex.ru/docs/checkout-api/)
For usage by those who implemented Yandex.Checkout using the API method.

## Requirements
* Go 1.x

## Installation
```bash
go get github.com/impnumb/yandex-checkout-sdk-go
```

## Update
```bash
go get -u github.com/impnumb/yandex-checkout-sdk-go
```

## Start using
```go
package main

import "github.com/impnumb/yandex-checkout-sdk-go/yacheckout"

func main(){
  checkout := &yacheckout.Checkout{
    ShopID
  }
}
```
