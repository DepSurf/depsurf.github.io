# Function: <code>set_page_dirty_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int set_page_dirty_lock(struct page * page)
```

```json
{
  "name": "set_page_dirty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580519184,
      "name": "set_page_dirty_lock",
      "external": true,
      "loc": "mm/page-writeback.c:2587",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__access_remote_vm",
        "fs/direct-io.c:dio_bio_complete",
        "fs/fuse/dev.c:fuse_copy_finish",
        "block/bio.c:bio_set_pages_dirty",
        "block/bio.c:bio_unmap_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580519184,
      "name": "set_page_dirty_lock",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int set_page_dirty_lock(struct page * page)
```

```json
{
  "name": "set_page_dirty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580604752,
      "name": "set_page_dirty_lock",
      "external": true,
      "loc": "mm/page-writeback.c:2632",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__access_remote_vm",
        "fs/direct-io.c:dio_bio_complete",
        "fs/fuse/dev.c:fuse_copy_finish",
        "fs/fuse/file.c:fuse_release_user_pages",
        "block/bio.c:bio_set_pages_dirty",
        "block/bio.c:bio_unmap_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580604752,
      "name": "set_page_dirty_lock",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int set_page_dirty_lock(struct page * page)
```

```json
{
  "name": "set_page_dirty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580671664,
      "name": "set_page_dirty_lock",
      "external": true,
      "loc": "mm/page-writeback.c:2599",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__access_remote_vm",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:dio_bio_complete",
        "fs/fuse/dev.c:fuse_copy_finish",
        "fs/fuse/file.c:fuse_release_user_pages",
        "block/bio.c:bio_set_pages_dirty",
        "block/bio.c:bio_unmap_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580671664,
      "name": "set_page_dirty_lock",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int set_page_dirty_lock(struct page * page)
```

```json
{
  "name": "set_page_dirty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580704864,
      "name": "set_page_dirty_lock",
      "external": true,
      "loc": "mm/page-writeback.c:2602",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__access_remote_vm",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:dio_bio_complete",
        "fs/fuse/dev.c:fuse_copy_finish",
        "fs/fuse/file.c:fuse_release_user_pages",
        "block/bio.c:bio_set_pages_dirty",
        "block/bio.c:bio_unmap_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580704864,
      "name": "set_page_dirty_lock",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int set_page_dirty_lock(struct page * page)
```

```json
{
  "name": "set_page_dirty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580790384,
      "name": "set_page_dirty_lock",
      "external": true,
      "loc": "mm/page-writeback.c:2585",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__access_remote_vm",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:dio_bio_complete",
        "fs/fuse/dev.c:fuse_copy_finish",
        "fs/fuse/file.c:fuse_release_user_pages",
        "block/bio.c:bio_set_pages_dirty",
        "block/bio.c:bio_unmap_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580790384,
      "name": "set_page_dirty_lock",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int set_page_dirty_lock(struct page * page)
```

```json
{
  "name": "set_page_dirty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580926800,
      "name": "set_page_dirty_lock",
      "external": true,
      "loc": "mm/page-writeback.c:2586",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__access_remote_vm",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:dio_bio_complete",
        "fs/fuse/dev.c:fuse_copy_finish",
        "fs/fuse/file.c:fuse_release_user_pages",
        "block/bio.c:bio_set_pages_dirty",
        "block/bio.c:bio_unmap_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580926800,
      "name": "set_page_dirty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int set_page_dirty_lock(struct page * page)
```

```json
{
  "name": "set_page_dirty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581001808,
      "name": "set_page_dirty_lock",
      "external": true,
      "loc": "mm/page-writeback.c:2580",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__access_remote_vm",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:dio_bio_complete",
        "fs/fuse/dev.c:fuse_copy_finish",
        "fs/fuse/file.c:fuse_release_user_pages",
        "block/bio.c:bio_set_pages_dirty",
        "block/bio.c:bio_unmap_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581001808,
      "name": "set_page_dirty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int set_page_dirty_lock(struct page * page)
```

```json
{
  "name": "set_page_dirty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581066096,
      "name": "set_page_dirty_lock",
      "external": true,
      "loc": "mm/page-writeback.c:2588",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__access_remote_vm",
        "fs/fuse/dev.c:fuse_copy_finish",
        "fs/fuse/file.c:fuse_release_user_pages",
        "block/bio.c:bio_set_pages_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581066096,
      "name": "set_page_dirty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int set_page_dirty_lock(struct page * page)
```

```json
{
  "name": "set_page_dirty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581122064,
      "name": "set_page_dirty_lock",
      "external": true,
      "loc": "mm/page-writeback.c:2592",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:put_user_pages_dirty_lock",
        "mm/memory.c:__access_remote_vm",
        "fs/fuse/dev.c:fuse_copy_finish",
        "fs/fuse/file.c:fuse_release_user_pages",
        "block/bio.c:bio_set_pages_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581122064,
      "name": "set_page_dirty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int set_page_dirty_lock(struct page * page)
```

```json
{
  "name": "set_page_dirty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581304736,
      "name": "set_page_dirty_lock",
      "external": true,
      "loc": "mm/page-writeback.c:2602",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__access_remote_vm",
        "fs/fuse/dev.c:fuse_copy_finish",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_aio_complete_req",
        "block/bio.c:bio_set_pages_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581304736,
      "name": "set_page_dirty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int set_page_dirty_lock(struct page * page)
```

```json
{
  "name": "set_page_dirty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581347248,
      "name": "set_page_dirty_lock",
      "external": true,
      "loc": "mm/page-writeback.c:2600",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__access_remote_vm",
        "fs/fuse/dev.c:fuse_copy_finish",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_aio_complete_req",
        "block/bio.c:bio_set_pages_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581347248,
      "name": "set_page_dirty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int set_page_dirty_lock(struct page * page)
```

```json
{
  "name": "set_page_dirty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581366224,
      "name": "set_page_dirty_lock",
      "external": true,
      "loc": "mm/page-writeback.c:2600",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:unpin_user_page_range_dirty_lock",
        "mm/gup.c:unpin_user_pages_dirty_lock",
        "mm/memory.c:__access_remote_vm",
        "fs/fuse/dev.c:fuse_copy_finish",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_aio_complete_req",
        "block/bio.c:bio_set_pages_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581366224,
      "name": "set_page_dirty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int set_page_dirty_lock(struct page * page)
```

```json
{
  "name": "set_page_dirty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581614896,
      "name": "set_page_dirty_lock",
      "external": true,
      "loc": "mm/page-writeback.c:2629",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:unpin_user_page_range_dirty_lock",
        "mm/gup.c:unpin_user_pages_dirty_lock",
        "mm/memory.c:__access_remote_vm",
        "fs/fuse/dev.c:fuse_copy_finish",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_aio_complete_req",
        "block/bio.c:bio_set_pages_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581614896,
      "name": "set_page_dirty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int set_page_dirty_lock(struct page * page)
```

```json
{
  "name": "set_page_dirty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581976016,
      "name": "set_page_dirty_lock",
      "external": true,
      "loc": "mm/page-writeback.c:2740",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__access_remote_vm",
        "fs/fuse/dev.c:fuse_copy_finish",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_aio_complete_req",
        "block/bio.c:bio_set_pages_dirty",
        "block/bio.c:__bio_release_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581976016,
      "name": "set_page_dirty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int set_page_dirty_lock(struct page * page)
```

```json
{
  "name": "set_page_dirty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582410976,
      "name": "set_page_dirty_lock",
      "external": true,
      "loc": "mm/page-writeback.c:2878",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__access_remote_vm",
        "fs/fuse/dev.c:fuse_copy_finish",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_aio_complete_req",
        "block/bio.c:bio_set_pages_dirty",
        "block/bio.c:__bio_release_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582410976,
      "name": "set_page_dirty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int set_page_dirty_lock(struct page * page)
```

```json
{
  "name": "set_page_dirty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582617424,
      "name": "set_page_dirty_lock",
      "external": true,
      "loc": "mm/page-writeback.c:2819",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__access_remote_vm",
        "fs/fuse/dev.c:fuse_copy_finish",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_aio_complete_req",
        "block/bio.c:bio_set_pages_dirty",
        "block/bio.c:__bio_release_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582617424,
      "name": "set_page_dirty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int set_page_dirty_lock(struct page * page)
```

```json
{
  "name": "set_page_dirty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582788944,
      "name": "set_page_dirty_lock",
      "external": true,
      "loc": "mm/page-writeback.c:2798",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__access_remote_vm",
        "fs/fuse/dev.c:fuse_copy_finish",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_aio_complete_req",
        "block/bio-integrity.c:bio_integrity_unpin_bvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582788944,
      "name": "set_page_dirty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int set_page_dirty_lock(struct page * page)
```

```json
{
  "name": "set_page_dirty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492499776,
      "name": "set_page_dirty_lock",
      "external": true,
      "loc": "mm/page-writeback.c:2592",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:put_user_pages_dirty_lock",
        "mm/memory.c:__access_remote_vm",
        "fs/fuse/dev.c:fuse_copy_finish",
        "block/bio.c:bio_set_pages_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492499776,
      "name": "set_page_dirty_lock",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int set_page_dirty_lock(struct page * page)
```

```json
{
  "name": "set_page_dirty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226365144,
      "name": "set_page_dirty_lock",
      "external": true,
      "loc": "mm/page-writeback.c:2592",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:put_user_pages_dirty_lock",
        "mm/memory.c:__access_remote_vm",
        "fs/fuse/dev.c:fuse_copy_finish",
        "fs/fuse/file.c:fuse_release_user_pages",
        "block/bio.c:bio_set_pages_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226365144,
      "name": "set_page_dirty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int set_page_dirty_lock(struct page * page)
```

```json
{
  "name": "set_page_dirty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285780688,
      "name": "set_page_dirty_lock",
      "external": true,
      "loc": "mm/page-writeback.c:2592",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:put_user_pages_dirty_lock",
        "mm/memory.c:__access_remote_vm",
        "fs/fuse/dev.c:fuse_copy_finish",
        "block/bio.c:bio_set_pages_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285780688,
      "name": "set_page_dirty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int set_page_dirty_lock(struct page * page)
```

```json
{
  "name": "set_page_dirty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272554628,
      "name": "set_page_dirty_lock",
      "external": true,
      "loc": "mm/page-writeback.c:2592",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:put_user_pages_dirty_lock",
        "mm/memory.c:__access_remote_vm",
        "fs/fuse/dev.c:fuse_copy_finish",
        "block/bio.c:bio_set_pages_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272554628,
      "name": "set_page_dirty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int set_page_dirty_lock(struct page * page)
```

```json
{
  "name": "set_page_dirty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581090912,
      "name": "set_page_dirty_lock",
      "external": true,
      "loc": "mm/page-writeback.c:2592",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:put_user_pages_dirty_lock",
        "mm/memory.c:__access_remote_vm",
        "fs/fuse/dev.c:fuse_copy_finish",
        "fs/fuse/file.c:fuse_release_user_pages",
        "block/bio.c:bio_set_pages_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581090912,
      "name": "set_page_dirty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int set_page_dirty_lock(struct page * page)
```

```json
{
  "name": "set_page_dirty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581038096,
      "name": "set_page_dirty_lock",
      "external": true,
      "loc": "mm/page-writeback.c:2592",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:put_user_pages_dirty_lock",
        "mm/memory.c:__access_remote_vm",
        "fs/fuse/dev.c:fuse_copy_finish",
        "fs/fuse/file.c:fuse_release_user_pages",
        "block/bio.c:bio_set_pages_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581038096,
      "name": "set_page_dirty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int set_page_dirty_lock(struct page * page)
```

```json
{
  "name": "set_page_dirty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581082112,
      "name": "set_page_dirty_lock",
      "external": true,
      "loc": "mm/page-writeback.c:2592",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:put_user_pages_dirty_lock",
        "mm/memory.c:__access_remote_vm",
        "fs/fuse/dev.c:fuse_copy_finish",
        "fs/fuse/file.c:fuse_release_user_pages",
        "block/bio.c:bio_set_pages_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581082112,
      "name": "set_page_dirty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int set_page_dirty_lock(struct page * page)
```

```json
{
  "name": "set_page_dirty_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581144656,
      "name": "set_page_dirty_lock",
      "external": true,
      "loc": "mm/page-writeback.c:2592",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:put_user_pages_dirty_lock",
        "mm/memory.c:__access_remote_vm",
        "fs/fuse/dev.c:fuse_copy_finish",
        "fs/fuse/file.c:fuse_release_user_pages",
        "block/bio.c:bio_set_pages_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581144656,
      "name": "set_page_dirty_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
