# Function: <code>unpin_user_page</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void unpin_user_page(struct page * page)
```

```json
{
  "name": "unpin_user_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581497984,
      "name": "unpin_user_page",
      "external": true,
      "loc": "mm/gup.c:224",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:undo_dev_pagemap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581497984,
      "name": "unpin_user_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void unpin_user_page(struct page * page)
```

```json
{
  "name": "unpin_user_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581539149,
      "name": "unpin_user_page",
      "external": true,
      "loc": "mm/gup.c:211",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/gup.c:undo_dev_pagemap"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581538816,
      "name": "unpin_user_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unpin_user_page(struct page * page)
```

```json
{
  "name": "unpin_user_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581561917,
      "name": "unpin_user_page",
      "external": true,
      "loc": "mm/gup.c:239",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/gup.c:undo_dev_pagemap"
      ],
      "caller_func": [
        "fs/io_uring.c:io_buffer_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581560096,
      "name": "unpin_user_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unpin_user_page(struct page * page)
```

```json
{
  "name": "unpin_user_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581826541,
      "name": "unpin_user_page",
      "external": true,
      "loc": "mm/gup.c:251",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/gup.c:undo_dev_pagemap"
      ],
      "caller_func": [
        "fs/io_uring.c:io_buffer_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581824720,
      "name": "unpin_user_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void unpin_user_page(struct page * page)
```

```json
{
  "name": "unpin_user_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582218513,
      "name": "unpin_user_page",
      "external": true,
      "loc": "mm/gup.c:240",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/gup.c:undo_dev_pagemap"
      ],
      "caller_func": [
        "io_uring/io_uring.c:__io_uring_register",
        "io_uring/io_uring.c:io_buffer_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582218368,
      "name": "unpin_user_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void unpin_user_page(struct page * page)
```

```json
{
  "name": "unpin_user_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582707633,
      "name": "unpin_user_page",
      "external": true,
      "loc": "mm/gup.c:255",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/gup.c:undo_dev_pagemap",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/gup.c:check_and_migrate_movable_pages"
      ],
      "caller_func": [
        "io_uring/kbuf.c:io_unregister_pbuf_ring",
        "io_uring/kbuf.c:io_destroy_buffers",
        "io_uring/kbuf.c:io_destroy_buffers",
        "io_uring/rsrc.c:io_buffer_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582708016,
      "name": "unpin_user_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void unpin_user_page(struct page * page)
```

```json
{
  "name": "unpin_user_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582922129,
      "name": "unpin_user_page",
      "external": true,
      "loc": "mm/gup.c:272",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/gup.c:undo_dev_pagemap",
        "mm/gup.c:migrate_longterm_unpinnable_pages",
        "mm/gup.c:migrate_longterm_unpinnable_pages"
      ],
      "caller_func": [
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "block/bio.c:__bio_iov_iter_get_pages",
        "block/bio.c:__bio_iov_iter_get_pages",
        "block/bio.c:__bio_release_pages",
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-map.c:bio_map_user_iov",
        "io_uring/io_uring.c:__io_uaddr_map",
        "io_uring/rsrc.c:io_buffer_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582922512,
      "name": "unpin_user_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void unpin_user_page(struct page * page)
```

```json
{
  "name": "unpin_user_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583096241,
      "name": "unpin_user_page",
      "external": true,
      "loc": "mm/gup.c:272",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/gup.c:undo_dev_pagemap",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/gup.c:check_and_migrate_movable_pages"
      ],
      "caller_func": [
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "block/bio.c:__bio_iov_iter_get_pages",
        "block/bio.c:__bio_iov_iter_get_pages",
        "block/bio.c:__bio_release_pages",
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-map.c:bio_map_user_iov",
        "block/bio-integrity.c:bio_integrity_map_user",
        "block/bio-integrity.c:bio_integrity_unpin_bvec",
        "io_uring/io_uring.c:__io_uaddr_map",
        "io_uring/rsrc.c:io_buffer_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583096608,
      "name": "unpin_user_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void unpin_user_page(struct page * page)
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
