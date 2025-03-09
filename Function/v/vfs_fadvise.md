# Function: <code>vfs_fadvise</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int vfs_fadvise(struct file * file, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "vfs_fadvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580966880,
      "name": "vfs_fadvise",
      "external": true,
      "loc": "mm/fadvise.c:182",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:ksys_fadvise64_64",
        "mm/readahead.c:ksys_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580966880,
      "name": "vfs_fadvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 642
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
int vfs_fadvise(struct file * file, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "vfs_fadvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581061984,
      "name": "vfs_fadvise",
      "external": true,
      "loc": "mm/fadvise.c:182",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:ksys_fadvise64_64",
        "mm/readahead.c:ksys_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581061984,
      "name": "vfs_fadvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 649
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
int vfs_fadvise(struct file * file, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "vfs_fadvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581118368,
      "name": "vfs_fadvise",
      "external": true,
      "loc": "mm/fadvise.c:182",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:ksys_fadvise64_64",
        "mm/readahead.c:ksys_readahead",
        "mm/madvise.c:__do_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581118368,
      "name": "vfs_fadvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int vfs_fadvise(struct file * file, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "vfs_fadvise",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581302208,
      "name": "vfs_fadvise",
      "external": true,
      "loc": "mm/fadvise.c:180",
      "file": "mm/fadvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/fadvise.c:ksys_fadvise64_64"
      ],
      "caller_func": [
        "mm/readahead.c:ksys_readahead",
        "mm/madvise.c:madvise_willneed",
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581302112,
      "name": "vfs_fadvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int vfs_fadvise(struct file * file, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "vfs_fadvise",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581345424,
      "name": "vfs_fadvise",
      "external": true,
      "loc": "mm/fadvise.c:181",
      "file": "mm/fadvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/fadvise.c:ksys_fadvise64_64"
      ],
      "caller_func": [
        "mm/readahead.c:ksys_readahead",
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581345328,
      "name": "vfs_fadvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int vfs_fadvise(struct file * file, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "vfs_fadvise",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581364512,
      "name": "vfs_fadvise",
      "external": true,
      "loc": "mm/fadvise.c:181",
      "file": "mm/fadvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/fadvise.c:ksys_fadvise64_64"
      ],
      "caller_func": [
        "mm/readahead.c:ksys_readahead",
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581364416,
      "name": "vfs_fadvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int vfs_fadvise(struct file * file, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "vfs_fadvise",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581612896,
      "name": "vfs_fadvise",
      "external": true,
      "loc": "mm/fadvise.c:181",
      "file": "mm/fadvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/fadvise.c:ksys_fadvise64_64"
      ],
      "caller_func": [
        "mm/readahead.c:ksys_readahead",
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581612800,
      "name": "vfs_fadvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int vfs_fadvise(struct file * file, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "vfs_fadvise",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581973124,
      "name": "vfs_fadvise",
      "external": true,
      "loc": "mm/fadvise.c:180",
      "file": "mm/fadvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/fadvise.c:ksys_fadvise64_64"
      ],
      "caller_func": [
        "mm/readahead.c:ksys_readahead",
        "mm/madvise.c:madvise_vma_behavior",
        "io_uring/io_uring.c:io_fadvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581973008,
      "name": "vfs_fadvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int vfs_fadvise(struct file * file, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "vfs_fadvise",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582407684,
      "name": "vfs_fadvise",
      "external": true,
      "loc": "mm/fadvise.c:180",
      "file": "mm/fadvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/fadvise.c:ksys_fadvise64_64"
      ],
      "caller_func": [
        "mm/readahead.c:ksys_readahead",
        "mm/madvise.c:madvise_vma_behavior",
        "io_uring/advise.c:io_fadvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582407552,
      "name": "vfs_fadvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_fadvise(struct file * file, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "vfs_fadvise",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582613732,
      "name": "vfs_fadvise",
      "external": true,
      "loc": "mm/fadvise.c:180",
      "file": "mm/fadvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/fadvise.c:ksys_fadvise64_64"
      ],
      "caller_func": [
        "mm/readahead.c:ksys_readahead",
        "mm/madvise.c:madvise_vma_behavior",
        "io_uring/advise.c:io_fadvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582613584,
      "name": "vfs_fadvise",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_fadvise(struct file * file, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "vfs_fadvise",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582785300,
      "name": "vfs_fadvise",
      "external": true,
      "loc": "mm/fadvise.c:180",
      "file": "mm/fadvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/fadvise.c:ksys_fadvise64_64"
      ],
      "caller_func": [
        "mm/readahead.c:ksys_readahead",
        "mm/madvise.c:madvise_vma_behavior",
        "io_uring/advise.c:io_fadvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582785152,
      "name": "vfs_fadvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int vfs_fadvise(struct file * file, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "vfs_fadvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492487272,
      "name": "vfs_fadvise",
      "external": true,
      "loc": "mm/fadvise.c:182",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:ksys_fadvise64_64",
        "mm/readahead.c:ksys_readahead",
        "mm/madvise.c:__arm64_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492487272,
      "name": "vfs_fadvise",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int vfs_fadvise(struct file * file, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "vfs_fadvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226360416,
      "name": "vfs_fadvise",
      "external": true,
      "loc": "mm/fadvise.c:182",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:ksys_fadvise64_64",
        "mm/readahead.c:ksys_readahead",
        "mm/madvise.c:__se_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226360416,
      "name": "vfs_fadvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int vfs_fadvise(struct file * file, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "vfs_fadvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285773728,
      "name": "vfs_fadvise",
      "external": true,
      "loc": "mm/fadvise.c:182",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:ksys_fadvise64_64",
        "mm/readahead.c:ksys_readahead",
        "mm/madvise.c:__se_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285773728,
      "name": "vfs_fadvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int vfs_fadvise(struct file * file, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "vfs_fadvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272551490,
      "name": "vfs_fadvise",
      "external": true,
      "loc": "mm/fadvise.c:182",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:ksys_fadvise64_64",
        "mm/readahead.c:ksys_readahead",
        "mm/madvise.c:__se_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272551490,
      "name": "vfs_fadvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int vfs_fadvise(struct file * file, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "vfs_fadvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581087216,
      "name": "vfs_fadvise",
      "external": true,
      "loc": "mm/fadvise.c:182",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:ksys_fadvise64_64",
        "mm/readahead.c:ksys_readahead",
        "mm/madvise.c:__do_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581087216,
      "name": "vfs_fadvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int vfs_fadvise(struct file * file, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "vfs_fadvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581034400,
      "name": "vfs_fadvise",
      "external": true,
      "loc": "mm/fadvise.c:182",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:ksys_fadvise64_64",
        "mm/readahead.c:ksys_readahead",
        "mm/madvise.c:__do_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581034400,
      "name": "vfs_fadvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int vfs_fadvise(struct file * file, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "vfs_fadvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581078416,
      "name": "vfs_fadvise",
      "external": true,
      "loc": "mm/fadvise.c:182",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:ksys_fadvise64_64",
        "mm/readahead.c:ksys_readahead",
        "mm/madvise.c:__do_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581078416,
      "name": "vfs_fadvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int vfs_fadvise(struct file * file, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "vfs_fadvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581140304,
      "name": "vfs_fadvise",
      "external": true,
      "loc": "mm/fadvise.c:182",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:ksys_fadvise64_64",
        "mm/readahead.c:ksys_readahead",
        "mm/madvise.c:__do_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581140304,
      "name": "vfs_fadvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int vfs_fadvise(struct file * file, loff_t offset, loff_t len, int advice)
```
</details>
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
