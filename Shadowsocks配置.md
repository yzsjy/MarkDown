# Shadowsocks配置

## 获取Shadwosocks一键脚本文件

```sh
wget —no–check–certificate –O shadowsocks–all.sh https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocks-all.sh
```

## 赋予一键脚本权限

```shell
chmod +x shadowsocks–all.sh
```

## 运行一键脚本文件

```shell
./shadowsocks–all.sh 2>&1 | tee shadowsocks–all.log
```



# Shadowsocks常用功能

## Shadowsocks-livev版本

```shell
/etc/init.d/shadowsocks–libev start
/etc/init.d/shadowsocks–libev stop
/etc/init.d/shadowsocks–libev restart
/etc/init.d/shadowsocks–libev status
```

## Shadowsocks-Python版本

```shell
/etc/init.d/shadowsocks–python start
/etc/init.d/shadowsocks–python stop
/etc/init.d/shadowsocks–python restart
/etc/init.d/shadowsocks–python status
```

## ShadowsocksR版本

```shell
/etc/init.d/shadowsocks–r start
/etc/init.d/shadowsocks–r stop
/etc/init.d/shadowsocks–r restart
/etc/init.d/shadowsocks–r status
```

## Shadowsocks-Go版本

```shell
/etc/init.d/shadowsocks–go start
/etc/init.d/shadowsocks–go stop
/etc/init.d/shadowsocks–go restart
/etc/init.d/shadowsocks–go status
```



# Shadowsocks卸载

```shell
./shadowsocks–all.sh uninstall
```

