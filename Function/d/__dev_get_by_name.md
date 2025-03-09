# Function: <code>__dev_get_by_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct net_device * __dev_get_by_name(struct net * net, const char * name)
```

```json
{
  "name": "__dev_get_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586284192,
      "name": "__dev_get_by_name",
      "external": true,
      "loc": "net/core/dev.c:723",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/dev.c:__dev_alloc_name",
        "net/core/dev.c:netdev_boot_base",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/wireless/wext-core.c:wireless_process_ioctl",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586284192,
      "name": "__dev_get_by_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
struct net_device * __dev_get_by_name(struct net * net, const char * name)
```

```json
{
  "name": "__dev_get_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586712304,
      "name": "__dev_get_by_name",
      "external": true,
      "loc": "net/core/dev.c:727",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/dev.c:__dev_alloc_name",
        "net/core/dev.c:netdev_boot_base",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/wireless/wext-core.c:wireless_process_ioctl",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586712304,
      "name": "__dev_get_by_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
struct net_device * __dev_get_by_name(struct net * net, const char * name)
```

```json
{
  "name": "__dev_get_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586897984,
      "name": "__dev_get_by_name",
      "external": true,
      "loc": "net/core/dev.c:726",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/dev.c:__dev_alloc_name",
        "net/core/dev.c:netdev_boot_base",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/wireless/wext-core.c:wireless_process_ioctl",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586897984,
      "name": "__dev_get_by_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
struct net_device * __dev_get_by_name(struct net * net, const char * name)
```

```json
{
  "name": "__dev_get_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587023168,
      "name": "__dev_get_by_name",
      "external": true,
      "loc": "net/core/dev.c:733",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/dev.c:__dev_alloc_name",
        "net/core/dev.c:netdev_boot_base",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/wireless/wext-core.c:wireless_process_ioctl",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587023168,
      "name": "__dev_get_by_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
struct net_device * __dev_get_by_name(struct net * net, const char * name)
```

```json
{
  "name": "__dev_get_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587521216,
      "name": "__dev_get_by_name",
      "external": true,
      "loc": "net/core/dev.c:736",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/core/dev.c:dev_alloc_name_ns",
        "net/core/dev.c:netdev_boot_base",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/wireless/wext-core.c:wireless_process_ioctl",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587521216,
      "name": "__dev_get_by_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
struct net_device * __dev_get_by_name(struct net * net, const char * name)
```

```json
{
  "name": "__dev_get_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dev_get_by_name",
      "external": true,
      "loc": "net/core/dev.c:736",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_alloc_name_ns",
        "net/core/dev.c:netdev_boot_base",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/wireless/wext-core.c:wireless_process_ioctl",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587860294,
      "name": "__dev_get_by_name.cold.152",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071587821984,
      "name": "__dev_get_by_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
struct net_device * __dev_get_by_name(struct net * net, const char * name)
```

```json
{
  "name": "__dev_get_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dev_get_by_name",
      "external": true,
      "loc": "net/core/dev.c:738",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_alloc_name_ns",
        "net/core/dev.c:netdev_boot_base",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/wireless/wext-core.c:wireless_process_ioctl",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588000690,
      "name": "__dev_get_by_name.cold.158",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071587954976,
      "name": "__dev_get_by_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
struct net_device * __dev_get_by_name(struct net * net, const char * name)
```

```json
{
  "name": "__dev_get_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dev_get_by_name",
      "external": true,
      "loc": "net/core/dev.c:734",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_alloc_name_ns",
        "net/core/dev.c:netdev_boot_base",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/wireless/wext-core.c:wireless_process_ioctl",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588311707,
      "name": "__dev_get_by_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071588269648,
      "name": "__dev_get_by_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
struct net_device * __dev_get_by_name(struct net * net, const char * name)
```

```json
{
  "name": "__dev_get_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dev_get_by_name",
      "external": true,
      "loc": "net/core/dev.c:652",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_alloc_name_ns",
        "net/core/dev.c:netdev_boot_base",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/wireless/wext-core.c:wireless_process_ioctl",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588518139,
      "name": "__dev_get_by_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071588476000,
      "name": "__dev_get_by_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * __dev_get_by_name(struct net * net, const char * name)
```

```json
{
  "name": "__dev_get_by_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589351352,
      "name": "__dev_get_by_name",
      "external": true,
      "loc": "net/core/dev.c:858",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:default_device_exit",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_get_valid_name",
        "net/core/dev.c:__dev_alloc_name",
        "net/core/dev.c:netdev_boot_base"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/netpoll.c:netpoll_setup",
        "net/ethtool/ioctl.c:dev_ethtool",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/fib_frontend.c:rtentry_to_fib_config",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv6/addrconf.c:addrconf_set_sit_dstaddr",
        "net/wireless/wext-core.c:wireless_process_ioctl",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589338832,
      "name": "__dev_get_by_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * __dev_get_by_name(struct net * net, const char * name)
```

```json
{
  "name": "__dev_get_by_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589352904,
      "name": "__dev_get_by_name",
      "external": true,
      "loc": "net/core/dev.c:861",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:default_device_exit",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_get_valid_name",
        "net/core/dev.c:__dev_alloc_name",
        "net/core/dev.c:netdev_boot_base"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/netpoll.c:netpoll_setup",
        "net/ethtool/ioctl.c:dev_ethtool",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/fib_frontend.c:rtentry_to_fib_config",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv6/addrconf.c:addrconf_set_sit_dstaddr",
        "net/wireless/wext-core.c:wireless_process_ioctl",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589340432,
      "name": "__dev_get_by_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * __dev_get_by_name(struct net * net, const char * name)
```

```json
{
  "name": "__dev_get_by_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589255944,
      "name": "__dev_get_by_name",
      "external": true,
      "loc": "net/core/dev.c:909",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:default_device_exit",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:dev_get_valid_name",
        "net/core/dev.c:__dev_alloc_name",
        "net/core/dev.c:netdev_boot_base"
      ],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/netpoll.c:netpoll_setup",
        "net/ethtool/ioctl.c:dev_ethtool",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/fib_frontend.c:rtentry_to_fib_config",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/wireless/wext-core.c:wireless_process_ioctl",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589236864,
      "name": "__dev_get_by_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * __dev_get_by_name(struct net * net, const char * name)
```

```json
{
  "name": "__dev_get_by_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589981501,
      "name": "__dev_get_by_name",
      "external": true,
      "loc": "net/core/dev.c:786",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:default_device_exit",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:dev_get_valid_name",
        "net/core/dev.c:__dev_alloc_name"
      ],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/netpoll.c:netpoll_setup",
        "net/ethtool/ioctl.c:dev_ethtool",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/fib_frontend.c:rtentry_to_fib_config",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/wireless/wext-core.c:wireless_process_ioctl",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589961392,
      "name": "__dev_get_by_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct net_device * __dev_get_by_name(struct net * net, const char * name)
```

```json
{
  "name": "__dev_get_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591509680,
      "name": "__dev_get_by_name",
      "external": true,
      "loc": "net/core/dev.c:733",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/netpoll.c:netpoll_setup",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/fib_frontend.c:rtentry_to_fib_config",
        "net/ipv4/fib_frontend.c:rtentry_to_fib_config",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/wireless/wext-core.c:wireless_process_ioctl",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591509680,
      "name": "__dev_get_by_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct net_device * __dev_get_by_name(struct net * net, const char * name)
```

```json
{
  "name": "__dev_get_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593280848,
      "name": "__dev_get_by_name",
      "external": true,
      "loc": "net/core/dev.c:733",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/netpoll.c:netpoll_setup",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/fib_frontend.c:rtentry_to_fib_config",
        "net/ipv4/fib_frontend.c:rtentry_to_fib_config",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/wireless/wext-core.c:wireless_process_ioctl",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593280848,
      "name": "__dev_get_by_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct net_device * __dev_get_by_name(struct net * net, const char * name)
```

```json
{
  "name": "__dev_get_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593739696,
      "name": "__dev_get_by_name",
      "external": true,
      "loc": "net/core/dev.c:731",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/netpoll.c:netpoll_setup",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/fib_frontend.c:rtentry_to_fib_config",
        "net/ipv4/fib_frontend.c:rtentry_to_fib_config",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/wireless/wext-core.c:wireless_process_ioctl",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593739696,
      "name": "__dev_get_by_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct net_device * __dev_get_by_name(struct net * net, const char * name)
```

```json
{
  "name": "__dev_get_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594516368,
      "name": "__dev_get_by_name",
      "external": true,
      "loc": "net/core/dev.c:748",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/netpoll.c:netpoll_setup",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/fib_frontend.c:rtentry_to_fib_config",
        "net/ipv4/fib_frontend.c:rtentry_to_fib_config",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/wireless/wext-core.c:wireless_process_ioctl",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594516368,
      "name": "__dev_get_by_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct net_device * __dev_get_by_name(struct net * net, const char * name)
```

```json
{
  "name": "__dev_get_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501993952,
      "name": "__dev_get_by_name",
      "external": true,
      "loc": "net/core/dev.c:652",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_alloc_name_ns",
        "net/core/dev.c:netdev_boot_base",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/fib_frontend.c:rtentry_to_fib_config",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/wireless/wext-core.c:wireless_process_ioctl",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501993952,
      "name": "__dev_get_by_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct net_device * __dev_get_by_name(struct net * net, const char * name)
```

```json
{
  "name": "__dev_get_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234759640,
      "name": "__dev_get_by_name",
      "external": true,
      "loc": "net/core/dev.c:652",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_alloc_name_ns",
        "net/core/dev.c:netdev_boot_base",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/fib_rules.c:fib_nl2rule",
        "net/core/fib_rules.c:fib_nl2rule",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/fib_frontend.c:rtentry_to_fib_config",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/wireless/wext-core.c:wext_handle_ioctl",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234759640,
      "name": "__dev_get_by_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct net_device * __dev_get_by_name(struct net * net, const char * name)
```

```json
{
  "name": "__dev_get_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295440896,
      "name": "__dev_get_by_name",
      "external": true,
      "loc": "net/core/dev.c:652",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_get_valid_name",
        "net/core/dev.c:dev_alloc_name_ns",
        "net/core/dev.c:netdev_boot_base",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/wireless/wext-core.c:wireless_process_ioctl",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295440896,
      "name": "__dev_get_by_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
struct net_device * __dev_get_by_name(struct net * net, const char * name)
```

```json
{
  "name": "__dev_get_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278294972,
      "name": "__dev_get_by_name",
      "external": true,
      "loc": "net/core/dev.c:652",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:netdev_boot_base",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/fib_frontend.c:rtentry_to_fib_config",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/wireless/wext-core.c:wext_handle_ioctl",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278294972,
      "name": "__dev_get_by_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
struct net_device * __dev_get_by_name(struct net * net, const char * name)
```

```json
{
  "name": "__dev_get_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dev_get_by_name",
      "external": true,
      "loc": "net/core/dev.c:652",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_alloc_name_ns",
        "net/core/dev.c:netdev_boot_base",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/wireless/wext-core.c:wireless_process_ioctl",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588124875,
      "name": "__dev_get_by_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071588082784,
      "name": "__dev_get_by_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
struct net_device * __dev_get_by_name(struct net * net, const char * name)
```

```json
{
  "name": "__dev_get_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dev_get_by_name",
      "external": true,
      "loc": "net/core/dev.c:652",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_alloc_name_ns",
        "net/core/dev.c:netdev_boot_base",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587837707,
      "name": "__dev_get_by_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071587796352,
      "name": "__dev_get_by_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
struct net_device * __dev_get_by_name(struct net * net, const char * name)
```

```json
{
  "name": "__dev_get_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dev_get_by_name",
      "external": true,
      "loc": "net/core/dev.c:652",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_alloc_name_ns",
        "net/core/dev.c:netdev_boot_base",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/wireless/wext-core.c:wireless_process_ioctl",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588456699,
      "name": "__dev_get_by_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071588414560,
      "name": "__dev_get_by_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
struct net_device * __dev_get_by_name(struct net * net, const char * name)
```

```json
{
  "name": "__dev_get_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dev_get_by_name",
      "external": true,
      "loc": "net/core/dev.c:652",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_alloc_name_ns",
        "net/core/dev.c:netdev_boot_base",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/fib_frontend.c:ip_rt_ioctl",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/wireless/wext-core.c:wireless_process_ioctl",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588593733,
      "name": "__dev_get_by_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071588553152,
      "name": "__dev_get_by_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
