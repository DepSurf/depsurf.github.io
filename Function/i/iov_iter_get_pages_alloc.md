# Function: <code>iov_iter_get_pages_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t iov_iter_get_pages_alloc(struct iov_iter * i, struct page * * * pages, size_t maxsize, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583024480,
      "name": "iov_iter_get_pages_alloc",
      "external": true,
      "loc": "lib/iov_iter.c:617",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583024480,
      "name": "iov_iter_get_pages_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 620
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
ssize_t iov_iter_get_pages_alloc(struct iov_iter * i, struct page * * * pages, size_t maxsize, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583311952,
      "name": "iov_iter_get_pages_alloc",
      "external": true,
      "loc": "lib/iov_iter.c:585",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583311952,
      "name": "iov_iter_get_pages_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 571
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
ssize_t iov_iter_get_pages_alloc(struct iov_iter * i, struct page * * * pages, size_t maxsize, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583432448,
      "name": "iov_iter_get_pages_alloc",
      "external": true,
      "loc": "lib/iov_iter.c:1008",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:default_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583432448,
      "name": "iov_iter_get_pages_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 932
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
ssize_t iov_iter_get_pages_alloc(struct iov_iter * i, struct page * * * pages, size_t maxsize, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583467456,
      "name": "iov_iter_get_pages_alloc",
      "external": true,
      "loc": "lib/iov_iter.c:1132",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:default_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583467456,
      "name": "iov_iter_get_pages_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1046
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
ssize_t iov_iter_get_pages_alloc(struct iov_iter * i, struct page * * * pages, size_t maxsize, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583648368,
      "name": "iov_iter_get_pages_alloc",
      "external": true,
      "loc": "lib/iov_iter.c:1134",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:default_file_splice_read",
        "block/bio.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583648368,
      "name": "iov_iter_get_pages_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1046
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
ssize_t iov_iter_get_pages_alloc(struct iov_iter * i, struct page * * * pages, size_t maxsize, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583849488,
      "name": "iov_iter_get_pages_alloc",
      "external": true,
      "loc": "lib/iov_iter.c:1264",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:default_file_splice_read",
        "block/bio.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583849488,
      "name": "iov_iter_get_pages_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1079
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
ssize_t iov_iter_get_pages_alloc(struct iov_iter * i, struct page * * * pages, size_t maxsize, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583933344,
      "name": "iov_iter_get_pages_alloc",
      "external": true,
      "loc": "lib/iov_iter.c:1339",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:default_file_splice_read",
        "block/bio.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583933344,
      "name": "iov_iter_get_pages_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1136
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
ssize_t iov_iter_get_pages_alloc(struct iov_iter * i, struct page * * * pages, size_t maxsize, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584111568,
      "name": "iov_iter_get_pages_alloc",
      "external": true,
      "loc": "lib/iov_iter.c:1355",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:default_file_splice_read",
        "block/bio.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584111568,
      "name": "iov_iter_get_pages_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1194
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
ssize_t iov_iter_get_pages_alloc(struct iov_iter * i, struct page * * * pages, size_t maxsize, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584234416,
      "name": "iov_iter_get_pages_alloc",
      "external": true,
      "loc": "lib/iov_iter.c:1355",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:default_file_splice_read",
        "block/bio.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584234416,
      "name": "iov_iter_get_pages_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1194
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
ssize_t iov_iter_get_pages_alloc(struct iov_iter * i, struct page * * * pages, size_t maxsize, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584640992,
      "name": "iov_iter_get_pages_alloc",
      "external": true,
      "loc": "lib/iov_iter.c:1390",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-map.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584640992,
      "name": "iov_iter_get_pages_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1192
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
ssize_t iov_iter_get_pages_alloc(struct iov_iter * i, struct page * * * pages, size_t maxsize, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584761792,
      "name": "iov_iter_get_pages_alloc",
      "external": true,
      "loc": "lib/iov_iter.c:1397",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-map.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584761792,
      "name": "iov_iter_get_pages_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1224
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
ssize_t iov_iter_get_pages_alloc(struct iov_iter * i, struct page * * * pages, size_t maxsize, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584800592,
      "name": "iov_iter_get_pages_alloc",
      "external": true,
      "loc": "lib/iov_iter.c:1646",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-map.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584800592,
      "name": "iov_iter_get_pages_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1978
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
ssize_t iov_iter_get_pages_alloc(struct iov_iter * i, struct page * * * pages, size_t maxsize, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iov_iter_get_pages_alloc",
      "external": true,
      "loc": "lib/iov_iter.c:1594",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-map.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592323305,
      "name": "iov_iter_get_pages_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071585225264,
      "name": "iov_iter_get_pages_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 888
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
ssize_t iov_iter_get_pages_alloc(struct iov_iter * i, struct page * * * pages, size_t maxsize, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iov_iter_get_pages_alloc",
      "external": true,
      "loc": "lib/iov_iter.c:1638",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-map.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594127131,
      "name": "iov_iter_get_pages_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071586063904,
      "name": "iov_iter_get_pages_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 977
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
ssize_t iov_iter_get_pages_alloc(struct iov_iter * i, struct page * * * pages, size_t maxsize, size_t * start, unsigned int gup_flags)
```

```json
{
  "name": "iov_iter_get_pages_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587049251,
      "name": "iov_iter_get_pages_alloc",
      "external": true,
      "loc": "lib/iov_iter.c:1516",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_get_pages_alloc2",
        "lib/iov_iter.c:iov_iter_get_pages_alloc2"
      ],
      "caller_func": [
        "block/blk-map.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587048992,
      "name": "iov_iter_get_pages_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
ssize_t iov_iter_get_pages_alloc(struct iov_iter * i, struct page * * * pages, size_t maxsize, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496110400,
      "name": "iov_iter_get_pages_alloc",
      "external": true,
      "loc": "lib/iov_iter.c:1355",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:default_file_splice_read",
        "block/bio.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496110400,
      "name": "iov_iter_get_pages_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1160
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
ssize_t iov_iter_get_pages_alloc(struct iov_iter * i, struct page * * * pages, size_t maxsize, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229436760,
      "name": "iov_iter_get_pages_alloc",
      "external": true,
      "loc": "lib/iov_iter.c:1355",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:default_file_splice_read",
        "block/bio.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229436760,
      "name": "iov_iter_get_pages_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1044
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
ssize_t iov_iter_get_pages_alloc(struct iov_iter * i, struct page * * * pages, size_t maxsize, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290359856,
      "name": "iov_iter_get_pages_alloc",
      "external": true,
      "loc": "lib/iov_iter.c:1355",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:default_file_splice_read",
        "block/bio.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290359856,
      "name": "iov_iter_get_pages_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1668
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
ssize_t iov_iter_get_pages_alloc(struct iov_iter * i, struct page * * * pages, size_t maxsize, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275175428,
      "name": "iov_iter_get_pages_alloc",
      "external": true,
      "loc": "lib/iov_iter.c:1355",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:default_file_splice_read",
        "block/bio.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275175428,
      "name": "iov_iter_get_pages_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 934
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
ssize_t iov_iter_get_pages_alloc(struct iov_iter * i, struct page * * * pages, size_t maxsize, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584203152,
      "name": "iov_iter_get_pages_alloc",
      "external": true,
      "loc": "lib/iov_iter.c:1355",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:default_file_splice_read",
        "block/bio.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584203152,
      "name": "iov_iter_get_pages_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1194
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
ssize_t iov_iter_get_pages_alloc(struct iov_iter * i, struct page * * * pages, size_t maxsize, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584138368,
      "name": "iov_iter_get_pages_alloc",
      "external": true,
      "loc": "lib/iov_iter.c:1355",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:default_file_splice_read",
        "block/bio.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584138368,
      "name": "iov_iter_get_pages_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1194
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
ssize_t iov_iter_get_pages_alloc(struct iov_iter * i, struct page * * * pages, size_t maxsize, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584186912,
      "name": "iov_iter_get_pages_alloc",
      "external": true,
      "loc": "lib/iov_iter.c:1355",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:default_file_splice_read",
        "block/bio.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584186912,
      "name": "iov_iter_get_pages_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1194
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
ssize_t iov_iter_get_pages_alloc(struct iov_iter * i, struct page * * * pages, size_t maxsize, size_t * start)
```

```json
{
  "name": "iov_iter_get_pages_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584291488,
      "name": "iov_iter_get_pages_alloc",
      "external": true,
      "loc": "lib/iov_iter.c:1355",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:default_file_splice_read",
        "block/bio.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584291488,
      "name": "iov_iter_get_pages_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1194
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
ssize_t iov_iter_get_pages_alloc(struct iov_iter * i, struct page * * * pages, size_t maxsize, size_t * start, unsigned int gup_flags)
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
