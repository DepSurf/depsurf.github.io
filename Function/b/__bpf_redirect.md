# Function: <code>__bpf_redirect</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int __bpf_redirect(struct sk_buff * skb, struct net_device * dev, u32 flags)
```

```json
{
  "name": "__bpf_redirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587019696,
      "name": "__bpf_redirect",
      "external": false,
      "loc": "net/core/filter.c:1703",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587019696,
      "name": "__bpf_redirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 655
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
int __bpf_redirect(struct sk_buff * skb, struct net_device * dev, u32 flags)
```

```json
{
  "name": "__bpf_redirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587145296,
      "name": "__bpf_redirect",
      "external": false,
      "loc": "net/core/filter.c:1729",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587145296,
      "name": "__bpf_redirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 635
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
int __bpf_redirect(struct sk_buff * skb, struct net_device * dev, u32 flags)
```

```json
{
  "name": "__bpf_redirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587650944,
      "name": "__bpf_redirect",
      "external": false,
      "loc": "net/core/filter.c:1750",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587650944,
      "name": "__bpf_redirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 661
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
int __bpf_redirect(struct sk_buff * skb, struct net_device * dev, u32 flags)
```

```json
{
  "name": "__bpf_redirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_redirect",
      "external": false,
      "loc": "net/core/filter.c:2036",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587970624,
      "name": "__bpf_redirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 686
    },
    {
      "addr": 18446744071587989416,
      "name": "__bpf_redirect.cold.95",
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
int __bpf_redirect(struct sk_buff * skb, struct net_device * dev, u32 flags)
```

```json
{
  "name": "__bpf_redirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_redirect",
      "external": false,
      "loc": "net/core/filter.c:2056",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588136448,
      "name": "__bpf_redirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 692
    },
    {
      "addr": 18446744071588148224,
      "name": "__bpf_redirect.cold.102",
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
int __bpf_redirect(struct sk_buff * skb, struct net_device * dev, u32 flags)
```

```json
{
  "name": "__bpf_redirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_redirect",
      "external": false,
      "loc": "net/core/filter.c:2102",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588452096,
      "name": "__bpf_redirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 769
    },
    {
      "addr": 18446744071588469265,
      "name": "__bpf_redirect.cold",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int __bpf_redirect(struct sk_buff * skb, struct net_device * dev, u32 flags)
```

```json
{
  "name": "__bpf_redirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_redirect",
      "external": false,
      "loc": "net/core/filter.c:2103",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588658528,
      "name": "__bpf_redirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 778
    },
    {
      "addr": 18446744071588674762,
      "name": "__bpf_redirect.cold",
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
int __bpf_redirect(struct sk_buff * skb, struct net_device * dev, u32 flags)
```

```json
{
  "name": "__bpf_redirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_redirect",
      "external": false,
      "loc": "net/core/filter.c:2128",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589531744,
      "name": "__bpf_redirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
    },
    {
      "addr": 18446744071589540402,
      "name": "__bpf_redirect.cold",
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
int __bpf_redirect(struct sk_buff * skb, struct net_device * dev, u32 flags)
```

```json
{
  "name": "__bpf_redirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_redirect",
      "external": false,
      "loc": "net/core/filter.c:2158",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589541104,
      "name": "__bpf_redirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
    },
    {
      "addr": 18446744071591630752,
      "name": "__bpf_redirect.cold",
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
int __bpf_redirect(struct sk_buff * skb, struct net_device * dev, u32 flags)
```

```json
{
  "name": "__bpf_redirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_redirect",
      "external": false,
      "loc": "net/core/filter.c:2155",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589438112,
      "name": "__bpf_redirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
    },
    {
      "addr": 18446744071591574185,
      "name": "__bpf_redirect.cold",
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
int __bpf_redirect(struct sk_buff * skb, struct net_device * dev, u32 flags)
```

```json
{
  "name": "__bpf_redirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_redirect",
      "external": false,
      "loc": "net/core/filter.c:2156",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590167808,
      "name": "__bpf_redirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 18446744071592703558,
      "name": "__bpf_redirect.cold",
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
int __bpf_redirect(struct sk_buff * skb, struct net_device * dev, u32 flags)
```

```json
{
  "name": "__bpf_redirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_redirect",
      "external": false,
      "loc": "net/core/filter.c:2157",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591727552,
      "name": "__bpf_redirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    },
    {
      "addr": 18446744071594590047,
      "name": "__bpf_redirect.cold",
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
int __bpf_redirect(struct sk_buff * skb, struct net_device * dev, u32 flags)
```

```json
{
  "name": "__bpf_redirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593515936,
      "name": "__bpf_redirect",
      "external": false,
      "loc": "net/core/filter.c:2164",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593515936,
      "name": "__bpf_redirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
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
int __bpf_redirect(struct sk_buff * skb, struct net_device * dev, u32 flags)
```

```json
{
  "name": "__bpf_redirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593980144,
      "name": "__bpf_redirect",
      "external": false,
      "loc": "net/core/filter.c:2176",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593980144,
      "name": "__bpf_redirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 447
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
int __bpf_redirect(struct sk_buff * skb, struct net_device * dev, u32 flags)
```

```json
{
  "name": "__bpf_redirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594764080,
      "name": "__bpf_redirect",
      "external": false,
      "loc": "net/core/filter.c:2183",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594764080,
      "name": "__bpf_redirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 447
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
int __bpf_redirect(struct sk_buff * skb, struct net_device * dev, u32 flags)
```

```json
{
  "name": "__bpf_redirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502219488,
      "name": "__bpf_redirect",
      "external": false,
      "loc": "net/core/filter.c:2103",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502219488,
      "name": "__bpf_redirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 732
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
int __bpf_redirect(struct sk_buff * skb, struct net_device * dev, u32 flags)
```

```json
{
  "name": "__bpf_redirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234956260,
      "name": "__bpf_redirect",
      "external": false,
      "loc": "net/core/filter.c:2103",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234956260,
      "name": "__bpf_redirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 752
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
int __bpf_redirect(struct sk_buff * skb, struct net_device * dev, u32 flags)
```

```json
{
  "name": "__bpf_redirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295700224,
      "name": "__bpf_redirect",
      "external": false,
      "loc": "net/core/filter.c:2103",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295700224,
      "name": "__bpf_redirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1032
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
int __bpf_redirect(struct sk_buff * skb, struct net_device * dev, u32 flags)
```

```json
{
  "name": "__bpf_redirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278461852,
      "name": "__bpf_redirect",
      "external": false,
      "loc": "net/core/filter.c:2103",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278461852,
      "name": "__bpf_redirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 724
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
int __bpf_redirect(struct sk_buff * skb, struct net_device * dev, u32 flags)
```

```json
{
  "name": "__bpf_redirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_redirect",
      "external": false,
      "loc": "net/core/filter.c:2103",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588265264,
      "name": "__bpf_redirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 778
    },
    {
      "addr": 18446744071588281498,
      "name": "__bpf_redirect.cold",
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
int __bpf_redirect(struct sk_buff * skb, struct net_device * dev, u32 flags)
```

```json
{
  "name": "__bpf_redirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_redirect",
      "external": false,
      "loc": "net/core/filter.c:2103",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587978080,
      "name": "__bpf_redirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 778
    },
    {
      "addr": 18446744071587994314,
      "name": "__bpf_redirect.cold",
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
int __bpf_redirect(struct sk_buff * skb, struct net_device * dev, u32 flags)
```

```json
{
  "name": "__bpf_redirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_redirect",
      "external": false,
      "loc": "net/core/filter.c:2103",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588597088,
      "name": "__bpf_redirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 778
    },
    {
      "addr": 18446744071588613322,
      "name": "__bpf_redirect.cold",
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
int __bpf_redirect(struct sk_buff * skb, struct net_device * dev, u32 flags)
```

```json
{
  "name": "__bpf_redirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_redirect",
      "external": false,
      "loc": "net/core/filter.c:2103",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588734752,
      "name": "__bpf_redirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 778
    },
    {
      "addr": 18446744071588751002,
      "name": "__bpf_redirect.cold",
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
<details>
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int __bpf_redirect(struct sk_buff * skb, struct net_device * dev, u32 flags)
```
</details>
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
