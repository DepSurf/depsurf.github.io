# Function: <code>memcpy_from_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void memcpy_from_page(char * to, struct page * page, size_t offset, size_t len)
```

```json
{
  "name": "memcpy_from_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583021232,
      "name": "memcpy_from_page",
      "external": false,
      "loc": "lib/iov_iter.c:365",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:copy_from_iter",
        "lib/iov_iter.c:copy_from_iter",
        "lib/iov_iter.c:copy_from_iter_nocache",
        "lib/iov_iter.c:copy_from_iter_nocache",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583021232,
      "name": "memcpy_from_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void memcpy_from_page(char * to, struct page * page, size_t offset, size_t len)
```

```json
{
  "name": "memcpy_from_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583312992,
      "name": "memcpy_from_page",
      "external": false,
      "loc": "lib/iov_iter.c:338",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:copy_from_iter_nocache",
        "lib/iov_iter.c:copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583312992,
      "name": "memcpy_from_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void memcpy_from_page(char * to, struct page * page, size_t offset, size_t len)
```

```json
{
  "name": "memcpy_from_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583433392,
      "name": "memcpy_from_page",
      "external": false,
      "loc": "lib/iov_iter.c:430",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:copy_from_iter_full_nocache",
        "lib/iov_iter.c:copy_from_iter_nocache",
        "lib/iov_iter.c:copy_from_iter_full",
        "lib/iov_iter.c:copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583433392,
      "name": "memcpy_from_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void memcpy_from_page(char * to, struct page * page, size_t offset, size_t len)
```

```json
{
  "name": "memcpy_from_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583452304,
      "name": "memcpy_from_page",
      "external": false,
      "loc": "lib/iov_iter.c:450",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:_copy_from_iter_full_nocache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583452304,
      "name": "memcpy_from_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
void memcpy_from_page(char * to, struct page * page, size_t offset, size_t len)
```

```json
{
  "name": "memcpy_from_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583632400,
      "name": "memcpy_from_page",
      "external": false,
      "loc": "lib/iov_iter.c:450",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:_copy_from_iter_full_nocache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583632400,
      "name": "memcpy_from_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
void memcpy_from_page(char * to, struct page * page, size_t offset, size_t len)
```

```json
{
  "name": "memcpy_from_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583848896,
      "name": "memcpy_from_page",
      "external": false,
      "loc": "lib/iov_iter.c:450",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:_copy_from_iter_full_nocache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583848896,
      "name": "memcpy_from_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
void memcpy_from_page(char * to, struct page * page, size_t offset, size_t len)
```

```json
{
  "name": "memcpy_from_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583932688,
      "name": "memcpy_from_page",
      "external": false,
      "loc": "lib/iov_iter.c:456",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:_copy_from_iter_full_nocache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583932688,
      "name": "memcpy_from_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
void memcpy_from_page(char * to, struct page * page, size_t offset, size_t len)
```

```json
{
  "name": "memcpy_from_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584110864,
      "name": "memcpy_from_page",
      "external": false,
      "loc": "lib/iov_iter.c:457",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:_copy_from_iter_full_nocache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584110864,
      "name": "memcpy_from_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
void memcpy_from_page(char * to, struct page * page, size_t offset, size_t len)
```

```json
{
  "name": "memcpy_from_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584233664,
      "name": "memcpy_from_page",
      "external": false,
      "loc": "lib/iov_iter.c:457",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:_copy_from_iter_full_nocache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584233664,
      "name": "memcpy_from_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
void memcpy_from_page(char * to, struct page * page, size_t offset, size_t len)
```

```json
{
  "name": "memcpy_from_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584643552,
      "name": "memcpy_from_page",
      "external": false,
      "loc": "lib/iov_iter.c:462",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:_copy_from_iter_full_nocache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584643552,
      "name": "memcpy_from_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
void memcpy_from_page(char * to, struct page * page, size_t offset, size_t len)
```

```json
{
  "name": "memcpy_from_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584764544,
      "name": "memcpy_from_page",
      "external": false,
      "loc": "lib/iov_iter.c:469",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:_copy_from_iter_full_nocache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584764544,
      "name": "memcpy_from_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcpy_from_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583424654,
      "name": "memcpy_from_page",
      "external": false,
      "loc": "include/linux/highmem.h:315",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/verity.c:pagecache_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584799508,
      "name": "memcpy_from_page",
      "external": false,
      "loc": "include/linux/highmem.h:315",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:_copy_from_iter_full_nocache",
        "lib/iov_iter.c:_copy_from_iter_full_nocache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_from_iter"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcpy_from_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583774126,
      "name": "memcpy_from_page",
      "external": false,
      "loc": "include/linux/highmem.h:301",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/verity.c:pagecache_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584950835,
      "name": "memcpy_from_page",
      "external": false,
      "loc": "include/linux/highmem.h:301",
      "file": "block/blk-map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-map.c:bio_copy_kern_endio_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcpy_from_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584334208,
      "name": "memcpy_from_page",
      "external": false,
      "loc": "include/linux/highmem.h:372",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/verity.c:pagecache_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585658132,
      "name": "memcpy_from_page",
      "external": false,
      "loc": "include/linux/highmem.h:372",
      "file": "block/blk-map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-map.c:bio_copy_kern_endio_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcpy_from_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "memcpy_from_page",
      "external": false,
      "loc": "include/linux/highmem.h:387",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584115991,
      "name": "memcpy_from_page",
      "external": false,
      "loc": "include/linux/highmem.h:387",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584983104,
      "name": "memcpy_from_page",
      "external": false,
      "loc": "include/linux/highmem.h:387",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/verity.c:pagecache_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586429412,
      "name": "memcpy_from_page",
      "external": false,
      "loc": "include/linux/highmem.h:387",
      "file": "block/blk-map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-map.c:bio_copy_kern_endio_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590457382,
      "name": "memcpy_from_page",
      "external": false,
      "loc": "include/linux/highmem.h:387",
      "file": "drivers/base/firmware_loader/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/sysfs.c:firmware_rw"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcpy_from_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "memcpy_from_page",
      "external": false,
      "loc": "include/linux/highmem.h:411",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586677028,
      "name": "memcpy_from_page",
      "external": false,
      "loc": "include/linux/highmem.h:411",
      "file": "block/blk-map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-map.c:bio_copy_kern_endio_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590777654,
      "name": "memcpy_from_page",
      "external": false,
      "loc": "include/linux/highmem.h:411",
      "file": "drivers/base/firmware_loader/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/sysfs.c:firmware_rw"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcpy_from_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "memcpy_from_page",
      "external": false,
      "loc": "include/linux/highmem.h:411",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586948356,
      "name": "memcpy_from_page",
      "external": false,
      "loc": "include/linux/highmem.h:411",
      "file": "block/blk-map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-map.c:bio_copy_kern_endio_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591120326,
      "name": "memcpy_from_page",
      "external": false,
      "loc": "include/linux/highmem.h:411",
      "file": "drivers/base/firmware_loader/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/sysfs.c:firmware_rw"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void memcpy_from_page(char * to, struct page * page, size_t offset, size_t len)
```

```json
{
  "name": "memcpy_from_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496109584,
      "name": "memcpy_from_page",
      "external": false,
      "loc": "lib/iov_iter.c:457",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:_copy_from_iter_full_nocache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496109584,
      "name": "memcpy_from_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void memcpy_from_page(char * to, struct page * page, size_t offset, size_t len)
```

```json
{
  "name": "memcpy_from_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229434980,
      "name": "memcpy_from_page",
      "external": false,
      "loc": "lib/iov_iter.c:457",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:_copy_from_iter_full_nocache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229434980,
      "name": "memcpy_from_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
void memcpy_from_page(char * to, struct page * page, size_t offset, size_t len)
```

```json
{
  "name": "memcpy_from_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290358512,
      "name": "memcpy_from_page",
      "external": false,
      "loc": "lib/iov_iter.c:457",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:_copy_from_iter_full_nocache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290358512,
      "name": "memcpy_from_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void memcpy_from_page(char * to, struct page * page, size_t offset, size_t len)
```

```json
{
  "name": "memcpy_from_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275174428,
      "name": "memcpy_from_page",
      "external": false,
      "loc": "lib/iov_iter.c:457",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:_copy_from_iter_full_nocache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275174428,
      "name": "memcpy_from_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void memcpy_from_page(char * to, struct page * page, size_t offset, size_t len)
```

```json
{
  "name": "memcpy_from_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584202400,
      "name": "memcpy_from_page",
      "external": false,
      "loc": "lib/iov_iter.c:457",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:_copy_from_iter_full_nocache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584202400,
      "name": "memcpy_from_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
void memcpy_from_page(char * to, struct page * page, size_t offset, size_t len)
```

```json
{
  "name": "memcpy_from_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584137616,
      "name": "memcpy_from_page",
      "external": false,
      "loc": "lib/iov_iter.c:457",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:_copy_from_iter_full_nocache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584137616,
      "name": "memcpy_from_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
void memcpy_from_page(char * to, struct page * page, size_t offset, size_t len)
```

```json
{
  "name": "memcpy_from_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584186160,
      "name": "memcpy_from_page",
      "external": false,
      "loc": "lib/iov_iter.c:457",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:_copy_from_iter_full_nocache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584186160,
      "name": "memcpy_from_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
void memcpy_from_page(char * to, struct page * page, size_t offset, size_t len)
```

```json
{
  "name": "memcpy_from_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584290608,
      "name": "memcpy_from_page",
      "external": false,
      "loc": "lib/iov_iter.c:457",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:_copy_from_iter_full_nocache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584290608,
      "name": "memcpy_from_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void memcpy_from_page(char * to, struct page * page, size_t offset, size_t len)
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
