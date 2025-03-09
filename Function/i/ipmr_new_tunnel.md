# Function: <code>ipmr_new_tunnel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ipmr_new_tunnel",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586873202,
      "name": "ipmr_new_tunnel",
      "external": false,
      "loc": "net/ipv4/ipmr.c:391",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:vif_add"
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
  "name": "ipmr_new_tunnel",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587825506,
      "name": "ipmr_new_tunnel",
      "external": false,
      "loc": "net/ipv4/ipmr.c:389",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:vif_add"
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
  "name": "ipmr_new_tunnel",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588040060,
      "name": "ipmr_new_tunnel",
      "external": false,
      "loc": "net/ipv4/ipmr.c:394",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:vif_add"
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
  "name": "ipmr_new_tunnel",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587664135,
      "name": "ipmr_new_tunnel",
      "external": false,
      "loc": "net/ipv4/ipmr.c:413",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:vif_add"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct net_device * ipmr_new_tunnel(struct net * net, struct vifctl * v)
```

```json
{
  "name": "ipmr_new_tunnel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588188960,
      "name": "ipmr_new_tunnel",
      "external": false,
      "loc": "net/ipv4/ipmr.c:445",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588188960,
      "name": "ipmr_new_tunnel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
struct net_device * ipmr_new_tunnel(struct net * net, struct vifctl * v)
```

```json
{
  "name": "ipmr_new_tunnel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588540256,
      "name": "ipmr_new_tunnel",
      "external": false,
      "loc": "net/ipv4/ipmr.c:471",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588540256,
      "name": "ipmr_new_tunnel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
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
struct net_device * ipmr_new_tunnel(struct net * net, struct vifctl * v)
```

```json
{
  "name": "ipmr_new_tunnel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588738736,
      "name": "ipmr_new_tunnel",
      "external": false,
      "loc": "net/ipv4/ipmr.c:474",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588738736,
      "name": "ipmr_new_tunnel",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct net_device * ipmr_new_tunnel(struct net * net, struct vifctl * v)
```

```json
{
  "name": "ipmr_new_tunnel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589170976,
      "name": "ipmr_new_tunnel",
      "external": false,
      "loc": "net/ipv4/ipmr.c:468",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589170976,
      "name": "ipmr_new_tunnel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
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
struct net_device * ipmr_new_tunnel(struct net * net, struct vifctl * v)
```

```json
{
  "name": "ipmr_new_tunnel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589395600,
      "name": "ipmr_new_tunnel",
      "external": false,
      "loc": "net/ipv4/ipmr.c:468",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589395600,
      "name": "ipmr_new_tunnel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
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
struct net_device * ipmr_new_tunnel(struct net * net, struct vifctl * v)
```

```json
{
  "name": "ipmr_new_tunnel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590382784,
      "name": "ipmr_new_tunnel",
      "external": false,
      "loc": "net/ipv4/ipmr.c:441",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590382784,
      "name": "ipmr_new_tunnel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 363
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
struct net_device * ipmr_new_tunnel(struct net * net, struct vifctl * v)
```

```json
{
  "name": "ipmr_new_tunnel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590440352,
      "name": "ipmr_new_tunnel",
      "external": false,
      "loc": "net/ipv4/ipmr.c:441",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590440352,
      "name": "ipmr_new_tunnel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 363
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
struct net_device * ipmr_new_tunnel(struct net * net, struct vifctl * v)
```

```json
{
  "name": "ipmr_new_tunnel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590365856,
      "name": "ipmr_new_tunnel",
      "external": false,
      "loc": "net/ipv4/ipmr.c:441",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590365856,
      "name": "ipmr_new_tunnel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
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
struct net_device * ipmr_new_tunnel(struct net * net, struct vifctl * v)
```

```json
{
  "name": "ipmr_new_tunnel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591158320,
      "name": "ipmr_new_tunnel",
      "external": false,
      "loc": "net/ipv4/ipmr.c:443",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591158320,
      "name": "ipmr_new_tunnel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct net_device * ipmr_new_tunnel(struct net * net, struct vifctl * v)
```

```json
{
  "name": "ipmr_new_tunnel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592816992,
      "name": "ipmr_new_tunnel",
      "external": false,
      "loc": "net/ipv4/ipmr.c:436",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592816992,
      "name": "ipmr_new_tunnel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct net_device * ipmr_new_tunnel(struct net * net, struct vifctl * v)
```

```json
{
  "name": "ipmr_new_tunnel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594689680,
      "name": "ipmr_new_tunnel",
      "external": false,
      "loc": "net/ipv4/ipmr.c:441",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594689680,
      "name": "ipmr_new_tunnel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct net_device * ipmr_new_tunnel(struct net * net, struct vifctl * v)
```

```json
{
  "name": "ipmr_new_tunnel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595081584,
      "name": "ipmr_new_tunnel",
      "external": false,
      "loc": "net/ipv4/ipmr.c:441",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595081584,
      "name": "ipmr_new_tunnel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct net_device * ipmr_new_tunnel(struct net * net, struct vifctl * v)
```

```json
{
  "name": "ipmr_new_tunnel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595894368,
      "name": "ipmr_new_tunnel",
      "external": false,
      "loc": "net/ipv4/ipmr.c:441",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595894368,
      "name": "ipmr_new_tunnel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
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
struct net_device * ipmr_new_tunnel(struct net * net, struct vifctl * v)
```

```json
{
  "name": "ipmr_new_tunnel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503049208,
      "name": "ipmr_new_tunnel",
      "external": false,
      "loc": "net/ipv4/ipmr.c:468",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503049208,
      "name": "ipmr_new_tunnel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
struct net_device * ipmr_new_tunnel(struct net * net, struct vifctl * v)
```

```json
{
  "name": "ipmr_new_tunnel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235729268,
      "name": "ipmr_new_tunnel",
      "external": false,
      "loc": "net/ipv4/ipmr.c:468",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235729268,
      "name": "ipmr_new_tunnel",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct net_device * ipmr_new_tunnel(struct net * net, struct vifctl * v)
```

```json
{
  "name": "ipmr_new_tunnel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296743424,
      "name": "ipmr_new_tunnel",
      "external": false,
      "loc": "net/ipv4/ipmr.c:468",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296743424,
      "name": "ipmr_new_tunnel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
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
struct net_device * ipmr_new_tunnel(struct net * net, struct vifctl * v)
```

```json
{
  "name": "ipmr_new_tunnel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279106532,
      "name": "ipmr_new_tunnel",
      "external": false,
      "loc": "net/ipv4/ipmr.c:468",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279106532,
      "name": "ipmr_new_tunnel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
struct net_device * ipmr_new_tunnel(struct net * net, struct vifctl * v)
```

```json
{
  "name": "ipmr_new_tunnel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589000880,
      "name": "ipmr_new_tunnel",
      "external": false,
      "loc": "net/ipv4/ipmr.c:468",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589000880,
      "name": "ipmr_new_tunnel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
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
struct net_device * ipmr_new_tunnel(struct net * net, struct vifctl * v)
```

```json
{
  "name": "ipmr_new_tunnel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588723936,
      "name": "ipmr_new_tunnel",
      "external": false,
      "loc": "net/ipv4/ipmr.c:468",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588723936,
      "name": "ipmr_new_tunnel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
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
struct net_device * ipmr_new_tunnel(struct net * net, struct vifctl * v)
```

```json
{
  "name": "ipmr_new_tunnel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589437264,
      "name": "ipmr_new_tunnel",
      "external": false,
      "loc": "net/ipv4/ipmr.c:468",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589437264,
      "name": "ipmr_new_tunnel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
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
struct net_device * ipmr_new_tunnel(struct net * net, struct vifctl * v)
```

```json
{
  "name": "ipmr_new_tunnel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589481856,
      "name": "ipmr_new_tunnel",
      "external": false,
      "loc": "net/ipv4/ipmr.c:468",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:vif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589481856,
      "name": "ipmr_new_tunnel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct net_device * ipmr_new_tunnel(struct net * net, struct vifctl * v)
```
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
