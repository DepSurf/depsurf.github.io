# Function: <code>iov_iter_get_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t iov_iter_get_pages(struct iov_iter * i, struct page * * pages, size_t maxsize, unsigned int maxpages, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583023952,
      "name": "iov_iter_get_pages",
      "external": true,
      "loc": "lib/iov_iter.c:572",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/fuse/file.c:fuse_direct_io",
        "net/core/datagram.c:zerocopy_sg_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583023952,
      "name": "iov_iter_get_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
ssize_t iov_iter_get_pages(struct iov_iter * i, struct page * * pages, size_t maxsize, unsigned int maxpages, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583322448,
      "name": "iov_iter_get_pages",
      "external": true,
      "loc": "lib/iov_iter.c:540",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/fuse/file.c:fuse_direct_io",
        "net/core/datagram.c:zerocopy_sg_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583322448,
      "name": "iov_iter_get_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 485
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
ssize_t iov_iter_get_pages(struct iov_iter * i, struct page * * pages, size_t maxsize, unsigned int maxpages, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583444352,
      "name": "iov_iter_get_pages",
      "external": true,
      "loc": "lib/iov_iter.c:930",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_to_pipe",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/fuse/file.c:fuse_direct_io",
        "block/bio.c:bio_iov_iter_get_pages",
        "net/core/datagram.c:zerocopy_sg_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583444352,
      "name": "iov_iter_get_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 817
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
ssize_t iov_iter_get_pages(struct iov_iter * i, struct page * * pages, size_t maxsize, unsigned int maxpages, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583453216,
      "name": "iov_iter_get_pages",
      "external": true,
      "loc": "lib/iov_iter.c:1057",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_to_pipe",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/fuse/file.c:fuse_direct_io",
        "block/bio.c:bio_iov_iter_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583453216,
      "name": "iov_iter_get_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 692
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
ssize_t iov_iter_get_pages(struct iov_iter * i, struct page * * pages, size_t maxsize, unsigned int maxpages, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583633312,
      "name": "iov_iter_get_pages",
      "external": true,
      "loc": "lib/iov_iter.c:1059",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_to_pipe",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/fuse/file.c:fuse_direct_io",
        "block/bio.c:bio_iov_iter_get_pages",
        "net/core/datagram.c:__zerocopy_sg_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583633312,
      "name": "iov_iter_get_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 692
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
ssize_t iov_iter_get_pages(struct iov_iter * i, struct page * * pages, size_t maxsize, unsigned int maxpages, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583866544,
      "name": "iov_iter_get_pages",
      "external": true,
      "loc": "lib/iov_iter.c:1189",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_to_pipe",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/file.c:fuse_direct_io",
        "block/bio.c:bio_iov_iter_get_pages",
        "net/core/datagram.c:__zerocopy_sg_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583866544,
      "name": "iov_iter_get_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 680
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
ssize_t iov_iter_get_pages(struct iov_iter * i, struct page * * pages, size_t maxsize, unsigned int maxpages, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583951808,
      "name": "iov_iter_get_pages",
      "external": true,
      "loc": "lib/iov_iter.c:1261",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_to_pipe",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/file.c:fuse_direct_io",
        "block/bio.c:bio_iov_iter_get_pages",
        "net/core/datagram.c:__zerocopy_sg_from_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583951808,
      "name": "iov_iter_get_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 741
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
ssize_t iov_iter_get_pages(struct iov_iter * i, struct page * * pages, size_t maxsize, unsigned int maxpages, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584131056,
      "name": "iov_iter_get_pages",
      "external": true,
      "loc": "lib/iov_iter.c:1275",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_to_pipe",
        "fs/direct-io.c:do_direct_IO",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/file.c:fuse_direct_io",
        "block/bio.c:bio_iov_iter_get_pages",
        "net/core/datagram.c:__zerocopy_sg_from_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584131056,
      "name": "iov_iter_get_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 825
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
ssize_t iov_iter_get_pages(struct iov_iter * i, struct page * * pages, size_t maxsize, unsigned int maxpages, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584253952,
      "name": "iov_iter_get_pages",
      "external": true,
      "loc": "lib/iov_iter.c:1275",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_to_pipe",
        "fs/direct-io.c:do_direct_IO",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/file.c:fuse_direct_io",
        "block/bio.c:bio_iov_iter_get_pages",
        "net/core/datagram.c:__zerocopy_sg_from_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584253952,
      "name": "iov_iter_get_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 825
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
ssize_t iov_iter_get_pages(struct iov_iter * i, struct page * * pages, size_t maxsize, unsigned int maxpages, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584647296,
      "name": "iov_iter_get_pages",
      "external": true,
      "loc": "lib/iov_iter.c:1311",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_to_pipe",
        "fs/direct-io.c:do_direct_IO",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/file.c:fuse_direct_io",
        "block/bio.c:__bio_iov_append_get_pages",
        "block/bio.c:__bio_iov_iter_get_pages",
        "net/core/datagram.c:__zerocopy_sg_from_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584647296,
      "name": "iov_iter_get_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 797
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
ssize_t iov_iter_get_pages(struct iov_iter * i, struct page * * pages, size_t maxsize, unsigned int maxpages, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584776784,
      "name": "iov_iter_get_pages",
      "external": true,
      "loc": "lib/iov_iter.c:1318",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_to_pipe",
        "fs/direct-io.c:do_direct_IO",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/file.c:fuse_direct_io",
        "block/bio.c:__bio_iov_append_get_pages",
        "block/bio.c:__bio_iov_iter_get_pages",
        "net/core/datagram.c:__zerocopy_sg_from_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584776784,
      "name": "iov_iter_get_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 891
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
ssize_t iov_iter_get_pages(struct iov_iter * i, struct page * * pages, size_t maxsize, unsigned int maxpages, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584796000,
      "name": "iov_iter_get_pages",
      "external": true,
      "loc": "lib/iov_iter.c:1519",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_to_pipe",
        "fs/direct-io.c:do_direct_IO",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/file.c:fuse_direct_io",
        "net/core/datagram.c:__zerocopy_sg_from_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584796000,
      "name": "iov_iter_get_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1558
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
ssize_t iov_iter_get_pages(struct iov_iter * i, struct page * * pages, size_t maxsize, unsigned int maxpages, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iov_iter_get_pages",
      "external": true,
      "loc": "lib/iov_iter.c:1473",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_to_pipe",
        "fs/direct-io.c:do_direct_IO",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/file.c:fuse_direct_io",
        "block/bio.c:__bio_iov_append_get_pages",
        "block/bio.c:__bio_iov_iter_get_pages",
        "net/core/datagram.c:__zerocopy_sg_from_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592323356,
      "name": "iov_iter_get_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071585226160,
      "name": "iov_iter_get_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1045
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
ssize_t iov_iter_get_pages(struct iov_iter * i, struct page * * pages, size_t maxsize, unsigned int maxpages, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iov_iter_get_pages",
      "external": true,
      "loc": "lib/iov_iter.c:1519",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_to_pipe",
        "fs/direct-io.c:do_direct_IO",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/file.c:fuse_direct_io",
        "block/bio.c:bio_iov_iter_get_pages",
        "net/core/datagram.c:__zerocopy_sg_from_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594127190,
      "name": "iov_iter_get_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071586064896,
      "name": "iov_iter_get_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 746
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
ssize_t iov_iter_get_pages(struct iov_iter * i, struct page * * pages, size_t maxsize, unsigned int maxpages, size_t * start, unsigned int gup_flags)
```

```json
{
  "name": "iov_iter_get_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587049147,
      "name": "iov_iter_get_pages",
      "external": true,
      "loc": "lib/iov_iter.c:1496",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_get_pages2"
      ],
      "caller_func": [
        "block/bio.c:__bio_iov_iter_get_pages",
        "block/blk-map.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587048896,
      "name": "iov_iter_get_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
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
ssize_t iov_iter_get_pages(struct iov_iter * i, struct page * * pages, size_t maxsize, unsigned int maxpages, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496132472,
      "name": "iov_iter_get_pages",
      "external": true,
      "loc": "lib/iov_iter.c:1275",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_to_pipe",
        "fs/direct-io.c:do_direct_IO",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/file.c:fuse_direct_io",
        "block/bio.c:bio_iov_iter_get_pages",
        "net/core/datagram.c:__zerocopy_sg_from_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496132472,
      "name": "iov_iter_get_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 844
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
ssize_t iov_iter_get_pages(struct iov_iter * i, struct page * * pages, size_t maxsize, unsigned int maxpages, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229456136,
      "name": "iov_iter_get_pages",
      "external": true,
      "loc": "lib/iov_iter.c:1275",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_to_pipe",
        "fs/direct-io.c:do_direct_IO",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/file.c:fuse_direct_io",
        "block/bio.c:bio_iov_iter_get_pages",
        "net/core/datagram.c:__zerocopy_sg_from_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229456136,
      "name": "iov_iter_get_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 852
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
ssize_t iov_iter_get_pages(struct iov_iter * i, struct page * * pages, size_t maxsize, unsigned int maxpages, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290387968,
      "name": "iov_iter_get_pages",
      "external": true,
      "loc": "lib/iov_iter.c:1275",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_to_pipe",
        "fs/direct-io.c:do_direct_IO",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/file.c:fuse_direct_io",
        "block/bio.c:bio_iov_iter_get_pages",
        "net/core/datagram.c:__zerocopy_sg_from_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290387968,
      "name": "iov_iter_get_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1180
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
ssize_t iov_iter_get_pages(struct iov_iter * i, struct page * * pages, size_t maxsize, unsigned int maxpages, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275190304,
      "name": "iov_iter_get_pages",
      "external": true,
      "loc": "lib/iov_iter.c:1275",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_to_pipe",
        "fs/direct-io.c:do_direct_IO",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/file.c:fuse_direct_io",
        "block/bio.c:bio_iov_iter_get_pages",
        "net/core/datagram.c:__zerocopy_sg_from_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275190304,
      "name": "iov_iter_get_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 738
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
ssize_t iov_iter_get_pages(struct iov_iter * i, struct page * * pages, size_t maxsize, unsigned int maxpages, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584222688,
      "name": "iov_iter_get_pages",
      "external": true,
      "loc": "lib/iov_iter.c:1275",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_to_pipe",
        "fs/direct-io.c:do_direct_IO",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/file.c:fuse_direct_io",
        "block/bio.c:bio_iov_iter_get_pages",
        "net/core/datagram.c:__zerocopy_sg_from_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584222688,
      "name": "iov_iter_get_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 825
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
ssize_t iov_iter_get_pages(struct iov_iter * i, struct page * * pages, size_t maxsize, unsigned int maxpages, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584157904,
      "name": "iov_iter_get_pages",
      "external": true,
      "loc": "lib/iov_iter.c:1275",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_to_pipe",
        "fs/direct-io.c:do_direct_IO",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/file.c:fuse_direct_io",
        "block/bio.c:bio_iov_iter_get_pages",
        "net/core/datagram.c:__zerocopy_sg_from_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584157904,
      "name": "iov_iter_get_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 825
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
ssize_t iov_iter_get_pages(struct iov_iter * i, struct page * * pages, size_t maxsize, unsigned int maxpages, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584206448,
      "name": "iov_iter_get_pages",
      "external": true,
      "loc": "lib/iov_iter.c:1275",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_to_pipe",
        "fs/direct-io.c:do_direct_IO",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/file.c:fuse_direct_io",
        "block/bio.c:bio_iov_iter_get_pages",
        "net/core/datagram.c:__zerocopy_sg_from_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584206448,
      "name": "iov_iter_get_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 825
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
ssize_t iov_iter_get_pages(struct iov_iter * i, struct page * * pages, size_t maxsize, unsigned int maxpages, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584311008,
      "name": "iov_iter_get_pages",
      "external": true,
      "loc": "lib/iov_iter.c:1275",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:iter_to_pipe",
        "fs/direct-io.c:do_direct_IO",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/file.c:fuse_direct_io",
        "block/bio.c:bio_iov_iter_get_pages",
        "net/core/datagram.c:__zerocopy_sg_from_iter",
        "net/core/skmsg.c:sk_msg_zerocopy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584311008,
      "name": "iov_iter_get_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 825
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int gup_flags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
ssize_t iov_iter_get_pages(struct iov_iter * i, struct page * * pages, size_t maxsize, unsigned int maxpages, size_t * start, unsigned int gup_flags)
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
