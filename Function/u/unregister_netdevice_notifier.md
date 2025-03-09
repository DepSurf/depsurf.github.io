# Function: <code>unregister_netdevice_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int unregister_netdevice_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_netdevice_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586270992,
      "name": "unregister_netdevice_notifier",
      "external": true,
      "loc": "net/core/dev.c:1598",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/ndisc.c:ndisc_late_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/packet/af_packet.c:packet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586270992,
      "name": "unregister_netdevice_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
int unregister_netdevice_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_netdevice_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586696976,
      "name": "unregister_netdevice_notifier",
      "external": true,
      "loc": "net/core/dev.c:1602",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_cleanup",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/ndisc.c:ndisc_late_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/packet/af_packet.c:packet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586696976,
      "name": "unregister_netdevice_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
int unregister_netdevice_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_netdevice_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586882896,
      "name": "unregister_netdevice_notifier",
      "external": true,
      "loc": "net/core/dev.c:1601",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_cleanup",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/ndisc.c:ndisc_late_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/packet/af_packet.c:packet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586882896,
      "name": "unregister_netdevice_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
int unregister_netdevice_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_netdevice_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587007408,
      "name": "unregister_netdevice_notifier",
      "external": true,
      "loc": "net/core/dev.c:1635",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_cleanup",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/ndisc.c:ndisc_late_cleanup",
        "net/ipv6/mcast.c:igmp6_late_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/packet/af_packet.c:packet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587007408,
      "name": "unregister_netdevice_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
int unregister_netdevice_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_netdevice_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587506224,
      "name": "unregister_netdevice_notifier",
      "external": true,
      "loc": "net/core/dev.c:1650",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_cleanup",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/ndisc.c:ndisc_late_cleanup",
        "net/ipv6/mcast.c:igmp6_late_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/packet/af_packet.c:packet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587506224,
      "name": "unregister_netdevice_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
int unregister_netdevice_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_netdevice_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587810384,
      "name": "unregister_netdevice_notifier",
      "external": true,
      "loc": "net/core/dev.c:1692",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_cleanup",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/ndisc.c:ndisc_late_cleanup",
        "net/ipv6/mcast.c:igmp6_late_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/packet/af_packet.c:packet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587810384,
      "name": "unregister_netdevice_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
int unregister_netdevice_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_netdevice_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587946144,
      "name": "unregister_netdevice_notifier",
      "external": true,
      "loc": "net/core/dev.c:1696",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_cleanup",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/ndisc.c:ndisc_late_cleanup",
        "net/ipv6/mcast.c:igmp6_late_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/packet/af_packet.c:packet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587946144,
      "name": "unregister_netdevice_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
int unregister_netdevice_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_netdevice_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588255696,
      "name": "unregister_netdevice_notifier",
      "external": true,
      "loc": "net/core/dev.c:1706",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_cleanup",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/ndisc.c:ndisc_late_cleanup",
        "net/ipv6/mcast.c:igmp6_late_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/packet/af_packet.c:packet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588255696,
      "name": "unregister_netdevice_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
int unregister_netdevice_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_netdevice_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588460848,
      "name": "unregister_netdevice_notifier",
      "external": true,
      "loc": "net/core/dev.c:1624",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_cleanup",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/ndisc.c:ndisc_late_cleanup",
        "net/ipv6/mcast.c:igmp6_late_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/packet/af_packet.c:packet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588460848,
      "name": "unregister_netdevice_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
int unregister_netdevice_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_netdevice_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589335424,
      "name": "unregister_netdevice_notifier",
      "external": true,
      "loc": "net/core/dev.c:1849",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_cleanup",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/ndisc.c:ndisc_late_cleanup",
        "net/ipv6/mcast.c:igmp6_late_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/packet/af_packet.c:packet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589335424,
      "name": "unregister_netdevice_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int unregister_netdevice_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_netdevice_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589335760,
      "name": "unregister_netdevice_notifier",
      "external": true,
      "loc": "net/core/dev.c:1874",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_cleanup",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/ndisc.c:ndisc_late_cleanup",
        "net/ipv6/mcast.c:igmp6_late_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/packet/af_packet.c:packet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589335760,
      "name": "unregister_netdevice_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int unregister_netdevice_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_netdevice_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589232512,
      "name": "unregister_netdevice_notifier",
      "external": true,
      "loc": "net/core/dev.c:1943",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_cleanup",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/ndisc.c:ndisc_late_cleanup",
        "net/ipv6/mcast.c:igmp6_late_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/packet/af_packet.c:packet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589232512,
      "name": "unregister_netdevice_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int unregister_netdevice_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_netdevice_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589957504,
      "name": "unregister_netdevice_notifier",
      "external": true,
      "loc": "net/core/dev.c:1818",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_cleanup",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/ndisc.c:ndisc_late_cleanup",
        "net/ipv6/mcast.c:igmp6_late_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/packet/af_packet.c:packet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589957504,
      "name": "unregister_netdevice_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int unregister_netdevice_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_netdevice_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591494976,
      "name": "unregister_netdevice_notifier",
      "external": true,
      "loc": "net/core/dev.c:1767",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_cleanup",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/ndisc.c:ndisc_late_cleanup",
        "net/ipv6/mcast.c:igmp6_late_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/packet/af_packet.c:packet_exit",
        "net/mctp/device.c:mctp_device_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591494976,
      "name": "unregister_netdevice_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int unregister_netdevice_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_netdevice_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593263328,
      "name": "unregister_netdevice_notifier",
      "external": true,
      "loc": "net/core/dev.c:1752",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_cleanup",
        "net/core/devlink.c:devlink_free",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/ndisc.c:ndisc_late_cleanup",
        "net/ipv6/mcast.c:igmp6_late_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/packet/af_packet.c:packet_init",
        "net/packet/af_packet.c:packet_exit",
        "net/mctp/device.c:mctp_device_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593263328,
      "name": "unregister_netdevice_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int unregister_netdevice_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_netdevice_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593720960,
      "name": "unregister_netdevice_notifier",
      "external": true,
      "loc": "net/core/dev.c:1778",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_cleanup",
        "net/core/netdev-genl.c:netdev_genl_init",
        "net/core/failover.c:failover_exit",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/ndisc.c:ndisc_late_cleanup",
        "net/ipv6/mcast.c:igmp6_late_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/packet/af_packet.c:packet_init",
        "net/packet/af_packet.c:packet_exit",
        "net/mctp/device.c:mctp_device_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593720960,
      "name": "unregister_netdevice_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int unregister_netdevice_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_netdevice_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594502240,
      "name": "unregister_netdevice_notifier",
      "external": true,
      "loc": "net/core/dev.c:1782",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_cleanup",
        "net/core/netdev-genl.c:netdev_genl_init",
        "net/core/failover.c:failover_exit",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/ndisc.c:ndisc_late_cleanup",
        "net/ipv6/mcast.c:igmp6_late_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/packet/af_packet.c:packet_init",
        "net/packet/af_packet.c:packet_exit",
        "net/mctp/device.c:mctp_device_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594502240,
      "name": "unregister_netdevice_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int unregister_netdevice_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_netdevice_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501985248,
      "name": "unregister_netdevice_notifier",
      "external": true,
      "loc": "net/core/dev.c:1624",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_cleanup",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/ndisc.c:ndisc_late_cleanup",
        "net/ipv6/mcast.c:igmp6_late_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/packet/af_packet.c:packet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501985248,
      "name": "unregister_netdevice_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int unregister_netdevice_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_netdevice_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234740500,
      "name": "unregister_netdevice_notifier",
      "external": true,
      "loc": "net/core/dev.c:1624",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_cleanup",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/ndisc.c:ndisc_late_cleanup",
        "net/ipv6/mcast.c:igmp6_late_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/packet/af_packet.c:packet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234740500,
      "name": "unregister_netdevice_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
int unregister_netdevice_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_netdevice_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295417552,
      "name": "unregister_netdevice_notifier",
      "external": true,
      "loc": "net/core/dev.c:1624",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_cleanup",
        "net/core/drop_monitor.c:exit_net_drop_monitor",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/ndisc.c:ndisc_late_cleanup",
        "net/ipv6/mcast.c:igmp6_late_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/packet/af_packet.c:packet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295417552,
      "name": "unregister_netdevice_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 492
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
int unregister_netdevice_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_netdevice_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278283788,
      "name": "unregister_netdevice_notifier",
      "external": true,
      "loc": "net/core/dev.c:1624",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_cleanup",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/ndisc.c:ndisc_late_cleanup",
        "net/ipv6/mcast.c:igmp6_late_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/packet/af_packet.c:packet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278283788,
      "name": "unregister_netdevice_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
int unregister_netdevice_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_netdevice_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588067632,
      "name": "unregister_netdevice_notifier",
      "external": true,
      "loc": "net/core/dev.c:1624",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_cleanup",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/ndisc.c:ndisc_late_cleanup",
        "net/ipv6/mcast.c:igmp6_late_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/packet/af_packet.c:packet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588067632,
      "name": "unregister_netdevice_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
int unregister_netdevice_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_netdevice_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587780720,
      "name": "unregister_netdevice_notifier",
      "external": true,
      "loc": "net/core/dev.c:1624",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_cleanup",
        "drivers/net/vxlan.c:vxlan_cleanup_module",
        "drivers/net/vxlan.c:vxlan_init_module",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/ndisc.c:ndisc_late_cleanup",
        "net/ipv6/mcast.c:igmp6_late_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/packet/af_packet.c:packet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587780720,
      "name": "unregister_netdevice_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
int unregister_netdevice_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_netdevice_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588399408,
      "name": "unregister_netdevice_notifier",
      "external": true,
      "loc": "net/core/dev.c:1624",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_cleanup",
        "net/netfilter/nfnetlink_queue.c:nfnetlink_queue_fini",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/ndisc.c:ndisc_late_cleanup",
        "net/ipv6/mcast.c:igmp6_late_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/packet/af_packet.c:packet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588399408,
      "name": "unregister_netdevice_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
int unregister_netdevice_notifier(struct notifier_block * nb)
```

```json
{
  "name": "unregister_netdevice_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588535808,
      "name": "unregister_netdevice_notifier",
      "external": true,
      "loc": "net/core/dev.c:1624",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_cleanup",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/ndisc.c:ndisc_late_cleanup",
        "net/ipv6/mcast.c:igmp6_late_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/packet/af_packet.c:packet_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588535808,
      "name": "unregister_netdevice_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
