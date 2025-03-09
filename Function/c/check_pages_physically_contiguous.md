# Function: <code>check_pages_physically_contiguous</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int check_pages_physically_contiguous(long unsigned int xen_pfn, unsigned int offset, size_t length)
```

```json
{
  "name": "check_pages_physically_contiguous",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583908416,
      "name": "check_pages_physically_contiguous",
      "external": false,
      "loc": "drivers/xen/swiotlb-xen.c:109",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583908416,
      "name": "check_pages_physically_contiguous",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
int check_pages_physically_contiguous(long unsigned int xen_pfn, unsigned int offset, size_t length)
```

```json
{
  "name": "check_pages_physically_contiguous",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584239920,
      "name": "check_pages_physically_contiguous",
      "external": false,
      "loc": "drivers/xen/swiotlb-xen.c:109",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584239920,
      "name": "check_pages_physically_contiguous",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
int check_pages_physically_contiguous(long unsigned int xen_pfn, unsigned int offset, size_t length)
```

```json
{
  "name": "check_pages_physically_contiguous",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584421360,
      "name": "check_pages_physically_contiguous",
      "external": false,
      "loc": "drivers/xen/swiotlb-xen.c:109",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584421360,
      "name": "check_pages_physically_contiguous",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
int check_pages_physically_contiguous(long unsigned int xen_pfn, unsigned int offset, size_t length)
```

```json
{
  "name": "check_pages_physically_contiguous",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584505248,
      "name": "check_pages_physically_contiguous",
      "external": false,
      "loc": "drivers/xen/swiotlb-xen.c:111",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584505248,
      "name": "check_pages_physically_contiguous",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
int check_pages_physically_contiguous(long unsigned int xen_pfn, unsigned int offset, size_t length)
```

```json
{
  "name": "check_pages_physically_contiguous",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584915264,
      "name": "check_pages_physically_contiguous",
      "external": false,
      "loc": "drivers/xen/swiotlb-xen.c:111",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584915264,
      "name": "check_pages_physically_contiguous",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
int check_pages_physically_contiguous(long unsigned int xen_pfn, unsigned int offset, size_t length)
```

```json
{
  "name": "check_pages_physically_contiguous",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585146592,
      "name": "check_pages_physically_contiguous",
      "external": false,
      "loc": "drivers/xen/swiotlb-xen.c:97",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585146592,
      "name": "check_pages_physically_contiguous",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
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
int check_pages_physically_contiguous(long unsigned int xen_pfn, unsigned int offset, size_t length)
```

```json
{
  "name": "check_pages_physically_contiguous",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585257600,
      "name": "check_pages_physically_contiguous",
      "external": false,
      "loc": "drivers/xen/swiotlb-xen.c:95",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585257600,
      "name": "check_pages_physically_contiguous",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
    }
  ]
}
```
</details>
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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
int check_pages_physically_contiguous(long unsigned int xen_pfn, unsigned int offset, size_t length)
```
</details>
</li>
</ul>
