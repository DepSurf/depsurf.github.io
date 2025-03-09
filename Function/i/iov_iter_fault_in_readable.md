# Function: <code>iov_iter_fault_in_readable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int iov_iter_fault_in_readable(struct iov_iter * i, size_t bytes)
```

```json
{
  "name": "iov_iter_fault_in_readable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583025936,
      "name": "iov_iter_fault_in_readable",
      "external": true,
      "loc": "lib/iov_iter.c:309",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/fuse/file.c:fuse_perform_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583025936,
      "name": "iov_iter_fault_in_readable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int iov_iter_fault_in_readable(struct iov_iter * i, size_t bytes)
```

```json
{
  "name": "iov_iter_fault_in_readable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583319280,
      "name": "iov_iter_fault_in_readable",
      "external": true,
      "loc": "lib/iov_iter.c:300",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/iomap.c:iomap_write_actor",
        "fs/fuse/file.c:fuse_perform_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583319280,
      "name": "iov_iter_fault_in_readable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
int iov_iter_fault_in_readable(struct iov_iter * i, size_t bytes)
```

```json
{
  "name": "iov_iter_fault_in_readable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583442528,
      "name": "iov_iter_fault_in_readable",
      "external": true,
      "loc": "lib/iov_iter.c:393",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/iomap.c:iomap_write_actor",
        "fs/fuse/file.c:fuse_perform_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583442528,
      "name": "iov_iter_fault_in_readable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
int iov_iter_fault_in_readable(struct iov_iter * i, size_t bytes)
```

```json
{
  "name": "iov_iter_fault_in_readable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583454416,
      "name": "iov_iter_fault_in_readable",
      "external": true,
      "loc": "lib/iov_iter.c:413",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/iomap.c:iomap_write_actor",
        "fs/fuse/file.c:fuse_perform_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583454416,
      "name": "iov_iter_fault_in_readable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
int iov_iter_fault_in_readable(struct iov_iter * i, size_t bytes)
```

```json
{
  "name": "iov_iter_fault_in_readable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583643792,
      "name": "iov_iter_fault_in_readable",
      "external": true,
      "loc": "lib/iov_iter.c:413",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/iomap.c:iomap_write_actor",
        "fs/fuse/file.c:fuse_perform_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583643792,
      "name": "iov_iter_fault_in_readable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
int iov_iter_fault_in_readable(struct iov_iter * i, size_t bytes)
```

```json
{
  "name": "iov_iter_fault_in_readable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583863984,
      "name": "iov_iter_fault_in_readable",
      "external": true,
      "loc": "lib/iov_iter.c:413",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/iomap.c:iomap_write_actor",
        "fs/fuse/file.c:fuse_perform_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583863984,
      "name": "iov_iter_fault_in_readable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
int iov_iter_fault_in_readable(struct iov_iter * i, size_t bytes)
```

```json
{
  "name": "iov_iter_fault_in_readable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583951504,
      "name": "iov_iter_fault_in_readable",
      "external": true,
      "loc": "lib/iov_iter.c:417",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/iomap.c:iomap_write_actor",
        "fs/fuse/file.c:fuse_perform_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583951504,
      "name": "iov_iter_fault_in_readable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
int iov_iter_fault_in_readable(struct iov_iter * i, size_t bytes)
```

```json
{
  "name": "iov_iter_fault_in_readable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584130752,
      "name": "iov_iter_fault_in_readable",
      "external": true,
      "loc": "lib/iov_iter.c:418",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/iomap/buffered-io.c:iomap_write_actor",
        "fs/fuse/file.c:fuse_perform_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584130752,
      "name": "iov_iter_fault_in_readable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
int iov_iter_fault_in_readable(struct iov_iter * i, size_t bytes)
```

```json
{
  "name": "iov_iter_fault_in_readable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584236016,
      "name": "iov_iter_fault_in_readable",
      "external": true,
      "loc": "lib/iov_iter.c:418",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/iomap/buffered-io.c:iomap_write_actor",
        "fs/fuse/file.c:fuse_perform_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584236016,
      "name": "iov_iter_fault_in_readable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
int iov_iter_fault_in_readable(struct iov_iter * i, size_t bytes)
```

```json
{
  "name": "iov_iter_fault_in_readable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584645184,
      "name": "iov_iter_fault_in_readable",
      "external": true,
      "loc": "lib/iov_iter.c:423",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/iomap/buffered-io.c:iomap_write_actor",
        "fs/fuse/file.c:fuse_fill_write_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584645184,
      "name": "iov_iter_fault_in_readable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
int iov_iter_fault_in_readable(struct iov_iter * i, size_t bytes)
```

```json
{
  "name": "iov_iter_fault_in_readable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584761136,
      "name": "iov_iter_fault_in_readable",
      "external": true,
      "loc": "lib/iov_iter.c:430",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/iomap/buffered-io.c:iomap_write_actor",
        "fs/fuse/file.c:fuse_fill_write_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584761136,
      "name": "iov_iter_fault_in_readable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int iov_iter_fault_in_readable(struct iov_iter * i, size_t bytes)
```

```json
{
  "name": "iov_iter_fault_in_readable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584789408,
      "name": "iov_iter_fault_in_readable",
      "external": true,
      "loc": "lib/iov_iter.c:472",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/iomap/buffered-io.c:iomap_write_actor",
        "fs/fuse/file.c:fuse_fill_write_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584789408,
      "name": "iov_iter_fault_in_readable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
int iov_iter_fault_in_readable(const struct iov_iter * i, size_t bytes)
```

```json
{
  "name": "iov_iter_fault_in_readable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585220176,
      "name": "iov_iter_fault_in_readable",
      "external": true,
      "loc": "lib/iov_iter.c:440",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/iomap/buffered-io.c:iomap_file_buffered_write",
        "fs/fuse/file.c:fuse_fill_write_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585220176,
      "name": "iov_iter_fault_in_readable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int iov_iter_fault_in_readable(struct iov_iter * i, size_t bytes)
```

```json
{
  "name": "iov_iter_fault_in_readable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496132320,
      "name": "iov_iter_fault_in_readable",
      "external": true,
      "loc": "lib/iov_iter.c:418",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/iomap/buffered-io.c:iomap_write_actor",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496132320,
      "name": "iov_iter_fault_in_readable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int iov_iter_fault_in_readable(struct iov_iter * i, size_t bytes)
```

```json
{
  "name": "iov_iter_fault_in_readable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229454404,
      "name": "iov_iter_fault_in_readable",
      "external": true,
      "loc": "lib/iov_iter.c:418",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/iomap/buffered-io.c:iomap_write_actor",
        "fs/fuse/file.c:fuse_perform_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229454404,
      "name": "iov_iter_fault_in_readable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
int iov_iter_fault_in_readable(struct iov_iter * i, size_t bytes)
```

```json
{
  "name": "iov_iter_fault_in_readable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290362832,
      "name": "iov_iter_fault_in_readable",
      "external": true,
      "loc": "lib/iov_iter.c:418",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/iomap/buffered-io.c:iomap_write_actor",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290362832,
      "name": "iov_iter_fault_in_readable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 740
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
int iov_iter_fault_in_readable(struct iov_iter * i, size_t bytes)
```

```json
{
  "name": "iov_iter_fault_in_readable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275176546,
      "name": "iov_iter_fault_in_readable",
      "external": true,
      "loc": "lib/iov_iter.c:418",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/iomap/buffered-io.c:iomap_write_actor",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275176546,
      "name": "iov_iter_fault_in_readable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int iov_iter_fault_in_readable(struct iov_iter * i, size_t bytes)
```

```json
{
  "name": "iov_iter_fault_in_readable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584204752,
      "name": "iov_iter_fault_in_readable",
      "external": true,
      "loc": "lib/iov_iter.c:418",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/iomap/buffered-io.c:iomap_write_actor",
        "fs/fuse/file.c:fuse_perform_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584204752,
      "name": "iov_iter_fault_in_readable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
int iov_iter_fault_in_readable(struct iov_iter * i, size_t bytes)
```

```json
{
  "name": "iov_iter_fault_in_readable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584139968,
      "name": "iov_iter_fault_in_readable",
      "external": true,
      "loc": "lib/iov_iter.c:418",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/iomap/buffered-io.c:iomap_write_actor",
        "fs/fuse/file.c:fuse_perform_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584139968,
      "name": "iov_iter_fault_in_readable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
int iov_iter_fault_in_readable(struct iov_iter * i, size_t bytes)
```

```json
{
  "name": "iov_iter_fault_in_readable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584188512,
      "name": "iov_iter_fault_in_readable",
      "external": true,
      "loc": "lib/iov_iter.c:418",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/iomap/buffered-io.c:iomap_write_actor",
        "fs/fuse/file.c:fuse_perform_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584188512,
      "name": "iov_iter_fault_in_readable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
int iov_iter_fault_in_readable(struct iov_iter * i, size_t bytes)
```

```json
{
  "name": "iov_iter_fault_in_readable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584292944,
      "name": "iov_iter_fault_in_readable",
      "external": true,
      "loc": "lib/iov_iter.c:418",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/iomap/buffered-io.c:iomap_write_actor",
        "fs/fuse/file.c:fuse_perform_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584292944,
      "name": "iov_iter_fault_in_readable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct iov_iter * i</code> ➡️ <code>const struct iov_iter * i</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int iov_iter_fault_in_readable(const struct iov_iter * i, size_t bytes)
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
