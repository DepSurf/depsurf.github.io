# Function: <code>__bpf_redirect_no_mac</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_redirect_no_mac",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587019807,
      "name": "__bpf_redirect_no_mac",
      "external": false,
      "loc": "net/core/filter.c:1668",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__bpf_redirect"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_redirect_no_mac",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587145394,
      "name": "__bpf_redirect_no_mac",
      "external": false,
      "loc": "net/core/filter.c:1694",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__bpf_redirect"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_redirect_no_mac",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587651042,
      "name": "__bpf_redirect_no_mac",
      "external": false,
      "loc": "net/core/filter.c:1715",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__bpf_redirect"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_redirect_no_mac",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587970702,
      "name": "__bpf_redirect_no_mac",
      "external": false,
      "loc": "net/core/filter.c:2001",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__bpf_redirect"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_redirect_no_mac",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588136582,
      "name": "__bpf_redirect_no_mac",
      "external": false,
      "loc": "net/core/filter.c:2020",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__bpf_redirect"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_redirect_no_mac",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588452223,
      "name": "__bpf_redirect_no_mac",
      "external": false,
      "loc": "net/core/filter.c:2066",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__bpf_redirect"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_redirect_no_mac",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588658655,
      "name": "__bpf_redirect_no_mac",
      "external": false,
      "loc": "net/core/filter.c:2067",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__bpf_redirect"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __bpf_redirect_no_mac(struct sk_buff * skb, struct net_device * dev, u32 flags)
```

```json
{
  "name": "__bpf_redirect_no_mac",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_redirect_no_mac",
      "external": false,
      "loc": "net/core/filter.c:2092",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589531232,
      "name": "__bpf_redirect_no_mac",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 509
    },
    {
      "addr": 18446744071589540385,
      "name": "__bpf_redirect_no_mac.cold",
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
int __bpf_redirect_no_mac(struct sk_buff * skb, struct net_device * dev, u32 flags)
```

```json
{
  "name": "__bpf_redirect_no_mac",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_redirect_no_mac",
      "external": false,
      "loc": "net/core/filter.c:2122",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589540592,
      "name": "__bpf_redirect_no_mac",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 509
    },
    {
      "addr": 18446744071591630735,
      "name": "__bpf_redirect_no_mac.cold",
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
int __bpf_redirect_no_mac(struct sk_buff * skb, struct net_device * dev, u32 flags)
```

```json
{
  "name": "__bpf_redirect_no_mac",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_redirect_no_mac",
      "external": false,
      "loc": "net/core/filter.c:2119",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589437584,
      "name": "__bpf_redirect_no_mac",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
    },
    {
      "addr": 18446744071591574168,
      "name": "__bpf_redirect_no_mac.cold",
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
int __bpf_redirect_no_mac(struct sk_buff * skb, struct net_device * dev, u32 flags)
```

```json
{
  "name": "__bpf_redirect_no_mac",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_redirect_no_mac",
      "external": false,
      "loc": "net/core/filter.c:2120",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590167296,
      "name": "__bpf_redirect_no_mac",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 507
    },
    {
      "addr": 18446744071592703541,
      "name": "__bpf_redirect_no_mac.cold",
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
int __bpf_redirect_no_mac(struct sk_buff * skb, struct net_device * dev, u32 flags)
```

```json
{
  "name": "__bpf_redirect_no_mac",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_redirect_no_mac",
      "external": false,
      "loc": "net/core/filter.c:2121",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591726928,
      "name": "__bpf_redirect_no_mac",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 611
    },
    {
      "addr": 18446744071594590030,
      "name": "__bpf_redirect_no_mac.cold",
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
int __bpf_redirect_no_mac(struct sk_buff * skb, struct net_device * dev, u32 flags)
```

```json
{
  "name": "__bpf_redirect_no_mac",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593515248,
      "name": "__bpf_redirect_no_mac",
      "external": false,
      "loc": "net/core/filter.c:2123",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593515248,
      "name": "__bpf_redirect_no_mac",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 665
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
int __bpf_redirect_no_mac(struct sk_buff * skb, struct net_device * dev, u32 flags)
```

```json
{
  "name": "__bpf_redirect_no_mac",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593979424,
      "name": "__bpf_redirect_no_mac",
      "external": false,
      "loc": "net/core/filter.c:2135",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593979424,
      "name": "__bpf_redirect_no_mac",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
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
int __bpf_redirect_no_mac(struct sk_buff * skb, struct net_device * dev, u32 flags)
```

```json
{
  "name": "__bpf_redirect_no_mac",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594763392,
      "name": "__bpf_redirect_no_mac",
      "external": false,
      "loc": "net/core/filter.c:2142",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594763392,
      "name": "__bpf_redirect_no_mac",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 663
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_redirect_no_mac",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502219624,
      "name": "__bpf_redirect_no_mac",
      "external": false,
      "loc": "net/core/filter.c:2067",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__bpf_redirect"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_redirect_no_mac",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234956400,
      "name": "__bpf_redirect_no_mac",
      "external": false,
      "loc": "net/core/filter.c:2067",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__bpf_redirect"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_redirect_no_mac",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295700400,
      "name": "__bpf_redirect_no_mac",
      "external": false,
      "loc": "net/core/filter.c:2067",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__bpf_redirect"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_redirect_no_mac",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278461986,
      "name": "__bpf_redirect_no_mac",
      "external": false,
      "loc": "net/core/filter.c:2067",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__bpf_redirect"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_redirect_no_mac",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588265391,
      "name": "__bpf_redirect_no_mac",
      "external": false,
      "loc": "net/core/filter.c:2067",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__bpf_redirect"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_redirect_no_mac",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587978207,
      "name": "__bpf_redirect_no_mac",
      "external": false,
      "loc": "net/core/filter.c:2067",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__bpf_redirect"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_redirect_no_mac",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588597215,
      "name": "__bpf_redirect_no_mac",
      "external": false,
      "loc": "net/core/filter.c:2067",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__bpf_redirect"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_redirect_no_mac",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588734879,
      "name": "__bpf_redirect_no_mac",
      "external": false,
      "loc": "net/core/filter.c:2067",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__bpf_redirect"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int __bpf_redirect_no_mac(struct sk_buff * skb, struct net_device * dev, u32 flags)
```
</details>
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
