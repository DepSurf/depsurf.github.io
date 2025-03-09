# Function: <code>__xsk_rcv</code>

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
  "name": "__xsk_rcv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589119557,
      "name": "__xsk_rcv",
      "external": false,
      "loc": "net/xdp/xsk.c:56",
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
  "name": "__xsk_rcv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589353144,
      "name": "__xsk_rcv",
      "external": false,
      "loc": "net/xdp/xsk.c:56",
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
  "name": "__xsk_rcv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589810123,
      "name": "__xsk_rcv",
      "external": false,
      "loc": "net/xdp/xsk.c:58",
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
  "name": "__xsk_rcv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590034578,
      "name": "__xsk_rcv",
      "external": false,
      "loc": "net/xdp/xsk.c:141",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __xsk_rcv(struct xdp_sock * xs, struct xdp_buff * xdp, u32 len, bool explicit_free)
```

```json
{
  "name": "__xsk_rcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591064736,
      "name": "__xsk_rcv",
      "external": false,
      "loc": "net/xdp/xsk.c:152",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591064736,
      "name": "__xsk_rcv",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int __xsk_rcv(struct xdp_sock * xs, struct xdp_buff * xdp, u32 len, bool explicit_free)
```

```json
{
  "name": "__xsk_rcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591128064,
      "name": "__xsk_rcv",
      "external": false,
      "loc": "net/xdp/xsk.c:187",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:__xsk_map_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591128064,
      "name": "__xsk_rcv",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int __xsk_rcv(struct xdp_sock * xs, struct xdp_buff * xdp)
```

```json
{
  "name": "__xsk_rcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591058352,
      "name": "__xsk_rcv",
      "external": false,
      "loc": "net/xdp/xsk.c:187",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:__xsk_map_redirect",
        "net/xdp/xsk.c:xsk_generic_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591058352,
      "name": "__xsk_rcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
int __xsk_rcv(struct xdp_sock * xs, struct xdp_buff * xdp)
```

```json
{
  "name": "__xsk_rcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591900720,
      "name": "__xsk_rcv",
      "external": false,
      "loc": "net/xdp/xsk.c:187",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:__xsk_map_redirect",
        "net/xdp/xsk.c:xsk_generic_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591900720,
      "name": "__xsk_rcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
int __xsk_rcv(struct xdp_sock * xs, struct xdp_buff * xdp)
```

```json
{
  "name": "__xsk_rcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593620016,
      "name": "__xsk_rcv",
      "external": false,
      "loc": "net/xdp/xsk.c:172",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:__xsk_map_redirect",
        "net/xdp/xsk.c:xsk_generic_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593620016,
      "name": "__xsk_rcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
int __xsk_rcv(struct xdp_sock * xs, struct xdp_buff * xdp)
```

```json
{
  "name": "__xsk_rcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595548816,
      "name": "__xsk_rcv",
      "external": false,
      "loc": "net/xdp/xsk.c:172",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:__xsk_map_redirect",
        "net/xdp/xsk.c:xsk_generic_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595548816,
      "name": "__xsk_rcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
int __xsk_rcv(struct xdp_sock * xs, struct xdp_buff * xdp)
```

```json
{
  "name": "__xsk_rcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596057072,
      "name": "__xsk_rcv",
      "external": false,
      "loc": "net/xdp/xsk.c:173",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:__xsk_map_redirect",
        "net/xdp/xsk.c:xsk_generic_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596057072,
      "name": "__xsk_rcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
int __xsk_rcv(struct xdp_sock * xs, struct xdp_buff * xdp, u32 len)
```

```json
{
  "name": "__xsk_rcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596922560,
      "name": "__xsk_rcv",
      "external": false,
      "loc": "net/xdp/xsk.c:228",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:__xsk_map_redirect",
        "net/xdp/xsk.c:xsk_generic_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596922560,
      "name": "__xsk_rcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 682
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
  "name": "__xsk_rcv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503788472,
      "name": "__xsk_rcv",
      "external": false,
      "loc": "net/xdp/xsk.c:141",
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
  "name": "__xsk_rcv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3236407188,
      "name": "__xsk_rcv",
      "external": false,
      "loc": "net/xdp/xsk.c:141",
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
  "name": "__xsk_rcv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055297630032,
      "name": "__xsk_rcv",
      "external": false,
      "loc": "net/xdp/xsk.c:141",
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
  "name": "__xsk_rcv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279694420,
      "name": "__xsk_rcv",
      "external": false,
      "loc": "net/xdp/xsk.c:141",
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
  "name": "__xsk_rcv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589638178,
      "name": "__xsk_rcv",
      "external": false,
      "loc": "net/xdp/xsk.c:141",
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
  "name": "__xsk_rcv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589362706,
      "name": "__xsk_rcv",
      "external": false,
      "loc": "net/xdp/xsk.c:141",
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
  "name": "__xsk_rcv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590080210,
      "name": "__xsk_rcv",
      "external": false,
      "loc": "net/xdp/xsk.c:141",
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
  "name": "__xsk_rcv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590130418,
      "name": "__xsk_rcv",
      "external": false,
      "loc": "net/xdp/xsk.c:141",
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
int __xsk_rcv(struct xdp_sock * xs, struct xdp_buff * xdp, u32 len, bool explicit_free)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u32 len</code>
</li>
<li>
<b>Param removed. </b>
<code>bool explicit_free</code>
</li>
</ul>
</details>
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
<code>u32 len</code>
</li>
</ul>
</details>
</li>
</ul>
