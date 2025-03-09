# Function: <code>free_xenballooned_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void free_xenballooned_pages(int nr_pages, struct page * * pages)
```

```json
{
  "name": "free_xenballooned_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583852448,
      "name": "free_xenballooned_pages",
      "external": true,
      "loc": "drivers/xen/balloon.c:670",
      "file": "drivers/xen/balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:xen_pvh_gnttab_setup",
        "drivers/xen/grant-table.c:gnttab_free_pages",
        "drivers/xen/balloon.c:alloc_xenballooned_pages",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583852448,
      "name": "free_xenballooned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void free_xenballooned_pages(int nr_pages, struct page * * pages)
```

```json
{
  "name": "free_xenballooned_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584182000,
      "name": "free_xenballooned_pages",
      "external": true,
      "loc": "drivers/xen/balloon.c:692",
      "file": "drivers/xen/balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_free_pages",
        "drivers/xen/balloon.c:alloc_xenballooned_pages",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584182000,
      "name": "free_xenballooned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void free_xenballooned_pages(int nr_pages, struct page * * pages)
```

```json
{
  "name": "free_xenballooned_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584363360,
      "name": "free_xenballooned_pages",
      "external": true,
      "loc": "drivers/xen/balloon.c:690",
      "file": "drivers/xen/balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_free_pages",
        "drivers/xen/balloon.c:alloc_xenballooned_pages",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584363360,
      "name": "free_xenballooned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void free_xenballooned_pages(int nr_pages, struct page * * pages)
```

```json
{
  "name": "free_xenballooned_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584444912,
      "name": "free_xenballooned_pages",
      "external": true,
      "loc": "drivers/xen/balloon.c:691",
      "file": "drivers/xen/balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_free_pages",
        "drivers/xen/balloon.c:alloc_xenballooned_pages",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584444912,
      "name": "free_xenballooned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void free_xenballooned_pages(int nr_pages, struct page * * pages)
```

```json
{
  "name": "free_xenballooned_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584854528,
      "name": "free_xenballooned_pages",
      "external": true,
      "loc": "drivers/xen/balloon.c:738",
      "file": "drivers/xen/balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_free_pages",
        "drivers/xen/balloon.c:alloc_xenballooned_pages",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584854528,
      "name": "free_xenballooned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void free_xenballooned_pages(int nr_pages, struct page * * pages)
```

```json
{
  "name": "free_xenballooned_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585085600,
      "name": "free_xenballooned_pages",
      "external": true,
      "loc": "drivers/xen/balloon.c:738",
      "file": "drivers/xen/balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_free_pages",
        "drivers/xen/balloon.c:alloc_xenballooned_pages",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585085600,
      "name": "free_xenballooned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void free_xenballooned_pages(int nr_pages, struct page * * pages)
```

```json
{
  "name": "free_xenballooned_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585196224,
      "name": "free_xenballooned_pages",
      "external": true,
      "loc": "drivers/xen/balloon.c:633",
      "file": "drivers/xen/balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/balloon.c:alloc_xenballooned_pages",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585196224,
      "name": "free_xenballooned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void free_xenballooned_pages(int nr_pages, struct page * * pages)
```

```json
{
  "name": "free_xenballooned_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585408592,
      "name": "free_xenballooned_pages",
      "external": true,
      "loc": "drivers/xen/balloon.c:649",
      "file": "drivers/xen/balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/balloon.c:alloc_xenballooned_pages",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585408592,
      "name": "free_xenballooned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void free_xenballooned_pages(int nr_pages, struct page * * pages)
```

```json
{
  "name": "free_xenballooned_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585549344,
      "name": "free_xenballooned_pages",
      "external": true,
      "loc": "drivers/xen/balloon.c:644",
      "file": "drivers/xen/balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/balloon.c:alloc_xenballooned_pages",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585549344,
      "name": "free_xenballooned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void free_xenballooned_pages(int nr_pages, struct page * * pages)
```

```json
{
  "name": "free_xenballooned_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586268128,
      "name": "free_xenballooned_pages",
      "external": true,
      "loc": "drivers/xen/balloon.c:650",
      "file": "drivers/xen/balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/balloon.c:alloc_xenballooned_pages",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586268128,
      "name": "free_xenballooned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void free_xenballooned_pages(int nr_pages, struct page * * pages)
```

```json
{
  "name": "free_xenballooned_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586387488,
      "name": "free_xenballooned_pages",
      "external": true,
      "loc": "drivers/xen/balloon.c:635",
      "file": "drivers/xen/balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/balloon.c:alloc_xenballooned_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586387488,
      "name": "free_xenballooned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void free_xenballooned_pages(int nr_pages, struct page * * pages)
```

```json
{
  "name": "free_xenballooned_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586271264,
      "name": "free_xenballooned_pages",
      "external": true,
      "loc": "drivers/xen/balloon.c:635",
      "file": "drivers/xen/balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/balloon.c:alloc_xenballooned_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586271264,
      "name": "free_xenballooned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void free_xenballooned_pages(int nr_pages, struct page * * pages)
```

```json
{
  "name": "free_xenballooned_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586783280,
      "name": "free_xenballooned_pages",
      "external": true,
      "loc": "drivers/xen/balloon.c:669",
      "file": "drivers/xen/balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/balloon.c:alloc_xenballooned_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586783280,
      "name": "free_xenballooned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void free_xenballooned_pages(int nr_pages, struct page * * pages)
```

```json
{
  "name": "free_xenballooned_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498211128,
      "name": "free_xenballooned_pages",
      "external": true,
      "loc": "drivers/xen/balloon.c:644",
      "file": "drivers/xen/balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/balloon.c:alloc_xenballooned_pages",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498211128,
      "name": "free_xenballooned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void free_xenballooned_pages(int nr_pages, struct page * * pages)
```

```json
{
  "name": "free_xenballooned_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585312256,
      "name": "free_xenballooned_pages",
      "external": true,
      "loc": "drivers/xen/balloon.c:644",
      "file": "drivers/xen/balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/balloon.c:alloc_xenballooned_pages",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585312256,
      "name": "free_xenballooned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void free_xenballooned_pages(int nr_pages, struct page * * pages)
```

```json
{
  "name": "free_xenballooned_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585499744,
      "name": "free_xenballooned_pages",
      "external": true,
      "loc": "drivers/xen/balloon.c:644",
      "file": "drivers/xen/balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/balloon.c:alloc_xenballooned_pages",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585499744,
      "name": "free_xenballooned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void free_xenballooned_pages(int nr_pages, struct page * * pages)
```

```json
{
  "name": "free_xenballooned_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585607792,
      "name": "free_xenballooned_pages",
      "external": true,
      "loc": "drivers/xen/balloon.c:644",
      "file": "drivers/xen/balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/balloon.c:alloc_xenballooned_pages",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585607792,
      "name": "free_xenballooned_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void free_xenballooned_pages(int nr_pages, struct page * * pages)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void free_xenballooned_pages(int nr_pages, struct page * * pages)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void free_xenballooned_pages(int nr_pages, struct page * * pages)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void free_xenballooned_pages(int nr_pages, struct page * * pages)
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
void free_xenballooned_pages(int nr_pages, struct page * * pages)
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
