# Function: <code>xp_free</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void xp_free(struct xdp_buff_xsk * xskb)
```

```json
{
  "name": "xp_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591072960,
      "name": "xp_free",
      "external": true,
      "loc": "net/xdp/xsk_buff_pool.c:254",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame",
        "net/xdp/xsk.c:__xsk_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591072960,
      "name": "xp_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void xp_free(struct xdp_buff_xsk * xskb)
```

```json
{
  "name": "xp_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591136432,
      "name": "xp_free",
      "external": true,
      "loc": "net/xdp/xsk_buff_pool.c:524",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame",
        "net/core/xdp.c:__xdp_return",
        "net/xdp/xsk.c:__xsk_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591136432,
      "name": "xp_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void xp_free(struct xdp_buff_xsk * xskb)
```

```json
{
  "name": "xp_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591067328,
      "name": "xp_free",
      "external": true,
      "loc": "net/xdp/xsk_buff_pool.c:518",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame",
        "net/core/xdp.c:__xdp_return",
        "net/xdp/xsk.c:__xsk_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591067328,
      "name": "xp_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void xp_free(struct xdp_buff_xsk * xskb)
```

```json
{
  "name": "xp_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591910224,
      "name": "xp_free",
      "external": true,
      "loc": "net/xdp/xsk_buff_pool.c:518",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame",
        "net/core/xdp.c:__xdp_return",
        "net/xdp/xsk.c:__xsk_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591910224,
      "name": "xp_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void xp_free(struct xdp_buff_xsk * xskb)
```

```json
{
  "name": "xp_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593631088,
      "name": "xp_free",
      "external": true,
      "loc": "net/xdp/xsk_buff_pool.c:637",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame",
        "net/core/xdp.c:__xdp_return",
        "net/xdp/xsk.c:__xsk_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593631088,
      "name": "xp_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void xp_free(struct xdp_buff_xsk * xskb)
```

```json
{
  "name": "xp_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595561312,
      "name": "xp_free",
      "external": true,
      "loc": "net/xdp/xsk_buff_pool.c:642",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame",
        "net/core/xdp.c:__xdp_return",
        "net/xdp/xsk.c:__xsk_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595561312,
      "name": "xp_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void xp_free(struct xdp_buff_xsk * xskb)
```

```json
{
  "name": "xp_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596069760,
      "name": "xp_free",
      "external": true,
      "loc": "net/xdp/xsk_buff_pool.c:646",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame",
        "net/core/xdp.c:__xdp_return",
        "net/xdp/xsk.c:__xsk_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596069760,
      "name": "xp_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void xp_free(struct xdp_buff_xsk * xskb)
```

```json
{
  "name": "xp_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596937760,
      "name": "xp_free",
      "external": true,
      "loc": "net/xdp/xsk_buff_pool.c:671",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame",
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:__xdp_return",
        "net/xdp/xsk.c:__xsk_map_redirect",
        "net/xdp/xsk.c:__xsk_map_redirect",
        "net/xdp/xsk.c:__xsk_rcv",
        "net/xdp/xsk.c:__xsk_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596937760,
      "name": "xp_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void xp_free(struct xdp_buff_xsk * xskb)
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
