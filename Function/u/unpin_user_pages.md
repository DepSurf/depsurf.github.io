# Function: <code>unpin_user_pages</code>

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
void unpin_user_pages(struct page * * pages, long unsigned int npages)
```

```json
{
  "name": "unpin_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581498160,
      "name": "unpin_user_pages",
      "external": true,
      "loc": "mm/gup.c:327",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/frame_vector.c:put_vaddr_frames",
        "fs/io_uring.c:io_sqe_buffer_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581498160,
      "name": "unpin_user_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void unpin_user_pages(struct page * * pages, long unsigned int npages)
```

```json
{
  "name": "unpin_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581538864,
      "name": "unpin_user_pages",
      "external": true,
      "loc": "mm/gup.c:293",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:lockless_pages_from_mm",
        "mm/frame_vector.c:put_vaddr_frames",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581538864,
      "name": "unpin_user_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void unpin_user_pages(struct page * * pages, long unsigned int npages)
```

```json
{
  "name": "unpin_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581560144,
      "name": "unpin_user_pages",
      "external": true,
      "loc": "mm/gup.c:404",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:lockless_pages_from_mm",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/gup.c:unpin_user_pages_dirty_lock",
        "fs/io_uring.c:io_sqe_buffer_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581560144,
      "name": "unpin_user_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
void unpin_user_pages(struct page * * pages, long unsigned int npages)
```

```json
{
  "name": "unpin_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581824768,
      "name": "unpin_user_pages",
      "external": true,
      "loc": "mm/gup.c:416",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:lockless_pages_from_mm",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/gup.c:unpin_user_pages_dirty_lock",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581824768,
      "name": "unpin_user_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
void unpin_user_pages(struct page * * pages, long unsigned int npages)
```

```json
{
  "name": "unpin_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582217168,
      "name": "unpin_user_pages",
      "external": true,
      "loc": "mm/gup.c:410",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/gup.c:unpin_user_pages_dirty_lock",
        "io_uring/io_uring.c:io_sqe_buffer_register",
        "io_uring/io_uring.c:io_pin_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582217168,
      "name": "unpin_user_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
void unpin_user_pages(struct page * * pages, long unsigned int npages)
```

```json
{
  "name": "unpin_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582705552,
      "name": "unpin_user_pages",
      "external": true,
      "loc": "mm/gup.c:425",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:unpin_user_pages_dirty_lock",
        "io_uring/rsrc.c:io_sqe_buffer_register",
        "io_uring/rsrc.c:io_pin_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582705552,
      "name": "unpin_user_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
void unpin_user_pages(struct page * * pages, long unsigned int npages)
```

```json
{
  "name": "unpin_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582920848,
      "name": "unpin_user_pages",
      "external": true,
      "loc": "mm/gup.c:469",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:unpin_user_pages_dirty_lock",
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/direct-io.c:__blockdev_direct_IO",
        "io_uring/rsrc.c:io_sqe_buffer_register",
        "io_uring/rsrc.c:io_sqe_buffer_register",
        "io_uring/rsrc.c:io_pin_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582920848,
      "name": "unpin_user_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
void unpin_user_pages(struct page * * pages, long unsigned int npages)
```

```json
{
  "name": "unpin_user_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583094976,
      "name": "unpin_user_pages",
      "external": true,
      "loc": "mm/gup.c:469",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:unpin_user_pages_dirty_lock",
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/direct-io.c:__blockdev_direct_IO",
        "io_uring/rsrc.c:io_sqe_buffer_register",
        "io_uring/rsrc.c:io_sqe_buffer_register",
        "io_uring/rsrc.c:io_pin_pages",
        "drivers/iommu/iommufd/iova_bitmap.c:iova_bitmap_for_each",
        "drivers/iommu/iommufd/iova_bitmap.c:iova_bitmap_for_each",
        "drivers/iommu/iommufd/iova_bitmap.c:iova_bitmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583094976,
      "name": "unpin_user_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void unpin_user_pages(struct page * * pages, long unsigned int npages)
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
