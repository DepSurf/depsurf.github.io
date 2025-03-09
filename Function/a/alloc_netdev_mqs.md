# Function: <code>alloc_netdev_mqs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct net_device * alloc_netdev_mqs(int sizeof_priv, const char * name, unsigned char name_assign_type, void (*)(struct net_device *) setup, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_netdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586298320,
      "name": "alloc_netdev_mqs",
      "external": true,
      "loc": "net/core/dev.c:7062",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ethernet/eth.c:alloc_etherdev_mqs",
        "net/802/fc.c:alloc_fcdev",
        "net/802/fddi.c:alloc_fddidev",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586298320,
      "name": "alloc_netdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1081
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct net_device * alloc_netdev_mqs(int sizeof_priv, const char * name, unsigned char name_assign_type, void (*)(struct net_device *) setup, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_netdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586726528,
      "name": "alloc_netdev_mqs",
      "external": true,
      "loc": "net/core/dev.c:7579",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ethernet/eth.c:alloc_etherdev_mqs",
        "net/802/fc.c:alloc_fcdev",
        "net/802/fddi.c:alloc_fddidev",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586726528,
      "name": "alloc_netdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1043
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct net_device * alloc_netdev_mqs(int sizeof_priv, const char * name, unsigned char name_assign_type, void (*)(struct net_device *) setup, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_netdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586912400,
      "name": "alloc_netdev_mqs",
      "external": true,
      "loc": "net/core/dev.c:7749",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ethernet/eth.c:alloc_etherdev_mqs",
        "net/802/fc.c:alloc_fcdev",
        "net/802/fddi.c:alloc_fddidev",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586912400,
      "name": "alloc_netdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1021
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct net_device * alloc_netdev_mqs(int sizeof_priv, const char * name, unsigned char name_assign_type, void (*)(struct net_device *) setup, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_netdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587018240,
      "name": "alloc_netdev_mqs",
      "external": true,
      "loc": "net/core/dev.c:7938",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs",
        "net/802/fc.c:alloc_fcdev",
        "net/802/fddi.c:alloc_fddidev",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587018240,
      "name": "alloc_netdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 958
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct net_device * alloc_netdev_mqs(int sizeof_priv, const char * name, unsigned char name_assign_type, void (*)(struct net_device *) setup, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_netdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587515984,
      "name": "alloc_netdev_mqs",
      "external": true,
      "loc": "net/core/dev.c:8117",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs",
        "net/802/fc.c:alloc_fcdev",
        "net/802/fddi.c:alloc_fddidev",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587515984,
      "name": "alloc_netdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 957
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
struct net_device * alloc_netdev_mqs(int sizeof_priv, const char * name, unsigned char name_assign_type, void (*)(struct net_device *) setup, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_netdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_netdev_mqs",
      "external": true,
      "loc": "net/core/dev.c:8380",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs",
        "net/802/fc.c:alloc_fcdev",
        "net/802/fddi.c:alloc_fddidev",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587860455,
      "name": "alloc_netdev_mqs.cold.157",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071587827888,
      "name": "alloc_netdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 999
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
struct net_device * alloc_netdev_mqs(int sizeof_priv, const char * name, unsigned char name_assign_type, void (*)(struct net_device *) setup, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_netdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_netdev_mqs",
      "external": true,
      "loc": "net/core/dev.c:9010",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs",
        "net/802/fc.c:alloc_fcdev",
        "net/802/fddi.c:alloc_fddidev",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588000831,
      "name": "alloc_netdev_mqs.cold.165",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071587960544,
      "name": "alloc_netdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 991
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct net_device * alloc_netdev_mqs(int sizeof_priv, const char * name, unsigned char name_assign_type, void (*)(struct net_device *) setup, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_netdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_netdev_mqs",
      "external": true,
      "loc": "net/core/dev.c:9115",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:blackhole_netdev_init",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs",
        "net/802/fc.c:alloc_fcdev",
        "net/802/fddi.c:alloc_fddidev",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588311869,
      "name": "alloc_netdev_mqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071588275328,
      "name": "alloc_netdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 991
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
struct net_device * alloc_netdev_mqs(int sizeof_priv, const char * name, unsigned char name_assign_type, void (*)(struct net_device *) setup, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_netdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_netdev_mqs",
      "external": true,
      "loc": "net/core/dev.c:9453",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:blackhole_netdev_init",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs",
        "net/802/fc.c:alloc_fcdev",
        "net/802/fddi.c:alloc_fddidev",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588518282,
      "name": "alloc_netdev_mqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071588480944,
      "name": "alloc_netdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1004
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct net_device * alloc_netdev_mqs(int sizeof_priv, const char * name, unsigned char name_assign_type, void (*)(struct net_device *) setup, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_netdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_netdev_mqs",
      "external": true,
      "loc": "net/core/dev.c:9909",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:blackhole_netdev_init",
        "drivers/net/loopback.c:loopback_net_init",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ethernet/eth.c:alloc_etherdev_mqs",
        "net/802/fc.c:alloc_fcdev",
        "net/802/fddi.c:alloc_fddidev",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:mif6_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589392086,
      "name": "alloc_netdev_mqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071589348320,
      "name": "alloc_netdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 831
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
struct net_device * alloc_netdev_mqs(int sizeof_priv, const char * name, unsigned char name_assign_type, void (*)(struct net_device *) setup, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_netdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_netdev_mqs",
      "external": true,
      "loc": "net/core/dev.c:10603",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:blackhole_netdev_init",
        "drivers/net/loopback.c:loopback_net_init",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ethernet/eth.c:alloc_etherdev_mqs",
        "net/802/fc.c:alloc_fcdev",
        "net/802/fddi.c:alloc_fddidev",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:mif6_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591629340,
      "name": "alloc_netdev_mqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071589356608,
      "name": "alloc_netdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 853
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
struct net_device * alloc_netdev_mqs(int sizeof_priv, const char * name, unsigned char name_assign_type, void (*)(struct net_device *) setup, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_netdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_netdev_mqs",
      "external": true,
      "loc": "net/core/dev.c:10775",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:blackhole_netdev_init",
        "drivers/net/loopback.c:loopback_net_init",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ethernet/eth.c:alloc_etherdev_mqs",
        "net/802/fc.c:alloc_fcdev",
        "net/802/fddi.c:alloc_fddidev",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:mif6_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591572758,
      "name": "alloc_netdev_mqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071589253008,
      "name": "alloc_netdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1046
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct net_device * alloc_netdev_mqs(int sizeof_priv, const char * name, unsigned char name_assign_type, void (*)(struct net_device *) setup, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_netdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_netdev_mqs",
      "external": true,
      "loc": "net/core/dev.c:10782",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:blackhole_netdev_init",
        "drivers/net/loopback.c:loopback_net_init",
        "drivers/net/wwan/wwan_core.c:wwan_rtnl_alloc",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ethernet/eth.c:alloc_etherdev_mqs",
        "net/802/fc.c:alloc_fcdev",
        "net/802/fddi.c:alloc_fddidev",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:mif6_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592698475,
      "name": "alloc_netdev_mqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071589978528,
      "name": "alloc_netdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1063
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct net_device * alloc_netdev_mqs(int sizeof_priv, const char * name, unsigned char name_assign_type, void (*)(struct net_device *) setup, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_netdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_netdev_mqs",
      "external": true,
      "loc": "net/core/dev.c:10555",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:blackhole_netdev_init",
        "drivers/net/loopback.c:loopback_net_init",
        "drivers/net/wwan/wwan_core.c:wwan_rtnl_alloc",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ethernet/eth.c:alloc_etherdev_mqs",
        "net/802/fc.c:alloc_fcdev",
        "net/802/fddi.c:alloc_fddidev",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:mif6_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594584022,
      "name": "alloc_netdev_mqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071591504320,
      "name": "alloc_netdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1082
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct net_device * alloc_netdev_mqs(int sizeof_priv, const char * name, unsigned char name_assign_type, void (*)(struct net_device *) setup, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_netdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593274080,
      "name": "alloc_netdev_mqs",
      "external": true,
      "loc": "net/core/dev.c:10550",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:blackhole_netdev_init",
        "drivers/net/loopback.c:loopback_net_init",
        "drivers/net/wwan/wwan_core.c:wwan_rtnl_alloc",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ethernet/eth.c:alloc_etherdev_mqs",
        "net/802/fc.c:alloc_fcdev",
        "net/802/fddi.c:alloc_fddidev",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:mif6_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593274080,
      "name": "alloc_netdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct net_device * alloc_netdev_mqs(int sizeof_priv, const char * name, unsigned char name_assign_type, void (*)(struct net_device *) setup, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_netdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593729936,
      "name": "alloc_netdev_mqs",
      "external": true,
      "loc": "net/core/dev.c:10564",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:blackhole_netdev_init",
        "drivers/net/loopback.c:loopback_net_init",
        "drivers/net/wwan/wwan_core.c:wwan_rtnl_alloc",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ethernet/eth.c:alloc_etherdev_mqs",
        "net/802/fc.c:alloc_fcdev",
        "net/802/fddi.c:alloc_fddidev",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:mif6_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593729936,
      "name": "alloc_netdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct net_device * alloc_netdev_mqs(int sizeof_priv, const char * name, unsigned char name_assign_type, void (*)(struct net_device *) setup, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_netdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594509328,
      "name": "alloc_netdev_mqs",
      "external": true,
      "loc": "net/core/dev.c:10774",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:blackhole_netdev_init",
        "drivers/net/loopback.c:loopback_net_init",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ethernet/eth.c:alloc_etherdev_mqs",
        "net/802/fc.c:alloc_fcdev",
        "net/802/fddi.c:alloc_fddidev",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:mif6_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594509328,
      "name": "alloc_netdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1169
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct net_device * alloc_netdev_mqs(int sizeof_priv, const char * name, unsigned char name_assign_type, void (*)(struct net_device *) setup, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_netdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502003416,
      "name": "alloc_netdev_mqs",
      "external": true,
      "loc": "net/core/dev.c:9453",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:blackhole_netdev_init",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs",
        "net/802/fc.c:alloc_fcdev",
        "net/802/fddi.c:alloc_fddidev",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502003416,
      "name": "alloc_netdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 900
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct net_device * alloc_netdev_mqs(int sizeof_priv, const char * name, unsigned char name_assign_type, void (*)(struct net_device *) setup, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_netdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234753200,
      "name": "alloc_netdev_mqs",
      "external": true,
      "loc": "net/core/dev.c:9453",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:blackhole_netdev_init",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs",
        "net/802/fc.c:alloc_fcdev",
        "net/802/fddi.c:alloc_fddidev",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234753200,
      "name": "alloc_netdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 836
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct net_device * alloc_netdev_mqs(int sizeof_priv, const char * name, unsigned char name_assign_type, void (*)(struct net_device *) setup, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_netdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295449568,
      "name": "alloc_netdev_mqs",
      "external": true,
      "loc": "net/core/dev.c:9453",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:blackhole_netdev_init",
        "drivers/net/loopback.c:loopback_net_init",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs",
        "net/802/fc.c:alloc_fcdev",
        "net/802/fddi.c:alloc_fddidev",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295449568,
      "name": "alloc_netdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1256
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct net_device * alloc_netdev_mqs(int sizeof_priv, const char * name, unsigned char name_assign_type, void (*)(struct net_device *) setup, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_netdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278298982,
      "name": "alloc_netdev_mqs",
      "external": true,
      "loc": "net/core/dev.c:9453",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:blackhole_netdev_init",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs",
        "net/802/fc.c:alloc_fcdev",
        "net/802/fddi.c:alloc_fddidev",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278298982,
      "name": "alloc_netdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 784
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
struct net_device * alloc_netdev_mqs(int sizeof_priv, const char * name, unsigned char name_assign_type, void (*)(struct net_device *) setup, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_netdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_netdev_mqs",
      "external": true,
      "loc": "net/core/dev.c:9453",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:blackhole_netdev_init",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs",
        "net/802/fc.c:alloc_fcdev",
        "net/802/fddi.c:alloc_fddidev",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588125018,
      "name": "alloc_netdev_mqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071588087728,
      "name": "alloc_netdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1004
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
struct net_device * alloc_netdev_mqs(int sizeof_priv, const char * name, unsigned char name_assign_type, void (*)(struct net_device *) setup, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_netdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_netdev_mqs",
      "external": true,
      "loc": "net/core/dev.c:9453",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:blackhole_netdev_init",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs",
        "net/802/fddi.c:alloc_fddidev",
        "net/ipv4/ip_tunnel.c:__ip_tunnel_create",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587837850,
      "name": "alloc_netdev_mqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071587800720,
      "name": "alloc_netdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1004
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
struct net_device * alloc_netdev_mqs(int sizeof_priv, const char * name, unsigned char name_assign_type, void (*)(struct net_device *) setup, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_netdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_netdev_mqs",
      "external": true,
      "loc": "net/core/dev.c:9453",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:blackhole_netdev_init",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs",
        "net/802/fc.c:alloc_fcdev",
        "net/802/fddi.c:alloc_fddidev",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588456842,
      "name": "alloc_netdev_mqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071588419504,
      "name": "alloc_netdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1004
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
struct net_device * alloc_netdev_mqs(int sizeof_priv, const char * name, unsigned char name_assign_type, void (*)(struct net_device *) setup, unsigned int txqs, unsigned int rxqs)
```

```json
{
  "name": "alloc_netdev_mqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_netdev_mqs",
      "external": true,
      "loc": "net/core/dev.c:9453",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:blackhole_netdev_init",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs",
        "net/802/fc.c:alloc_fcdev",
        "net/802/fddi.c:alloc_fddidev",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588593619,
      "name": "alloc_netdev_mqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071588544896,
      "name": "alloc_netdev_mqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1004
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
