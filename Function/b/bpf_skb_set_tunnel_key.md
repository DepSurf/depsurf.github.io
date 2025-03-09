# Function: <code>bpf_skb_set_tunnel_key</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
u64 bpf_skb_set_tunnel_key(u64 r1, u64 r2, u64 size, u64 flags, u64 r5)
```

```json
{
  "name": "bpf_skb_set_tunnel_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586388848,
      "name": "bpf_skb_set_tunnel_key",
      "external": false,
      "loc": "net/core/filter.c:1584",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586388848,
      "name": "bpf_skb_set_tunnel_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
u64 bpf_skb_set_tunnel_key(u64 r1, u64 r2, u64 size, u64 flags, u64 r5)
```

```json
{
  "name": "bpf_skb_set_tunnel_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586827664,
      "name": "bpf_skb_set_tunnel_key",
      "external": false,
      "loc": "net/core/filter.c:2165",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586827664,
      "name": "bpf_skb_set_tunnel_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 559
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
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_skb_set_tunnel_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587016096,
      "name": "bpf_skb_set_tunnel_key",
      "external": true,
      "loc": "net/core/filter.c:2421",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587016096,
      "name": "bpf_skb_set_tunnel_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 553
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
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_skb_set_tunnel_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587143296,
      "name": "bpf_skb_set_tunnel_key",
      "external": true,
      "loc": "net/core/filter.c:2580",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587143296,
      "name": "bpf_skb_set_tunnel_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 646
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
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_skb_set_tunnel_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587648784,
      "name": "bpf_skb_set_tunnel_key",
      "external": true,
      "loc": "net/core/filter.c:2978",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587648784,
      "name": "bpf_skb_set_tunnel_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 646
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_skb_set_tunnel_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_skb_set_tunnel_key",
      "external": true,
      "loc": "net/core/filter.c:3600",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587989404,
      "name": "bpf_skb_set_tunnel_key.cold.94",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071587967024,
      "name": "bpf_skb_set_tunnel_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 676
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_skb_set_tunnel_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_skb_set_tunnel_key",
      "external": true,
      "loc": "net/core/filter.c:3788",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588148212,
      "name": "bpf_skb_set_tunnel_key.cold.101",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071588118144,
      "name": "bpf_skb_set_tunnel_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 678
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_skb_set_tunnel_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_skb_set_tunnel_key",
      "external": true,
      "loc": "net/core/filter.c:3925",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588469182,
      "name": "bpf_skb_set_tunnel_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071588436992,
      "name": "bpf_skb_set_tunnel_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 656
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_skb_set_tunnel_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_skb_set_tunnel_key",
      "external": true,
      "loc": "net/core/filter.c:3932",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588674750,
      "name": "bpf_skb_set_tunnel_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071588643408,
      "name": "bpf_skb_set_tunnel_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 663
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
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_skb_set_tunnel_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_skb_set_tunnel_key",
      "external": true,
      "loc": "net/core/filter.c:3904",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589540361,
      "name": "bpf_skb_set_tunnel_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071589501760,
      "name": "bpf_skb_set_tunnel_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_skb_set_tunnel_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_skb_set_tunnel_key",
      "external": true,
      "loc": "net/core/filter.c:4312",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591630677,
      "name": "bpf_skb_set_tunnel_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071589504160,
      "name": "bpf_skb_set_tunnel_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_skb_set_tunnel_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_skb_set_tunnel_key",
      "external": true,
      "loc": "net/core/filter.c:4251",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591574110,
      "name": "bpf_skb_set_tunnel_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071589402176,
      "name": "bpf_skb_set_tunnel_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 655
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
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_skb_set_tunnel_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_skb_set_tunnel_key",
      "external": true,
      "loc": "net/core/filter.c:4309",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592701841,
      "name": "bpf_skb_set_tunnel_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071590128416,
      "name": "bpf_skb_set_tunnel_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 690
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
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_skb_set_tunnel_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591679936,
      "name": "bpf_skb_set_tunnel_key",
      "external": true,
      "loc": "net/core/filter.c:4595",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591679936,
      "name": "bpf_skb_set_tunnel_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 689
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
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_skb_set_tunnel_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593475232,
      "name": "bpf_skb_set_tunnel_key",
      "external": true,
      "loc": "net/core/filter.c:4613",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593475232,
      "name": "bpf_skb_set_tunnel_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 689
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
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_skb_set_tunnel_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593941120,
      "name": "bpf_skb_set_tunnel_key",
      "external": true,
      "loc": "net/core/filter.c:4664",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593941120,
      "name": "bpf_skb_set_tunnel_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 748
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
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_skb_set_tunnel_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594723888,
      "name": "bpf_skb_set_tunnel_key",
      "external": true,
      "loc": "net/core/filter.c:4738",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594723888,
      "name": "bpf_skb_set_tunnel_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 748
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
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_skb_set_tunnel_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502218872,
      "name": "bpf_skb_set_tunnel_key",
      "external": true,
      "loc": "net/core/filter.c:3932",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502218872,
      "name": "bpf_skb_set_tunnel_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 612
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
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_skb_set_tunnel_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234941168,
      "name": "bpf_skb_set_tunnel_key",
      "external": true,
      "loc": "net/core/filter.c:3932",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234941168,
      "name": "bpf_skb_set_tunnel_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 636
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
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_skb_set_tunnel_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295667184,
      "name": "bpf_skb_set_tunnel_key",
      "external": true,
      "loc": "net/core/filter.c:3932",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295667184,
      "name": "bpf_skb_set_tunnel_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 792
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
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_skb_set_tunnel_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278458782,
      "name": "bpf_skb_set_tunnel_key",
      "external": true,
      "loc": "net/core/filter.c:3932",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278458782,
      "name": "bpf_skb_set_tunnel_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 578
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_skb_set_tunnel_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_skb_set_tunnel_key",
      "external": true,
      "loc": "net/core/filter.c:3932",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588281486,
      "name": "bpf_skb_set_tunnel_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071588250144,
      "name": "bpf_skb_set_tunnel_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 663
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_skb_set_tunnel_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_skb_set_tunnel_key",
      "external": true,
      "loc": "net/core/filter.c:3932",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587994302,
      "name": "bpf_skb_set_tunnel_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071587962960,
      "name": "bpf_skb_set_tunnel_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 663
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_skb_set_tunnel_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_skb_set_tunnel_key",
      "external": true,
      "loc": "net/core/filter.c:3932",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588613310,
      "name": "bpf_skb_set_tunnel_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071588581968,
      "name": "bpf_skb_set_tunnel_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 663
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
u64 bpf_skb_set_tunnel_key(u64 skb, u64 from, u64 size, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_skb_set_tunnel_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_skb_set_tunnel_key",
      "external": true,
      "loc": "net/core/filter.c:3932",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588750990,
      "name": "bpf_skb_set_tunnel_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071588719456,
      "name": "bpf_skb_set_tunnel_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 663
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 skb</code>
</li>
<li>
<b>Param added. </b>
<code>u64 from</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_1</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r1</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r2</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r5</code>
</li>
</ul>
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
