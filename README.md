# 入门

## 先决条件

* go 1.19 +
* mysql
* [Genshin Impact](https://genshin.hoyoverse.com/) 3.1.5x - 3.2.0

## 编译

```
git clone --recurse-submodules https://github.com/mari-track/MariGS.git
cd MariGS
go mod tidy # 安装依赖
go build cmd/server/main.go # 编译
```

{% hint style="info" %}
项目属于起步阶段，功能少且不完善.
{% endhint %}
