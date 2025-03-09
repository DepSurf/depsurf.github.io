# Function: <code>ip6mr_mfc_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6mr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587212008,
      "name": "ip6mr_mfc_add",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1449",
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
  "name": "ip6mr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587668804,
      "name": "ip6mr_mfc_add",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1451",
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
  "name": "ip6mr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587877268,
      "name": "ip6mr_mfc_add",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1451",
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
  "name": "ip6mr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588034227,
      "name": "ip6mr_mfc_add",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1454",
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
  "name": "ip6mr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588571475,
      "name": "ip6mr_mfc_add",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1454",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int ip6mr_mfc_add(struct net * net, struct mr_table * mrt, struct mf6cctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ip6mr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588933376,
      "name": "ip6mr_mfc_add",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1388",
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
      "addr": 18446744071588933376,
      "name": "ip6mr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2201
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
int ip6mr_mfc_add(struct net * net, struct mr_table * mrt, struct mf6cctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ip6mr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589157408,
      "name": "ip6mr_mfc_add",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1406",
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
      "addr": 18446744071589157408,
      "name": "ip6mr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2215
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
int ip6mr_mfc_add(struct net * net, struct mr_table * mrt, struct mf6cctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ip6mr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589612240,
      "name": "ip6mr_mfc_add",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1401",
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
      "addr": 18446744071589612240,
      "name": "ip6mr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2301
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
int ip6mr_mfc_add(struct net * net, struct mr_table * mrt, struct mf6cctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ip6mr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589836480,
      "name": "ip6mr_mfc_add",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1401",
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
      "addr": 18446744071589836480,
      "name": "ip6mr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2301
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
int ip6mr_mfc_add(struct net * net, struct mr_table * mrt, struct mf6cctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ip6mr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6mr_mfc_add",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1406",
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
      "addr": 18446744071590864336,
      "name": "ip6mr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1005
    },
    {
      "addr": 18446744071590870591,
      "name": "ip6mr_mfc_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
int ip6mr_mfc_add(struct net * net, struct mr_table * mrt, struct mf6cctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ip6mr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6mr_mfc_add",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1406",
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
      "addr": 18446744071590925200,
      "name": "ip6mr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1010
    },
    {
      "addr": 18446744071591636952,
      "name": "ip6mr_mfc_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
int ip6mr_mfc_add(struct net * net, struct mr_table * mrt, struct mf6cctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ip6mr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6mr_mfc_add",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1406",
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
      "addr": 18446744071590854400,
      "name": "ip6mr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1330
    },
    {
      "addr": 18446744071591580379,
      "name": "ip6mr_mfc_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
int ip6mr_mfc_add(struct net * net, struct mr_table * mrt, struct mf6cctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ip6mr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6mr_mfc_add",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1407",
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
      "addr": 18446744071591684000,
      "name": "ip6mr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1402
    },
    {
      "addr": 18446744071592743831,
      "name": "ip6mr_mfc_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
int ip6mr_mfc_add(struct net * net, struct mr_table * mrt, struct mf6cctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ip6mr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6mr_mfc_add",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1416",
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
      "addr": 18446744071593381664,
      "name": "ip6mr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1547
    },
    {
      "addr": 18446744071594630388,
      "name": "ip6mr_mfc_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
int ip6mr_mfc_add(struct net * net, struct mr_table * mrt, struct mf6cctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ip6mr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6mr_mfc_add",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1425",
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
      "addr": 18446744071595287472,
      "name": "ip6mr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1554
    },
    {
      "addr": 18446744071596363938,
      "name": "ip6mr_mfc_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
int ip6mr_mfc_add(struct net * net, struct mr_table * mrt, struct mf6cctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ip6mr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6mr_mfc_add",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1425",
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
      "addr": 18446744071595685936,
      "name": "ip6mr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1554
    },
    {
      "addr": 18446744071596892116,
      "name": "ip6mr_mfc_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
int ip6mr_mfc_add(struct net * net, struct mr_table * mrt, struct mf6cctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ip6mr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6mr_mfc_add",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1425",
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
      "addr": 18446744071596533696,
      "name": "ip6mr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1554
    },
    {
      "addr": 18446744071597816841,
      "name": "ip6mr_mfc_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
int ip6mr_mfc_add(struct net * net, struct mr_table * mrt, struct mf6cctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ip6mr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503546456,
      "name": "ip6mr_mfc_add",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1401",
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
      "addr": 18446603336503546456,
      "name": "ip6mr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2280
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
int ip6mr_mfc_add(struct net * net, struct mr_table * mrt, struct mf6cctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ip6mr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236199964,
      "name": "ip6mr_mfc_add",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1401",
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
      "addr": 3236199964,
      "name": "ip6mr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2432
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
int ip6mr_mfc_add(struct net * net, struct mr_table * mrt, struct mf6cctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ip6mr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297346864,
      "name": "ip6mr_mfc_add",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1401",
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
      "addr": 13835058055297346864,
      "name": "ip6mr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2596
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
int ip6mr_mfc_add(struct net * net, struct mr_table * mrt, struct mf6cctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ip6mr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279512412,
      "name": "ip6mr_mfc_add",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1401",
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
      "addr": 18446743936279512412,
      "name": "ip6mr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2082
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
int ip6mr_mfc_add(struct net * net, struct mr_table * mrt, struct mf6cctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ip6mr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589440848,
      "name": "ip6mr_mfc_add",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1401",
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
      "addr": 18446744071589440848,
      "name": "ip6mr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2301
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
int ip6mr_mfc_add(struct net * net, struct mr_table * mrt, struct mf6cctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ip6mr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589165840,
      "name": "ip6mr_mfc_add",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1401",
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
      "addr": 18446744071589165840,
      "name": "ip6mr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2301
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
int ip6mr_mfc_add(struct net * net, struct mr_table * mrt, struct mf6cctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ip6mr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589877712,
      "name": "ip6mr_mfc_add",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1401",
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
      "addr": 18446744071589877712,
      "name": "ip6mr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2301
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
int ip6mr_mfc_add(struct net * net, struct mr_table * mrt, struct mf6cctl * mfc, int mrtsock, int parent)
```

```json
{
  "name": "ip6mr_mfc_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589929520,
      "name": "ip6mr_mfc_add",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1401",
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
      "addr": 18446744071589929520,
      "name": "ip6mr_mfc_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2642
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
int ip6mr_mfc_add(struct net * net, struct mr_table * mrt, struct mf6cctl * mfc, int mrtsock, int parent)
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
