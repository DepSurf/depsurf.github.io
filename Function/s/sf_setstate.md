# Function: <code>sf_setstate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
int sf_setstate(struct ip_mc_list * pmc)
```

```json
{
  "name": "sf_setstate",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586796816,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv4/igmp.c:1892",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_del_src",
        "net/ipv4/igmp.c:ip_mc_add_src"
      ]
    },
    {
      "addr": 18446744071587139024,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv6/mcast.c:2214",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:ip6_mc_add_src"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586796816,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
    },
    {
      "addr": 18446744071587139024,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
int sf_setstate(struct ip_mc_list * pmc)
```

```json
{
  "name": "sf_setstate",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587245808,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv4/igmp.c:1902",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_add_src",
        "net/ipv4/igmp.c:ip_mc_del_src"
      ]
    },
    {
      "addr": 18446744071587591696,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv6/mcast.c:2213",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_del_src"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587245808,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
    },
    {
      "addr": 18446744071587591696,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
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
int sf_setstate(struct ip_mc_list * pmc)
```

```json
{
  "name": "sf_setstate",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587446416,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv4/igmp.c:1940",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_add_src",
        "net/ipv4/igmp.c:ip_mc_del_src"
      ]
    },
    {
      "addr": 18446744071587795984,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv6/mcast.c:2237",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_del_src"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587446416,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
    },
    {
      "addr": 18446744071587795984,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
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
int sf_setstate(struct ip_mc_list * pmc)
```

```json
{
  "name": "sf_setstate",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587583040,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv4/igmp.c:1949",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_add_src",
        "net/ipv4/igmp.c:ip_mc_del_src"
      ]
    },
    {
      "addr": 18446744071587953312,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv6/mcast.c:2236",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_del_src"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587583040,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
    },
    {
      "addr": 18446744071587953312,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 449
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
int sf_setstate(struct ip_mc_list * pmc)
```

```json
{
  "name": "sf_setstate",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588106976,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv4/igmp.c:1975",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_add_src",
        "net/ipv4/igmp.c:ip_mc_del_src"
      ]
    },
    {
      "addr": 18446744071588489152,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv6/mcast.c:2241",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_del_src"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588106976,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
    },
    {
      "addr": 18446744071588489152,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 449
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
int sf_setstate(struct ip_mc_list * pmc)
```

```json
{
  "name": "sf_setstate",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588461632,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv4/igmp.c:1986",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_add_src",
        "net/ipv4/igmp.c:ip_mc_del_src"
      ]
    },
    {
      "addr": 18446744071588852176,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv6/mcast.c:2266",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_del_src"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588461632,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
    },
    {
      "addr": 18446744071588852176,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 442
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
int sf_setstate(struct ip_mc_list * pmc)
```

```json
{
  "name": "sf_setstate",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588655312,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv4/igmp.c:2002",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_add_src",
        "net/ipv4/igmp.c:ip_mc_del_src"
      ]
    },
    {
      "addr": 18446744071589075696,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv6/mcast.c:2266",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_del_src"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588655312,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
    },
    {
      "addr": 18446744071589075696,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 442
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
int sf_setstate(struct ip_mc_list * pmc)
```

```json
{
  "name": "sf_setstate",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589068240,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv4/igmp.c:2004",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_add_src",
        "net/ipv4/igmp.c:ip_mc_del_src"
      ]
    },
    {
      "addr": 18446744071589529856,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv6/mcast.c:2265",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_del_src"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589068240,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
    },
    {
      "addr": 18446744071589529856,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
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
int sf_setstate(struct ip_mc_list * pmc)
```

```json
{
  "name": "sf_setstate",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589292400,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv4/igmp.c:2004",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_add_src",
        "net/ipv4/igmp.c:ip_mc_del_src"
      ]
    },
    {
      "addr": 18446744071589753936,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv6/mcast.c:2265",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_del_src"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589292400,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
    },
    {
      "addr": 18446744071589753936,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
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
int sf_setstate(struct ip_mc_list * pmc)
```

```json
{
  "name": "sf_setstate",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590268016,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv4/igmp.c:2002",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_add_src"
      ]
    },
    {
      "addr": 18446744071590772448,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv6/mcast.c:2262",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ip6_mc_add_src"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590268016,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
    },
    {
      "addr": 18446744071590772448,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
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
int sf_setstate(struct ip_mc_list * pmc)
```

```json
{
  "name": "sf_setstate",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590320960,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv4/igmp.c:2002",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_add_src"
      ]
    },
    {
      "addr": 18446744071590831696,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv6/mcast.c:2262",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ip6_mc_add_src"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590320960,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
    },
    {
      "addr": 18446744071590831696,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
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
int sf_setstate(struct ip_mc_list * pmc)
```

```json
{
  "name": "sf_setstate",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590236976,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv4/igmp.c:2010",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_add_src"
      ]
    },
    {
      "addr": 18446744071590758992,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv6/mcast.c:2418",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ip6_mc_add_src"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590236976,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
    },
    {
      "addr": 18446744071590758992,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 446
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision ❓</summary>

```c
int sf_setstate(struct ip_mc_list * pmc)
```

```json
{
  "name": "sf_setstate",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591020448,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv4/igmp.c:2010",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_add_src"
      ]
    },
    {
      "addr": 18446744071591576224,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv6/mcast.c:2416",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ip6_mc_add_src"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591020448,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
    },
    {
      "addr": 18446744071591576224,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 446
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision ❓</summary>

```c
int sf_setstate(struct ip_mc_list * pmc)
```

```json
{
  "name": "sf_setstate",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592667088,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv4/igmp.c:2017",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_add_src"
      ]
    },
    {
      "addr": 18446744071593268192,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv6/mcast.c:2418",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ip6_mc_add_src"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592667088,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 383
    },
    {
      "addr": 18446744071593268192,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision ❓</summary>

```c
int sf_setstate(struct ip_mc_list * pmc)
```

```json
{
  "name": "sf_setstate",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594534832,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv4/igmp.c:2017",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_add_src"
      ]
    },
    {
      "addr": 18446744071595170688,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv6/mcast.c:2418",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ip6_mc_add_src"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594534832,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 383
    },
    {
      "addr": 18446744071595170688,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision ❓</summary>

```c
int sf_setstate(struct ip_mc_list * pmc)
```

```json
{
  "name": "sf_setstate",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594926624,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv4/igmp.c:2018",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_add_src"
      ]
    },
    {
      "addr": 18446744071595566240,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv6/mcast.c:2418",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ip6_mc_add_src"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594926624,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 383
    },
    {
      "addr": 18446744071595566240,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision ❓</summary>

```c
int sf_setstate(struct ip_mc_list * pmc)
```

```json
{
  "name": "sf_setstate",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595738768,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv4/igmp.c:2020",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_add_src"
      ]
    },
    {
      "addr": 18446744071596409040,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv6/mcast.c:2415",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ip6_mc_add_src"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595738768,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
    },
    {
      "addr": 18446744071596409040,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 515
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
int sf_setstate(struct ip_mc_list * pmc)
```

```json
{
  "name": "sf_setstate",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502924392,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv4/igmp.c:2004",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_add_src",
        "net/ipv4/igmp.c:ip_mc_del_src"
      ]
    },
    {
      "addr": 18446603336503448696,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv6/mcast.c:2265",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_del_src"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502924392,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
    },
    {
      "addr": 18446603336503448696,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
int sf_setstate(struct ip_mc_list * pmc)
```

```json
{
  "name": "sf_setstate",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235618148,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv4/igmp.c:2004",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_add_src",
        "net/ipv4/igmp.c:ip_mc_del_src"
      ]
    },
    {
      "addr": 3236107996,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv6/mcast.c:2265",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_del_src"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235618148,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
    },
    {
      "addr": 3236107996,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
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
int sf_setstate(struct ip_mc_list * pmc)
```

```json
{
  "name": "sf_setstate",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296596304,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv4/igmp.c:2004",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_add_src",
        "net/ipv4/igmp.c:ip_mc_del_src"
      ]
    },
    {
      "addr": 13835058055297234208,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv6/mcast.c:2265",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_del_src"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296596304,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
    },
    {
      "addr": 13835058055297234208,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
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
int sf_setstate(struct ip_mc_list * pmc)
```

```json
{
  "name": "sf_setstate",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279016606,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv4/igmp.c:2004",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_add_src",
        "net/ipv4/igmp.c:ip_mc_del_src"
      ]
    },
    {
      "addr": 18446743936279435042,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv6/mcast.c:2265",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_del_src"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279016606,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
    },
    {
      "addr": 18446743936279435042,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
int sf_setstate(struct ip_mc_list * pmc)
```

```json
{
  "name": "sf_setstate",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588898576,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv4/igmp.c:2004",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_add_src",
        "net/ipv4/igmp.c:ip_mc_del_src"
      ]
    },
    {
      "addr": 18446744071589358304,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv6/mcast.c:2265",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_del_src"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588898576,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
    },
    {
      "addr": 18446744071589358304,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
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
int sf_setstate(struct ip_mc_list * pmc)
```

```json
{
  "name": "sf_setstate",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588610512,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv4/igmp.c:2004",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_add_src",
        "net/ipv4/igmp.c:ip_mc_del_src"
      ]
    },
    {
      "addr": 18446744071589083296,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv6/mcast.c:2265",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_del_src"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588610512,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
    },
    {
      "addr": 18446744071589083296,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
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
int sf_setstate(struct ip_mc_list * pmc)
```

```json
{
  "name": "sf_setstate",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589334960,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv4/igmp.c:2004",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_add_src",
        "net/ipv4/igmp.c:ip_mc_del_src"
      ]
    },
    {
      "addr": 18446744071589795168,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv6/mcast.c:2265",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_del_src"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589334960,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
    },
    {
      "addr": 18446744071589795168,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
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
int sf_setstate(struct ip_mc_list * pmc)
```

```json
{
  "name": "sf_setstate",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589377184,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv4/igmp.c:2004",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:ip_mc_add_src",
        "net/ipv4/igmp.c:ip_mc_del_src"
      ]
    },
    {
      "addr": 18446744071589845888,
      "name": "sf_setstate",
      "external": false,
      "loc": "net/ipv6/mcast.c:2265",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_del_src"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589377184,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
    },
    {
      "addr": 18446744071589845888,
      "name": "sf_setstate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
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
