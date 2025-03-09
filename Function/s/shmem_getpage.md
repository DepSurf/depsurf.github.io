# Function: <code>shmem_getpage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "shmem_getpage",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580589350,
      "name": "shmem_getpage",
      "external": false,
      "loc": "mm/shmem.c:131",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_follow_link",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_splice_read",
        "mm/shmem.c:shmem_file_splice_read",
        "mm/shmem.c:shmem_fault",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_symlink"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int shmem_getpage(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp)
```

```json
{
  "name": "shmem_getpage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580692740,
      "name": "shmem_getpage",
      "external": true,
      "loc": "mm/shmem.c:124",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_splice_read",
        "mm/shmem.c:shmem_file_splice_read",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": [
        "mm/khugepaged.c:collapse_shmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580694784,
      "name": "shmem_getpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int shmem_getpage(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp)
```

```json
{
  "name": "shmem_getpage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580758416,
      "name": "shmem_getpage",
      "external": true,
      "loc": "mm/shmem.c:120",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": [
        "mm/khugepaged.c:collapse_shmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580760432,
      "name": "shmem_getpage",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int shmem_getpage(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp)
```

```json
{
  "name": "shmem_getpage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580788753,
      "name": "shmem_getpage",
      "external": true,
      "loc": "mm/shmem.c:131",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": [
        "mm/khugepaged.c:collapse_shmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580795136,
      "name": "shmem_getpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int shmem_getpage(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp)
```

```json
{
  "name": "shmem_getpage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580878241,
      "name": "shmem_getpage",
      "external": true,
      "loc": "mm/shmem.c:132",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": [
        "mm/khugepaged.c:collapse_shmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580884944,
      "name": "shmem_getpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int shmem_getpage(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp)
```

```json
{
  "name": "shmem_getpage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581015325,
      "name": "shmem_getpage",
      "external": true,
      "loc": "mm/shmem.c:132",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": [
        "mm/khugepaged.c:collapse_shmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581021296,
      "name": "shmem_getpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int shmem_getpage(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp)
```

```json
{
  "name": "shmem_getpage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581088698,
      "name": "shmem_getpage",
      "external": true,
      "loc": "mm/shmem.c:134",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": [
        "mm/khugepaged.c:collapse_shmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581098928,
      "name": "shmem_getpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int shmem_getpage(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp)
```

```json
{
  "name": "shmem_getpage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581160426,
      "name": "shmem_getpage",
      "external": true,
      "loc": "mm/shmem.c:139",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": [
        "mm/khugepaged.c:collapse_shmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581164160,
      "name": "shmem_getpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int shmem_getpage(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp)
```

```json
{
  "name": "shmem_getpage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581218346,
      "name": "shmem_getpage",
      "external": true,
      "loc": "mm/shmem.c:154",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": [
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581222080,
      "name": "shmem_getpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int shmem_getpage(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp)
```

```json
{
  "name": "shmem_getpage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581399018,
      "name": "shmem_getpage",
      "external": true,
      "loc": "mm/shmem.c:153",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": [
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581409600,
      "name": "shmem_getpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int shmem_getpage(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp)
```

```json
{
  "name": "shmem_getpage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581444954,
      "name": "shmem_getpage",
      "external": true,
      "loc": "mm/shmem.c:152",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": [
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581451760,
      "name": "shmem_getpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int shmem_getpage(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp)
```

```json
{
  "name": "shmem_getpage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581465804,
      "name": "shmem_getpage",
      "external": true,
      "loc": "mm/shmem.c:152",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": [
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581472704,
      "name": "shmem_getpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int shmem_getpage(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp)
```

```json
{
  "name": "shmem_getpage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581720540,
      "name": "shmem_getpage",
      "external": true,
      "loc": "mm/shmem.c:148",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": [
        "mm/khugepaged.c:collapse_file",
        "mm/userfaultfd.c:mcopy_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581718720,
      "name": "shmem_getpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int shmem_getpage(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp)
```

```json
{
  "name": "shmem_getpage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582099587,
      "name": "shmem_getpage",
      "external": true,
      "loc": "mm/shmem.c:146",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin"
      ],
      "caller_func": [
        "mm/khugepaged.c:collapse_file",
        "mm/userfaultfd.c:mcopy_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582105424,
      "name": "shmem_getpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int shmem_getpage(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp)
```

```json
{
  "name": "shmem_getpage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492603616,
      "name": "shmem_getpage",
      "external": true,
      "loc": "mm/shmem.c:154",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": [
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492607688,
      "name": "shmem_getpage",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int shmem_getpage(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp)
```

```json
{
  "name": "shmem_getpage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226458764,
      "name": "shmem_getpage",
      "external": true,
      "loc": "mm/shmem.c:154",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226462356,
      "name": "shmem_getpage",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int shmem_getpage(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp)
```

```json
{
  "name": "shmem_getpage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285921732,
      "name": "shmem_getpage",
      "external": true,
      "loc": "mm/shmem.c:154",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": [
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285926208,
      "name": "shmem_getpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int shmem_getpage(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp)
```

```json
{
  "name": "shmem_getpage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272634728,
      "name": "shmem_getpage",
      "external": true,
      "loc": "mm/shmem.c:154",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272637422,
      "name": "shmem_getpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int shmem_getpage(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp)
```

```json
{
  "name": "shmem_getpage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581187194,
      "name": "shmem_getpage",
      "external": true,
      "loc": "mm/shmem.c:154",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": [
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581190928,
      "name": "shmem_getpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int shmem_getpage(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp)
```

```json
{
  "name": "shmem_getpage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581133946,
      "name": "shmem_getpage",
      "external": true,
      "loc": "mm/shmem.c:154",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": [
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581137680,
      "name": "shmem_getpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int shmem_getpage(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp)
```

```json
{
  "name": "shmem_getpage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581178394,
      "name": "shmem_getpage",
      "external": true,
      "loc": "mm/shmem.c:154",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": [
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581182128,
      "name": "shmem_getpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int shmem_getpage(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp)
```

```json
{
  "name": "shmem_getpage",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581241610,
      "name": "shmem_getpage",
      "external": true,
      "loc": "mm/shmem.c:154",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": [
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581245360,
      "name": "shmem_getpage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int shmem_getpage(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp)
```
</details>
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
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int shmem_getpage(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp)
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
