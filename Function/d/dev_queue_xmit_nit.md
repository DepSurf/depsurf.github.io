# Function: <code>dev_queue_xmit_nit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_queue_xmit_nit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586302108,
      "name": "dev_queue_xmit_nit",
      "external": false,
      "loc": "net/core/dev.c:1835",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_hard_start_xmit"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void dev_queue_xmit_nit(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "dev_queue_xmit_nit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586714432,
      "name": "dev_queue_xmit_nit",
      "external": true,
      "loc": "net/core/dev.c:1855",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_hard_start_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586714432,
      "name": "dev_queue_xmit_nit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 525
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
void dev_queue_xmit_nit(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "dev_queue_xmit_nit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586900272,
      "name": "dev_queue_xmit_nit",
      "external": true,
      "loc": "net/core/dev.c:1871",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_hard_start_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586900272,
      "name": "dev_queue_xmit_nit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 525
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
void dev_queue_xmit_nit(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "dev_queue_xmit_nit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587025568,
      "name": "dev_queue_xmit_nit",
      "external": true,
      "loc": "net/core/dev.c:1905",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_hard_start_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587025568,
      "name": "dev_queue_xmit_nit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 519
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
void dev_queue_xmit_nit(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "dev_queue_xmit_nit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587525280,
      "name": "dev_queue_xmit_nit",
      "external": true,
      "loc": "net/core/dev.c:1920",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_hard_start_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587525280,
      "name": "dev_queue_xmit_nit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 614
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
void dev_queue_xmit_nit(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "dev_queue_xmit_nit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_queue_xmit_nit",
      "external": true,
      "loc": "net/core/dev.c:1964",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_hard_start_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587860563,
      "name": "dev_queue_xmit_nit.cold.161",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071587830000,
      "name": "dev_queue_xmit_nit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
void dev_queue_xmit_nit(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "dev_queue_xmit_nit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_queue_xmit_nit",
      "external": true,
      "loc": "net/core/dev.c:2009",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_hard_start_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588000796,
      "name": "dev_queue_xmit_nit.cold.164",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071587959040,
      "name": "dev_queue_xmit_nit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
void dev_queue_xmit_nit(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "dev_queue_xmit_nit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_queue_xmit_nit",
      "external": true,
      "loc": "net/core/dev.c:2019",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_hard_start_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588311812,
      "name": "dev_queue_xmit_nit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071588273184,
      "name": "dev_queue_xmit_nit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 630
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
void dev_queue_xmit_nit(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "dev_queue_xmit_nit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_queue_xmit_nit",
      "external": true,
      "loc": "net/core/dev.c:1937",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_hard_start_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588518225,
      "name": "dev_queue_xmit_nit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071588478800,
      "name": "dev_queue_xmit_nit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 630
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
void dev_queue_xmit_nit(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "dev_queue_xmit_nit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_queue_xmit_nit",
      "external": true,
      "loc": "net/core/dev.c:2297",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_hard_start_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589392020,
      "name": "dev_queue_xmit_nit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071589343264,
      "name": "dev_queue_xmit_nit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 675
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
void dev_queue_xmit_nit(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "dev_queue_xmit_nit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_queue_xmit_nit",
      "external": true,
      "loc": "net/core/dev.c:2322",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591629168,
      "name": "dev_queue_xmit_nit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071589345248,
      "name": "dev_queue_xmit_nit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 667
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
void dev_queue_xmit_nit(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "dev_queue_xmit_nit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_queue_xmit_nit",
      "external": true,
      "loc": "net/core/dev.c:2387",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591572597,
      "name": "dev_queue_xmit_nit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071589240912,
      "name": "dev_queue_xmit_nit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 661
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
void dev_queue_xmit_nit(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "dev_queue_xmit_nit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_queue_xmit_nit",
      "external": true,
      "loc": "net/core/dev.c:2262",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592697868,
      "name": "dev_queue_xmit_nit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071589965104,
      "name": "dev_queue_xmit_nit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 671
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
void dev_queue_xmit_nit(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "dev_queue_xmit_nit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_queue_xmit_nit",
      "external": true,
      "loc": "net/core/dev.c:2239",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_hard_start_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594584089,
      "name": "dev_queue_xmit_nit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071591508448,
      "name": "dev_queue_xmit_nit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 696
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
void dev_queue_xmit_nit(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "dev_queue_xmit_nit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_queue_xmit_nit",
      "external": true,
      "loc": "net/core/dev.c:2224",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_hard_start_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596323825,
      "name": "dev_queue_xmit_nit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071593275488,
      "name": "dev_queue_xmit_nit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 725
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
void dev_queue_xmit_nit(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "dev_queue_xmit_nit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_queue_xmit_nit",
      "external": true,
      "loc": "net/core/dev.c:2250",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_hard_start_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596853819,
      "name": "dev_queue_xmit_nit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071593731536,
      "name": "dev_queue_xmit_nit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 725
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
void dev_queue_xmit_nit(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "dev_queue_xmit_nit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_queue_xmit_nit",
      "external": true,
      "loc": "net/core/dev.c:2254",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_hard_start_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597778810,
      "name": "dev_queue_xmit_nit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071594510992,
      "name": "dev_queue_xmit_nit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 732
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
void dev_queue_xmit_nit(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "dev_queue_xmit_nit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501993352,
      "name": "dev_queue_xmit_nit",
      "external": true,
      "loc": "net/core/dev.c:1937",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_hard_start_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501993352,
      "name": "dev_queue_xmit_nit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
void dev_queue_xmit_nit(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "dev_queue_xmit_nit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234758760,
      "name": "dev_queue_xmit_nit",
      "external": true,
      "loc": "net/core/dev.c:1937",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_hard_start_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234758760,
      "name": "dev_queue_xmit_nit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 636
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
void dev_queue_xmit_nit(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "dev_queue_xmit_nit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295442544,
      "name": "dev_queue_xmit_nit",
      "external": true,
      "loc": "net/core/dev.c:1937",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_hard_start_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295442544,
      "name": "dev_queue_xmit_nit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 832
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
void dev_queue_xmit_nit(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "dev_queue_xmit_nit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278297072,
      "name": "dev_queue_xmit_nit",
      "external": true,
      "loc": "net/core/dev.c:1937",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_hard_start_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278297072,
      "name": "dev_queue_xmit_nit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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
void dev_queue_xmit_nit(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "dev_queue_xmit_nit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_queue_xmit_nit",
      "external": true,
      "loc": "net/core/dev.c:1937",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_hard_start_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588124961,
      "name": "dev_queue_xmit_nit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071588085584,
      "name": "dev_queue_xmit_nit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 630
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
void dev_queue_xmit_nit(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "dev_queue_xmit_nit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_queue_xmit_nit",
      "external": true,
      "loc": "net/core/dev.c:1937",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_hard_start_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587837793,
      "name": "dev_queue_xmit_nit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071587799056,
      "name": "dev_queue_xmit_nit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 630
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
void dev_queue_xmit_nit(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "dev_queue_xmit_nit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_queue_xmit_nit",
      "external": true,
      "loc": "net/core/dev.c:1937",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_hard_start_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588456785,
      "name": "dev_queue_xmit_nit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071588417360,
      "name": "dev_queue_xmit_nit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 630
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
void dev_queue_xmit_nit(struct sk_buff * skb, struct net_device * dev)
```

```json
{
  "name": "dev_queue_xmit_nit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_queue_xmit_nit",
      "external": true,
      "loc": "net/core/dev.c:1937",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_hard_start_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588593819,
      "name": "dev_queue_xmit_nit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071588556336,
      "name": "dev_queue_xmit_nit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 630
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
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void dev_queue_xmit_nit(struct sk_buff * skb, struct net_device * dev)
```
</details>
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
