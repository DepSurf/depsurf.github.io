# Function: <code>ipmr_expire_process</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
void ipmr_expire_process(long unsigned int arg)
```

```json
{
  "name": "ipmr_expire_process",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586876816,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv4/ipmr.c:651",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587208128,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:888",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586876816,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
    },
    {
      "addr": 18446744071587208128,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
void ipmr_expire_process(long unsigned int arg)
```

```json
{
  "name": "ipmr_expire_process",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587325328,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv4/ipmr.c:667",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587664960,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:888",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587325328,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
    },
    {
      "addr": 18446744071587664960,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void ipmr_expire_process(long unsigned int arg)
```

```json
{
  "name": "ipmr_expire_process",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587528000,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv4/ipmr.c:672",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587873424,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:888",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587528000,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
    },
    {
      "addr": 18446744071587873424,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void ipmr_expire_process(long unsigned int arg)
```

```json
{
  "name": "ipmr_expire_process",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587669552,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv4/ipmr.c:692",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588030032,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:891",
      "file": "net/ipv6/ip6mr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587669552,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
    },
    {
      "addr": 18446744071588030032,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void ipmr_expire_process(struct timer_list * t)
```

```json
{
  "name": "ipmr_expire_process",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588195760,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv4/ipmr.c:806",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588568976,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:891",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588195760,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    },
    {
      "addr": 18446744071588568976,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void ipmr_expire_process(struct timer_list * t)
```

```json
{
  "name": "ipmr_expire_process",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588549984,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv4/ipmr.c:773",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588926496,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:807",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588549984,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
    },
    {
      "addr": 18446744071588926496,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void ipmr_expire_process(struct timer_list * t)
```

```json
{
  "name": "ipmr_expire_process",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588747728,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv4/ipmr.c:776",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589150592,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:821",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588747728,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
    },
    {
      "addr": 18446744071589150592,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void ipmr_expire_process(struct timer_list * t)
```

```json
{
  "name": "ipmr_expire_process",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589179728,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv4/ipmr.c:770",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589604912,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:816",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589179728,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    },
    {
      "addr": 18446744071589604912,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
void ipmr_expire_process(struct timer_list * t)
```

```json
{
  "name": "ipmr_expire_process",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589404720,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv4/ipmr.c:770",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589829008,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:816",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589404720,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    },
    {
      "addr": 18446744071589829008,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void ipmr_expire_process(struct timer_list * t)
```

```json
{
  "name": "ipmr_expire_process",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590397056,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv4/ipmr.c:744",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590855680,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:820",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590397056,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    },
    {
      "addr": 18446744071590855680,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void ipmr_expire_process(struct timer_list * t)
```

```json
{
  "name": "ipmr_expire_process",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590454768,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv4/ipmr.c:747",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590916464,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:820",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590454768,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    },
    {
      "addr": 18446744071590916464,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void ipmr_expire_process(struct timer_list * t)
```

```json
{
  "name": "ipmr_expire_process",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590378768,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv4/ipmr.c:747",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590845936,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:820",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590378768,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    },
    {
      "addr": 18446744071590845936,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void ipmr_expire_process(struct timer_list * t)
```

```json
{
  "name": "ipmr_expire_process",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591169600,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv4/ipmr.c:749",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591674528,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:821",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591169600,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    },
    {
      "addr": 18446744071591674528,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void ipmr_expire_process(struct timer_list * t)
```

```json
{
  "name": "ipmr_expire_process",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592826816,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv4/ipmr.c:742",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593371216,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:814",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592826816,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
    },
    {
      "addr": 18446744071593371216,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void ipmr_expire_process(struct timer_list * t)
```

```json
{
  "name": "ipmr_expire_process",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594703632,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv4/ipmr.c:749",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595279200,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:822",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594703632,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
    },
    {
      "addr": 18446744071595279200,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void ipmr_expire_process(struct timer_list * t)
```

```json
{
  "name": "ipmr_expire_process",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595095568,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv4/ipmr.c:749",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595674368,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:822",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595095568,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
    },
    {
      "addr": 18446744071595674368,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void ipmr_expire_process(struct timer_list * t)
```

```json
{
  "name": "ipmr_expire_process",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595908240,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv4/ipmr.c:749",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596522192,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:822",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595908240,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
    },
    {
      "addr": 18446744071596522192,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline ❓</summary>

```c
void ipmr_expire_process(struct timer_list * t)
```

```json
{
  "name": "ipmr_expire_process",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503045728,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv4/ipmr.c:770",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503538000,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:816",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503045728,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
    },
    {
      "addr": 18446603336503538000,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void ipmr_expire_process(struct timer_list * t)
```

```json
{
  "name": "ipmr_expire_process",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235735108,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv4/ipmr.c:770",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3236190576,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:816",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235735108,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
    },
    {
      "addr": 3236190576,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void ipmr_expire_process(struct timer_list * t)
```

```json
{
  "name": "ipmr_expire_process",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296761072,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv4/ipmr.c:770",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297335600,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:816",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296761072,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
    },
    {
      "addr": 13835058055297335600,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
void ipmr_expire_process(struct timer_list * t)
```

```json
{
  "name": "ipmr_expire_process",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279121684,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv4/ipmr.c:770",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279504924,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:816",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279121684,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
    },
    {
      "addr": 18446743936279504924,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
void ipmr_expire_process(struct timer_list * t)
```

```json
{
  "name": "ipmr_expire_process",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589009744,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv4/ipmr.c:770",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589433376,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:816",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589009744,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    },
    {
      "addr": 18446744071589433376,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
void ipmr_expire_process(struct timer_list * t)
```

```json
{
  "name": "ipmr_expire_process",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588732800,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv4/ipmr.c:770",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589158368,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:816",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588732800,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    },
    {
      "addr": 18446744071589158368,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
void ipmr_expire_process(struct timer_list * t)
```

```json
{
  "name": "ipmr_expire_process",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589446128,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv4/ipmr.c:770",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589870240,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:816",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589446128,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    },
    {
      "addr": 18446744071589870240,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
void ipmr_expire_process(struct timer_list * t)
```

```json
{
  "name": "ipmr_expire_process",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589491008,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv4/ipmr.c:770",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589921408,
      "name": "ipmr_expire_process",
      "external": false,
      "loc": "net/ipv6/ip6mr.c:816",
      "file": "net/ipv6/ip6mr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589491008,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
    },
    {
      "addr": 18446744071589921408,
      "name": "ipmr_expire_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct timer_list * t</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int arg</code>
</li>
</ul>
</details>
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
