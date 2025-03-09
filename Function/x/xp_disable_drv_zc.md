# Function: <code>xp_disable_drv_zc</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void xp_disable_drv_zc(struct xsk_buff_pool * pool)
```

```json
{
  "name": "xp_disable_drv_zc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591136640,
      "name": "xp_disable_drv_zc",
      "external": false,
      "loc": "net/xdp/xsk_buff_pool.c:103",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk_buff_pool.c:xp_release_deferred",
        "net/xdp/xsk_buff_pool.c:__xp_assign_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591136640,
      "name": "xp_disable_drv_zc",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void xp_disable_drv_zc(struct xsk_buff_pool * pool)
```

```json
{
  "name": "xp_disable_drv_zc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591067536,
      "name": "xp_disable_drv_zc",
      "external": false,
      "loc": "net/xdp/xsk_buff_pool.c:103",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk_buff_pool.c:xp_release_deferred",
        "net/xdp/xsk_buff_pool.c:xp_assign_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591067536,
      "name": "xp_disable_drv_zc",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void xp_disable_drv_zc(struct xsk_buff_pool * pool)
```

```json
{
  "name": "xp_disable_drv_zc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xp_disable_drv_zc",
      "external": false,
      "loc": "net/xdp/xsk_buff_pool.c:103",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk_buff_pool.c:xp_release_deferred",
        "net/xdp/xsk_buff_pool.c:xp_assign_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591910896,
      "name": "xp_disable_drv_zc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
    },
    {
      "addr": 18446744071592751427,
      "name": "xp_disable_drv_zc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void xp_disable_drv_zc(struct xsk_buff_pool * pool)
```

```json
{
  "name": "xp_disable_drv_zc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xp_disable_drv_zc",
      "external": false,
      "loc": "net/xdp/xsk_buff_pool.c:124",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk_buff_pool.c:xp_release_deferred",
        "net/xdp/xsk_buff_pool.c:xp_assign_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593631856,
      "name": "xp_disable_drv_zc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
    },
    {
      "addr": 18446744071594638038,
      "name": "xp_disable_drv_zc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void xp_disable_drv_zc(struct xsk_buff_pool * pool)
```

```json
{
  "name": "xp_disable_drv_zc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xp_disable_drv_zc",
      "external": false,
      "loc": "net/xdp/xsk_buff_pool.c:124",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk_buff_pool.c:xp_release_deferred",
        "net/xdp/xsk_buff_pool.c:xp_assign_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595562192,
      "name": "xp_disable_drv_zc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
    },
    {
      "addr": 18446744071596367489,
      "name": "xp_disable_drv_zc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void xp_disable_drv_zc(struct xsk_buff_pool * pool)
```

```json
{
  "name": "xp_disable_drv_zc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xp_disable_drv_zc",
      "external": false,
      "loc": "net/xdp/xsk_buff_pool.c:124",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk_buff_pool.c:xp_release_deferred",
        "net/xdp/xsk_buff_pool.c:xp_assign_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596070640,
      "name": "xp_disable_drv_zc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
    },
    {
      "addr": 18446744071596897226,
      "name": "xp_disable_drv_zc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void xp_disable_drv_zc(struct xsk_buff_pool * pool)
```

```json
{
  "name": "xp_disable_drv_zc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xp_disable_drv_zc",
      "external": false,
      "loc": "net/xdp/xsk_buff_pool.c:140",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk_buff_pool.c:xp_release_deferred",
        "net/xdp/xsk_buff_pool.c:xp_assign_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596939328,
      "name": "xp_disable_drv_zc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071597822652,
      "name": "xp_disable_drv_zc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void xp_disable_drv_zc(struct xsk_buff_pool * pool)
```
</details>
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
