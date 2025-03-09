# Function: <code>xp_raw_get_data</code>

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
void * xp_raw_get_data(struct xsk_buff_pool * pool, u64 addr)
```

```json
{
  "name": "xp_raw_get_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591073024,
      "name": "xp_raw_get_data",
      "external": true,
      "loc": "net/xdp/xsk_buff_pool.c:261",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_generic_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591073024,
      "name": "xp_raw_get_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void * xp_raw_get_data(struct xsk_buff_pool * pool, u64 addr)
```

```json
{
  "name": "xp_raw_get_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591136496,
      "name": "xp_raw_get_data",
      "external": true,
      "loc": "net/xdp/xsk_buff_pool.c:531",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_generic_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591136496,
      "name": "xp_raw_get_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void * xp_raw_get_data(struct xsk_buff_pool * pool, u64 addr)
```

```json
{
  "name": "xp_raw_get_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591067392,
      "name": "xp_raw_get_data",
      "external": true,
      "loc": "net/xdp/xsk_buff_pool.c:525",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_generic_xmit",
        "net/xdp/xsk.c:xsk_build_skb_zerocopy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591067392,
      "name": "xp_raw_get_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void * xp_raw_get_data(struct xsk_buff_pool * pool, u64 addr)
```

```json
{
  "name": "xp_raw_get_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xp_raw_get_data",
      "external": true,
      "loc": "net/xdp/xsk_buff_pool.c:525",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_generic_xmit",
        "net/xdp/xsk.c:xsk_build_skb_zerocopy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592751340,
      "name": "xp_raw_get_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071591910544,
      "name": "xp_raw_get_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void * xp_raw_get_data(struct xsk_buff_pool * pool, u64 addr)
```

```json
{
  "name": "xp_raw_get_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xp_raw_get_data",
      "external": true,
      "loc": "net/xdp/xsk_buff_pool.c:647",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_generic_xmit",
        "net/xdp/xsk.c:xsk_build_skb_zerocopy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594637988,
      "name": "xp_raw_get_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071593631632,
      "name": "xp_raw_get_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void * xp_raw_get_data(struct xsk_buff_pool * pool, u64 addr)
```

```json
{
  "name": "xp_raw_get_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xp_raw_get_data",
      "external": true,
      "loc": "net/xdp/xsk_buff_pool.c:652",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:__xsk_generic_xmit",
        "net/xdp/xsk.c:xsk_build_skb_zerocopy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596367439,
      "name": "xp_raw_get_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071595561936,
      "name": "xp_raw_get_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void * xp_raw_get_data(struct xsk_buff_pool * pool, u64 addr)
```

```json
{
  "name": "xp_raw_get_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xp_raw_get_data",
      "external": true,
      "loc": "net/xdp/xsk_buff_pool.c:656",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:__xsk_generic_xmit",
        "net/xdp/xsk.c:xsk_build_skb_zerocopy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596897176,
      "name": "xp_raw_get_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071596070384,
      "name": "xp_raw_get_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void * xp_raw_get_data(struct xsk_buff_pool * pool, u64 addr)
```

```json
{
  "name": "xp_raw_get_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xp_raw_get_data",
      "external": true,
      "loc": "net/xdp/xsk_buff_pool.c:681",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_build_skb",
        "net/xdp/xsk.c:xsk_build_skb_zerocopy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597822510,
      "name": "xp_raw_get_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071596938384,
      "name": "xp_raw_get_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void * xp_raw_get_data(struct xsk_buff_pool * pool, u64 addr)
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
