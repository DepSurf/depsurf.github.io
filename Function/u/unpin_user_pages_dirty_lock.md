# Function: <code>unpin_user_pages_dirty_lock</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unpin_user_pages_dirty_lock(struct page * * pages, long unsigned int npages, bool make_dirty)
```

```json
{
  "name": "unpin_user_pages_dirty_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581498416,
      "name": "unpin_user_pages_dirty_lock",
      "external": true,
      "loc": "mm/gup.c:273",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:process_vm_rw_single_vec",
        "mm/process_vm_access.c:process_vm_rw_single_vec",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_page_external",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_umem_pin_pages",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581498416,
      "name": "unpin_user_pages_dirty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unpin_user_pages_dirty_lock(struct page * * pages, long unsigned int npages, bool make_dirty)
```

```json
{
  "name": "unpin_user_pages_dirty_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581538960,
      "name": "unpin_user_pages_dirty_lock",
      "external": true,
      "loc": "mm/gup.c:239",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_page_external",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_umem_pin_pages",
        "net/xdp/xdp_umem.c:xdp_put_umem",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581538960,
      "name": "unpin_user_pages_dirty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void unpin_user_pages_dirty_lock(struct page * * pages, long unsigned int npages, bool make_dirty)
```

```json
{
  "name": "unpin_user_pages_dirty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581561152,
      "name": "unpin_user_pages_dirty_lock",
      "external": true,
      "loc": "mm/gup.c:319",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_batch_unpin",
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_umem_pin_pages",
        "net/xdp/xdp_umem.c:xdp_put_umem",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581561152,
      "name": "unpin_user_pages_dirty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
void unpin_user_pages_dirty_lock(struct page * * pages, long unsigned int npages, bool make_dirty)
```

```json
{
  "name": "unpin_user_pages_dirty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581825776,
      "name": "unpin_user_pages_dirty_lock",
      "external": true,
      "loc": "mm/gup.c:331",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_batch_unpin",
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_put_umem",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581825776,
      "name": "unpin_user_pages_dirty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
void unpin_user_pages_dirty_lock(struct page * * pages, long unsigned int npages, bool make_dirty)
```

```json
{
  "name": "unpin_user_pages_dirty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582217936,
      "name": "unpin_user_pages_dirty_lock",
      "external": true,
      "loc": "mm/gup.c:299",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_batch_unpin",
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_umem_pin_pages",
        "net/xdp/xdp_umem.c:xdp_put_umem",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582217936,
      "name": "unpin_user_pages_dirty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 431
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
void unpin_user_pages_dirty_lock(struct page * * pages, long unsigned int npages, bool make_dirty)
```

```json
{
  "name": "unpin_user_pages_dirty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582707136,
      "name": "unpin_user_pages_dirty_lock",
      "external": true,
      "loc": "mm/gup.c:314",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_put_umem",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582707136,
      "name": "unpin_user_pages_dirty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 431
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
void unpin_user_pages_dirty_lock(struct page * * pages, long unsigned int npages, bool make_dirty)
```

```json
{
  "name": "unpin_user_pages_dirty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582921616,
      "name": "unpin_user_pages_dirty_lock",
      "external": true,
      "loc": "mm/gup.c:358",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_user.c:user_event_enabler_write",
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_put_umem",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582921616,
      "name": "unpin_user_pages_dirty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
void unpin_user_pages_dirty_lock(struct page * * pages, long unsigned int npages, bool make_dirty)
```

```json
{
  "name": "unpin_user_pages_dirty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583095744,
      "name": "unpin_user_pages_dirty_lock",
      "external": true,
      "loc": "mm/gup.c:358",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_user.c:user_event_enabler_write",
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_put_umem",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583095744,
      "name": "unpin_user_pages_dirty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
void unpin_user_pages_dirty_lock(struct page * * pages, long unsigned int npages, bool make_dirty)
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
