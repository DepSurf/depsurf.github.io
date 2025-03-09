# Function: <code>vmap_range_noflush</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int vmap_range_noflush(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot, unsigned int max_page_shift)
```

```json
{
  "name": "vmap_range_noflush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581695680,
      "name": "vmap_range_noflush",
      "external": false,
      "loc": "mm/vmalloc.c:256",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vmap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581695680,
      "name": "vmap_range_noflush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1567
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
int vmap_range_noflush(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot, unsigned int max_page_shift)
```

```json
{
  "name": "vmap_range_noflush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vmap_range_noflush",
      "external": false,
      "loc": "mm/vmalloc.c:285",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:ioremap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581967856,
      "name": "vmap_range_noflush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1607
    },
    {
      "addr": 18446744071592201702,
      "name": "vmap_range_noflush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
int vmap_range_noflush(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot, unsigned int max_page_shift)
```

```json
{
  "name": "vmap_range_noflush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vmap_range_noflush",
      "external": false,
      "loc": "mm/vmalloc.c:286",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vmap_pages_range_noflush",
        "mm/vmalloc.c:vmap_pages_range_noflush",
        "mm/vmalloc.c:ioremap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582390848,
      "name": "vmap_range_noflush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1768
    },
    {
      "addr": 18446744071593978507,
      "name": "vmap_range_noflush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
int vmap_range_noflush(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot, unsigned int max_page_shift)
```

```json
{
  "name": "vmap_range_noflush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vmap_range_noflush",
      "external": false,
      "loc": "mm/vmalloc.c:289",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vmap_pages_range_noflush",
        "mm/vmalloc.c:__vmap_pages_range_noflush",
        "mm/vmalloc.c:ioremap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582897136,
      "name": "vmap_range_noflush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1733
    },
    {
      "addr": 18446744071596034456,
      "name": "vmap_range_noflush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
int vmap_range_noflush(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot, unsigned int max_page_shift)
```

```json
{
  "name": "vmap_range_noflush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vmap_range_noflush",
      "external": false,
      "loc": "mm/vmalloc.c:278",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vmap_pages_range_noflush",
        "mm/vmalloc.c:__vmap_pages_range_noflush",
        "mm/vmalloc.c:ioremap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583112272,
      "name": "vmap_range_noflush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1734
    },
    {
      "addr": 18446744071596556445,
      "name": "vmap_range_noflush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
int vmap_range_noflush(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot, unsigned int max_page_shift)
```

```json
{
  "name": "vmap_range_noflush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vmap_range_noflush",
      "external": false,
      "loc": "mm/vmalloc.c:278",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vmap_pages_range_noflush",
        "mm/vmalloc.c:__vmap_pages_range_noflush",
        "mm/vmalloc.c:ioremap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583294640,
      "name": "vmap_range_noflush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1734
    },
    {
      "addr": 18446744071597460700,
      "name": "vmap_range_noflush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int vmap_range_noflush(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot, unsigned int max_page_shift)
```
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
