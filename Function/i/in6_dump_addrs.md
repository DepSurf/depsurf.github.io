# Function: <code>in6_dump_addrs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "in6_dump_addrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587022695,
      "name": "in6_dump_addrs",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4415",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_dump_addr"
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
  "name": "in6_dump_addrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587467717,
      "name": "in6_dump_addrs",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4667",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_dump_addr"
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
  "name": "in6_dump_addrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587671013,
      "name": "in6_dump_addrs",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4710",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_dump_addr"
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
  "name": "in6_dump_addrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587819899,
      "name": "in6_dump_addrs",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4788",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_dump_addr"
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
  "name": "in6_dump_addrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588349899,
      "name": "in6_dump_addrs",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4792",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_dump_addr"
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
  "name": "in6_dump_addrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588709433,
      "name": "in6_dump_addrs",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4919",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_dump_addr"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int in6_dump_addrs(struct inet6_dev * idev, struct sk_buff * skb, struct netlink_callback * cb, int s_ip_idx, struct inet6_fill_args * fillargs)
```

```json
{
  "name": "in6_dump_addrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588925920,
      "name": "in6_dump_addrs",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4966",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588925920,
      "name": "in6_dump_addrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1116
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
int in6_dump_addrs(struct inet6_dev * idev, struct sk_buff * skb, struct netlink_callback * cb, int s_ip_idx, struct inet6_fill_args * fillargs)
```

```json
{
  "name": "in6_dump_addrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "in6_dump_addrs",
      "external": false,
      "loc": "net/ipv6/addrconf.c:5002",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589368752,
      "name": "in6_dump_addrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1242
    },
    {
      "addr": 18446744071589401240,
      "name": "in6_dump_addrs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
int in6_dump_addrs(struct inet6_dev * idev, struct sk_buff * skb, struct netlink_callback * cb, int s_ip_idx, struct inet6_fill_args * fillargs)
```

```json
{
  "name": "in6_dump_addrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589593248,
      "name": "in6_dump_addrs",
      "external": false,
      "loc": "net/ipv6/addrconf.c:5031",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589593248,
      "name": "in6_dump_addrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1236
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
int in6_dump_addrs(struct inet6_dev * idev, struct sk_buff * skb, struct netlink_callback * cb, int s_ip_idx, struct inet6_fill_args * fillargs)
```

```json
{
  "name": "in6_dump_addrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590600192,
      "name": "in6_dump_addrs",
      "external": false,
      "loc": "net/ipv6/addrconf.c:5048",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590600192,
      "name": "in6_dump_addrs",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int in6_dump_addrs(struct inet6_dev * idev, struct sk_buff * skb, struct netlink_callback * cb, int s_ip_idx, struct inet6_fill_args * fillargs)
```

```json
{
  "name": "in6_dump_addrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590662880,
      "name": "in6_dump_addrs",
      "external": false,
      "loc": "net/ipv6/addrconf.c:5079",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590662880,
      "name": "in6_dump_addrs",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int in6_dump_addrs(struct inet6_dev * idev, struct sk_buff * skb, struct netlink_callback * cb, int s_ip_idx, struct inet6_fill_args * fillargs)
```

```json
{
  "name": "in6_dump_addrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590587888,
      "name": "in6_dump_addrs",
      "external": false,
      "loc": "net/ipv6/addrconf.c:5083",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590587888,
      "name": "in6_dump_addrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 949
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
int in6_dump_addrs(struct inet6_dev * idev, struct sk_buff * skb, struct netlink_callback * cb, int s_ip_idx, struct inet6_fill_args * fillargs)
```

```json
{
  "name": "in6_dump_addrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591399568,
      "name": "in6_dump_addrs",
      "external": false,
      "loc": "net/ipv6/addrconf.c:5121",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591399568,
      "name": "in6_dump_addrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 949
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
int in6_dump_addrs(struct inet6_dev * idev, struct sk_buff * skb, struct netlink_callback * cb, int s_ip_idx, struct inet6_fill_args * fillargs)
```

```json
{
  "name": "in6_dump_addrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593075824,
      "name": "in6_dump_addrs",
      "external": false,
      "loc": "net/ipv6/addrconf.c:5138",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593075824,
      "name": "in6_dump_addrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 959
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
int in6_dump_addrs(struct inet6_dev * idev, struct sk_buff * skb, struct netlink_callback * cb, int s_ip_idx, struct inet6_fill_args * fillargs)
```

```json
{
  "name": "in6_dump_addrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594970016,
      "name": "in6_dump_addrs",
      "external": false,
      "loc": "net/ipv6/addrconf.c:5151",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594970016,
      "name": "in6_dump_addrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 959
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
int in6_dump_addrs(struct inet6_dev * idev, struct sk_buff * skb, struct netlink_callback * cb, int s_ip_idx, struct inet6_fill_args * fillargs)
```

```json
{
  "name": "in6_dump_addrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595362768,
      "name": "in6_dump_addrs",
      "external": false,
      "loc": "net/ipv6/addrconf.c:5157",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595362768,
      "name": "in6_dump_addrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 959
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
int in6_dump_addrs(struct inet6_dev * idev, struct sk_buff * skb, struct netlink_callback * cb, int s_ip_idx, struct inet6_fill_args * fillargs)
```

```json
{
  "name": "in6_dump_addrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596203664,
      "name": "in6_dump_addrs",
      "external": false,
      "loc": "net/ipv6/addrconf.c:5212",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596203664,
      "name": "in6_dump_addrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 961
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
int in6_dump_addrs(struct inet6_dev * idev, struct sk_buff * skb, struct netlink_callback * cb, int s_ip_idx, struct inet6_fill_args * fillargs)
```

```json
{
  "name": "in6_dump_addrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503268120,
      "name": "in6_dump_addrs",
      "external": false,
      "loc": "net/ipv6/addrconf.c:5031",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503268120,
      "name": "in6_dump_addrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1204
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
int in6_dump_addrs(struct inet6_dev * idev, struct sk_buff * skb, struct netlink_callback * cb, int s_ip_idx, struct inet6_fill_args * fillargs)
```

```json
{
  "name": "in6_dump_addrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235942040,
      "name": "in6_dump_addrs",
      "external": false,
      "loc": "net/ipv6/addrconf.c:5031",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235942040,
      "name": "in6_dump_addrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1144
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
int in6_dump_addrs(struct inet6_dev * idev, struct sk_buff * skb, struct netlink_callback * cb, int s_ip_idx, struct inet6_fill_args * fillargs)
```

```json
{
  "name": "in6_dump_addrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297020560,
      "name": "in6_dump_addrs",
      "external": false,
      "loc": "net/ipv6/addrconf.c:5031",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297020560,
      "name": "in6_dump_addrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1424
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
int in6_dump_addrs(struct inet6_dev * idev, struct sk_buff * skb, struct netlink_callback * cb, int s_ip_idx, struct inet6_fill_args * fillargs)
```

```json
{
  "name": "in6_dump_addrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279294526,
      "name": "in6_dump_addrs",
      "external": false,
      "loc": "net/ipv6/addrconf.c:5031",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279294526,
      "name": "in6_dump_addrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 826
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
int in6_dump_addrs(struct inet6_dev * idev, struct sk_buff * skb, struct netlink_callback * cb, int s_ip_idx, struct inet6_fill_args * fillargs)
```

```json
{
  "name": "in6_dump_addrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589197616,
      "name": "in6_dump_addrs",
      "external": false,
      "loc": "net/ipv6/addrconf.c:5031",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589197616,
      "name": "in6_dump_addrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1236
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
int in6_dump_addrs(struct inet6_dev * idev, struct sk_buff * skb, struct netlink_callback * cb, int s_ip_idx, struct inet6_fill_args * fillargs)
```

```json
{
  "name": "in6_dump_addrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588922608,
      "name": "in6_dump_addrs",
      "external": false,
      "loc": "net/ipv6/addrconf.c:5031",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588922608,
      "name": "in6_dump_addrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1236
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
int in6_dump_addrs(struct inet6_dev * idev, struct sk_buff * skb, struct netlink_callback * cb, int s_ip_idx, struct inet6_fill_args * fillargs)
```

```json
{
  "name": "in6_dump_addrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589634480,
      "name": "in6_dump_addrs",
      "external": false,
      "loc": "net/ipv6/addrconf.c:5031",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589634480,
      "name": "in6_dump_addrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1236
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
int in6_dump_addrs(struct inet6_dev * idev, struct sk_buff * skb, struct netlink_callback * cb, int s_ip_idx, struct inet6_fill_args * fillargs)
```

```json
{
  "name": "in6_dump_addrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589683440,
      "name": "in6_dump_addrs",
      "external": false,
      "loc": "net/ipv6/addrconf.c:5031",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589683440,
      "name": "in6_dump_addrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1236
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int in6_dump_addrs(struct inet6_dev * idev, struct sk_buff * skb, struct netlink_callback * cb, int s_ip_idx, struct inet6_fill_args * fillargs)
```
</details>
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
