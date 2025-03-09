# Function: <code>ipv6_get_lladdr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ipv6_get_lladdr(struct net_device * dev, struct in6_addr * addr, u32 banned_flags)
```

```json
{
  "name": "ipv6_get_lladdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587034944,
      "name": "ipv6_get_lladdr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1611",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:inet6_set_link_af",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/mcast.c:igmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587034944,
      "name": "ipv6_get_lladdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int ipv6_get_lladdr(struct net_device * dev, struct in6_addr * addr, u32 banned_flags)
```

```json
{
  "name": "ipv6_get_lladdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587483136,
      "name": "ipv6_get_lladdr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1673",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_set_link_af",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/mcast.c:igmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587483136,
      "name": "ipv6_get_lladdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int ipv6_get_lladdr(struct net_device * dev, struct in6_addr * addr, u32 banned_flags)
```

```json
{
  "name": "ipv6_get_lladdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587686592,
      "name": "ipv6_get_lladdr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1721",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_set_link_af",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/mcast.c:igmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587686592,
      "name": "ipv6_get_lladdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int ipv6_get_lladdr(struct net_device * dev, struct in6_addr * addr, u32 banned_flags)
```

```json
{
  "name": "ipv6_get_lladdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587837584,
      "name": "ipv6_get_lladdr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1763",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_set_link_af",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/mcast.c:igmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587837584,
      "name": "ipv6_get_lladdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int ipv6_get_lladdr(struct net_device * dev, struct in6_addr * addr, u32 banned_flags)
```

```json
{
  "name": "ipv6_get_lladdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588366704,
      "name": "ipv6_get_lladdr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1807",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_set_link_af",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/mcast.c:igmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588366704,
      "name": "ipv6_get_lladdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int ipv6_get_lladdr(struct net_device * dev, struct in6_addr * addr, u32 banned_flags)
```

```json
{
  "name": "ipv6_get_lladdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588724640,
      "name": "ipv6_get_lladdr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1808",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_set_link_af",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/mcast.c:igmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588724640,
      "name": "ipv6_get_lladdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int ipv6_get_lladdr(struct net_device * dev, struct in6_addr * addr, u32 banned_flags)
```

```json
{
  "name": "ipv6_get_lladdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588944448,
      "name": "ipv6_get_lladdr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1824",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_set_link_af",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/mcast.c:igmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588944448,
      "name": "ipv6_get_lladdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int ipv6_get_lladdr(struct net_device * dev, struct in6_addr * addr, u32 banned_flags)
```

```json
{
  "name": "ipv6_get_lladdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589388304,
      "name": "ipv6_get_lladdr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1857",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/mcast.c:igmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589388304,
      "name": "ipv6_get_lladdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int ipv6_get_lladdr(struct net_device * dev, struct in6_addr * addr, u32 banned_flags)
```

```json
{
  "name": "ipv6_get_lladdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589612880,
      "name": "ipv6_get_lladdr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1859",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/mcast.c:igmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589612880,
      "name": "ipv6_get_lladdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int ipv6_get_lladdr(struct net_device * dev, struct in6_addr * addr, u32 banned_flags)
```

```json
{
  "name": "ipv6_get_lladdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590623376,
      "name": "ipv6_get_lladdr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1850",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_set_iftoken",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/mcast.c:igmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590623376,
      "name": "ipv6_get_lladdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int ipv6_get_lladdr(struct net_device * dev, struct in6_addr * addr, u32 banned_flags)
```

```json
{
  "name": "ipv6_get_lladdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590684064,
      "name": "ipv6_get_lladdr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1850",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_set_iftoken",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/mcast.c:igmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590684064,
      "name": "ipv6_get_lladdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int ipv6_get_lladdr(struct net_device * dev, struct in6_addr * addr, u32 banned_flags)
```

```json
{
  "name": "ipv6_get_lladdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590609184,
      "name": "ipv6_get_lladdr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1852",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_set_iftoken",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/mcast.c:igmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590609184,
      "name": "ipv6_get_lladdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int ipv6_get_lladdr(struct net_device * dev, struct in6_addr * addr, u32 banned_flags)
```

```json
{
  "name": "ipv6_get_lladdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591422144,
      "name": "ipv6_get_lladdr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1859",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_set_iftoken",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/mcast.c:igmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591422144,
      "name": "ipv6_get_lladdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int ipv6_get_lladdr(struct net_device * dev, struct in6_addr * addr, u32 banned_flags)
```

```json
{
  "name": "ipv6_get_lladdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593100016,
      "name": "ipv6_get_lladdr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1866",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_set_iftoken",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/mcast.c:igmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593100016,
      "name": "ipv6_get_lladdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int ipv6_get_lladdr(struct net_device * dev, struct in6_addr * addr, u32 banned_flags)
```

```json
{
  "name": "ipv6_get_lladdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594995600,
      "name": "ipv6_get_lladdr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1866",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_set_iftoken",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/mcast.c:igmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594995600,
      "name": "ipv6_get_lladdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int ipv6_get_lladdr(struct net_device * dev, struct in6_addr * addr, u32 banned_flags)
```

```json
{
  "name": "ipv6_get_lladdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595389088,
      "name": "ipv6_get_lladdr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1865",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_set_iftoken",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/mcast.c:igmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595389088,
      "name": "ipv6_get_lladdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int ipv6_get_lladdr(struct net_device * dev, struct in6_addr * addr, u32 banned_flags)
```

```json
{
  "name": "ipv6_get_lladdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596230592,
      "name": "ipv6_get_lladdr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1893",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_set_iftoken",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/mcast.c:igmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596230592,
      "name": "ipv6_get_lladdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int ipv6_get_lladdr(struct net_device * dev, struct in6_addr * addr, u32 banned_flags)
```

```json
{
  "name": "ipv6_get_lladdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503292448,
      "name": "ipv6_get_lladdr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1859",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/mcast.c:igmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503292448,
      "name": "ipv6_get_lladdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int ipv6_get_lladdr(struct net_device * dev, struct in6_addr * addr, u32 banned_flags)
```

```json
{
  "name": "ipv6_get_lladdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235962252,
      "name": "ipv6_get_lladdr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1859",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/mcast.c:igmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235962252,
      "name": "ipv6_get_lladdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int ipv6_get_lladdr(struct net_device * dev, struct in6_addr * addr, u32 banned_flags)
```

```json
{
  "name": "ipv6_get_lladdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297046080,
      "name": "ipv6_get_lladdr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1859",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/mcast.c:igmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297046080,
      "name": "ipv6_get_lladdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int ipv6_get_lladdr(struct net_device * dev, struct in6_addr * addr, u32 banned_flags)
```

```json
{
  "name": "ipv6_get_lladdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279312242,
      "name": "ipv6_get_lladdr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1859",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/mcast.c:igmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279312242,
      "name": "ipv6_get_lladdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int ipv6_get_lladdr(struct net_device * dev, struct in6_addr * addr, u32 banned_flags)
```

```json
{
  "name": "ipv6_get_lladdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589217248,
      "name": "ipv6_get_lladdr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1859",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/mcast.c:igmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589217248,
      "name": "ipv6_get_lladdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int ipv6_get_lladdr(struct net_device * dev, struct in6_addr * addr, u32 banned_flags)
```

```json
{
  "name": "ipv6_get_lladdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588942240,
      "name": "ipv6_get_lladdr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1859",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/mcast.c:igmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588942240,
      "name": "ipv6_get_lladdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int ipv6_get_lladdr(struct net_device * dev, struct in6_addr * addr, u32 banned_flags)
```

```json
{
  "name": "ipv6_get_lladdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589654112,
      "name": "ipv6_get_lladdr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1859",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/mcast.c:igmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589654112,
      "name": "ipv6_get_lladdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int ipv6_get_lladdr(struct net_device * dev, struct in6_addr * addr, u32 banned_flags)
```

```json
{
  "name": "ipv6_get_lladdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589703168,
      "name": "ipv6_get_lladdr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1859",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/ndisc.c:ndisc_send_ns",
        "net/ipv6/mcast.c:igmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589703168,
      "name": "ipv6_get_lladdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
