# Function: <code>mapping_seek_hole_data</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
loff_t mapping_seek_hole_data(struct address_space * mapping, loff_t start, loff_t end, int whence)
```

```json
{
  "name": "mapping_seek_hole_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581348288,
      "name": "mapping_seek_hole_data",
      "external": true,
      "loc": "mm/filemap.c:2763",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_file_llseek",
        "fs/iomap/seek.c:iomap_seek_data_actor",
        "fs/iomap/seek.c:iomap_seek_hole_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581348288,
      "name": "mapping_seek_hole_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1386
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
loff_t mapping_seek_hole_data(struct address_space * mapping, loff_t start, loff_t end, int whence)
```

```json
{
  "name": "mapping_seek_hole_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mapping_seek_hole_data",
      "external": true,
      "loc": "mm/filemap.c:2844",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_file_llseek",
        "fs/iomap/seek.c:iomap_seek_data",
        "fs/iomap/seek.c:iomap_seek_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592189961,
      "name": "mapping_seek_hole_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071581595888,
      "name": "mapping_seek_hole_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1523
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
loff_t mapping_seek_hole_data(struct address_space * mapping, loff_t start, loff_t end, int whence)
```

```json
{
  "name": "mapping_seek_hole_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mapping_seek_hole_data",
      "external": true,
      "loc": "mm/filemap.c:2896",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_file_llseek",
        "fs/iomap/seek.c:iomap_seek_data",
        "fs/iomap/seek.c:iomap_seek_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593965214,
      "name": "mapping_seek_hole_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
    },
    {
      "addr": 18446744071581952272,
      "name": "mapping_seek_hole_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1750
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
loff_t mapping_seek_hole_data(struct address_space * mapping, loff_t start, loff_t end, int whence)
```

```json
{
  "name": "mapping_seek_hole_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mapping_seek_hole_data",
      "external": true,
      "loc": "mm/filemap.c:2903",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_file_llseek",
        "fs/iomap/buffered-io.c:iomap_write_delalloc_release",
        "fs/iomap/buffered-io.c:iomap_write_delalloc_release",
        "fs/iomap/seek.c:iomap_seek_data",
        "fs/iomap/seek.c:iomap_seek_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596024537,
      "name": "mapping_seek_hole_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
    },
    {
      "addr": 18446744071582384688,
      "name": "mapping_seek_hole_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1519
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
loff_t mapping_seek_hole_data(struct address_space * mapping, loff_t start, loff_t end, int whence)
```

```json
{
  "name": "mapping_seek_hole_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mapping_seek_hole_data",
      "external": true,
      "loc": "mm/filemap.c:3047",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_file_llseek",
        "fs/iomap/buffered-io.c:iomap_write_delalloc_release",
        "fs/iomap/buffered-io.c:iomap_write_delalloc_release",
        "fs/iomap/seek.c:iomap_seek_data",
        "fs/iomap/seek.c:iomap_seek_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596546738,
      "name": "mapping_seek_hole_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
    },
    {
      "addr": 18446744071582590912,
      "name": "mapping_seek_hole_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1545
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
loff_t mapping_seek_hole_data(struct address_space * mapping, loff_t start, loff_t end, int whence)
```

```json
{
  "name": "mapping_seek_hole_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mapping_seek_hole_data",
      "external": true,
      "loc": "mm/filemap.c:2994",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_file_llseek",
        "fs/iomap/buffered-io.c:iomap_write_delalloc_release",
        "fs/iomap/buffered-io.c:iomap_write_delalloc_release",
        "fs/iomap/seek.c:iomap_seek_data",
        "fs/iomap/seek.c:iomap_seek_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597450471,
      "name": "mapping_seek_hole_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    },
    {
      "addr": 18446744071582762112,
      "name": "mapping_seek_hole_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1533
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
loff_t mapping_seek_hole_data(struct address_space * mapping, loff_t start, loff_t end, int whence)
```
</details>
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
