# Function: <code>d_alloc_pseudo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dentry * d_alloc_pseudo(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "d_alloc_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581096416,
      "name": "d_alloc_pseudo",
      "external": true,
      "loc": "fs/dcache.c:1645",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:__shmem_file_setup",
        "mm/shmem.c:__shmem_file_setup",
        "fs/pipe.c:create_pipe_files",
        "fs/nsfs.c:ns_get_path",
        "fs/aio.c:SyS_io_setup",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581096416,
      "name": "d_alloc_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct dentry * d_alloc_pseudo(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "d_alloc_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581260576,
      "name": "d_alloc_pseudo",
      "external": true,
      "loc": "fs/dcache.c:1682",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:__shmem_file_setup",
        "mm/shmem.c:__shmem_file_setup",
        "fs/pipe.c:create_pipe_files",
        "fs/nsfs.c:ns_get_path",
        "fs/aio.c:aio_setup_ring",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581260576,
      "name": "d_alloc_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct dentry * d_alloc_pseudo(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "d_alloc_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581338624,
      "name": "d_alloc_pseudo",
      "external": true,
      "loc": "fs/dcache.c:1691",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:__shmem_file_setup",
        "mm/shmem.c:__shmem_file_setup",
        "fs/pipe.c:create_pipe_files",
        "fs/nsfs.c:__ns_get_path",
        "fs/aio.c:aio_setup_ring",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581338624,
      "name": "d_alloc_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct dentry * d_alloc_pseudo(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "d_alloc_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581393872,
      "name": "d_alloc_pseudo",
      "external": true,
      "loc": "fs/dcache.c:1721",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:create_pipe_files",
        "fs/nsfs.c:__ns_get_path",
        "fs/aio.c:aio_setup_ring",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581393872,
      "name": "d_alloc_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct dentry * d_alloc_pseudo(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "d_alloc_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581535472,
      "name": "d_alloc_pseudo",
      "external": true,
      "loc": "fs/dcache.c:1733",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:create_pipe_files",
        "fs/nsfs.c:__ns_get_path",
        "fs/aio.c:aio_setup_ring",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581535472,
      "name": "d_alloc_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct dentry * d_alloc_pseudo(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "d_alloc_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581693504,
      "name": "d_alloc_pseudo",
      "external": true,
      "loc": "fs/dcache.c:1741",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:create_pipe_files",
        "fs/aio.c:aio_setup_ring",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "net/socket.c:sock_alloc_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581693504,
      "name": "d_alloc_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct dentry * d_alloc_pseudo(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "d_alloc_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581779872,
      "name": "d_alloc_pseudo",
      "external": true,
      "loc": "fs/dcache.c:1744",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581779872,
      "name": "d_alloc_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct dentry * d_alloc_pseudo(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "d_alloc_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581897680,
      "name": "d_alloc_pseudo",
      "external": true,
      "loc": "fs/dcache.c:1816",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581897680,
      "name": "d_alloc_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct dentry * d_alloc_pseudo(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "d_alloc_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581970288,
      "name": "d_alloc_pseudo",
      "external": true,
      "loc": "fs/dcache.c:1816",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581970288,
      "name": "d_alloc_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct dentry * d_alloc_pseudo(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "d_alloc_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582202960,
      "name": "d_alloc_pseudo",
      "external": true,
      "loc": "fs/dcache.c:1837",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582202960,
      "name": "d_alloc_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct dentry * d_alloc_pseudo(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "d_alloc_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582250448,
      "name": "d_alloc_pseudo",
      "external": true,
      "loc": "fs/dcache.c:1844",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582250448,
      "name": "d_alloc_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct dentry * d_alloc_pseudo(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "d_alloc_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582276176,
      "name": "d_alloc_pseudo",
      "external": true,
      "loc": "fs/dcache.c:1871",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582276176,
      "name": "d_alloc_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct dentry * d_alloc_pseudo(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "d_alloc_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582594656,
      "name": "d_alloc_pseudo",
      "external": true,
      "loc": "fs/dcache.c:1872",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582594656,
      "name": "d_alloc_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct dentry * d_alloc_pseudo(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "d_alloc_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583124928,
      "name": "d_alloc_pseudo",
      "external": true,
      "loc": "fs/dcache.c:1897",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583124928,
      "name": "d_alloc_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
struct dentry * d_alloc_pseudo(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "d_alloc_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583695616,
      "name": "d_alloc_pseudo",
      "external": true,
      "loc": "fs/dcache.c:1897",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583695616,
      "name": "d_alloc_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
struct dentry * d_alloc_pseudo(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "d_alloc_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583913504,
      "name": "d_alloc_pseudo",
      "external": true,
      "loc": "fs/dcache.c:1897",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583913504,
      "name": "d_alloc_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
struct dentry * d_alloc_pseudo(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "d_alloc_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584119360,
      "name": "d_alloc_pseudo",
      "external": true,
      "loc": "fs/dcache.c:1751",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584119360,
      "name": "d_alloc_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
struct dentry * d_alloc_pseudo(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "d_alloc_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493474504,
      "name": "d_alloc_pseudo",
      "external": true,
      "loc": "fs/dcache.c:1816",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493474504,
      "name": "d_alloc_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct dentry * d_alloc_pseudo(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "d_alloc_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227038332,
      "name": "d_alloc_pseudo",
      "external": true,
      "loc": "fs/dcache.c:1816",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227038332,
      "name": "d_alloc_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct dentry * d_alloc_pseudo(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "d_alloc_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287034240,
      "name": "d_alloc_pseudo",
      "external": true,
      "loc": "fs/dcache.c:1816",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287034240,
      "name": "d_alloc_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct dentry * d_alloc_pseudo(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "d_alloc_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273154106,
      "name": "d_alloc_pseudo",
      "external": true,
      "loc": "fs/dcache.c:1816",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273154106,
      "name": "d_alloc_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
struct dentry * d_alloc_pseudo(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "d_alloc_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581939024,
      "name": "d_alloc_pseudo",
      "external": true,
      "loc": "fs/dcache.c:1816",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581939024,
      "name": "d_alloc_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct dentry * d_alloc_pseudo(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "d_alloc_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581876608,
      "name": "d_alloc_pseudo",
      "external": true,
      "loc": "fs/dcache.c:1816",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581876608,
      "name": "d_alloc_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct dentry * d_alloc_pseudo(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "d_alloc_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581930336,
      "name": "d_alloc_pseudo",
      "external": true,
      "loc": "fs/dcache.c:1816",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581930336,
      "name": "d_alloc_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct dentry * d_alloc_pseudo(struct super_block * sb, const struct qstr * name)
```

```json
{
  "name": "d_alloc_pseudo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582000416,
      "name": "d_alloc_pseudo",
      "external": true,
      "loc": "fs/dcache.c:1816",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_pseudo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582000416,
      "name": "d_alloc_pseudo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
