# Function: <code>__readahead_batch</code>

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
unsigned int __readahead_batch(struct readahead_control * rac, struct page * * array, unsigned int array_sz)
```

```json
{
  "name": "__readahead_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583522112,
      "name": "__readahead_batch",
      "external": false,
      "loc": "include/linux/pagemap.h:738",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583522112,
      "name": "__readahead_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
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
unsigned int __readahead_batch(struct readahead_control * rac, struct page * * array, unsigned int array_sz)
```

```json
{
  "name": "__readahead_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583634032,
      "name": "__readahead_batch",
      "external": false,
      "loc": "include/linux/pagemap.h:893",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583634032,
      "name": "__readahead_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 589
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
unsigned int __readahead_batch(struct readahead_control * rac, struct page * * array, unsigned int array_sz)
```

```json
{
  "name": "__readahead_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583654848,
      "name": "__readahead_batch",
      "external": false,
      "loc": "include/linux/pagemap.h:935",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583654848,
      "name": "__readahead_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 596
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__readahead_batch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584018259,
      "name": "__readahead_batch",
      "external": false,
      "loc": "include/linux/pagemap.h:938",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_readahead"
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
  "name": "__readahead_batch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584607448,
      "name": "__readahead_batch",
      "external": false,
      "loc": "include/linux/pagemap.h:1313",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_readahead"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
unsigned int __readahead_batch(struct readahead_control * rac, struct page * * array, unsigned int array_sz)
```

```json
{
  "name": "__readahead_batch",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585062736,
      "name": "__readahead_batch",
      "external": false,
      "loc": "include/linux/pagemap.h:1289",
      "file": "fs/squashfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_readahead"
      ]
    },
    {
      "addr": 18446744071585286552,
      "name": "__readahead_batch",
      "external": false,
      "loc": "include/linux/pagemap.h:1289",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_readahead"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585062736,
      "name": "__readahead_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 639
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
unsigned int __readahead_batch(struct readahead_control * rac, struct page * * array, unsigned int array_sz)
```

```json
{
  "name": "__readahead_batch",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585292048,
      "name": "__readahead_batch",
      "external": false,
      "loc": "include/linux/pagemap.h:1292",
      "file": "fs/squashfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_readahead"
      ]
    },
    {
      "addr": 18446744071585516911,
      "name": "__readahead_batch",
      "external": false,
      "loc": "include/linux/pagemap.h:1292",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_readahead"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585292048,
      "name": "__readahead_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
unsigned int __readahead_batch(struct readahead_control * rac, struct page * * array, unsigned int array_sz)
```

```json
{
  "name": "__readahead_batch",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585525840,
      "name": "__readahead_batch",
      "external": false,
      "loc": "include/linux/pagemap.h:1379",
      "file": "fs/squashfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_readahead"
      ]
    },
    {
      "addr": 18446744071585753807,
      "name": "__readahead_batch",
      "external": false,
      "loc": "include/linux/pagemap.h:1379",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_readahead"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585525840,
      "name": "__readahead_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 573
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
unsigned int __readahead_batch(struct readahead_control * rac, struct page * * array, unsigned int array_sz)
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
unsigned int __readahead_batch(struct readahead_control * rac, struct page * * array, unsigned int array_sz)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
unsigned int __readahead_batch(struct readahead_control * rac, struct page * * array, unsigned int array_sz)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
