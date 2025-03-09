# Function: <code>add_grec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
struct sk_buff * add_grec(struct sk_buff * skb, struct ip_mc_list * pmc, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "add_grec",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586800640,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv4/igmp.c:432",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmpv3_send_report",
        "net/ipv4/igmp.c:igmpv3_send_report",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire"
      ]
    },
    {
      "addr": 18446744071587145088,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv6/mcast.c:1695",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586800640,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1116
    },
    {
      "addr": 18446744071587145088,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1192
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
struct sk_buff * add_grec(struct sk_buff * skb, struct ip_mc_list * pmc, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "add_grec",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587250576,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv4/igmp.c:425",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmpv3_send_report",
        "net/ipv4/igmp.c:igmpv3_send_report"
      ]
    },
    {
      "addr": 18446744071587597904,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv6/mcast.c:1694",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587250576,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1124
    },
    {
      "addr": 18446744071587597904,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1192
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
struct sk_buff * add_grec(struct sk_buff * skb, struct ip_mc_list * pmc, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "add_grec",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587451152,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv4/igmp.c:430",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmpv3_send_report",
        "net/ipv4/igmp.c:igmpv3_send_report"
      ]
    },
    {
      "addr": 18446744071587802160,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv6/mcast.c:1708",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587451152,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1199
    },
    {
      "addr": 18446744071587802160,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1270
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision ❓</summary>

```c
struct sk_buff * add_grec(struct sk_buff * skb, struct ip_mc_list * pmc, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "add_grec",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587587664,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv4/igmp.c:430",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmpv3_send_report",
        "net/ipv4/igmp.c:igmpv3_send_report"
      ]
    },
    {
      "addr": 18446744071587961200,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv6/mcast.c:1708",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587587664,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1209
    },
    {
      "addr": 18446744071587961200,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1189
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision ❓</summary>

```c
struct sk_buff * add_grec(struct sk_buff * skb, struct ip_mc_list * pmc, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "add_grec",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588111632,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv4/igmp.c:453",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmpv3_send_report",
        "net/ipv4/igmp.c:igmpv3_send_report"
      ]
    },
    {
      "addr": 18446744071588494576,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv6/mcast.c:1708",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588111632,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1198
    },
    {
      "addr": 18446744071588494576,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision ❓</summary>

```c
struct sk_buff * add_grec(struct sk_buff * skb, struct ip_mc_list * pmc, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "add_grec",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588466256,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv4/igmp.c:453",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmpv3_send_report",
        "net/ipv4/igmp.c:igmpv3_send_report"
      ]
    },
    {
      "addr": 18446744071588857984,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv6/mcast.c:1731",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588466256,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1227
    },
    {
      "addr": 18446744071588857984,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1284
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision ❓</summary>

```c
struct sk_buff * add_grec(struct sk_buff * skb, struct ip_mc_list * pmc, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "add_grec",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588659952,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv4/igmp.c:450",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmpv3_send_report",
        "net/ipv4/igmp.c:igmpv3_send_report"
      ]
    },
    {
      "addr": 18446744071589081344,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv6/mcast.c:1731",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588659952,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1218
    },
    {
      "addr": 18446744071589081344,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1275
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision ❓</summary>

```c
struct sk_buff * add_grec(struct sk_buff * skb, struct ip_mc_list * pmc, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "add_grec",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589072880,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv4/igmp.c:459",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmpv3_send_report",
        "net/ipv4/igmp.c:igmpv3_send_report"
      ]
    },
    {
      "addr": 18446744071589535552,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv6/mcast.c:1730",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589072880,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1231
    },
    {
      "addr": 18446744071589535552,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1281
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision ❓</summary>

```c
struct sk_buff * add_grec(struct sk_buff * skb, struct ip_mc_list * pmc, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "add_grec",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589297040,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv4/igmp.c:459",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmpv3_send_report",
        "net/ipv4/igmp.c:igmpv3_send_report"
      ]
    },
    {
      "addr": 18446744071589759632,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv6/mcast.c:1730",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589297040,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1231
    },
    {
      "addr": 18446744071589759632,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1281
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision ❓</summary>

```c
struct sk_buff * add_grec(struct sk_buff * skb, struct ip_mc_list * pmc, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "add_grec",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590270688,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv4/igmp.c:457",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr"
      ]
    },
    {
      "addr": 18446744071590776928,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv6/mcast.c:1727",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590270688,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1211
    },
    {
      "addr": 18446744071590776928,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1261
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision ❓</summary>

```c
struct sk_buff * add_grec(struct sk_buff * skb, struct ip_mc_list * pmc, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "add_grec",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590323616,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv4/igmp.c:457",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr"
      ]
    },
    {
      "addr": 18446744071590836192,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv6/mcast.c:1727",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590323616,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1211
    },
    {
      "addr": 18446744071590836192,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1261
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision ❓</summary>

```c
struct sk_buff * add_grec(struct sk_buff * skb, struct ip_mc_list * pmc, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "add_grec",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590239616,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv4/igmp.c:457",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr"
      ]
    },
    {
      "addr": 18446744071590763312,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv6/mcast.c:1869",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590239616,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1210
    },
    {
      "addr": 18446744071590763312,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1256
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision ❓</summary>

```c
struct sk_buff * add_grec(struct sk_buff * skb, struct ip_mc_list * pmc, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "add_grec",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591023136,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv4/igmp.c:457",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr"
      ]
    },
    {
      "addr": 18446744071591579616,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv6/mcast.c:1867",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591023136,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1210
    },
    {
      "addr": 18446744071591579616,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1262
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision ❓</summary>

```c
struct sk_buff * add_grec(struct sk_buff * skb, struct ip_mc_list * pmc, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "add_grec",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592670096,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv4/igmp.c:457",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr"
      ]
    },
    {
      "addr": 18446744071593272048,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv6/mcast.c:1869",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592670096,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1313
    },
    {
      "addr": 18446744071593272048,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1425
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision ❓</summary>

```c
struct sk_buff * add_grec(struct sk_buff * skb, struct ip_mc_list * pmc, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "add_grec",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594538064,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv4/igmp.c:457",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr"
      ]
    },
    {
      "addr": 18446744071595175920,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv6/mcast.c:1869",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594538064,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1313
    },
    {
      "addr": 18446744071595175920,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1425
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision ❓</summary>

```c
struct sk_buff * add_grec(struct sk_buff * skb, struct ip_mc_list * pmc, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "add_grec",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594929872,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv4/igmp.c:458",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr"
      ]
    },
    {
      "addr": 18446744071595570672,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv6/mcast.c:1869",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594929872,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1330
    },
    {
      "addr": 18446744071595570672,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1468
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision ❓</summary>

```c
struct sk_buff * add_grec(struct sk_buff * skb, struct ip_mc_list * pmc, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "add_grec",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595742080,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv4/igmp.c:460",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr",
        "net/ipv4/igmp.c:igmpv3_send_cr"
      ]
    },
    {
      "addr": 18446744071596414576,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv6/mcast.c:1867",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595742080,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1327
    },
    {
      "addr": 18446744071596414576,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1465
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
struct sk_buff * add_grec(struct sk_buff * skb, struct ip_mc_list * pmc, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "add_grec",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502926632,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv4/igmp.c:459",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmpv3_send_report",
        "net/ipv4/igmp.c:igmpv3_send_report"
      ]
    },
    {
      "addr": 18446603336503455888,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv6/mcast.c:1730",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502926632,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1120
    },
    {
      "addr": 18446603336503455888,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
struct sk_buff * add_grec(struct sk_buff * skb, struct ip_mc_list * pmc, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "add_grec",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235623184,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv4/igmp.c:459",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmpv3_send_report",
        "net/ipv4/igmp.c:igmpv3_send_report"
      ]
    },
    {
      "addr": 3236114156,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv6/mcast.c:1730",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235623184,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1264
    },
    {
      "addr": 3236114156,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1256
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision ❓</summary>

```c
struct sk_buff * add_grec(struct sk_buff * skb, struct ip_mc_list * pmc, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "add_grec",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296602096,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv4/igmp.c:459",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmpv3_send_report",
        "net/ipv4/igmp.c:igmpv3_send_report"
      ]
    },
    {
      "addr": 13835058055297244640,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv6/mcast.c:1730",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296602096,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1620
    },
    {
      "addr": 13835058055297244640,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1676
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision ❓</summary>

```c
struct sk_buff * add_grec(struct sk_buff * skb, struct ip_mc_list * pmc, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "add_grec",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279021422,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv4/igmp.c:459",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmpv3_send_report",
        "net/ipv4/igmp.c:igmpv3_send_report"
      ]
    },
    {
      "addr": 18446743936279441208,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv6/mcast.c:1730",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279021422,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 910
    },
    {
      "addr": 18446743936279441208,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 920
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision ❓</summary>

```c
struct sk_buff * add_grec(struct sk_buff * skb, struct ip_mc_list * pmc, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "add_grec",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588903216,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv4/igmp.c:459",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmpv3_send_report",
        "net/ipv4/igmp.c:igmpv3_send_report"
      ]
    },
    {
      "addr": 18446744071589364000,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv6/mcast.c:1730",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588903216,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1231
    },
    {
      "addr": 18446744071589364000,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1281
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision ❓</summary>

```c
struct sk_buff * add_grec(struct sk_buff * skb, struct ip_mc_list * pmc, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "add_grec",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588615152,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv4/igmp.c:459",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmpv3_send_report",
        "net/ipv4/igmp.c:igmpv3_send_report"
      ]
    },
    {
      "addr": 18446744071589088992,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv6/mcast.c:1730",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588615152,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1231
    },
    {
      "addr": 18446744071589088992,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1281
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision ❓</summary>

```c
struct sk_buff * add_grec(struct sk_buff * skb, struct ip_mc_list * pmc, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "add_grec",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589339600,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv4/igmp.c:459",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmpv3_send_report",
        "net/ipv4/igmp.c:igmpv3_send_report"
      ]
    },
    {
      "addr": 18446744071589800864,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv6/mcast.c:1730",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589339600,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1231
    },
    {
      "addr": 18446744071589800864,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1281
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision ❓</summary>

```c
struct sk_buff * add_grec(struct sk_buff * skb, struct ip_mc_list * pmc, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "add_grec",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589381872,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv4/igmp.c:459",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmpv3_send_report",
        "net/ipv4/igmp.c:igmpv3_send_report"
      ]
    },
    {
      "addr": 18446744071589851680,
      "name": "add_grec",
      "external": false,
      "loc": "net/ipv6/mcast.c:1730",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589381872,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1231
    },
    {
      "addr": 18446744071589851680,
      "name": "add_grec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1281
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
