# Function: <code>netlink_compare</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int netlink_compare(struct rhashtable_compare_arg * arg, const void * ptr)
```

```json
{
  "name": "netlink_compare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586487824,
      "name": "netlink_compare",
      "external": false,
      "loc": "net/netlink/af_netlink.c:1028",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_lookup",
        "net/netlink/af_netlink.c:netlink_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586487824,
      "name": "netlink_compare",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int netlink_compare(struct rhashtable_compare_arg * arg, const void * ptr)
```

```json
{
  "name": "netlink_compare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586934048,
      "name": "netlink_compare",
      "external": false,
      "loc": "net/netlink/af_netlink.c:414",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_insert",
        "net/netlink/af_netlink.c:netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586934048,
      "name": "netlink_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
int netlink_compare(struct rhashtable_compare_arg * arg, const void * ptr)
```

```json
{
  "name": "netlink_compare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587129248,
      "name": "netlink_compare",
      "external": false,
      "loc": "net/netlink/af_netlink.c:421",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_insert",
        "net/netlink/af_netlink.c:__netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587129248,
      "name": "netlink_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int netlink_compare(struct rhashtable_compare_arg * arg, const void * ptr)
```

```json
{
  "name": "netlink_compare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587266984,
      "name": "netlink_compare",
      "external": false,
      "loc": "net/netlink/af_netlink.c:452",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_insert"
      ],
      "caller_func": [
        "net/netlink/af_netlink.c:__netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587259744,
      "name": "netlink_compare",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int netlink_compare(struct rhashtable_compare_arg * arg, const void * ptr)
```

```json
{
  "name": "netlink_compare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587786736,
      "name": "netlink_compare",
      "external": false,
      "loc": "net/netlink/af_netlink.c:454",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_insert"
      ],
      "caller_func": [
        "net/netlink/af_netlink.c:__netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587779232,
      "name": "netlink_compare",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int netlink_compare(struct rhashtable_compare_arg * arg, const void * ptr)
```

```json
{
  "name": "netlink_compare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588131113,
      "name": "netlink_compare",
      "external": false,
      "loc": "net/netlink/af_netlink.c:488",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_insert"
      ],
      "caller_func": [
        "net/netlink/af_netlink.c:__netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588121728,
      "name": "netlink_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int netlink_compare(struct rhashtable_compare_arg * arg, const void * ptr)
```

```json
{
  "name": "netlink_compare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588313659,
      "name": "netlink_compare",
      "external": false,
      "loc": "net/netlink/af_netlink.c:488",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_insert"
      ],
      "caller_func": [
        "net/netlink/af_netlink.c:__netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588303984,
      "name": "netlink_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int netlink_compare(struct rhashtable_compare_arg * arg, const void * ptr)
```

```json
{
  "name": "netlink_compare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588711562,
      "name": "netlink_compare",
      "external": false,
      "loc": "net/netlink/af_netlink.c:479",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_insert"
      ],
      "caller_func": [
        "net/netlink/af_netlink.c:__netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588701696,
      "name": "netlink_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int netlink_compare(struct rhashtable_compare_arg * arg, const void * ptr)
```

```json
{
  "name": "netlink_compare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588935466,
      "name": "netlink_compare",
      "external": false,
      "loc": "net/netlink/af_netlink.c:479",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_insert"
      ],
      "caller_func": [
        "net/netlink/af_netlink.c:__netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588925584,
      "name": "netlink_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int netlink_compare(struct rhashtable_compare_arg * arg, const void * ptr)
```

```json
{
  "name": "netlink_compare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589814992,
      "name": "netlink_compare",
      "external": false,
      "loc": "net/netlink/af_netlink.c:479",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:__netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589814992,
      "name": "netlink_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int netlink_compare(struct rhashtable_compare_arg * arg, const void * ptr)
```

```json
{
  "name": "netlink_compare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589861940,
      "name": "netlink_compare",
      "external": false,
      "loc": "net/netlink/af_netlink.c:480",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589851200,
      "name": "netlink_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int netlink_compare(struct rhashtable_compare_arg * arg, const void * ptr)
```

```json
{
  "name": "netlink_compare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589767980,
      "name": "netlink_compare",
      "external": false,
      "loc": "net/netlink/af_netlink.c:490",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589756640,
      "name": "netlink_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int netlink_compare(struct rhashtable_compare_arg * arg, const void * ptr)
```

```json
{
  "name": "netlink_compare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590527276,
      "name": "netlink_compare",
      "external": false,
      "loc": "net/netlink/af_netlink.c:490",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590515712,
      "name": "netlink_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int netlink_compare(struct rhashtable_compare_arg * arg, const void * ptr)
```

```json
{
  "name": "netlink_compare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592122336,
      "name": "netlink_compare",
      "external": false,
      "loc": "net/netlink/af_netlink.c:494",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592122336,
      "name": "netlink_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
int netlink_compare(struct rhashtable_compare_arg * arg, const void * ptr)
```

```json
{
  "name": "netlink_compare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593944912,
      "name": "netlink_compare",
      "external": false,
      "loc": "net/netlink/af_netlink.c:494",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593944912,
      "name": "netlink_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
int netlink_compare(struct rhashtable_compare_arg * arg, const void * ptr)
```

```json
{
  "name": "netlink_compare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594321168,
      "name": "netlink_compare",
      "external": false,
      "loc": "net/netlink/af_netlink.c:494",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594321168,
      "name": "netlink_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
int netlink_compare(struct rhashtable_compare_arg * arg, const void * ptr)
```

```json
{
  "name": "netlink_compare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595120736,
      "name": "netlink_compare",
      "external": false,
      "loc": "net/netlink/af_netlink.c:492",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595120736,
      "name": "netlink_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
int netlink_compare(struct rhashtable_compare_arg * arg, const void * ptr)
```

```json
{
  "name": "netlink_compare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502519248,
      "name": "netlink_compare",
      "external": false,
      "loc": "net/netlink/af_netlink.c:479",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:__netlink_insert",
        "net/netlink/af_netlink.c:__netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502519248,
      "name": "netlink_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int netlink_compare(struct rhashtable_compare_arg * arg, const void * ptr)
```

```json
{
  "name": "netlink_compare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235240892,
      "name": "netlink_compare",
      "external": false,
      "loc": "net/netlink/af_netlink.c:479",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_insert"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235229904,
      "name": "netlink_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
int netlink_compare(struct rhashtable_compare_arg * arg, const void * ptr)
```

```json
{
  "name": "netlink_compare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296090608,
      "name": "netlink_compare",
      "external": false,
      "loc": "net/netlink/af_netlink.c:479",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:__netlink_insert",
        "net/netlink/af_netlink.c:__netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296090608,
      "name": "netlink_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
int netlink_compare(struct rhashtable_compare_arg * arg, const void * ptr)
```

```json
{
  "name": "netlink_compare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278689870,
      "name": "netlink_compare",
      "external": false,
      "loc": "net/netlink/af_netlink.c:479",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:__netlink_insert",
        "net/netlink/af_netlink.c:__netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278689870,
      "name": "netlink_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int netlink_compare(struct rhashtable_compare_arg * arg, const void * ptr)
```

```json
{
  "name": "netlink_compare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588541850,
      "name": "netlink_compare",
      "external": false,
      "loc": "net/netlink/af_netlink.c:479",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_insert"
      ],
      "caller_func": [
        "net/netlink/af_netlink.c:__netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588531968,
      "name": "netlink_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int netlink_compare(struct rhashtable_compare_arg * arg, const void * ptr)
```

```json
{
  "name": "netlink_compare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588253850,
      "name": "netlink_compare",
      "external": false,
      "loc": "net/netlink/af_netlink.c:479",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_insert"
      ],
      "caller_func": [
        "net/netlink/af_netlink.c:__netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588243968,
      "name": "netlink_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int netlink_compare(struct rhashtable_compare_arg * arg, const void * ptr)
```

```json
{
  "name": "netlink_compare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588874026,
      "name": "netlink_compare",
      "external": false,
      "loc": "net/netlink/af_netlink.c:479",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_insert"
      ],
      "caller_func": [
        "net/netlink/af_netlink.c:__netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588864144,
      "name": "netlink_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int netlink_compare(struct rhashtable_compare_arg * arg, const void * ptr)
```

```json
{
  "name": "netlink_compare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589015542,
      "name": "netlink_compare",
      "external": false,
      "loc": "net/netlink/af_netlink.c:479",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_insert"
      ],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589005616,
      "name": "netlink_compare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
