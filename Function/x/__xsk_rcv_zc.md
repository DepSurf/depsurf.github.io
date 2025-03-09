# Function: <code>__xsk_rcv_zc</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__xsk_rcv_zc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589119940,
      "name": "__xsk_rcv_zc",
      "external": false,
      "loc": "net/xdp/xsk.c:83",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_rcv"
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
  "name": "__xsk_rcv_zc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589353546,
      "name": "__xsk_rcv_zc",
      "external": false,
      "loc": "net/xdp/xsk.c:93",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_rcv"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__xsk_rcv_zc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589810471,
      "name": "__xsk_rcv_zc",
      "external": false,
      "loc": "net/xdp/xsk.c:95",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_rcv"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__xsk_rcv_zc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590034723,
      "name": "__xsk_rcv_zc",
      "external": false,
      "loc": "net/xdp/xsk.c:179",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_rcv"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __xsk_rcv_zc(struct xdp_sock * xs, struct xdp_buff * xdp, u32 len)
```

```json
{
  "name": "__xsk_rcv_zc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591064560,
      "name": "__xsk_rcv_zc",
      "external": false,
      "loc": "net/xdp/xsk.c:117",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:__xsk_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591064560,
      "name": "__xsk_rcv_zc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
int __xsk_rcv_zc(struct xdp_sock * xs, struct xdp_buff * xdp, u32 len)
```

```json
{
  "name": "__xsk_rcv_zc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591127856,
      "name": "__xsk_rcv_zc",
      "external": false,
      "loc": "net/xdp/xsk.c:152",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:__xsk_map_redirect",
        "net/xdp/xsk.c:__xsk_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591127856,
      "name": "__xsk_rcv_zc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
int __xsk_rcv_zc(struct xdp_sock * xs, struct xdp_buff * xdp, u32 len)
```

```json
{
  "name": "__xsk_rcv_zc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591058144,
      "name": "__xsk_rcv_zc",
      "external": false,
      "loc": "net/xdp/xsk.c:152",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:__xsk_map_redirect",
        "net/xdp/xsk.c:__xsk_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591058144,
      "name": "__xsk_rcv_zc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __xsk_rcv_zc(struct xdp_sock * xs, struct xdp_buff * xdp, u32 len)
```

```json
{
  "name": "__xsk_rcv_zc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591900641,
      "name": "__xsk_rcv_zc",
      "external": false,
      "loc": "net/xdp/xsk.c:152",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:__xsk_map_redirect",
        "net/xdp/xsk.c:__xsk_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591900480,
      "name": "__xsk_rcv_zc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071592751134,
      "name": "__xsk_rcv_zc.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int __xsk_rcv_zc(struct xdp_sock * xs, struct xdp_buff * xdp, u32 len)
```

```json
{
  "name": "__xsk_rcv_zc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__xsk_rcv_zc",
      "external": false,
      "loc": "net/xdp/xsk.c:137",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:__xsk_map_redirect",
        "net/xdp/xsk.c:__xsk_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593619728,
      "name": "__xsk_rcv_zc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    },
    {
      "addr": 18446744071594637706,
      "name": "__xsk_rcv_zc.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int __xsk_rcv_zc(struct xdp_sock * xs, struct xdp_buff * xdp, u32 len)
```

```json
{
  "name": "__xsk_rcv_zc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__xsk_rcv_zc",
      "external": false,
      "loc": "net/xdp/xsk.c:137",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:__xsk_map_redirect",
        "net/xdp/xsk.c:__xsk_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595548512,
      "name": "__xsk_rcv_zc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    },
    {
      "addr": 18446744071596367115,
      "name": "__xsk_rcv_zc.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int __xsk_rcv_zc(struct xdp_sock * xs, struct xdp_buff * xdp, u32 len)
```

```json
{
  "name": "__xsk_rcv_zc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__xsk_rcv_zc",
      "external": false,
      "loc": "net/xdp/xsk.c:138",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:__xsk_map_redirect",
        "net/xdp/xsk.c:__xsk_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596056768,
      "name": "__xsk_rcv_zc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    },
    {
      "addr": 18446744071596896850,
      "name": "__xsk_rcv_zc.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int __xsk_rcv_zc(struct xdp_sock * xs, struct xdp_buff_xsk * xskb, u32 len, u32 flags)
```

```json
{
  "name": "__xsk_rcv_zc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__xsk_rcv_zc",
      "external": false,
      "loc": "net/xdp/xsk.c:140",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:__xsk_map_redirect",
        "net/xdp/xsk.c:__xsk_map_redirect",
        "net/xdp/xsk.c:__xsk_rcv",
        "net/xdp/xsk.c:__xsk_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596922240,
      "name": "__xsk_rcv_zc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    },
    {
      "addr": 18446744071597822161,
      "name": "__xsk_rcv_zc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__xsk_rcv_zc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503788612,
      "name": "__xsk_rcv_zc",
      "external": false,
      "loc": "net/xdp/xsk.c:179",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_rcv"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__xsk_rcv_zc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3236407740,
      "name": "__xsk_rcv_zc",
      "external": false,
      "loc": "net/xdp/xsk.c:179",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_rcv"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__xsk_rcv_zc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055297630520,
      "name": "__xsk_rcv_zc",
      "external": false,
      "loc": "net/xdp/xsk.c:179",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_rcv"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__xsk_rcv_zc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279694746,
      "name": "__xsk_rcv_zc",
      "external": false,
      "loc": "net/xdp/xsk.c:179",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_rcv"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__xsk_rcv_zc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589638323,
      "name": "__xsk_rcv_zc",
      "external": false,
      "loc": "net/xdp/xsk.c:179",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_rcv"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__xsk_rcv_zc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589362851,
      "name": "__xsk_rcv_zc",
      "external": false,
      "loc": "net/xdp/xsk.c:179",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_rcv"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__xsk_rcv_zc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590080355,
      "name": "__xsk_rcv_zc",
      "external": false,
      "loc": "net/xdp/xsk.c:179",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_rcv"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__xsk_rcv_zc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590130563,
      "name": "__xsk_rcv_zc",
      "external": false,
      "loc": "net/xdp/xsk.c:179",
      "file": "net/xdp/xsk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_rcv"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int __xsk_rcv_zc(struct xdp_sock * xs, struct xdp_buff * xdp, u32 len)
```
</details>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct xdp_buff_xsk * xskb</code>
</li>
<li>
<b>Param added. </b>
<code>u32 flags</code>
</li>
<li>
<b>Param removed. </b>
<code>struct xdp_buff * xdp</code>
</li>
</ul>
</details>
</li>
</ul>
