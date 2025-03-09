# Function: <code>__fib_validate_source</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__fib_validate_source",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586819338,
      "name": "__fib_validate_source",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:324",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:fib_validate_source"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__fib_validate_source",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587268887,
      "name": "__fib_validate_source",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:323",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:fib_validate_source"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__fib_validate_source",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587469791,
      "name": "__fib_validate_source",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:315",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:fib_validate_source"
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
  "name": "__fib_validate_source",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587606345,
      "name": "__fib_validate_source",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:315",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:fib_validate_source"
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
  "name": "__fib_validate_source",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588130518,
      "name": "__fib_validate_source",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:325",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:fib_validate_source"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int __fib_validate_source(struct sk_buff * skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device * dev, int rpf, struct in_device * idev, u32 * itag)
```

```json
{
  "name": "__fib_validate_source",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588483440,
      "name": "__fib_validate_source",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:326",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:fib_validate_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588483440,
      "name": "__fib_validate_source",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1219
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
int __fib_validate_source(struct sk_buff * skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device * dev, int rpf, struct in_device * idev, u32 * itag)
```

```json
{
  "name": "__fib_validate_source",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588678240,
      "name": "__fib_validate_source",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:352",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:fib_validate_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588678240,
      "name": "__fib_validate_source",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1085
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
int __fib_validate_source(struct sk_buff * skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device * dev, int rpf, struct in_device * idev, u32 * itag)
```

```json
{
  "name": "__fib_validate_source",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589090624,
      "name": "__fib_validate_source",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:351",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:fib_validate_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589090624,
      "name": "__fib_validate_source",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1107
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
int __fib_validate_source(struct sk_buff * skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device * dev, int rpf, struct in_device * idev, u32 * itag)
```

```json
{
  "name": "__fib_validate_source",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589314784,
      "name": "__fib_validate_source",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:352",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:fib_validate_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589314784,
      "name": "__fib_validate_source",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1107
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
int __fib_validate_source(struct sk_buff * skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device * dev, int rpf, struct in_device * idev, u32 * itag)
```

```json
{
  "name": "__fib_validate_source",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590290128,
      "name": "__fib_validate_source",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:343",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:fib_validate_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590290128,
      "name": "__fib_validate_source",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1123
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
int __fib_validate_source(struct sk_buff * skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device * dev, int rpf, struct in_device * idev, u32 * itag)
```

```json
{
  "name": "__fib_validate_source",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590342960,
      "name": "__fib_validate_source",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:343",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:fib_validate_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590342960,
      "name": "__fib_validate_source",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1173
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
int __fib_validate_source(struct sk_buff * skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device * dev, int rpf, struct in_device * idev, u32 * itag)
```

```json
{
  "name": "__fib_validate_source",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590258800,
      "name": "__fib_validate_source",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:343",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:fib_validate_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590258800,
      "name": "__fib_validate_source",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1159
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
int __fib_validate_source(struct sk_buff * skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device * dev, int rpf, struct in_device * idev, u32 * itag)
```

```json
{
  "name": "__fib_validate_source",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__fib_validate_source",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:343",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:fib_validate_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591043328,
      "name": "__fib_validate_source",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1185
    },
    {
      "addr": 18446744071592724234,
      "name": "__fib_validate_source.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
int __fib_validate_source(struct sk_buff * skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device * dev, int rpf, struct in_device * idev, u32 * itag)
```

```json
{
  "name": "__fib_validate_source",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__fib_validate_source",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:344",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:fib_validate_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592691696,
      "name": "__fib_validate_source",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1160
    },
    {
      "addr": 18446744071594610511,
      "name": "__fib_validate_source.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
int __fib_validate_source(struct sk_buff * skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device * dev, int rpf, struct in_device * idev, u32 * itag)
```

```json
{
  "name": "__fib_validate_source",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__fib_validate_source",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:344",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:fib_validate_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594560752,
      "name": "__fib_validate_source",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1158
    },
    {
      "addr": 18446744071596345512,
      "name": "__fib_validate_source.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
int __fib_validate_source(struct sk_buff * skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device * dev, int rpf, struct in_device * idev, u32 * itag)
```

```json
{
  "name": "__fib_validate_source",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__fib_validate_source",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:344",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:fib_validate_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594952496,
      "name": "__fib_validate_source",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1158
    },
    {
      "addr": 18446744071596874543,
      "name": "__fib_validate_source.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
int __fib_validate_source(struct sk_buff * skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device * dev, int rpf, struct in_device * idev, u32 * itag)
```

```json
{
  "name": "__fib_validate_source",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__fib_validate_source",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:344",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:fib_validate_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595764912,
      "name": "__fib_validate_source",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1157
    },
    {
      "addr": 18446744071597798637,
      "name": "__fib_validate_source.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
int __fib_validate_source(struct sk_buff * skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device * dev, int rpf, struct in_device * idev, u32 * itag)
```

```json
{
  "name": "__fib_validate_source",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502953264,
      "name": "__fib_validate_source",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:352",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:fib_validate_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502953264,
      "name": "__fib_validate_source",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 952
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
int __fib_validate_source(struct sk_buff * skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device * dev, int rpf, struct in_device * idev, u32 * itag)
```

```json
{
  "name": "__fib_validate_source",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235641868,
      "name": "__fib_validate_source",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:352",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:fib_validate_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235641868,
      "name": "__fib_validate_source",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 960
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
int __fib_validate_source(struct sk_buff * skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device * dev, int rpf, struct in_device * idev, u32 * itag)
```

```json
{
  "name": "__fib_validate_source",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296627968,
      "name": "__fib_validate_source",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:352",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:fib_validate_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296627968,
      "name": "__fib_validate_source",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1240
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
int __fib_validate_source(struct sk_buff * skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device * dev, int rpf, struct in_device * idev, u32 * itag)
```

```json
{
  "name": "__fib_validate_source",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279036462,
      "name": "__fib_validate_source",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:352",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:fib_validate_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279036462,
      "name": "__fib_validate_source",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 774
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
int __fib_validate_source(struct sk_buff * skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device * dev, int rpf, struct in_device * idev, u32 * itag)
```

```json
{
  "name": "__fib_validate_source",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588920960,
      "name": "__fib_validate_source",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:352",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:fib_validate_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588920960,
      "name": "__fib_validate_source",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1107
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
int __fib_validate_source(struct sk_buff * skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device * dev, int rpf, struct in_device * idev, u32 * itag)
```

```json
{
  "name": "__fib_validate_source",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588632896,
      "name": "__fib_validate_source",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:352",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:fib_validate_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588632896,
      "name": "__fib_validate_source",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1107
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
int __fib_validate_source(struct sk_buff * skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device * dev, int rpf, struct in_device * idev, u32 * itag)
```

```json
{
  "name": "__fib_validate_source",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589357344,
      "name": "__fib_validate_source",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:352",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:fib_validate_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589357344,
      "name": "__fib_validate_source",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1107
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
int __fib_validate_source(struct sk_buff * skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device * dev, int rpf, struct in_device * idev, u32 * itag)
```

```json
{
  "name": "__fib_validate_source",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589399968,
      "name": "__fib_validate_source",
      "external": false,
      "loc": "net/ipv4/fib_frontend.c:352",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:fib_validate_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589399968,
      "name": "__fib_validate_source",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1167
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int __fib_validate_source(struct sk_buff * skb, __be32 src, __be32 dst, u8 tos, int oif, struct net_device * dev, int rpf, struct in_device * idev, u32 * itag)
```
</details>
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
