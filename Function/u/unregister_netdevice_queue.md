# Function: <code>unregister_netdevice_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unregister_netdevice_queue(struct net_device * dev, struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586281680,
      "name": "unregister_netdevice_queue",
      "external": true,
      "loc": "net/core/dev.c:7242",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_release",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/core/dev.c:unregister_netdev",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:mif6_delete",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586281680,
      "name": "unregister_netdevice_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unregister_netdevice_queue(struct net_device * dev, struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586707616,
      "name": "unregister_netdevice_queue",
      "external": true,
      "loc": "net/core/dev.c:7760",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_dellink",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_release",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:unregister_netdev",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586707616,
      "name": "unregister_netdevice_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unregister_netdevice_queue(struct net_device * dev, struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586892496,
      "name": "unregister_netdevice_queue",
      "external": true,
      "loc": "net/core/dev.c:7931",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_dellink",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_release",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:unregister_netdev",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586892496,
      "name": "unregister_netdevice_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unregister_netdevice_queue(struct net_device * dev, struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587017296,
      "name": "unregister_netdevice_queue",
      "external": true,
      "loc": "net/core/dev.c:8125",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_dellink",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_release",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:unregister_netdev",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587017296,
      "name": "unregister_netdevice_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unregister_netdevice_queue(struct net_device * dev, struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587515104,
      "name": "unregister_netdevice_queue",
      "external": true,
      "loc": "net/core/dev.c:8304",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_dellink",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_release",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:unregister_netdev",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587515104,
      "name": "unregister_netdevice_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void unregister_netdevice_queue(struct net_device * dev, struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587856816,
      "name": "unregister_netdevice_queue",
      "external": true,
      "loc": "net/core/dev.c:8554",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_dellink",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_release",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:unregister_netdev",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587856816,
      "name": "unregister_netdevice_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void unregister_netdevice_queue(struct net_device * dev, struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587997200,
      "name": "unregister_netdevice_queue",
      "external": true,
      "loc": "net/core/dev.c:9184",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_dellink",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_release",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:unregister_netdev",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587997200,
      "name": "unregister_netdevice_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void unregister_netdevice_queue(struct net_device * dev, struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588268752,
      "name": "unregister_netdevice_queue",
      "external": true,
      "loc": "net/core/dev.c:9289",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_dellink",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_release",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:unregister_netdev",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588268752,
      "name": "unregister_netdevice_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unregister_netdevice_queue(struct net_device * dev, struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588475104,
      "name": "unregister_netdevice_queue",
      "external": true,
      "loc": "net/core/dev.c:9633",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_dellink",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_release",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:unregister_netdev",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588475104,
      "name": "unregister_netdevice_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void unregister_netdevice_queue(struct net_device * dev, struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589388800,
      "name": "unregister_netdevice_queue",
      "external": true,
      "loc": "net/core/dev.c:10088",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_dellink",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_release",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:unregister_netdev",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589388800,
      "name": "unregister_netdevice_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void unregister_netdevice_queue(struct net_device * dev, struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589354864,
      "name": "unregister_netdevice_queue",
      "external": true,
      "loc": "net/core/dev.c:10797",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_dellink",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_release",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:unregister_netdev",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589354864,
      "name": "unregister_netdevice_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void unregister_netdevice_queue(struct net_device * dev, struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589250800,
      "name": "unregister_netdevice_queue",
      "external": true,
      "loc": "net/core/dev.c:10978",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_dellink",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_release",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:unregister_netdev",
        "net/core/dev.c:register_netdevice",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589250800,
      "name": "unregister_netdevice_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
void unregister_netdevice_queue(struct net_device * dev, struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unregister_netdevice_queue",
      "external": true,
      "loc": "net/core/dev.c:10985",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_dellink",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_release",
        "drivers/net/wwan/wwan_core.c:wwan_rtnl_dellink",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:unregister_netdev",
        "net/core/dev.c:register_netdevice",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592698299,
      "name": "unregister_netdevice_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589975568,
      "name": "unregister_netdevice_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
void unregister_netdevice_queue(struct net_device * dev, struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unregister_netdevice_queue",
      "external": true,
      "loc": "net/core/dev.c:10765",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_dellink",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_release",
        "drivers/net/wwan/wwan_core.c:wwan_rtnl_dellink",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:unregister_netdev",
        "net/core/dev.c:register_netdevice",
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594584617,
      "name": "unregister_netdevice_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071591521872,
      "name": "unregister_netdevice_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void unregister_netdevice_queue(struct net_device * dev, struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unregister_netdevice_queue",
      "external": true,
      "loc": "net/core/dev.c:10760",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_dellink",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_release",
        "drivers/net/wwan/wwan_core.c:wwan_rtnl_dellink",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:unregister_netdev",
        "net/core/dev.c:register_netdevice",
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596325360,
      "name": "unregister_netdevice_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593333232,
      "name": "unregister_netdevice_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void unregister_netdevice_queue(struct net_device * dev, struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unregister_netdevice_queue",
      "external": true,
      "loc": "net/core/dev.c:10776",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_dellink",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_release",
        "drivers/net/wwan/wwan_core.c:wwan_rtnl_dellink",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:unregister_netdev",
        "net/core/dev.c:register_netdevice",
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596855597,
      "name": "unregister_netdevice_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593795040,
      "name": "unregister_netdevice_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void unregister_netdevice_queue(struct net_device * dev, struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unregister_netdevice_queue",
      "external": true,
      "loc": "net/core/dev.c:10987",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/netkit.c:netkit_del_link",
        "drivers/net/netkit.c:netkit_del_link",
        "drivers/net/netkit.c:netkit_new_link",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_dellink",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_release",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:unregister_netdev",
        "net/core/dev.c:register_netdevice",
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597780570,
      "name": "unregister_netdevice_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071594575904,
      "name": "unregister_netdevice_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
void unregister_netdevice_queue(struct net_device * dev, struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502001448,
      "name": "unregister_netdevice_queue",
      "external": true,
      "loc": "net/core/dev.c:9633",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_dellink",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_release",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:unregister_netdev",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502001448,
      "name": "unregister_netdevice_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void unregister_netdevice_queue(struct net_device * dev, struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234766744,
      "name": "unregister_netdevice_queue",
      "external": true,
      "loc": "net/core/dev.c:9633",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_dellink",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_release",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:unregister_netdev",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234766744,
      "name": "unregister_netdevice_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void unregister_netdevice_queue(struct net_device * dev, struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295437136,
      "name": "unregister_netdevice_queue",
      "external": true,
      "loc": "net/core/dev.c:9633",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_dellink",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_release",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:unregister_netdev",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295437136,
      "name": "unregister_netdevice_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void unregister_netdevice_queue(struct net_device * dev, struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278304762,
      "name": "unregister_netdevice_queue",
      "external": true,
      "loc": "net/core/dev.c:9633",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_dellink",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_release",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:unregister_netdev",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278304762,
      "name": "unregister_netdevice_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void unregister_netdevice_queue(struct net_device * dev, struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588081888,
      "name": "unregister_netdevice_queue",
      "external": true,
      "loc": "net/core/dev.c:9633",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_dellink",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_release",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:unregister_netdev",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588081888,
      "name": "unregister_netdevice_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void unregister_netdevice_queue(struct net_device * dev, struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587795456,
      "name": "unregister_netdevice_queue",
      "external": true,
      "loc": "net/core/dev.c:9633",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/vxlan.c:vxlan_exit_batch_net",
        "drivers/net/vxlan.c:vxlan_exit_batch_net",
        "drivers/net/vxlan.c:vxlan_dellink",
        "drivers/net/vxlan.c:__vxlan_dev_create",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_dellink",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_release",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:unregister_netdev",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/ipv4/ip_tunnel.c:ip_tunnel_newlink",
        "net/ipv4/ip_tunnel.c:ip_tunnel_delete_nets",
        "net/ipv4/ip_tunnel.c:ip_tunnel_delete_nets",
        "net/ipv4/ip_tunnel.c:ip_tunnel_dellink",
        "net/ipv4/ip_tunnel.c:ip_tunnel_ioctl",
        "net/ipv4/ip_tunnel.c:ip_tunnel_ioctl",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587795456,
      "name": "unregister_netdevice_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void unregister_netdevice_queue(struct net_device * dev, struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588413664,
      "name": "unregister_netdevice_queue",
      "external": true,
      "loc": "net/core/dev.c:9633",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_dellink",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_release",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:unregister_netdev",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588413664,
      "name": "unregister_netdevice_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void unregister_netdevice_queue(struct net_device * dev, struct list_head * head)
```

```json
{
  "name": "unregister_netdevice_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588552256,
      "name": "unregister_netdevice_queue",
      "external": true,
      "loc": "net/core/dev.c:9633",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_dellink",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/net/ppp/ppp_generic.c:ppp_release",
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:unregister_netdev",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588552256,
      "name": "unregister_netdevice_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
