# Function: <code>is_in</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
int is_in(struct ip_mc_list * pmc, struct ip_sf_list * psf, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "is_in",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586795328,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv4/igmp.c:267",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:add_grec"
      ]
    },
    {
      "addr": 18446744071587138400,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv6/mcast.c:1468",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:add_grec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586795328,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    },
    {
      "addr": 18446744071587138400,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
int is_in(struct ip_mc_list * pmc, struct ip_sf_list * psf, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "is_in",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587244320,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv4/igmp.c:261",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:add_grec"
      ]
    },
    {
      "addr": 18446744071587591072,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv6/mcast.c:1468",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:add_grec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587244320,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    },
    {
      "addr": 18446744071587591072,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
int is_in(struct ip_mc_list * pmc, struct ip_sf_list * psf, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "is_in",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587444960,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv4/igmp.c:266",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:add_grec"
      ]
    },
    {
      "addr": 18446744071587795360,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv6/mcast.c:1482",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:add_grec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587444960,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    },
    {
      "addr": 18446744071587795360,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
int is_in(struct ip_mc_list * pmc, struct ip_sf_list * psf, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "is_in",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587581584,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv4/igmp.c:266",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:add_grec"
      ]
    },
    {
      "addr": 18446744071587952688,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv6/mcast.c:1482",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:add_grec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587581584,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071587952688,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
int is_in(struct ip_mc_list * pmc, struct ip_sf_list * psf, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "is_in",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588105536,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv4/igmp.c:267",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:add_grec"
      ]
    },
    {
      "addr": 18446744071588488528,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv6/mcast.c:1482",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:add_grec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588105536,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    },
    {
      "addr": 18446744071588488528,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
int is_in(struct ip_mc_list * pmc, struct ip_sf_list * psf, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "is_in",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588460192,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv4/igmp.c:267",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:add_grec"
      ]
    },
    {
      "addr": 18446744071588851792,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv6/mcast.c:1507",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:add_grec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588460192,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
    },
    {
      "addr": 18446744071588851792,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
int is_in(struct ip_mc_list * pmc, struct ip_sf_list * psf, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "is_in",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588653872,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv4/igmp.c:264",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:add_grec"
      ]
    },
    {
      "addr": 18446744071589075312,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv6/mcast.c:1507",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:add_grec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588653872,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
    },
    {
      "addr": 18446744071589075312,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
int is_in(struct ip_mc_list * pmc, struct ip_sf_list * psf, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "is_in",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589066688,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv4/igmp.c:272",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:add_grec"
      ]
    },
    {
      "addr": 18446744071589529472,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv6/mcast.c:1506",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:add_grec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589066688,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071589529472,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
int is_in(struct ip_mc_list * pmc, struct ip_sf_list * psf, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "is_in",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589290848,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv4/igmp.c:272",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:add_grec"
      ]
    },
    {
      "addr": 18446744071589753552,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv6/mcast.c:1506",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:add_grec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589290848,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071589753552,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
int is_in(struct ip_mc_list * pmc, struct ip_sf_list * psf, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "is_in",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590266944,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv4/igmp.c:270",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:add_grec"
      ]
    },
    {
      "addr": 18446744071590771968,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv6/mcast.c:1503",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:add_grec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590266944,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
    },
    {
      "addr": 18446744071590771968,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
int is_in(struct ip_mc_list * pmc, struct ip_sf_list * psf, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "is_in",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590319856,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv4/igmp.c:270",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:add_grec"
      ]
    },
    {
      "addr": 18446744071590831216,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv6/mcast.c:1503",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:add_grec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590319856,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
    },
    {
      "addr": 18446744071590831216,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
int is_in(struct ip_mc_list * pmc, struct ip_sf_list * psf, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "is_in",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590235872,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv4/igmp.c:270",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:add_grec"
      ]
    },
    {
      "addr": 18446744071590758448,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv6/mcast.c:1647",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:add_grec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590235872,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
    },
    {
      "addr": 18446744071590758448,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
int is_in(struct ip_mc_list * pmc, struct ip_sf_list * psf, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "is_in",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591019216,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv4/igmp.c:270",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:add_grec"
      ]
    },
    {
      "addr": 18446744071591575680,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv6/mcast.c:1642",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:add_grec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591019216,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
    },
    {
      "addr": 18446744071591575680,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
int is_in(struct ip_mc_list * pmc, struct ip_sf_list * psf, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "is_in",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592665696,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv4/igmp.c:270",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:add_grec"
      ]
    },
    {
      "addr": 18446744071593267120,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv6/mcast.c:1644",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:add_grec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592665696,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
    },
    {
      "addr": 18446744071593267120,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
int is_in(struct ip_mc_list * pmc, struct ip_sf_list * psf, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "is_in",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594533328,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv4/igmp.c:270",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:add_grec"
      ]
    },
    {
      "addr": 18446744071595169520,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv6/mcast.c:1644",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:add_grec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594533328,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
    },
    {
      "addr": 18446744071595169520,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
int is_in(struct ip_mc_list * pmc, struct ip_sf_list * psf, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "is_in",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594925104,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv4/igmp.c:270",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:add_grec"
      ]
    },
    {
      "addr": 18446744071595565072,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv6/mcast.c:1644",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:add_grec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594925104,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
    },
    {
      "addr": 18446744071595565072,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
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
int is_in(struct ip_mc_list * pmc, struct ip_sf_list * psf, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "is_in",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595737248,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv4/igmp.c:272",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:add_grec"
      ]
    },
    {
      "addr": 18446744071596407872,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv6/mcast.c:1644",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:add_grec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595737248,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
    },
    {
      "addr": 18446744071596407872,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
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
int is_in(struct ip_mc_list * pmc, struct ip_sf_list * psf, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "is_in",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502922408,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv4/igmp.c:272",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:add_grec"
      ]
    },
    {
      "addr": 18446603336503448320,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv6/mcast.c:1506",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:add_grec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502922408,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
    },
    {
      "addr": 18446603336503448320,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int is_in(struct ip_mc_list * pmc, struct ip_sf_list * psf, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "is_in",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235615180,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv4/igmp.c:272",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:add_grec"
      ]
    },
    {
      "addr": 3236106492,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv6/mcast.c:1506",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:add_grec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235615180,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    },
    {
      "addr": 3236106492,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
int is_in(struct ip_mc_list * pmc, struct ip_sf_list * psf, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "is_in",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296593136,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv4/igmp.c:272",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:add_grec"
      ]
    },
    {
      "addr": 13835058055297232704,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv6/mcast.c:1506",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:add_grec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296593136,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
    },
    {
      "addr": 13835058055297232704,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
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
int is_in(struct ip_mc_list * pmc, struct ip_sf_list * psf, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "is_in",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279014148,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv4/igmp.c:272",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:add_grec"
      ]
    },
    {
      "addr": 18446743936279434166,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv6/mcast.c:1506",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:add_grec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279014148,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
    },
    {
      "addr": 18446743936279434166,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
int is_in(struct ip_mc_list * pmc, struct ip_sf_list * psf, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "is_in",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588897024,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv4/igmp.c:272",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:add_grec"
      ]
    },
    {
      "addr": 18446744071589357920,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv6/mcast.c:1506",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:add_grec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588897024,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071589357920,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
int is_in(struct ip_mc_list * pmc, struct ip_sf_list * psf, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "is_in",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588608960,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv4/igmp.c:272",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:add_grec"
      ]
    },
    {
      "addr": 18446744071589082912,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv6/mcast.c:1506",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:add_grec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588608960,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071589082912,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
int is_in(struct ip_mc_list * pmc, struct ip_sf_list * psf, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "is_in",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589333408,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv4/igmp.c:272",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:add_grec"
      ]
    },
    {
      "addr": 18446744071589794784,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv6/mcast.c:1506",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:add_grec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589333408,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071589794784,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
int is_in(struct ip_mc_list * pmc, struct ip_sf_list * psf, int type, int gdeleted, int sdeleted)
```

```json
{
  "name": "is_in",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589375616,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv4/igmp.c:272",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:add_grec",
        "net/ipv4/igmp.c:add_grec"
      ]
    },
    {
      "addr": 18446744071589845488,
      "name": "is_in",
      "external": false,
      "loc": "net/ipv6/mcast.c:1506",
      "file": "net/ipv6/mcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:add_grec",
        "net/ipv6/mcast.c:add_grec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589375616,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071589845488,
      "name": "is_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
