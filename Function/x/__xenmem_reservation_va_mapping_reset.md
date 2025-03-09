# Function: <code>__xenmem_reservation_va_mapping_reset</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __xenmem_reservation_va_mapping_reset(long unsigned int count, struct page * * pages)
```

```json
{
  "name": "__xenmem_reservation_va_mapping_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585201968,
      "name": "__xenmem_reservation_va_mapping_reset",
      "external": true,
      "loc": "drivers/xen/mem-reservation.c:63",
      "file": "drivers/xen/mem-reservation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/balloon.c:decrease_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585201968,
      "name": "__xenmem_reservation_va_mapping_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __xenmem_reservation_va_mapping_reset(long unsigned int count, struct page * * pages)
```

```json
{
  "name": "__xenmem_reservation_va_mapping_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585414464,
      "name": "__xenmem_reservation_va_mapping_reset",
      "external": true,
      "loc": "drivers/xen/mem-reservation.c:63",
      "file": "drivers/xen/mem-reservation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/balloon.c:decrease_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585414464,
      "name": "__xenmem_reservation_va_mapping_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __xenmem_reservation_va_mapping_reset(long unsigned int count, struct page * * pages)
```

```json
{
  "name": "__xenmem_reservation_va_mapping_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585555184,
      "name": "__xenmem_reservation_va_mapping_reset",
      "external": true,
      "loc": "drivers/xen/mem-reservation.c:63",
      "file": "drivers/xen/mem-reservation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/balloon.c:decrease_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585555184,
      "name": "__xenmem_reservation_va_mapping_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void __xenmem_reservation_va_mapping_reset(long unsigned int count, struct page * * pages)
```

```json
{
  "name": "__xenmem_reservation_va_mapping_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586273856,
      "name": "__xenmem_reservation_va_mapping_reset",
      "external": true,
      "loc": "drivers/xen/mem-reservation.c:63",
      "file": "drivers/xen/mem-reservation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/balloon.c:decrease_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586273856,
      "name": "__xenmem_reservation_va_mapping_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void __xenmem_reservation_va_mapping_reset(long unsigned int count, struct page * * pages)
```

```json
{
  "name": "__xenmem_reservation_va_mapping_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586390976,
      "name": "__xenmem_reservation_va_mapping_reset",
      "external": true,
      "loc": "drivers/xen/mem-reservation.c:63",
      "file": "drivers/xen/mem-reservation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/balloon.c:decrease_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586390976,
      "name": "__xenmem_reservation_va_mapping_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void __xenmem_reservation_va_mapping_reset(long unsigned int count, struct page * * pages)
```

```json
{
  "name": "__xenmem_reservation_va_mapping_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586274944,
      "name": "__xenmem_reservation_va_mapping_reset",
      "external": true,
      "loc": "drivers/xen/mem-reservation.c:63",
      "file": "drivers/xen/mem-reservation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/balloon.c:decrease_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586274944,
      "name": "__xenmem_reservation_va_mapping_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void __xenmem_reservation_va_mapping_reset(long unsigned int count, struct page * * pages)
```

```json
{
  "name": "__xenmem_reservation_va_mapping_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586787552,
      "name": "__xenmem_reservation_va_mapping_reset",
      "external": true,
      "loc": "drivers/xen/mem-reservation.c:63",
      "file": "drivers/xen/mem-reservation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/balloon.c:decrease_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586787552,
      "name": "__xenmem_reservation_va_mapping_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void __xenmem_reservation_va_mapping_reset(long unsigned int count, struct page * * pages)
```

```json
{
  "name": "__xenmem_reservation_va_mapping_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588067952,
      "name": "__xenmem_reservation_va_mapping_reset",
      "external": true,
      "loc": "drivers/xen/mem-reservation.c:58",
      "file": "drivers/xen/mem-reservation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/balloon.c:decrease_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588067952,
      "name": "__xenmem_reservation_va_mapping_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void __xenmem_reservation_va_mapping_reset(long unsigned int count, struct page * * pages)
```

```json
{
  "name": "__xenmem_reservation_va_mapping_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589449280,
      "name": "__xenmem_reservation_va_mapping_reset",
      "external": true,
      "loc": "drivers/xen/mem-reservation.c:58",
      "file": "drivers/xen/mem-reservation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/balloon.c:decrease_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589449280,
      "name": "__xenmem_reservation_va_mapping_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void __xenmem_reservation_va_mapping_reset(long unsigned int count, struct page * * pages)
```

```json
{
  "name": "__xenmem_reservation_va_mapping_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589748800,
      "name": "__xenmem_reservation_va_mapping_reset",
      "external": true,
      "loc": "drivers/xen/mem-reservation.c:58",
      "file": "drivers/xen/mem-reservation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/balloon.c:decrease_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589748800,
      "name": "__xenmem_reservation_va_mapping_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void __xenmem_reservation_va_mapping_reset(long unsigned int count, struct page * * pages)
```

```json
{
  "name": "__xenmem_reservation_va_mapping_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590086784,
      "name": "__xenmem_reservation_va_mapping_reset",
      "external": true,
      "loc": "drivers/xen/mem-reservation.c:58",
      "file": "drivers/xen/mem-reservation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/balloon.c:decrease_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590086784,
      "name": "__xenmem_reservation_va_mapping_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void __xenmem_reservation_va_mapping_reset(long unsigned int count, struct page * * pages)
```

```json
{
  "name": "__xenmem_reservation_va_mapping_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585316896,
      "name": "__xenmem_reservation_va_mapping_reset",
      "external": true,
      "loc": "drivers/xen/mem-reservation.c:63",
      "file": "drivers/xen/mem-reservation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/balloon.c:decrease_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585316896,
      "name": "__xenmem_reservation_va_mapping_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void __xenmem_reservation_va_mapping_reset(long unsigned int count, struct page * * pages)
```

```json
{
  "name": "__xenmem_reservation_va_mapping_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585505584,
      "name": "__xenmem_reservation_va_mapping_reset",
      "external": true,
      "loc": "drivers/xen/mem-reservation.c:63",
      "file": "drivers/xen/mem-reservation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/balloon.c:decrease_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585505584,
      "name": "__xenmem_reservation_va_mapping_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void __xenmem_reservation_va_mapping_reset(long unsigned int count, struct page * * pages)
```

```json
{
  "name": "__xenmem_reservation_va_mapping_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585613568,
      "name": "__xenmem_reservation_va_mapping_reset",
      "external": true,
      "loc": "drivers/xen/mem-reservation.c:63",
      "file": "drivers/xen/mem-reservation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/balloon.c:decrease_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585613568,
      "name": "__xenmem_reservation_va_mapping_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void __xenmem_reservation_va_mapping_reset(long unsigned int count, struct page * * pages)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void __xenmem_reservation_va_mapping_reset(long unsigned int count, struct page * * pages)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __xenmem_reservation_va_mapping_reset(long unsigned int count, struct page * * pages)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __xenmem_reservation_va_mapping_reset(long unsigned int count, struct page * * pages)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __xenmem_reservation_va_mapping_reset(long unsigned int count, struct page * * pages)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void __xenmem_reservation_va_mapping_reset(long unsigned int count, struct page * * pages)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
