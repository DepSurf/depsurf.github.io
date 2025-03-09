# Function: <code>copy_page_from_iter_atomic</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
size_t copy_page_from_iter_atomic(struct page * page, unsigned int offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_from_iter_atomic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_page_from_iter_atomic",
      "external": true,
      "loc": "lib/iov_iter.c:911",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
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
      "addr": 18446744071592323243,
      "name": "copy_page_from_iter_atomic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071585222016,
      "name": "copy_page_from_iter_atomic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1752
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
size_t copy_page_from_iter_atomic(struct page * page, unsigned int offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_from_iter_atomic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_page_from_iter_atomic",
      "external": true,
      "loc": "lib/iov_iter.c:963",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/iomap/buffered-io.c:iomap_write_iter",
        "fs/fuse/file.c:fuse_fill_write_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594127256,
      "name": "copy_page_from_iter_atomic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071586065648,
      "name": "copy_page_from_iter_atomic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1868
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
size_t copy_page_from_iter_atomic(struct page * page, unsigned int offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_from_iter_atomic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_page_from_iter_atomic",
      "external": true,
      "loc": "lib/iov_iter.c:809",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/iomap/buffered-io.c:iomap_write_iter",
        "fs/fuse/file.c:fuse_fill_write_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596114684,
      "name": "copy_page_from_iter_atomic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071587058832,
      "name": "copy_page_from_iter_atomic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1650
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
size_t copy_page_from_iter_atomic(struct page * page, unsigned int offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_from_iter_atomic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_page_from_iter_atomic",
      "external": true,
      "loc": "lib/iov_iter.c:569",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/iomap/buffered-io.c:iomap_write_iter",
        "fs/fuse/file.c:fuse_fill_write_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596640112,
      "name": "copy_page_from_iter_atomic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071587315392,
      "name": "copy_page_from_iter_atomic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1464
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
size_t copy_page_from_iter_atomic(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_from_iter_atomic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_page_from_iter_atomic",
      "external": true,
      "loc": "lib/iov_iter.c:460",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_perform_write",
        "fs/iomap/buffered-io.c:iomap_write_iter",
        "fs/fuse/file.c:fuse_fill_write_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597548183,
      "name": "copy_page_from_iter_atomic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071587594912,
      "name": "copy_page_from_iter_atomic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1679
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
size_t copy_page_from_iter_atomic(struct page * page, unsigned int offset, size_t bytes, struct iov_iter * i)
```
</details>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int offset</code> ➡️ <code>size_t offset</code>
</li>
</ul>
</details>
</li>
</ul>
