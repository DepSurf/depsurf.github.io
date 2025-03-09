# Function: <code>free_netdev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void free_netdev(struct net_device * dev)
```

```json
{
  "name": "free_netdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586276192,
      "name": "free_netdev",
      "external": true,
      "loc": "net/core/dev.c:7179",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:loopback_dev_free",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/virtio_net.c:virtnet_remove",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/xen-netfront.c:xennet_free_netdev",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586276192,
      "name": "free_netdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
void free_netdev(struct net_device * dev)
```

```json
{
  "name": "free_netdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586702576,
      "name": "free_netdev",
      "external": true,
      "loc": "net/core/dev.c:7696",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:loopback_dev_free",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/virtio_net.c:virtnet_remove",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/xen-netfront.c:xennet_free_netdev",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586702576,
      "name": "free_netdev",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void free_netdev(struct net_device * dev)
```

```json
{
  "name": "free_netdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586888944,
      "name": "free_netdev",
      "external": true,
      "loc": "net/core/dev.c:7867",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:loopback_dev_free",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/xen-netfront.c:xennet_free_netdev",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586888944,
      "name": "free_netdev",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void free_netdev(struct net_device * dev)
```

```json
{
  "name": "free_netdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587013248,
      "name": "free_netdev",
      "external": true,
      "loc": "net/core/dev.c:8054",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/xen-netfront.c:xennet_free_netdev",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/dev.c:netdev_run_todo",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/ethernet/eth.c:devm_free_netdev",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587013248,
      "name": "free_netdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
void free_netdev(struct net_device * dev)
```

```json
{
  "name": "free_netdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587511680,
      "name": "free_netdev",
      "external": true,
      "loc": "net/core/dev.c:8233",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/xen-netfront.c:xennet_free_netdev",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/dev.c:netdev_run_todo",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/ethernet/eth.c:devm_free_netdev",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587511680,
      "name": "free_netdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
void free_netdev(struct net_device * dev)
```

```json
{
  "name": "free_netdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587827584,
      "name": "free_netdev",
      "external": true,
      "loc": "net/core/dev.c:8492",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/xen-netfront.c:xennet_remove",
        "drivers/net/xen-netfront.c:netfront_probe",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/dev.c:netdev_run_todo",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/ethernet/eth.c:devm_free_netdev",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587827584,
      "name": "free_netdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
void free_netdev(struct net_device * dev)
```

```json
{
  "name": "free_netdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587960240,
      "name": "free_netdev",
      "external": true,
      "loc": "net/core/dev.c:9122",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/xen-netfront.c:xennet_remove",
        "drivers/net/xen-netfront.c:netfront_probe",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/dev.c:netdev_run_todo",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/ethernet/eth.c:devm_free_netdev",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587960240,
      "name": "free_netdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
void free_netdev(struct net_device * dev)
```

```json
{
  "name": "free_netdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588275024,
      "name": "free_netdev",
      "external": true,
      "loc": "net/core/dev.c:9227",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/xen-netfront.c:xennet_remove",
        "drivers/net/xen-netfront.c:netfront_probe",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/dev.c:netdev_run_todo",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/ethernet/eth.c:devm_free_netdev",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588275024,
      "name": "free_netdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void free_netdev(struct net_device * dev)
```

```json
{
  "name": "free_netdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588480640,
      "name": "free_netdev",
      "external": true,
      "loc": "net/core/dev.c:9569",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/xen-netfront.c:xennet_remove",
        "drivers/net/xen-netfront.c:netfront_probe",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/dev.c:netdev_run_todo",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ethernet/eth.c:devm_free_netdev",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588480640,
      "name": "free_netdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
void free_netdev(struct net_device * dev)
```

```json
{
  "name": "free_netdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589347984,
      "name": "free_netdev",
      "external": true,
      "loc": "net/core/dev.c:10024",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:loopback_net_init",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/xen-netfront.c:xennet_remove",
        "drivers/net/xen-netfront.c:xennet_create_dev",
        "net/devres.c:devm_free_netdev",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/dev.c:netdev_run_todo",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:mif6_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589347984,
      "name": "free_netdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
void free_netdev(struct net_device * dev)
```

```json
{
  "name": "free_netdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589356192,
      "name": "free_netdev",
      "external": true,
      "loc": "net/core/dev.c:10722",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:loopback_net_init",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/xen-netfront.c:xennet_remove",
        "drivers/net/xen-netfront.c:xennet_create_dev",
        "net/devres.c:devm_free_netdev",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/dev.c:netdev_run_todo",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:mif6_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589356192,
      "name": "free_netdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
void free_netdev(struct net_device * dev)
```

```json
{
  "name": "free_netdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589252592,
      "name": "free_netdev",
      "external": true,
      "loc": "net/core/dev.c:10901",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:loopback_net_init",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/xen-netfront.c:xennet_remove",
        "drivers/net/xen-netfront.c:xennet_create_dev",
        "net/devres.c:devm_free_netdev",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/dev.c:netdev_run_todo",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:mif6_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589252592,
      "name": "free_netdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
void free_netdev(struct net_device * dev)
```

```json
{
  "name": "free_netdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "free_netdev",
      "external": true,
      "loc": "net/core/dev.c:10908",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:loopback_net_init",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/wwan/wwan_core.c:wwan_create_default_link",
        "drivers/net/xen-netfront.c:xennet_remove",
        "drivers/net/xen-netfront.c:xennet_create_dev",
        "net/devres.c:devm_free_netdev",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/dev.c:netdev_run_todo",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:mif6_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592698454,
      "name": "free_netdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589978096,
      "name": "free_netdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
void free_netdev(struct net_device * dev)
```

```json
{
  "name": "free_netdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "free_netdev",
      "external": true,
      "loc": "net/core/dev.c:10685",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:loopback_net_init",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/wwan/wwan_core.c:wwan_create_default_link",
        "drivers/net/xen-netfront.c:xennet_remove",
        "net/devres.c:devm_free_netdev",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/dev.c:netdev_run_todo",
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:mif6_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594584001,
      "name": "free_netdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071591503824,
      "name": "free_netdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 489
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
void free_netdev(struct net_device * dev)
```

```json
{
  "name": "free_netdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "free_netdev",
      "external": true,
      "loc": "net/core/dev.c:10680",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:loopback_net_init",
        "drivers/net/wwan/wwan_core.c:wwan_create_default_link",
        "drivers/net/xen-netfront.c:xennet_remove",
        "net/devres.c:devm_free_netdev",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/dev.c:netdev_run_todo",
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:mif6_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596323783,
      "name": "free_netdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593273568,
      "name": "free_netdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 489
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
void free_netdev(struct net_device * dev)
```

```json
{
  "name": "free_netdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "free_netdev",
      "external": true,
      "loc": "net/core/dev.c:10696",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:loopback_net_init",
        "drivers/net/virtio_net.c:virtnet_remove",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/wwan/wwan_core.c:wwan_create_default_link",
        "drivers/net/xen-netfront.c:xennet_remove",
        "drivers/net/net_failover.c:net_failover_create",
        "net/devres.c:devm_free_netdev",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/dev.c:netdev_run_todo",
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:mif6_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596853756,
      "name": "free_netdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593729424,
      "name": "free_netdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 489
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
void free_netdev(struct net_device * dev)
```

```json
{
  "name": "free_netdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "free_netdev",
      "external": true,
      "loc": "net/core/dev.c:10907",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:loopback_net_init",
        "drivers/net/netkit.c:netkit_new_link",
        "drivers/net/virtio_net.c:virtnet_remove",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/xen-netfront.c:xennet_remove",
        "drivers/net/net_failover.c:net_failover_create",
        "net/devres.c:devm_free_netdev",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/dev.c:netdev_run_todo",
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:mif6_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597778747,
      "name": "free_netdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071594508816,
      "name": "free_netdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 492
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
void free_netdev(struct net_device * dev)
```

```json
{
  "name": "free_netdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502003144,
      "name": "free_netdev",
      "external": true,
      "loc": "net/core/dev.c:9569",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_remove",
        "drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_drv_remove",
        "drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/xen-netfront.c:xennet_remove",
        "drivers/net/xen-netfront.c:netfront_probe",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/dev.c:netdev_run_todo",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ethernet/eth.c:devm_free_netdev",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502003144,
      "name": "free_netdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
void free_netdev(struct net_device * dev)
```

```json
{
  "name": "free_netdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234747336,
      "name": "free_netdev",
      "external": true,
      "loc": "net/core/dev.c:9569",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/dev.c:netdev_run_todo",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ethernet/eth.c:devm_free_netdev",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234747336,
      "name": "free_netdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
void free_netdev(struct net_device * dev)
```

```json
{
  "name": "free_netdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295449184,
      "name": "free_netdev",
      "external": true,
      "loc": "net/core/dev.c:9569",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:loopback_net_init",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/dev.c:netdev_run_todo",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ethernet/eth.c:devm_free_netdev",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295449184,
      "name": "free_netdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
void free_netdev(struct net_device * dev)
```

```json
{
  "name": "free_netdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278298714,
      "name": "free_netdev",
      "external": true,
      "loc": "net/core/dev.c:9569",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/dev.c:netdev_run_todo",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ethernet/eth.c:devm_free_netdev",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278298714,
      "name": "free_netdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void free_netdev(struct net_device * dev)
```

```json
{
  "name": "free_netdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588087424,
      "name": "free_netdev",
      "external": true,
      "loc": "net/core/dev.c:9569",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/xen-netfront.c:xennet_remove",
        "drivers/net/xen-netfront.c:netfront_probe",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/dev.c:netdev_run_todo",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ethernet/eth.c:devm_free_netdev",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588087424,
      "name": "free_netdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void free_netdev(struct net_device * dev)
```

```json
{
  "name": "free_netdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587800416,
      "name": "free_netdev",
      "external": true,
      "loc": "net/core/dev.c:9569",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/vxlan.c:vxlan_dev_create",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/dev.c:netdev_run_todo",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ethernet/eth.c:devm_free_netdev",
        "net/ipv4/ip_tunnel.c:__ip_tunnel_create",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587800416,
      "name": "free_netdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void free_netdev(struct net_device * dev)
```

```json
{
  "name": "free_netdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588419200,
      "name": "free_netdev",
      "external": true,
      "loc": "net/core/dev.c:9569",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/xen-netfront.c:xennet_remove",
        "drivers/net/xen-netfront.c:netfront_probe",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/dev.c:netdev_run_todo",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ethernet/eth.c:devm_free_netdev",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588419200,
      "name": "free_netdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void free_netdev(struct net_device * dev)
```

```json
{
  "name": "free_netdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588544032,
      "name": "free_netdev",
      "external": true,
      "loc": "net/core/dev.c:9569",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/xen-netfront.c:xennet_remove",
        "drivers/net/xen-netfront.c:netfront_probe",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/dev.c:netdev_run_todo",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ethernet/eth.c:devm_free_netdev",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588544032,
      "name": "free_netdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
