# Function: <code>gen_pool_dma_zalloc_align</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void * gen_pool_dma_zalloc_align(struct gen_pool * pool, size_t size, dma_addr_t * dma, int align)
```

```json
{
  "name": "gen_pool_dma_zalloc_align",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584181776,
      "name": "gen_pool_dma_zalloc_align",
      "external": true,
      "loc": "lib/genalloc.c:464",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:td_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584181776,
      "name": "gen_pool_dma_zalloc_align",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void * gen_pool_dma_zalloc_align(struct gen_pool * pool, size_t size, dma_addr_t * dma, int align)
```

```json
{
  "name": "gen_pool_dma_zalloc_align",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584315472,
      "name": "gen_pool_dma_zalloc_align",
      "external": true,
      "loc": "lib/genalloc.c:464",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:td_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584315472,
      "name": "gen_pool_dma_zalloc_align",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void * gen_pool_dma_zalloc_align(struct gen_pool * pool, size_t size, dma_addr_t * dma, int align)
```

```json
{
  "name": "gen_pool_dma_zalloc_align",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584727568,
      "name": "gen_pool_dma_zalloc_align",
      "external": true,
      "loc": "lib/genalloc.c:464",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:td_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584727568,
      "name": "gen_pool_dma_zalloc_align",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void * gen_pool_dma_zalloc_align(struct gen_pool * pool, size_t size, dma_addr_t * dma, int align)
```

```json
{
  "name": "gen_pool_dma_zalloc_align",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584840800,
      "name": "gen_pool_dma_zalloc_align",
      "external": true,
      "loc": "lib/genalloc.c:465",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:td_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584840800,
      "name": "gen_pool_dma_zalloc_align",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void * gen_pool_dma_zalloc_align(struct gen_pool * pool, size_t size, dma_addr_t * dma, int align)
```

```json
{
  "name": "gen_pool_dma_zalloc_align",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584885456,
      "name": "gen_pool_dma_zalloc_align",
      "external": true,
      "loc": "lib/genalloc.c:466",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:td_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584885456,
      "name": "gen_pool_dma_zalloc_align",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void * gen_pool_dma_zalloc_align(struct gen_pool * pool, size_t size, dma_addr_t * dma, int align)
```

```json
{
  "name": "gen_pool_dma_zalloc_align",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585311296,
      "name": "gen_pool_dma_zalloc_align",
      "external": true,
      "loc": "lib/genalloc.c:466",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:td_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585311296,
      "name": "gen_pool_dma_zalloc_align",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void * gen_pool_dma_zalloc_align(struct gen_pool * pool, size_t size, dma_addr_t * dma, int align)
```

```json
{
  "name": "gen_pool_dma_zalloc_align",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586168608,
      "name": "gen_pool_dma_zalloc_align",
      "external": true,
      "loc": "lib/genalloc.c:466",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:td_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586168608,
      "name": "gen_pool_dma_zalloc_align",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void * gen_pool_dma_zalloc_align(struct gen_pool * pool, size_t size, dma_addr_t * dma, int align)
```

```json
{
  "name": "gen_pool_dma_zalloc_align",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587163168,
      "name": "gen_pool_dma_zalloc_align",
      "external": true,
      "loc": "lib/genalloc.c:466",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:td_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587163168,
      "name": "gen_pool_dma_zalloc_align",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void * gen_pool_dma_zalloc_align(struct gen_pool * pool, size_t size, dma_addr_t * dma, int align)
```

```json
{
  "name": "gen_pool_dma_zalloc_align",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587426000,
      "name": "gen_pool_dma_zalloc_align",
      "external": true,
      "loc": "lib/genalloc.c:464",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:td_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587426000,
      "name": "gen_pool_dma_zalloc_align",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void * gen_pool_dma_zalloc_align(struct gen_pool * pool, size_t size, dma_addr_t * dma, int align)
```

```json
{
  "name": "gen_pool_dma_zalloc_align",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587761056,
      "name": "gen_pool_dma_zalloc_align",
      "external": true,
      "loc": "lib/genalloc.c:466",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:td_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587761056,
      "name": "gen_pool_dma_zalloc_align",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void * gen_pool_dma_zalloc_align(struct gen_pool * pool, size_t size, dma_addr_t * dma, int align)
```

```json
{
  "name": "gen_pool_dma_zalloc_align",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496203792,
      "name": "gen_pool_dma_zalloc_align",
      "external": true,
      "loc": "lib/genalloc.c:464",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:td_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496203792,
      "name": "gen_pool_dma_zalloc_align",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void * gen_pool_dma_zalloc_align(struct gen_pool * pool, size_t size, dma_addr_t * dma, int align)
```

```json
{
  "name": "gen_pool_dma_zalloc_align",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229528340,
      "name": "gen_pool_dma_zalloc_align",
      "external": true,
      "loc": "lib/genalloc.c:464",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:td_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229528340,
      "name": "gen_pool_dma_zalloc_align",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void * gen_pool_dma_zalloc_align(struct gen_pool * pool, size_t size, dma_addr_t * dma, int align)
```

```json
{
  "name": "gen_pool_dma_zalloc_align",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290486944,
      "name": "gen_pool_dma_zalloc_align",
      "external": true,
      "loc": "lib/genalloc.c:464",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:td_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290486944,
      "name": "gen_pool_dma_zalloc_align",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void * gen_pool_dma_zalloc_align(struct gen_pool * pool, size_t size, dma_addr_t * dma, int align)
```

```json
{
  "name": "gen_pool_dma_zalloc_align",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275254384,
      "name": "gen_pool_dma_zalloc_align",
      "external": true,
      "loc": "lib/genalloc.c:464",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:td_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275254384,
      "name": "gen_pool_dma_zalloc_align",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void * gen_pool_dma_zalloc_align(struct gen_pool * pool, size_t size, dma_addr_t * dma, int align)
```

```json
{
  "name": "gen_pool_dma_zalloc_align",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584284208,
      "name": "gen_pool_dma_zalloc_align",
      "external": true,
      "loc": "lib/genalloc.c:464",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:td_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584284208,
      "name": "gen_pool_dma_zalloc_align",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void * gen_pool_dma_zalloc_align(struct gen_pool * pool, size_t size, dma_addr_t * dma, int align)
```

```json
{
  "name": "gen_pool_dma_zalloc_align",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584219408,
      "name": "gen_pool_dma_zalloc_align",
      "external": true,
      "loc": "lib/genalloc.c:464",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584219408,
      "name": "gen_pool_dma_zalloc_align",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void * gen_pool_dma_zalloc_align(struct gen_pool * pool, size_t size, dma_addr_t * dma, int align)
```

```json
{
  "name": "gen_pool_dma_zalloc_align",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584267120,
      "name": "gen_pool_dma_zalloc_align",
      "external": true,
      "loc": "lib/genalloc.c:464",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:td_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584267120,
      "name": "gen_pool_dma_zalloc_align",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void * gen_pool_dma_zalloc_align(struct gen_pool * pool, size_t size, dma_addr_t * dma, int align)
```

```json
{
  "name": "gen_pool_dma_zalloc_align",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584373104,
      "name": "gen_pool_dma_zalloc_align",
      "external": true,
      "loc": "lib/genalloc.c:464",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:td_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584373104,
      "name": "gen_pool_dma_zalloc_align",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void * gen_pool_dma_zalloc_align(struct gen_pool * pool, size_t size, dma_addr_t * dma, int align)
```
</details>
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
