# Function: <code>bio_free_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_free_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582720028,
      "name": "bio_free_pages",
      "external": false,
      "loc": "block/bio.c:1069",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_uncopy_user",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_kern_endio"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_free_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582999464,
      "name": "bio_free_pages",
      "external": false,
      "loc": "block/bio.c:1071",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_kern_endio",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_uncopy_user"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bio_free_pages(struct bio * bio)
```

```json
{
  "name": "bio_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583104392,
      "name": "bio_free_pages",
      "external": true,
      "loc": "block/bio.c:1125",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_kern_endio",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_uncopy_user"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583095376,
      "name": "bio_free_pages",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bio_free_pages(struct bio * bio)
```

```json
{
  "name": "bio_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583160046,
      "name": "bio_free_pages",
      "external": true,
      "loc": "block/bio.c:1141",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_kern_endio",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_uncopy_user"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583151760,
      "name": "bio_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bio_free_pages(struct bio * bio)
```

```json
{
  "name": "bio_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583335806,
      "name": "bio_free_pages",
      "external": true,
      "loc": "block/bio.c:1146",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_kern_endio",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_uncopy_user"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583326912,
      "name": "bio_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bio_free_pages(struct bio * bio)
```

```json
{
  "name": "bio_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583545033,
      "name": "bio_free_pages",
      "external": true,
      "loc": "block/bio.c:1201",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_kern_endio",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_uncopy_user"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583535760,
      "name": "bio_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bio_free_pages(struct bio * bio)
```

```json
{
  "name": "bio_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583668281,
      "name": "bio_free_pages",
      "external": true,
      "loc": "block/bio.c:1125",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_kern_endio",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_uncopy_user"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583659104,
      "name": "bio_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void bio_free_pages(struct bio * bio)
```

```json
{
  "name": "bio_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583849776,
      "name": "bio_free_pages",
      "external": true,
      "loc": "block/bio.c:1183",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_kern_endio_read",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_uncopy_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583849776,
      "name": "bio_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void bio_free_pages(struct bio * bio)
```

```json
{
  "name": "bio_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583952688,
      "name": "bio_free_pages",
      "external": true,
      "loc": "block/bio.c:1222",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_kern_endio_read",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_uncopy_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583952688,
      "name": "bio_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void bio_free_pages(struct bio * bio)
```

```json
{
  "name": "bio_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584341632,
      "name": "bio_free_pages",
      "external": true,
      "loc": "block/bio.c:1272",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_bio_read",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:__blk_rq_unmap_user",
        "block/blk-map.c:bio_copy_kern_endio_read",
        "block/blk-map.c:bio_copy_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584341632,
      "name": "bio_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void bio_free_pages(struct bio * bio)
```

```json
{
  "name": "bio_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584459712,
      "name": "bio_free_pages",
      "external": true,
      "loc": "block/bio.c:1275",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_bio_read",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:bio_copy_kern_endio_read",
        "block/blk-map.c:bio_copy_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584459712,
      "name": "bio_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void bio_free_pages(struct bio * bio)
```

```json
{
  "name": "bio_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584494016,
      "name": "bio_free_pages",
      "external": true,
      "loc": "block/bio.c:1239",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_bio_read",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:bio_copy_kern_endio_read",
        "block/blk-map.c:bio_copy_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584494016,
      "name": "bio_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void bio_free_pages(struct bio * bio)
```

```json
{
  "name": "bio_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584902576,
      "name": "bio_free_pages",
      "external": true,
      "loc": "block/bio.c:1321",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_bio_read",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:bio_copy_kern_endio_read",
        "block/blk-map.c:bio_copy_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584902576,
      "name": "bio_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void bio_free_pages(struct bio * bio)
```

```json
{
  "name": "bio_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585602272,
      "name": "bio_free_pages",
      "external": true,
      "loc": "block/bio.c:1380",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_bio_read",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:bio_copy_kern_endio_read",
        "block/blk-map.c:bio_copy_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585602272,
      "name": "bio_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
void bio_free_pages(struct bio * bio)
```

```json
{
  "name": "bio_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586370448,
      "name": "bio_free_pages",
      "external": true,
      "loc": "block/bio.c:1443",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_bio_read",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:bio_copy_kern_endio_read",
        "block/blk-map.c:bio_copy_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586370448,
      "name": "bio_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
void bio_free_pages(struct bio * bio)
```

```json
{
  "name": "bio_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586617616,
      "name": "bio_free_pages",
      "external": true,
      "loc": "block/bio.c:1428",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_bio_read",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:bio_copy_kern",
        "block/blk-map.c:bio_copy_kern_endio_read",
        "block/blk-map.c:bio_copy_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586617616,
      "name": "bio_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
void bio_free_pages(struct bio * bio)
```

```json
{
  "name": "bio_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586885920,
      "name": "bio_free_pages",
      "external": true,
      "loc": "block/bio.c:1440",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_bio_read",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:bio_copy_kern",
        "block/blk-map.c:bio_copy_kern_endio_read",
        "block/blk-map.c:bio_copy_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586885920,
      "name": "bio_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
void bio_free_pages(struct bio * bio)
```

```json
{
  "name": "bio_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495771928,
      "name": "bio_free_pages",
      "external": true,
      "loc": "block/bio.c:1222",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_kern_endio_read",
        "block/bio.c:bio_copy_kern_endio_read",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_uncopy_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495771928,
      "name": "bio_free_pages",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void bio_free_pages(struct bio * bio)
```

```json
{
  "name": "bio_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229125800,
      "name": "bio_free_pages",
      "external": true,
      "loc": "block/bio.c:1222",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_kern_endio_read",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_uncopy_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229125800,
      "name": "bio_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void bio_free_pages(struct bio * bio)
```

```json
{
  "name": "bio_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289948416,
      "name": "bio_free_pages",
      "external": true,
      "loc": "block/bio.c:1222",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_kern_endio_read",
        "block/bio.c:bio_copy_kern_endio_read",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_uncopy_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289948416,
      "name": "bio_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void bio_free_pages(struct bio * bio)
```

```json
{
  "name": "bio_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274919000,
      "name": "bio_free_pages",
      "external": true,
      "loc": "block/bio.c:1222",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_kern_endio_read",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_uncopy_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274919000,
      "name": "bio_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void bio_free_pages(struct bio * bio)
```

```json
{
  "name": "bio_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583921424,
      "name": "bio_free_pages",
      "external": true,
      "loc": "block/bio.c:1222",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_kern_endio_read",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_uncopy_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583921424,
      "name": "bio_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void bio_free_pages(struct bio * bio)
```

```json
{
  "name": "bio_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583858384,
      "name": "bio_free_pages",
      "external": true,
      "loc": "block/bio.c:1222",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_kern_endio_read",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_uncopy_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583858384,
      "name": "bio_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void bio_free_pages(struct bio * bio)
```

```json
{
  "name": "bio_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583905184,
      "name": "bio_free_pages",
      "external": true,
      "loc": "block/bio.c:1222",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_kern_endio_read",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_uncopy_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583905184,
      "name": "bio_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void bio_free_pages(struct bio * bio)
```

```json
{
  "name": "bio_free_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584006128,
      "name": "bio_free_pages",
      "external": true,
      "loc": "block/bio.c:1222",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_kern_endio_read",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_uncopy_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584006128,
      "name": "bio_free_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void bio_free_pages(struct bio * bio)
```
</details>
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
