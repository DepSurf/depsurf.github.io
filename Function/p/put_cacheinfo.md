# Function: <code>put_cacheinfo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int put_cacheinfo(struct sk_buff * skb, long unsigned int cstamp, long unsigned int tstamp, u32 preferred, u32 valid)
```

```json
{
  "name": "put_cacheinfo",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586777797,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv4/devinet.c:1490",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587009200,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4265",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587009200,
      "name": "put_cacheinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int put_cacheinfo(struct sk_buff * skb, long unsigned int cstamp, long unsigned int tstamp, u32 preferred, u32 valid)
```

```json
{
  "name": "put_cacheinfo",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587225077,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv4/devinet.c:1516",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587456144,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4517",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587456144,
      "name": "put_cacheinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int put_cacheinfo(struct sk_buff * skb, long unsigned int cstamp, long unsigned int tstamp, u32 preferred, u32 valid)
```

```json
{
  "name": "put_cacheinfo",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587425621,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv4/devinet.c:1516",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587659680,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4560",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587659680,
      "name": "put_cacheinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int put_cacheinfo(struct sk_buff * skb, long unsigned int cstamp, long unsigned int tstamp, u32 preferred, u32 valid)
```

```json
{
  "name": "put_cacheinfo",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587562017,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv4/devinet.c:1556",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587809024,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4638",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587809024,
      "name": "put_cacheinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int put_cacheinfo(struct sk_buff * skb, long unsigned int cstamp, long unsigned int tstamp, u32 preferred, u32 valid)
```

```json
{
  "name": "put_cacheinfo",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588085329,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv4/devinet.c:1565",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588338320,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4642",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588338320,
      "name": "put_cacheinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int put_cacheinfo(struct sk_buff * skb, long unsigned int cstamp, long unsigned int tstamp, u32 preferred, u32 valid)
```

```json
{
  "name": "put_cacheinfo",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588438841,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv4/devinet.c:1573",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588695360,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4763",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588695360,
      "name": "put_cacheinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int put_cacheinfo(struct sk_buff * skb, long unsigned int cstamp, long unsigned int tstamp, u32 preferred, u32 valid)
```

```json
{
  "name": "put_cacheinfo",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588631421,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv4/devinet.c:1585",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588913600,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4785",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588913600,
      "name": "put_cacheinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int put_cacheinfo(struct sk_buff * skb, long unsigned int cstamp, long unsigned int tstamp, u32 preferred, u32 valid)
```

```json
{
  "name": "put_cacheinfo",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589043464,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv4/devinet.c:1635",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589355856,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4821",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589355856,
      "name": "put_cacheinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int put_cacheinfo(struct sk_buff * skb, long unsigned int cstamp, long unsigned int tstamp, u32 preferred, u32 valid)
```

```json
{
  "name": "put_cacheinfo",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589267608,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv4/devinet.c:1630",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589579968,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4850",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589579968,
      "name": "put_cacheinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_cacheinfo",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590242312,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv4/devinet.c:1636",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590593623,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4867",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_fill_ifacaddr",
        "net/ipv6/addrconf.c:inet6_fill_ifmcaddr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_cacheinfo",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590295016,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv4/devinet.c:1635",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590661287,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4894",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_fill_ifacaddr",
        "net/ipv6/addrconf.c:inet6_fill_ifmcaddr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_cacheinfo",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590210648,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv4/devinet.c:1635",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590588281,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4898",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifacaddr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_cacheinfo",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590991512,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv4/devinet.c:1635",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591399961,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4934",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifacaddr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_cacheinfo",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592637420,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv4/devinet.c:1640",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593076233,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4946",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifacaddr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_cacheinfo",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594503414,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv4/devinet.c:1641",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594970425,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4959",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifacaddr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_cacheinfo",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594895030,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv4/devinet.c:1644",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595363254,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4965",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifacaddr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_cacheinfo",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595706359,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv4/devinet.c:1661",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596204150,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv6/addrconf.c:5020",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifacaddr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline ❓</summary>

```c
int put_cacheinfo(struct sk_buff * skb, long unsigned int cstamp, long unsigned int tstamp, u32 preferred, u32 valid)
```

```json
{
  "name": "put_cacheinfo",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502897380,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv4/devinet.c:1630",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503255232,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4850",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503255232,
      "name": "put_cacheinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision, Selective Inline ❓</summary>

```c
int put_cacheinfo(struct sk_buff * skb, long unsigned int cstamp, long unsigned int tstamp, u32 preferred, u32 valid)
```

```json
{
  "name": "put_cacheinfo",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235590668,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv4/devinet.c:1630",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 3235929228,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4850",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235929228,
      "name": "put_cacheinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline ❓</summary>

```c
int put_cacheinfo(struct sk_buff * skb, long unsigned int cstamp, long unsigned int tstamp, u32 preferred, u32 valid)
```

```json
{
  "name": "put_cacheinfo",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296561056,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv4/devinet.c:1630",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297000720,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4850",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297000720,
      "name": "put_cacheinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision, Selective Inline ❓</summary>

```c
int put_cacheinfo(struct sk_buff * skb, long unsigned int cstamp, long unsigned int tstamp, u32 preferred, u32 valid)
```

```json
{
  "name": "put_cacheinfo",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278994534,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv4/devinet.c:1630",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279283100,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4850",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279283100,
      "name": "put_cacheinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int put_cacheinfo(struct sk_buff * skb, long unsigned int cstamp, long unsigned int tstamp, u32 preferred, u32 valid)
```

```json
{
  "name": "put_cacheinfo",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588873784,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv4/devinet.c:1630",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589184336,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4850",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589184336,
      "name": "put_cacheinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int put_cacheinfo(struct sk_buff * skb, long unsigned int cstamp, long unsigned int tstamp, u32 preferred, u32 valid)
```

```json
{
  "name": "put_cacheinfo",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588585720,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv4/devinet.c:1630",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588909328,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4850",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588909328,
      "name": "put_cacheinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int put_cacheinfo(struct sk_buff * skb, long unsigned int cstamp, long unsigned int tstamp, u32 preferred, u32 valid)
```

```json
{
  "name": "put_cacheinfo",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589310168,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv4/devinet.c:1630",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589621200,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4850",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589621200,
      "name": "put_cacheinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int put_cacheinfo(struct sk_buff * skb, long unsigned int cstamp, long unsigned int tstamp, u32 preferred, u32 valid)
```

```json
{
  "name": "put_cacheinfo",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589351977,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv4/devinet.c:1630",
      "file": "net/ipv4/devinet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589669712,
      "name": "put_cacheinfo",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4850",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589669712,
      "name": "put_cacheinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int put_cacheinfo(struct sk_buff * skb, long unsigned int cstamp, long unsigned int tstamp, u32 preferred, u32 valid)
```
</details>
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
