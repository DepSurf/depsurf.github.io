# Function: <code>xsk_rcv</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int xsk_rcv(struct xdp_sock * xs, struct xdp_buff * xdp)
```

```json
{
  "name": "xsk_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589119488,
      "name": "xsk_rcv",
      "external": true,
      "loc": "net/xdp/xsk.c:93",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:__xsk_map_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589119488,
      "name": "xsk_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 573
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
int xsk_rcv(struct xdp_sock * xs, struct xdp_buff * xdp)
```

```json
{
  "name": "xsk_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589353072,
      "name": "xsk_rcv",
      "external": true,
      "loc": "net/xdp/xsk.c:103",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:__xsk_map_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589353072,
      "name": "xsk_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 605
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
int xsk_rcv(struct xdp_sock * xs, struct xdp_buff * xdp)
```

```json
{
  "name": "xsk_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589810048,
      "name": "xsk_rcv",
      "external": true,
      "loc": "net/xdp/xsk.c:105",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:__xsk_map_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589810048,
      "name": "xsk_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 546
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
int xsk_rcv(struct xdp_sock * xs, struct xdp_buff * xdp)
```

```json
{
  "name": "xsk_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590034480,
      "name": "xsk_rcv",
      "external": true,
      "loc": "net/xdp/xsk.c:199",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:__xsk_map_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590034480,
      "name": "xsk_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 884
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xsk_rcv",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591067947,
      "name": "xsk_rcv",
      "external": false,
      "loc": "net/xdp/xsk.c:190",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:__xsk_map_redirect",
        "net/xdp/xsk.c:xsk_generic_rcv"
      ],
      "caller_func": [
        "net/xdp/xsk.c:__xsk_map_redirect",
        "net/xdp/xsk.c:xsk_generic_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591064960,
      "name": "xsk_rcv.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
int xsk_rcv(struct xdp_sock * xs, struct xdp_buff * xdp, bool explicit_free)
```

```json
{
  "name": "xsk_rcv",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591132683,
      "name": "xsk_rcv",
      "external": false,
      "loc": "net/xdp/xsk.c:233",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:__xsk_map_redirect",
        "net/xdp/xsk.c:__xsk_map_redirect"
      ],
      "caller_func": [
        "net/xdp/xsk.c:xsk_generic_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591128288,
      "name": "xsk_rcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xsk_rcv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591063503,
      "name": "xsk_rcv",
      "external": false,
      "loc": "net/xdp/xsk.c:265",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:__xsk_map_redirect"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xsk_rcv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591906383,
      "name": "xsk_rcv",
      "external": false,
      "loc": "net/xdp/xsk.c:265",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:__xsk_map_redirect"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xsk_rcv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593626874,
      "name": "xsk_rcv",
      "external": false,
      "loc": "net/xdp/xsk.c:250",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:__xsk_map_redirect"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xsk_rcv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595556762,
      "name": "xsk_rcv",
      "external": false,
      "loc": "net/xdp/xsk.c:250",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:__xsk_map_redirect"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xsk_rcv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596065082,
      "name": "xsk_rcv",
      "external": false,
      "loc": "net/xdp/xsk.c:251",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:__xsk_map_redirect"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xsk_rcv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596932421,
      "name": "xsk_rcv",
      "external": false,
      "loc": "net/xdp/xsk.c:353",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:__xsk_map_redirect"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
int xsk_rcv(struct xdp_sock * xs, struct xdp_buff * xdp)
```

```json
{
  "name": "xsk_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503788352,
      "name": "xsk_rcv",
      "external": true,
      "loc": "net/xdp/xsk.c:199",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:__xsk_map_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503788352,
      "name": "xsk_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 900
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
int xsk_rcv(struct xdp_sock * xs, struct xdp_buff * xdp)
```

```json
{
  "name": "xsk_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236407060,
      "name": "xsk_rcv",
      "external": true,
      "loc": "net/xdp/xsk.c:199",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:__xsk_map_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236407060,
      "name": "xsk_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1284
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
int xsk_rcv(struct xdp_sock * xs, struct xdp_buff * xdp)
```

```json
{
  "name": "xsk_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297629888,
      "name": "xsk_rcv",
      "external": true,
      "loc": "net/xdp/xsk.c:199",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:__xsk_map_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297629888,
      "name": "xsk_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1176
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
int xsk_rcv(struct xdp_sock * xs, struct xdp_buff * xdp)
```

```json
{
  "name": "xsk_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279694292,
      "name": "xsk_rcv",
      "external": true,
      "loc": "net/xdp/xsk.c:199",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:__xsk_map_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279694292,
      "name": "xsk_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 716
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
int xsk_rcv(struct xdp_sock * xs, struct xdp_buff * xdp)
```

```json
{
  "name": "xsk_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589638080,
      "name": "xsk_rcv",
      "external": true,
      "loc": "net/xdp/xsk.c:199",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:__xsk_map_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589638080,
      "name": "xsk_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 884
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
int xsk_rcv(struct xdp_sock * xs, struct xdp_buff * xdp)
```

```json
{
  "name": "xsk_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589362608,
      "name": "xsk_rcv",
      "external": true,
      "loc": "net/xdp/xsk.c:199",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:__xsk_map_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589362608,
      "name": "xsk_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 884
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
int xsk_rcv(struct xdp_sock * xs, struct xdp_buff * xdp)
```

```json
{
  "name": "xsk_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590080112,
      "name": "xsk_rcv",
      "external": true,
      "loc": "net/xdp/xsk.c:199",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:__xsk_map_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590080112,
      "name": "xsk_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 884
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
int xsk_rcv(struct xdp_sock * xs, struct xdp_buff * xdp)
```

```json
{
  "name": "xsk_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590130320,
      "name": "xsk_rcv",
      "external": true,
      "loc": "net/xdp/xsk.c:199",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/xskmap.c:__xsk_map_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590130320,
      "name": "xsk_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 884
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
int xsk_rcv(struct xdp_sock * xs, struct xdp_buff * xdp)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int xsk_rcv(struct xdp_sock * xs, struct xdp_buff * xdp)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int xsk_rcv(struct xdp_sock * xs, struct xdp_buff * xdp, bool explicit_free)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int xsk_rcv(struct xdp_sock * xs, struct xdp_buff * xdp, bool explicit_free)
```
</details>
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
