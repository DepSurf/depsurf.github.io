# Function: <code>xen_free_unpopulated_pages</code>

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
void xen_free_unpopulated_pages(unsigned int nr_pages, struct page * * pages)
```

```json
{
  "name": "xen_free_unpopulated_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586461264,
      "name": "xen_free_unpopulated_pages",
      "external": true,
      "loc": "drivers/xen/unpopulated-alloc.c:157",
      "file": "drivers/xen/unpopulated-alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_page_cache_shrink",
        "drivers/xen/grant-table.c:gnttab_page_cache_shrink",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586461264,
      "name": "xen_free_unpopulated_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void xen_free_unpopulated_pages(unsigned int nr_pages, struct page * * pages)
```

```json
{
  "name": "xen_free_unpopulated_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586345024,
      "name": "xen_free_unpopulated_pages",
      "external": true,
      "loc": "drivers/xen/unpopulated-alloc.c:159",
      "file": "drivers/xen/unpopulated-alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_page_cache_shrink",
        "drivers/xen/grant-table.c:gnttab_page_cache_shrink",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586345024,
      "name": "xen_free_unpopulated_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void xen_free_unpopulated_pages(unsigned int nr_pages, struct page * * pages)
```

```json
{
  "name": "xen_free_unpopulated_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586865344,
      "name": "xen_free_unpopulated_pages",
      "external": true,
      "loc": "drivers/xen/unpopulated-alloc.c:159",
      "file": "drivers/xen/unpopulated-alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_page_cache_shrink",
        "drivers/xen/grant-table.c:gnttab_page_cache_shrink",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586865344,
      "name": "xen_free_unpopulated_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xen_free_unpopulated_pages(unsigned int nr_pages, struct page * * pages)
```

```json
{
  "name": "xen_free_unpopulated_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588151472,
      "name": "xen_free_unpopulated_pages",
      "external": true,
      "loc": "drivers/xen/unpopulated-alloc.c:214",
      "file": "drivers/xen/unpopulated-alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_page_cache_shrink",
        "drivers/xen/grant-table.c:gnttab_page_cache_shrink",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588151472,
      "name": "xen_free_unpopulated_pages",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xen_free_unpopulated_pages(unsigned int nr_pages, struct page * * pages)
```

```json
{
  "name": "xen_free_unpopulated_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589545312,
      "name": "xen_free_unpopulated_pages",
      "external": true,
      "loc": "drivers/xen/unpopulated-alloc.c:214",
      "file": "drivers/xen/unpopulated-alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_page_cache_shrink",
        "drivers/xen/grant-table.c:gnttab_page_cache_shrink",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589545312,
      "name": "xen_free_unpopulated_pages",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xen_free_unpopulated_pages(unsigned int nr_pages, struct page * * pages)
```

```json
{
  "name": "xen_free_unpopulated_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589846896,
      "name": "xen_free_unpopulated_pages",
      "external": true,
      "loc": "drivers/xen/unpopulated-alloc.c:214",
      "file": "drivers/xen/unpopulated-alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_page_cache_shrink",
        "drivers/xen/grant-table.c:gnttab_page_cache_shrink",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589846896,
      "name": "xen_free_unpopulated_pages",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xen_free_unpopulated_pages(unsigned int nr_pages, struct page * * pages)
```

```json
{
  "name": "xen_free_unpopulated_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590184016,
      "name": "xen_free_unpopulated_pages",
      "external": true,
      "loc": "drivers/xen/unpopulated-alloc.c:214",
      "file": "drivers/xen/unpopulated-alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_page_cache_shrink",
        "drivers/xen/grant-table.c:gnttab_page_cache_shrink",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590184016,
      "name": "xen_free_unpopulated_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void xen_free_unpopulated_pages(unsigned int nr_pages, struct page * * pages)
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
