# Function: <code>rt6_sync_down_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rt6_sync_down_dev(struct net_device * dev, long unsigned int event)
```

```json
{
  "name": "rt6_sync_down_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588776130,
      "name": "rt6_sync_down_dev",
      "external": true,
      "loc": "net/ipv6/route.c:4067",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_disable_ip"
      ],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588775984,
      "name": "rt6_sync_down_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void rt6_sync_down_dev(struct net_device * dev, long unsigned int event)
```

```json
{
  "name": "rt6_sync_down_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588996144,
      "name": "rt6_sync_down_dev",
      "external": true,
      "loc": "net/ipv6/route.c:4046",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/route.c:rt6_disable_ip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588996144,
      "name": "rt6_sync_down_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void rt6_sync_down_dev(struct net_device * dev, long unsigned int event)
```

```json
{
  "name": "rt6_sync_down_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589446288,
      "name": "rt6_sync_down_dev",
      "external": true,
      "loc": "net/ipv6/route.c:4711",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/route.c:rt6_disable_ip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589446288,
      "name": "rt6_sync_down_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void rt6_sync_down_dev(struct net_device * dev, long unsigned int event)
```

```json
{
  "name": "rt6_sync_down_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589670672,
      "name": "rt6_sync_down_dev",
      "external": true,
      "loc": "net/ipv6/route.c:4724",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/route.c:rt6_disable_ip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589670672,
      "name": "rt6_sync_down_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void rt6_sync_down_dev(struct net_device * dev, long unsigned int event)
```

```json
{
  "name": "rt6_sync_down_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590684165,
      "name": "rt6_sync_down_dev",
      "external": true,
      "loc": "net/ipv6/route.c:4765",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_disable_ip"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590684016,
      "name": "rt6_sync_down_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void rt6_sync_down_dev(struct net_device * dev, long unsigned int event)
```

```json
{
  "name": "rt6_sync_down_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590744709,
      "name": "rt6_sync_down_dev",
      "external": true,
      "loc": "net/ipv6/route.c:4749",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_disable_ip"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590744560,
      "name": "rt6_sync_down_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void rt6_sync_down_dev(struct net_device * dev, long unsigned int event)
```

```json
{
  "name": "rt6_sync_down_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590670716,
      "name": "rt6_sync_down_dev",
      "external": true,
      "loc": "net/ipv6/route.c:4764",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_disable_ip"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590670560,
      "name": "rt6_sync_down_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void rt6_sync_down_dev(struct net_device * dev, long unsigned int event)
```

```json
{
  "name": "rt6_sync_down_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rt6_sync_down_dev",
      "external": true,
      "loc": "net/ipv6/route.c:4894",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_disable_ip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592739154,
      "name": "rt6_sync_down_dev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071591486256,
      "name": "rt6_sync_down_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void rt6_sync_down_dev(struct net_device * dev, long unsigned int event)
```

```json
{
  "name": "rt6_sync_down_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rt6_sync_down_dev",
      "external": true,
      "loc": "net/ipv6/route.c:4881",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_disable_ip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594625747,
      "name": "rt6_sync_down_dev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071593169936,
      "name": "rt6_sync_down_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void rt6_sync_down_dev(struct net_device * dev, long unsigned int event)
```

```json
{
  "name": "rt6_sync_down_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rt6_sync_down_dev",
      "external": true,
      "loc": "net/ipv6/route.c:4881",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_disable_ip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596359938,
      "name": "rt6_sync_down_dev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071595068288,
      "name": "rt6_sync_down_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void rt6_sync_down_dev(struct net_device * dev, long unsigned int event)
```

```json
{
  "name": "rt6_sync_down_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595462172,
      "name": "rt6_sync_down_dev",
      "external": true,
      "loc": "net/ipv6/route.c:4879",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_disable_ip"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595462000,
      "name": "rt6_sync_down_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void rt6_sync_down_dev(struct net_device * dev, long unsigned int event)
```

```json
{
  "name": "rt6_sync_down_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596304300,
      "name": "rt6_sync_down_dev",
      "external": true,
      "loc": "net/ipv6/route.c:4879",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_disable_ip"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596304128,
      "name": "rt6_sync_down_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void rt6_sync_down_dev(struct net_device * dev, long unsigned int event)
```

```json
{
  "name": "rt6_sync_down_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503357328,
      "name": "rt6_sync_down_dev",
      "external": true,
      "loc": "net/ipv6/route.c:4724",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/route.c:rt6_disable_ip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503357328,
      "name": "rt6_sync_down_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void rt6_sync_down_dev(struct net_device * dev, long unsigned int event)
```

```json
{
  "name": "rt6_sync_down_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236023184,
      "name": "rt6_sync_down_dev",
      "external": true,
      "loc": "net/ipv6/route.c:4724",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/route.c:rt6_disable_ip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236023184,
      "name": "rt6_sync_down_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void rt6_sync_down_dev(struct net_device * dev, long unsigned int event)
```

```json
{
  "name": "rt6_sync_down_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297124400,
      "name": "rt6_sync_down_dev",
      "external": true,
      "loc": "net/ipv6/route.c:4724",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/route.c:rt6_disable_ip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297124400,
      "name": "rt6_sync_down_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void rt6_sync_down_dev(struct net_device * dev, long unsigned int event)
```

```json
{
  "name": "rt6_sync_down_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279364044,
      "name": "rt6_sync_down_dev",
      "external": true,
      "loc": "net/ipv6/route.c:4724",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/route.c:rt6_disable_ip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279364044,
      "name": "rt6_sync_down_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void rt6_sync_down_dev(struct net_device * dev, long unsigned int event)
```

```json
{
  "name": "rt6_sync_down_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589275040,
      "name": "rt6_sync_down_dev",
      "external": true,
      "loc": "net/ipv6/route.c:4724",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/route.c:rt6_disable_ip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589275040,
      "name": "rt6_sync_down_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void rt6_sync_down_dev(struct net_device * dev, long unsigned int event)
```

```json
{
  "name": "rt6_sync_down_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589000032,
      "name": "rt6_sync_down_dev",
      "external": true,
      "loc": "net/ipv6/route.c:4724",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/route.c:rt6_disable_ip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589000032,
      "name": "rt6_sync_down_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void rt6_sync_down_dev(struct net_device * dev, long unsigned int event)
```

```json
{
  "name": "rt6_sync_down_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589711904,
      "name": "rt6_sync_down_dev",
      "external": true,
      "loc": "net/ipv6/route.c:4724",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/route.c:rt6_disable_ip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589711904,
      "name": "rt6_sync_down_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void rt6_sync_down_dev(struct net_device * dev, long unsigned int event)
```

```json
{
  "name": "rt6_sync_down_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589762048,
      "name": "rt6_sync_down_dev",
      "external": true,
      "loc": "net/ipv6/route.c:4724",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/route.c:rt6_disable_ip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589762048,
      "name": "rt6_sync_down_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void rt6_sync_down_dev(struct net_device * dev, long unsigned int event)
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
