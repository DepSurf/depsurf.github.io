# Function: <code>ipmr_cache_report</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ipmr_cache_report(struct mr_table * mrt, struct sk_buff * pkt, vifi_t vifi, int assert)
```

```json
{
  "name": "ipmr_cache_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586869968,
      "name": "ipmr_cache_report",
      "external": false,
      "loc": "net/ipv4/ipmr.c:943",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:reg_vif_xmit",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/ipv4/ipmr.c:ip_mr_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586869968,
      "name": "ipmr_cache_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 771
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
int ipmr_cache_report(struct mr_table * mrt, struct sk_buff * pkt, vifi_t vifi, int assert)
```

```json
{
  "name": "ipmr_cache_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587319744,
      "name": "ipmr_cache_report",
      "external": false,
      "loc": "net/ipv4/ipmr.c:949",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587319744,
      "name": "ipmr_cache_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 748
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
int ipmr_cache_report(struct mr_table * mrt, struct sk_buff * pkt, vifi_t vifi, int assert)
```

```json
{
  "name": "ipmr_cache_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587522432,
      "name": "ipmr_cache_report",
      "external": false,
      "loc": "net/ipv4/ipmr.c:954",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587522432,
      "name": "ipmr_cache_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 748
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
int ipmr_cache_report(struct mr_table * mrt, struct sk_buff * pkt, vifi_t vifi, int assert)
```

```json
{
  "name": "ipmr_cache_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587665056,
      "name": "ipmr_cache_report",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1003",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587665056,
      "name": "ipmr_cache_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1287
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
int ipmr_cache_report(struct mr_table * mrt, struct sk_buff * pkt, vifi_t vifi, int assert)
```

```json
{
  "name": "ipmr_cache_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588190960,
      "name": "ipmr_cache_report",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1129",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588190960,
      "name": "ipmr_cache_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1352
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
int ipmr_cache_report(struct mr_table * mrt, struct sk_buff * pkt, vifi_t vifi, int assert)
```

```json
{
  "name": "ipmr_cache_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ipmr_cache_report",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1044",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588544928,
      "name": "ipmr_cache_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1333
    },
    {
      "addr": 18446744071588561017,
      "name": "ipmr_cache_report.cold.68",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int ipmr_cache_report(struct mr_table * mrt, struct sk_buff * pkt, vifi_t vifi, int assert)
```

```json
{
  "name": "ipmr_cache_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ipmr_cache_report",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1047",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588741152,
      "name": "ipmr_cache_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1343
    },
    {
      "addr": 18446744071588757961,
      "name": "ipmr_cache_report.cold.69",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int ipmr_cache_report(struct mr_table * mrt, struct sk_buff * pkt, vifi_t vifi, int assert)
```

```json
{
  "name": "ipmr_cache_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ipmr_cache_report",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1039",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589173472,
      "name": "ipmr_cache_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1291
    },
    {
      "addr": 18446744071589190776,
      "name": "ipmr_cache_report.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
int ipmr_cache_report(struct mr_table * mrt, struct sk_buff * pkt, vifi_t vifi, int assert)
```

```json
{
  "name": "ipmr_cache_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ipmr_cache_report",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1039",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589398336,
      "name": "ipmr_cache_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1297
    },
    {
      "addr": 18446744071589416373,
      "name": "ipmr_cache_report.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int ipmr_cache_report(struct mr_table * mrt, struct sk_buff * pkt, vifi_t vifi, int assert)
```

```json
{
  "name": "ipmr_cache_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ipmr_cache_report",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1007",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590388096,
      "name": "ipmr_cache_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 797
    },
    {
      "addr": 18446744071590403383,
      "name": "ipmr_cache_report.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int ipmr_cache_report(struct mr_table * mrt, struct sk_buff * pkt, vifi_t vifi, int assert)
```

```json
{
  "name": "ipmr_cache_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ipmr_cache_report",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1010",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590446368,
      "name": "ipmr_cache_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 828
    },
    {
      "addr": 18446744071591635509,
      "name": "ipmr_cache_report.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int ipmr_cache_report(struct mr_table * mrt, struct sk_buff * pkt, vifi_t vifi, int assert)
```

```json
{
  "name": "ipmr_cache_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ipmr_cache_report",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1010",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590371632,
      "name": "ipmr_cache_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 830
    },
    {
      "addr": 18446744071591578926,
      "name": "ipmr_cache_report.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int ipmr_cache_report(struct mr_table * mrt, struct sk_buff * pkt, vifi_t vifi, int assert)
```

```json
{
  "name": "ipmr_cache_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ipmr_cache_report",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1012",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591162816,
      "name": "ipmr_cache_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 872
    },
    {
      "addr": 18446744071592733221,
      "name": "ipmr_cache_report.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int ipmr_cache_report(struct mr_table * mrt, struct sk_buff * pkt, vifi_t vifi, int assert)
```

```json
{
  "name": "ipmr_cache_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ipmr_cache_report",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1006",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592821072,
      "name": "ipmr_cache_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 889
    },
    {
      "addr": 18446744071594619728,
      "name": "ipmr_cache_report.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int ipmr_cache_report(const struct mr_table * mrt, struct sk_buff * pkt, vifi_t vifi, int assert)
```

```json
{
  "name": "ipmr_cache_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594697520,
      "name": "ipmr_cache_report",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1018",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594697520,
      "name": "ipmr_cache_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 882
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
int ipmr_cache_report(const struct mr_table * mrt, struct sk_buff * pkt, vifi_t vifi, int assert)
```

```json
{
  "name": "ipmr_cache_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595089440,
      "name": "ipmr_cache_report",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1018",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595089440,
      "name": "ipmr_cache_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 897
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
int ipmr_cache_report(const struct mr_table * mrt, struct sk_buff * pkt, vifi_t vifi, int assert)
```

```json
{
  "name": "ipmr_cache_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595902560,
      "name": "ipmr_cache_report",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1018",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595902560,
      "name": "ipmr_cache_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 851
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
int ipmr_cache_report(struct mr_table * mrt, struct sk_buff * pkt, vifi_t vifi, int assert)
```

```json
{
  "name": "ipmr_cache_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503047104,
      "name": "ipmr_cache_report",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1039",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503047104,
      "name": "ipmr_cache_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1120
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
int ipmr_cache_report(struct mr_table * mrt, struct sk_buff * pkt, vifi_t vifi, int assert)
```

```json
{
  "name": "ipmr_cache_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235731632,
      "name": "ipmr_cache_report",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1039",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235731632,
      "name": "ipmr_cache_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1200
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
int ipmr_cache_report(struct mr_table * mrt, struct sk_buff * pkt, vifi_t vifi, int assert)
```

```json
{
  "name": "ipmr_cache_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296745504,
      "name": "ipmr_cache_report",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1039",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296745504,
      "name": "ipmr_cache_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1380
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
int ipmr_cache_report(struct mr_table * mrt, struct sk_buff * pkt, vifi_t vifi, int assert)
```

```json
{
  "name": "ipmr_cache_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279111434,
      "name": "ipmr_cache_report",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1039",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279111434,
      "name": "ipmr_cache_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 948
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
int ipmr_cache_report(struct mr_table * mrt, struct sk_buff * pkt, vifi_t vifi, int assert)
```

```json
{
  "name": "ipmr_cache_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ipmr_cache_report",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1039",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589003600,
      "name": "ipmr_cache_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1297
    },
    {
      "addr": 18446744071589020744,
      "name": "ipmr_cache_report.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int ipmr_cache_report(struct mr_table * mrt, struct sk_buff * pkt, vifi_t vifi, int assert)
```

```json
{
  "name": "ipmr_cache_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ipmr_cache_report",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1039",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588726656,
      "name": "ipmr_cache_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1297
    },
    {
      "addr": 18446744071588743800,
      "name": "ipmr_cache_report.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int ipmr_cache_report(struct mr_table * mrt, struct sk_buff * pkt, vifi_t vifi, int assert)
```

```json
{
  "name": "ipmr_cache_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ipmr_cache_report",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1039",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589439984,
      "name": "ipmr_cache_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1297
    },
    {
      "addr": 18446744071589457128,
      "name": "ipmr_cache_report.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int ipmr_cache_report(struct mr_table * mrt, struct sk_buff * pkt, vifi_t vifi, int assert)
```

```json
{
  "name": "ipmr_cache_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ipmr_cache_report",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1039",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589484624,
      "name": "ipmr_cache_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1313
    },
    {
      "addr": 18446744071589503402,
      "name": "ipmr_cache_report.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct mr_table * mrt</code> ➡️ <code>const struct mr_table * mrt</code>
</li>
</ul>
</details>
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
