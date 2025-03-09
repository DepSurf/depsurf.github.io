# Function: <code>ip6mr_mfc_delete</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6mr_mfc_delete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587212780,
      "name": "ip6mr_mfc_delete",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1299",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
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
  "name": "ip6mr_mfc_delete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587669565,
      "name": "ip6mr_mfc_delete",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1301",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
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
  "name": "ip6mr_mfc_delete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587878029,
      "name": "ip6mr_mfc_delete",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1301",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
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
  "name": "ip6mr_mfc_delete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588035019,
      "name": "ip6mr_mfc_delete",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1306",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
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
  "name": "ip6mr_mfc_delete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588572266,
      "name": "ip6mr_mfc_delete",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1306",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
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
  "name": "ip6mr_mfc_delete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588937339,
      "name": "ip6mr_mfc_delete",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1194",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
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
  "name": "ip6mr_mfc_delete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589161470,
      "name": "ip6mr_mfc_delete",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1212",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int ip6mr_mfc_delete(struct mr_table * mrt, struct mf6cctl * mfc, int parent)
```

```json
{
  "name": "ip6mr_mfc_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589611440,
      "name": "ip6mr_mfc_delete",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1207",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589611440,
      "name": "ip6mr_mfc_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 793
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
int ip6mr_mfc_delete(struct mr_table * mrt, struct mf6cctl * mfc, int parent)
```

```json
{
  "name": "ip6mr_mfc_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589835680,
      "name": "ip6mr_mfc_delete",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1207",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589835680,
      "name": "ip6mr_mfc_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 793
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
int ip6mr_mfc_delete(struct mr_table * mrt, struct mf6cctl * mfc, int parent)
```

```json
{
  "name": "ip6mr_mfc_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590861520,
      "name": "ip6mr_mfc_delete",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1211",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590861520,
      "name": "ip6mr_mfc_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 529
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
int ip6mr_mfc_delete(struct mr_table * mrt, struct mf6cctl * mfc, int parent)
```

```json
{
  "name": "ip6mr_mfc_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590922304,
      "name": "ip6mr_mfc_delete",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1211",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590922304,
      "name": "ip6mr_mfc_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 539
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
int ip6mr_mfc_delete(struct mr_table * mrt, struct mf6cctl * mfc, int parent)
```

```json
{
  "name": "ip6mr_mfc_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590851760,
      "name": "ip6mr_mfc_delete",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1211",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590851760,
      "name": "ip6mr_mfc_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 571
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
int ip6mr_mfc_delete(struct mr_table * mrt, struct mf6cctl * mfc, int parent)
```

```json
{
  "name": "ip6mr_mfc_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6mr_mfc_delete",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1212",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591680624,
      "name": "ip6mr_mfc_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 587
    },
    {
      "addr": 18446744071592743753,
      "name": "ip6mr_mfc_delete.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int ip6mr_mfc_delete(struct mr_table * mrt, struct mf6cctl * mfc, int parent)
```

```json
{
  "name": "ip6mr_mfc_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6mr_mfc_delete",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1209",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593376528,
      "name": "ip6mr_mfc_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
    },
    {
      "addr": 18446744071594630231,
      "name": "ip6mr_mfc_delete.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int ip6mr_mfc_delete(struct mr_table * mrt, struct mf6cctl * mfc, int parent)
```

```json
{
  "name": "ip6mr_mfc_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6mr_mfc_delete",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1218",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595289872,
      "name": "ip6mr_mfc_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
    },
    {
      "addr": 18446744071596363998,
      "name": "ip6mr_mfc_delete.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int ip6mr_mfc_delete(struct mr_table * mrt, struct mf6cctl * mfc, int parent)
```

```json
{
  "name": "ip6mr_mfc_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6mr_mfc_delete",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1218",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595682528,
      "name": "ip6mr_mfc_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
    },
    {
      "addr": 18446744071596892046,
      "name": "ip6mr_mfc_delete.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int ip6mr_mfc_delete(struct mr_table * mrt, struct mf6cctl * mfc, int parent)
```

```json
{
  "name": "ip6mr_mfc_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6mr_mfc_delete",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1218",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596530288,
      "name": "ip6mr_mfc_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
    },
    {
      "addr": 18446744071597816771,
      "name": "ip6mr_mfc_delete.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int ip6mr_mfc_delete(struct mr_table * mrt, struct mf6cctl * mfc, int parent)
```

```json
{
  "name": "ip6mr_mfc_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503539768,
      "name": "ip6mr_mfc_delete",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1207",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503539768,
      "name": "ip6mr_mfc_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1164
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
int ip6mr_mfc_delete(struct mr_table * mrt, struct mf6cctl * mfc, int parent)
```

```json
{
  "name": "ip6mr_mfc_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236198076,
      "name": "ip6mr_mfc_delete",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1207",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236198076,
      "name": "ip6mr_mfc_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1132
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
int ip6mr_mfc_delete(struct mr_table * mrt, struct mf6cctl * mfc, int parent)
```

```json
{
  "name": "ip6mr_mfc_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297343024,
      "name": "ip6mr_mfc_delete",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1207",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297343024,
      "name": "ip6mr_mfc_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1476
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
int ip6mr_mfc_delete(struct mr_table * mrt, struct mf6cctl * mfc, int parent)
```

```json
{
  "name": "ip6mr_mfc_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279509806,
      "name": "ip6mr_mfc_delete",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1207",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279509806,
      "name": "ip6mr_mfc_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1062
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
int ip6mr_mfc_delete(struct mr_table * mrt, struct mf6cctl * mfc, int parent)
```

```json
{
  "name": "ip6mr_mfc_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589440048,
      "name": "ip6mr_mfc_delete",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1207",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589440048,
      "name": "ip6mr_mfc_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 793
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
int ip6mr_mfc_delete(struct mr_table * mrt, struct mf6cctl * mfc, int parent)
```

```json
{
  "name": "ip6mr_mfc_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589165040,
      "name": "ip6mr_mfc_delete",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1207",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589165040,
      "name": "ip6mr_mfc_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 793
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
int ip6mr_mfc_delete(struct mr_table * mrt, struct mf6cctl * mfc, int parent)
```

```json
{
  "name": "ip6mr_mfc_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589876912,
      "name": "ip6mr_mfc_delete",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1207",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589876912,
      "name": "ip6mr_mfc_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 793
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
int ip6mr_mfc_delete(struct mr_table * mrt, struct mf6cctl * mfc, int parent)
```

```json
{
  "name": "ip6mr_mfc_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589928592,
      "name": "ip6mr_mfc_delete",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1207",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589928592,
      "name": "ip6mr_mfc_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 917
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int ip6mr_mfc_delete(struct mr_table * mrt, struct mf6cctl * mfc, int parent)
```
</details>
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
