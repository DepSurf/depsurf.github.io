# Function: <code>file_modified</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int file_modified(struct file * file)
```

```json
{
  "name": "file_modified",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581904912,
      "name": "file_modified",
      "external": true,
      "loc": "fs/inode.c:1904",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/fuse/file.c:__fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581904912,
      "name": "file_modified",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int file_modified(struct file * file)
```

```json
{
  "name": "file_modified",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581977424,
      "name": "file_modified",
      "external": true,
      "loc": "fs/inode.c:1915",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/fuse/file.c:__fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581977424,
      "name": "file_modified",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int file_modified(struct file * file)
```

```json
{
  "name": "file_modified",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582210592,
      "name": "file_modified",
      "external": true,
      "loc": "fs/inode.c:1999",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dio_write_checks",
        "fs/ext4/file.c:ext4_buffered_write_iter",
        "fs/fuse/file.c:__fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582210592,
      "name": "file_modified",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int file_modified(struct file * file)
```

```json
{
  "name": "file_modified",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582258080,
      "name": "file_modified",
      "external": true,
      "loc": "fs/inode.c:2000",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/remap_range.c:generic_remap_file_range_prep",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dio_write_checks",
        "fs/ext4/file.c:ext4_buffered_write_iter",
        "fs/fuse/file.c:__fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582258080,
      "name": "file_modified",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int file_modified(struct file * file)
```

```json
{
  "name": "file_modified",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582283488,
      "name": "file_modified",
      "external": true,
      "loc": "fs/inode.c:2009",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/remap_range.c:generic_remap_file_range_prep",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/file.c:ext4_buffered_write_iter",
        "fs/fuse/file.c:__fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582283488,
      "name": "file_modified",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int file_modified(struct file * file)
```

```json
{
  "name": "file_modified",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582601728,
      "name": "file_modified",
      "external": true,
      "loc": "fs/inode.c:2014",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/remap_range.c:generic_remap_file_range_prep",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_buffered_write_iter",
        "fs/fuse/file.c:__fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582601728,
      "name": "file_modified",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int file_modified(struct file * file)
```

```json
{
  "name": "file_modified",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583137888,
      "name": "file_modified",
      "external": true,
      "loc": "fs/inode.c:2095",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/remap_range.c:generic_remap_file_range_prep",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_buffered_write_iter",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/fuse/file.c:__fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583137888,
      "name": "file_modified",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int file_modified(struct file * file)
```

```json
{
  "name": "file_modified",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583709376,
      "name": "file_modified",
      "external": true,
      "loc": "fs/inode.c:2144",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fallocate",
        "fs/remap_range.c:__generic_remap_file_range_prep",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_buffered_write_iter",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583709376,
      "name": "file_modified",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int file_modified(struct file * file)
```

```json
{
  "name": "file_modified",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583926848,
      "name": "file_modified",
      "external": true,
      "loc": "fs/inode.c:2188",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fallocate",
        "fs/remap_range.c:__generic_remap_file_range_prep",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_buffered_write_iter",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583926848,
      "name": "file_modified",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int file_modified(struct file * file)
```

```json
{
  "name": "file_modified",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584132704,
      "name": "file_modified",
      "external": true,
      "loc": "fs/inode.c:2191",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fallocate",
        "fs/remap_range.c:__generic_remap_file_range_prep",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dio_write_checks",
        "fs/ext4/file.c:ext4_buffered_write_iter",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584132704,
      "name": "file_modified",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int file_modified(struct file * file)
```

```json
{
  "name": "file_modified",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493483400,
      "name": "file_modified",
      "external": true,
      "loc": "fs/inode.c:1915",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/fuse/file.c:__fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493483400,
      "name": "file_modified",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int file_modified(struct file * file)
```

```json
{
  "name": "file_modified",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227048528,
      "name": "file_modified",
      "external": true,
      "loc": "fs/inode.c:1915",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/fuse/file.c:__fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227048528,
      "name": "file_modified",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int file_modified(struct file * file)
```

```json
{
  "name": "file_modified",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287046976,
      "name": "file_modified",
      "external": true,
      "loc": "fs/inode.c:1915",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/fuse/file.c:__fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287046976,
      "name": "file_modified",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int file_modified(struct file * file)
```

```json
{
  "name": "file_modified",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273161044,
      "name": "file_modified",
      "external": true,
      "loc": "fs/inode.c:1915",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/fuse/file.c:__fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273161044,
      "name": "file_modified",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int file_modified(struct file * file)
```

```json
{
  "name": "file_modified",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581946160,
      "name": "file_modified",
      "external": true,
      "loc": "fs/inode.c:1915",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/fuse/file.c:__fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581946160,
      "name": "file_modified",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int file_modified(struct file * file)
```

```json
{
  "name": "file_modified",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581883728,
      "name": "file_modified",
      "external": true,
      "loc": "fs/inode.c:1915",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/fuse/file.c:__fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581883728,
      "name": "file_modified",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int file_modified(struct file * file)
```

```json
{
  "name": "file_modified",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581937472,
      "name": "file_modified",
      "external": true,
      "loc": "fs/inode.c:1915",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/fuse/file.c:__fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581937472,
      "name": "file_modified",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int file_modified(struct file * file)
```

```json
{
  "name": "file_modified",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582009456,
      "name": "file_modified",
      "external": true,
      "loc": "fs/inode.c:1915",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/fuse/file.c:__fuse_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582009456,
      "name": "file_modified",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int file_modified(struct file * file)
```
</details>
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
