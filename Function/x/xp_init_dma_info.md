# Function: <code>xp_init_dma_info</code>

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
int xp_init_dma_info(struct xsk_buff_pool * pool, struct xsk_dma_map * dma_map)
```

```json
{
  "name": "xp_init_dma_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591137536,
      "name": "xp_init_dma_info",
      "external": false,
      "loc": "net/xdp/xsk_buff_pool.c:364",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591137536,
      "name": "xp_init_dma_info",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int xp_init_dma_info(struct xsk_buff_pool * pool, struct xsk_dma_map * dma_map)
```

```json
{
  "name": "xp_init_dma_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591067920,
      "name": "xp_init_dma_info",
      "external": false,
      "loc": "net/xdp/xsk_buff_pool.c:358",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591067920,
      "name": "xp_init_dma_info",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int xp_init_dma_info(struct xsk_buff_pool * pool, struct xsk_dma_map * dma_map)
```

```json
{
  "name": "xp_init_dma_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xp_init_dma_info",
      "external": false,
      "loc": "net/xdp/xsk_buff_pool.c:358",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591910752,
      "name": "xp_init_dma_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071592751390,
      "name": "xp_init_dma_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
int xp_init_dma_info(struct xsk_buff_pool * pool, struct xsk_dma_map * dma_map)
```

```json
{
  "name": "xp_init_dma_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xp_init_dma_info",
      "external": false,
      "loc": "net/xdp/xsk_buff_pool.c:380",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk_buff_pool.c:xp_dma_map",
        "net/xdp/xsk_buff_pool.c:xp_dma_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593632144,
      "name": "xp_init_dma_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    },
    {
      "addr": 18446744071594638080,
      "name": "xp_init_dma_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
int xp_init_dma_info(struct xsk_buff_pool * pool, struct xsk_dma_map * dma_map)
```

```json
{
  "name": "xp_init_dma_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xp_init_dma_info",
      "external": false,
      "loc": "net/xdp/xsk_buff_pool.c:381",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk_buff_pool.c:xp_dma_map",
        "net/xdp/xsk_buff_pool.c:xp_dma_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595562496,
      "name": "xp_init_dma_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071596367531,
      "name": "xp_init_dma_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
int xp_init_dma_info(struct xsk_buff_pool * pool, struct xsk_dma_map * dma_map)
```

```json
{
  "name": "xp_init_dma_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xp_init_dma_info",
      "external": false,
      "loc": "net/xdp/xsk_buff_pool.c:385",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk_buff_pool.c:xp_dma_map",
        "net/xdp/xsk_buff_pool.c:xp_dma_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596070944,
      "name": "xp_init_dma_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
    },
    {
      "addr": 18446744071596897268,
      "name": "xp_init_dma_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
int xp_init_dma_info(struct xsk_buff_pool * pool, struct xsk_dma_map * dma_map)
```

```json
{
  "name": "xp_init_dma_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xp_init_dma_info",
      "external": false,
      "loc": "net/xdp/xsk_buff_pool.c:409",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk_buff_pool.c:xp_dma_map",
        "net/xdp/xsk_buff_pool.c:xp_dma_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596939040,
      "name": "xp_init_dma_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
    },
    {
      "addr": 18446744071597822597,
      "name": "xp_init_dma_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
int xp_init_dma_info(struct xsk_buff_pool * pool, struct xsk_dma_map * dma_map)
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
