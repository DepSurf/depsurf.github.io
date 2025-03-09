# Function: <code>mroute_clean_tables</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
void mroute_clean_tables(struct mr_table * mrt, bool all)
```

```json
{
  "name": "mroute_clean_tables",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586875744,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1203",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:ipmr_net_exit"
      ]
    },
    {
      "addr": 18446744071587206864,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1541",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6mr_rules_exit",
        "net/ipv6/ip6mr.c:ip6mr_sk_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586875744,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
    },
    {
      "addr": 18446744071587206864,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 470
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
void mroute_clean_tables(struct mr_table * mrt, bool all)
```

```json
{
  "name": "mroute_clean_tables",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587324208,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1187",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:mrtsock_destruct"
      ]
    },
    {
      "addr": 18446744071587663632,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1543",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:ip6mr_rules_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587324208,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
    },
    {
      "addr": 18446744071587663632,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
void mroute_clean_tables(struct mr_table * mrt, bool all)
```

```json
{
  "name": "mroute_clean_tables",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587526880,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1192",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/ipv4/ipmr.c:mrtsock_destruct"
      ]
    },
    {
      "addr": 18446744071587872096,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1543",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:ip6mr_rules_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587526880,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
    },
    {
      "addr": 18446744071587872096,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision ❓</summary>

```c
void mroute_clean_tables(struct mr_table * mrt, bool all)
```

```json
{
  "name": "mroute_clean_tables",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587672432,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1246",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:ipmr_free_table"
      ]
    },
    {
      "addr": 18446744071588028704,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1546",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:ip6mr_rules_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587672432,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 855
    },
    {
      "addr": 18446744071588028704,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision ❓</summary>

```c
void mroute_clean_tables(struct mr_table * mrt, bool all)
```

```json
{
  "name": "mroute_clean_tables",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588198672,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1377",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:ipmr_free_table"
      ]
    },
    {
      "addr": 18446744071588567648,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1546",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:ip6mr_rules_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588198672,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 918
    },
    {
      "addr": 18446744071588567648,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision ❓</summary>

```c
void mroute_clean_tables(struct mr_table * mrt, bool all)
```

```json
{
  "name": "mroute_clean_tables",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588552912,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1296",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:ipmr_free_table"
      ]
    },
    {
      "addr": 18446744071588931616,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1481",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:ip6mr_free_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588552912,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1025
    },
    {
      "addr": 18446744071588931616,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1024
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision ❓</summary>

```c
void mroute_clean_tables(struct mr_table * mrt, bool all)
```

```json
{
  "name": "mroute_clean_tables",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588749008,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1302",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:ipmr_free_table"
      ]
    },
    {
      "addr": 18446744071589155280,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1499",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:ip6mr_free_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588749008,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1022
    },
    {
      "addr": 18446744071589155280,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1008
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision ❓</summary>

```c
void mroute_clean_tables(struct mr_table * mrt, int flags)
```

```json
{
  "name": "mroute_clean_tables",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589181392,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1294",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:ipmr_free_table"
      ]
    },
    {
      "addr": 18446744071589609456,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1494",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:ip6mr_free_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589181392,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1272
    },
    {
      "addr": 18446744071589609456,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1252
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision ❓</summary>

```c
void mroute_clean_tables(struct mr_table * mrt, int flags)
```

```json
{
  "name": "mroute_clean_tables",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589406464,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1294",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:ipmr_free_table"
      ]
    },
    {
      "addr": 18446744071589833696,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1494",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:ip6mr_free_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589406464,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1272
    },
    {
      "addr": 18446744071589833696,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1252
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision ❓</summary>

```c
void mroute_clean_tables(struct mr_table * mrt, int flags)
```

```json
{
  "name": "mroute_clean_tables",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590395168,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1262",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:ipmr_rules_exit"
      ]
    },
    {
      "addr": 18446744071590859776,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1499",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:ip6mr_rules_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590395168,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 870
    },
    {
      "addr": 18446744071590859776,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 886
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision ❓</summary>

```c
void mroute_clean_tables(struct mr_table * mrt, int flags)
```

```json
{
  "name": "mroute_clean_tables",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590452880,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1269",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:ipmr_rules_exit"
      ]
    },
    {
      "addr": 18446744071590920560,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1499",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:ip6mr_rules_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590452880,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 875
    },
    {
      "addr": 18446744071590920560,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 891
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision ❓</summary>

```c
void mroute_clean_tables(struct mr_table * mrt, int flags)
```

```json
{
  "name": "mroute_clean_tables",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590376896,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1269",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:ipmr_rules_exit"
      ]
    },
    {
      "addr": 18446744071590850032,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1499",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:ip6mr_rules_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590376896,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 906
    },
    {
      "addr": 18446744071590850032,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 918
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void mroute_clean_tables(struct mr_table * mrt, int flags)
```

```json
{
  "name": "mroute_clean_tables",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1271",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:ipmr_rules_exit"
      ]
    },
    {
      "addr": 0,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1500",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:ip6mr_rules_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591170912,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1001
    },
    {
      "addr": 18446744071592733366,
      "name": "mroute_clean_tables.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071591678784,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1020
    },
    {
      "addr": 18446744071592743712,
      "name": "mroute_clean_tables.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void mroute_clean_tables(struct mr_table * mrt, int flags)
```

```json
{
  "name": "mroute_clean_tables",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1265",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:ipmr_rules_exit"
      ]
    },
    {
      "addr": 0,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1509",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:ip6mr_rules_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592831200,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 948
    },
    {
      "addr": 18446744071594619917,
      "name": "mroute_clean_tables.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593377040,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 940
    },
    {
      "addr": 18446744071594630252,
      "name": "mroute_clean_tables.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void mroute_clean_tables(struct mr_table * mrt, int flags)
```

```json
{
  "name": "mroute_clean_tables",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1279",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:ipmr_rules_exit"
      ]
    },
    {
      "addr": 0,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1518",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:ip6mr_rules_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594709424,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 948
    },
    {
      "addr": 18446744071596354788,
      "name": "mroute_clean_tables.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071595290400,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 940
    },
    {
      "addr": 18446744071596364019,
      "name": "mroute_clean_tables.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void mroute_clean_tables(struct mr_table * mrt, int flags)
```

```json
{
  "name": "mroute_clean_tables",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1279",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:ipmr_rules_exit"
      ]
    },
    {
      "addr": 0,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1518",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:ip6mr_rules_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595099216,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 943
    },
    {
      "addr": 18446744071596883572,
      "name": "mroute_clean_tables.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071595683056,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 937
    },
    {
      "addr": 18446744071596892067,
      "name": "mroute_clean_tables.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void mroute_clean_tables(struct mr_table * mrt, int flags)
```

```json
{
  "name": "mroute_clean_tables",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1278",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:ipmr_rules_exit"
      ]
    },
    {
      "addr": 0,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1518",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:ip6mr_rules_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595911888,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 943
    },
    {
      "addr": 18446744071597807744,
      "name": "mroute_clean_tables.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071596530816,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 937
    },
    {
      "addr": 18446744071597816792,
      "name": "mroute_clean_tables.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
void mroute_clean_tables(struct mr_table * mrt, int flags)
```

```json
{
  "name": "mroute_clean_tables",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503049680,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1294",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:ipmr_free_table"
      ]
    },
    {
      "addr": 18446603336503544184,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1494",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:ip6mr_free_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503049680,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1444
    },
    {
      "addr": 18446603336503544184,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1584
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
void mroute_clean_tables(struct mr_table * mrt, int flags)
```

```json
{
  "name": "mroute_clean_tables",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235740520,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1294",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:ipmr_free_table"
      ]
    },
    {
      "addr": 3236195888,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1494",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:ip6mr_free_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235740520,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1548
    },
    {
      "addr": 3236195888,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1528
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision ❓</summary>

```c
void mroute_clean_tables(struct mr_table * mrt, int flags)
```

```json
{
  "name": "mroute_clean_tables",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296757936,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1294",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:ipmr_free_table"
      ]
    },
    {
      "addr": 13835058055297339968,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1494",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:ip6mr_free_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296757936,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1876
    },
    {
      "addr": 13835058055297339968,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2036
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision ❓</summary>

```c
void mroute_clean_tables(struct mr_table * mrt, int flags)
```

```json
{
  "name": "mroute_clean_tables",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279119648,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1294",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:ipmr_free_table"
      ]
    },
    {
      "addr": 18446743936279507686,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1494",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:ip6mr_free_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279119648,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1246
    },
    {
      "addr": 18446743936279507686,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1440
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision ❓</summary>

```c
void mroute_clean_tables(struct mr_table * mrt, int flags)
```

```json
{
  "name": "mroute_clean_tables",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589011392,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1294",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:ipmr_free_table"
      ]
    },
    {
      "addr": 18446744071589438064,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1494",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:ip6mr_free_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589011392,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1272
    },
    {
      "addr": 18446744071589438064,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1252
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision ❓</summary>

```c
void mroute_clean_tables(struct mr_table * mrt, int flags)
```

```json
{
  "name": "mroute_clean_tables",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588734448,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1294",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:ipmr_free_table"
      ]
    },
    {
      "addr": 18446744071589163056,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1494",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:ip6mr_free_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588734448,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1272
    },
    {
      "addr": 18446744071589163056,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1252
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision ❓</summary>

```c
void mroute_clean_tables(struct mr_table * mrt, int flags)
```

```json
{
  "name": "mroute_clean_tables",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589447776,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1294",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:ipmr_free_table"
      ]
    },
    {
      "addr": 18446744071589874928,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1494",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:ip6mr_free_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589447776,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1272
    },
    {
      "addr": 18446744071589874928,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1252
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision ❓</summary>

```c
void mroute_clean_tables(struct mr_table * mrt, int flags)
```

```json
{
  "name": "mroute_clean_tables",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589492768,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv4/ipmr.c:1294",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:mrtsock_destruct",
        "net/ipv4/ipmr.c:ipmr_free_table"
      ]
    },
    {
      "addr": 18446744071589926512,
      "name": "mroute_clean_tables",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:1494",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:ip6mr_free_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589492768,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1371
    },
    {
      "addr": 18446744071589926512,
      "name": "mroute_clean_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1357
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool all</code>
</li>
</ul>
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
