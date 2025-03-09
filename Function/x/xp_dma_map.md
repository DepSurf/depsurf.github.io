# Function: <code>xp_dma_map</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int xp_dma_map(struct xsk_buff_pool * pool, struct device * dev, long unsigned int attrs, struct page * * pages, u32 nr_pages)
```

```json
{
  "name": "xp_dma_map",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591074016,
      "name": "xp_dma_map",
      "external": true,
      "loc": "net/xdp/xsk_buff_pool.c:124",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591074016,
      "name": "xp_dma_map.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
    },
    {
      "addr": 18446744071591074352,
      "name": "xp_dma_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int xp_dma_map(struct xsk_buff_pool * pool, struct device * dev, long unsigned int attrs, struct page * * pages, u32 nr_pages)
```

```json
{
  "name": "xp_dma_map",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591138336,
      "name": "xp_dma_map",
      "external": true,
      "loc": "net/xdp/xsk_buff_pool.c:379",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591138336,
      "name": "xp_dma_map.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
    },
    {
      "addr": 18446744071591139040,
      "name": "xp_dma_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int xp_dma_map(struct xsk_buff_pool * pool, struct device * dev, long unsigned int attrs, struct page * * pages, u32 nr_pages)
```

```json
{
  "name": "xp_dma_map",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591068704,
      "name": "xp_dma_map",
      "external": true,
      "loc": "net/xdp/xsk_buff_pool.c:373",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591068704,
      "name": "xp_dma_map.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
    },
    {
      "addr": 18446744071591069376,
      "name": "xp_dma_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int xp_dma_map(struct xsk_buff_pool * pool, struct device * dev, long unsigned int attrs, struct page * * pages, u32 nr_pages)
```

```json
{
  "name": "xp_dma_map",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591912464,
      "name": "xp_dma_map",
      "external": true,
      "loc": "net/xdp/xsk_buff_pool.c:373",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591911808,
      "name": "xp_dma_map.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 471
    },
    {
      "addr": 18446744071592751511,
      "name": "xp_dma_map.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071591912464,
      "name": "xp_dma_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int xp_dma_map(struct xsk_buff_pool * pool, struct device * dev, long unsigned int attrs, struct page * * pages, u32 nr_pages)
```

```json
{
  "name": "xp_dma_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xp_dma_map",
      "external": true,
      "loc": "net/xdp/xsk_buff_pool.c:395",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594638216,
      "name": "xp_dma_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071593632992,
      "name": "xp_dma_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 767
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
int xp_dma_map(struct xsk_buff_pool * pool, struct device * dev, long unsigned int attrs, struct page * * pages, u32 nr_pages)
```

```json
{
  "name": "xp_dma_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xp_dma_map",
      "external": true,
      "loc": "net/xdp/xsk_buff_pool.c:406",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596367685,
      "name": "xp_dma_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071595563520,
      "name": "xp_dma_map",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int xp_dma_map(struct xsk_buff_pool * pool, struct device * dev, long unsigned int attrs, struct page * * pages, u32 nr_pages)
```

```json
{
  "name": "xp_dma_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xp_dma_map",
      "external": true,
      "loc": "net/xdp/xsk_buff_pool.c:410",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596897422,
      "name": "xp_dma_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071596071936,
      "name": "xp_dma_map",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int xp_dma_map(struct xsk_buff_pool * pool, struct device * dev, long unsigned int attrs, struct page * * pages, u32 nr_pages)
```

```json
{
  "name": "xp_dma_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xp_dma_map",
      "external": true,
      "loc": "net/xdp/xsk_buff_pool.c:434",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597822793,
      "name": "xp_dma_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071596940368,
      "name": "xp_dma_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 723
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
int xp_dma_map(struct xsk_buff_pool * pool, struct device * dev, long unsigned int attrs, struct page * * pages, u32 nr_pages)
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
