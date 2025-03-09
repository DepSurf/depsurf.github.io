# Function: <code>__netlink_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586495993,
      "name": "__netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:1046",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_lookup"
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
  "name": "__netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586942137,
      "name": "__netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:432",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_lookup"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct sock * __netlink_lookup(struct netlink_table * table, u32 portid, struct net * net)
```

```json
{
  "name": "__netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587137360,
      "name": "__netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:439",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587137360,
      "name": "__netlink_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
struct sock * __netlink_lookup(struct netlink_table * table, u32 portid, struct net * net)
```

```json
{
  "name": "__netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587268368,
      "name": "__netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:470",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587268368,
      "name": "__netlink_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
struct sock * __netlink_lookup(struct netlink_table * table, u32 portid, struct net * net)
```

```json
{
  "name": "__netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587788176,
      "name": "__netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:472",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587788176,
      "name": "__netlink_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
struct sock * __netlink_lookup(struct netlink_table * table, u32 portid, struct net * net)
```

```json
{
  "name": "__netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588129888,
      "name": "__netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:506",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588129888,
      "name": "__netlink_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
struct sock * __netlink_lookup(struct netlink_table * table, u32 portid, struct net * net)
```

```json
{
  "name": "__netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588312384,
      "name": "__netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:506",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588312384,
      "name": "__netlink_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
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
struct sock * __netlink_lookup(struct netlink_table * table, u32 portid, struct net * net)
```

```json
{
  "name": "__netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588710384,
      "name": "__netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:497",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588710384,
      "name": "__netlink_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
struct sock * __netlink_lookup(struct netlink_table * table, u32 portid, struct net * net)
```

```json
{
  "name": "__netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588934288,
      "name": "__netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:497",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588934288,
      "name": "__netlink_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
struct sock * __netlink_lookup(struct netlink_table * table, u32 portid, struct net * net)
```

```json
{
  "name": "__netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589824128,
      "name": "__netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:497",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589824128,
      "name": "__netlink_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
struct sock * __netlink_lookup(struct netlink_table * table, u32 portid, struct net * net)
```

```json
{
  "name": "__netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589861792,
      "name": "__netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:498",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589861792,
      "name": "__netlink_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
struct sock * __netlink_lookup(struct netlink_table * table, u32 portid, struct net * net)
```

```json
{
  "name": "__netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589767840,
      "name": "__netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:508",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589767840,
      "name": "__netlink_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
struct sock * __netlink_lookup(struct netlink_table * table, u32 portid, struct net * net)
```

```json
{
  "name": "__netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590527136,
      "name": "__netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:508",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590527136,
      "name": "__netlink_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct sock * __netlink_lookup(struct netlink_table * table, u32 portid, struct net * net)
```

```json
{
  "name": "__netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592134368,
      "name": "__netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:512",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592138864,
      "name": "__netlink_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct sock * __netlink_lookup(struct netlink_table * table, u32 portid, struct net * net)
```

```json
{
  "name": "__netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593960160,
      "name": "__netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:512",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593963072,
      "name": "__netlink_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct sock * __netlink_lookup(struct netlink_table * table, u32 portid, struct net * net)
```

```json
{
  "name": "__netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594336928,
      "name": "__netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:512",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594338640,
      "name": "__netlink_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct sock * __netlink_lookup(struct netlink_table * table, u32 portid, struct net * net)
```

```json
{
  "name": "__netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595136272,
      "name": "__netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:510",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595137984,
      "name": "__netlink_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
struct sock * __netlink_lookup(struct netlink_table * table, u32 portid, struct net * net)
```

```json
{
  "name": "__netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502529448,
      "name": "__netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:497",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502529448,
      "name": "__netlink_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235241844,
      "name": "__netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:497",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_autobind",
        "net/netlink/af_netlink.c:netlink_lookup"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct sock * __netlink_lookup(struct netlink_table * table, u32 portid, struct net * net)
```

```json
{
  "name": "__netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296105344,
      "name": "__netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:497",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_autobind",
        "net/netlink/af_netlink.c:netlink_autobind",
        "net/netlink/af_netlink.c:netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296105344,
      "name": "__netlink_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
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
struct sock * __netlink_lookup(struct netlink_table * table, u32 portid, struct net * net)
```

```json
{
  "name": "__netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278699174,
      "name": "__netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:497",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:__netlink_dump_start",
        "net/netlink/af_netlink.c:netlink_unicast",
        "net/netlink/af_netlink.c:netlink_autobind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278699174,
      "name": "__netlink_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
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
struct sock * __netlink_lookup(struct netlink_table * table, u32 portid, struct net * net)
```

```json
{
  "name": "__netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588540672,
      "name": "__netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:497",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588540672,
      "name": "__netlink_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
struct sock * __netlink_lookup(struct netlink_table * table, u32 portid, struct net * net)
```

```json
{
  "name": "__netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588252672,
      "name": "__netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:497",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588252672,
      "name": "__netlink_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
struct sock * __netlink_lookup(struct netlink_table * table, u32 portid, struct net * net)
```

```json
{
  "name": "__netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588872848,
      "name": "__netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:497",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588872848,
      "name": "__netlink_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__netlink_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589014442,
      "name": "__netlink_lookup",
      "external": false,
      "loc": "net/netlink/af_netlink.c:497",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_lookup"
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
struct sock * __netlink_lookup(struct netlink_table * table, u32 portid, struct net * net)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct sock * __netlink_lookup(struct netlink_table * table, u32 portid, struct net * net)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ➖</summary>

```c
struct sock * __netlink_lookup(struct netlink_table * table, u32 portid, struct net * net)
```
</details>
</li>
</ul>
