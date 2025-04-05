# Interactive Brokers API - GoLang Implement
## Credits: This project is based on the work by github.com/hadrianl/ibapi. 

<img
style="display: block; margin: 0 auto;"
src="http://interactivebrokers.github.io/tws-api/nav_iblogo.png"
/>

* Interactive Brokers API 9.80
* pure golang Implement
* Unofficial, use at you own risk

## INSTALL

`go get -u github.com/hadrianl/ibapi`

---

## USAGE

Implement `IbWrapper` to handle datas delivered via tws or gateway, `Wrapper` in demo is a default implement that just output data to std.
[Go to IbWrapper](https://github.com/hadrianl/ibapi/blob/83846bf1194bbdc4f039c8c66033f717e015e9fc/wrapper.go#L11)

1. **implement** your own `IbWrapper`
2. **connect** to TWS or Gateway
3. **handshake** with TWS or Gateway
4. **run** the loop
5. do some **request**

## Reference

1. [Offical Document](https://interactivebrokers.github.io/tws-api/)
2. [Order Types](https://www.interactivebrokers.com/en/index.php?f=4985)
3. [Product](https://www.interactivebrokers.com/en/index.php?f=4599)
4. [Margin](https://www.interactivebrokers.com/en/index.php?f=24176)
5. [Market Data](https://www.interactivebrokers.com/en/index.php?f=14193)
6. [Commissions](https://www.interactivebrokers.com/en/index.php?f=1590)
