# Function: <code>kernfs_get_active</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct kernfs_node * kernfs_get_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581509008,
      "name": "kernfs_get_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:452",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rmdir",
        "fs/kernfs/dir.c:kernfs_iop_mkdir"
      ],
      "caller_func": [
        "fs/kernfs/file.c:kernfs_seq_start",
        "fs/kernfs/file.c:kernfs_fop_mmap",
        "fs/kernfs/file.c:kernfs_vma_get_policy",
        "fs/kernfs/file.c:kernfs_vma_set_policy",
        "fs/kernfs/file.c:kernfs_vma_access",
        "fs/kernfs/file.c:kernfs_vma_fault",
        "fs/kernfs/file.c:kernfs_vma_open",
        "fs/kernfs/file.c:kernfs_fop_poll",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/kernfs/file.c:kernfs_fop_write",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_fop_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581509008,
      "name": "kernfs_get_active",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct kernfs_node * kernfs_get_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581694608,
      "name": "kernfs_get_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:451",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rmdir",
        "fs/kernfs/dir.c:kernfs_iop_mkdir"
      ],
      "caller_func": [
        "fs/kernfs/file.c:kernfs_fop_poll",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_mmap",
        "fs/kernfs/file.c:kernfs_vma_get_policy",
        "fs/kernfs/file.c:kernfs_vma_set_policy",
        "fs/kernfs/file.c:kernfs_vma_access",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/kernfs/file.c:kernfs_vma_fault",
        "fs/kernfs/file.c:kernfs_vma_open",
        "fs/kernfs/file.c:kernfs_fop_write",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581694400,
      "name": "kernfs_get_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
struct kernfs_node * kernfs_get_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581782569,
      "name": "kernfs_get_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:401",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rmdir",
        "fs/kernfs/dir.c:kernfs_iop_mkdir"
      ],
      "caller_func": [
        "fs/kernfs/file.c:kernfs_fop_poll",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_mmap",
        "fs/kernfs/file.c:kernfs_vma_get_policy",
        "fs/kernfs/file.c:kernfs_vma_set_policy",
        "fs/kernfs/file.c:kernfs_vma_access",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/kernfs/file.c:kernfs_vma_fault",
        "fs/kernfs/file.c:kernfs_vma_open",
        "fs/kernfs/file.c:kernfs_fop_write",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581782352,
      "name": "kernfs_get_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct kernfs_node * kernfs_get_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581837311,
      "name": "kernfs_get_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:411",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rmdir",
        "fs/kernfs/dir.c:kernfs_iop_mkdir"
      ],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rmdir",
        "fs/kernfs/dir.c:kernfs_iop_mkdir",
        "fs/kernfs/file.c:kernfs_fop_poll",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_mmap",
        "fs/kernfs/file.c:kernfs_vma_get_policy",
        "fs/kernfs/file.c:kernfs_vma_set_policy",
        "fs/kernfs/file.c:kernfs_vma_access",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/kernfs/file.c:kernfs_vma_fault",
        "fs/kernfs/file.c:kernfs_vma_open",
        "fs/kernfs/file.c:kernfs_fop_write",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581836480,
      "name": "kernfs_get_active.part.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071581837136,
      "name": "kernfs_get_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct kernfs_node * kernfs_get_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581986933,
      "name": "kernfs_get_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:412",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rmdir",
        "fs/kernfs/dir.c:kernfs_iop_mkdir"
      ],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rmdir",
        "fs/kernfs/dir.c:kernfs_iop_mkdir",
        "fs/kernfs/file.c:kernfs_fop_poll",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_mmap",
        "fs/kernfs/file.c:kernfs_vma_get_policy",
        "fs/kernfs/file.c:kernfs_vma_set_policy",
        "fs/kernfs/file.c:kernfs_vma_access",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/kernfs/file.c:kernfs_vma_fault",
        "fs/kernfs/file.c:kernfs_vma_open",
        "fs/kernfs/file.c:kernfs_fop_write",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581986080,
      "name": "kernfs_get_active.part.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071581986736,
      "name": "kernfs_get_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct kernfs_node * kernfs_get_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582174475,
      "name": "kernfs_get_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:412",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rmdir",
        "fs/kernfs/dir.c:kernfs_iop_mkdir"
      ],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rmdir",
        "fs/kernfs/dir.c:kernfs_iop_mkdir",
        "fs/kernfs/file.c:kernfs_fop_poll",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_mmap",
        "fs/kernfs/file.c:kernfs_vma_get_policy",
        "fs/kernfs/file.c:kernfs_vma_set_policy",
        "fs/kernfs/file.c:kernfs_vma_access",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/kernfs/file.c:kernfs_vma_fault",
        "fs/kernfs/file.c:kernfs_vma_open",
        "fs/kernfs/file.c:kernfs_fop_write",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582171504,
      "name": "kernfs_get_active.part.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071582174272,
      "name": "kernfs_get_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
struct kernfs_node * kernfs_get_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582269550,
      "name": "kernfs_get_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:412",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rmdir",
        "fs/kernfs/dir.c:kernfs_iop_mkdir"
      ],
      "caller_func": [
        "fs/kernfs/file.c:kernfs_fop_poll",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_mmap",
        "fs/kernfs/file.c:kernfs_vma_get_policy",
        "fs/kernfs/file.c:kernfs_vma_set_policy",
        "fs/kernfs/file.c:kernfs_vma_access",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/kernfs/file.c:kernfs_vma_fault",
        "fs/kernfs/file.c:kernfs_vma_open",
        "fs/kernfs/file.c:kernfs_fop_write",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582269312,
      "name": "kernfs_get_active",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct kernfs_node * kernfs_get_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582433992,
      "name": "kernfs_get_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:411",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rmdir",
        "fs/kernfs/dir.c:kernfs_iop_mkdir"
      ],
      "caller_func": [
        "fs/kernfs/file.c:kernfs_fop_poll",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_mmap",
        "fs/kernfs/file.c:kernfs_vma_get_policy",
        "fs/kernfs/file.c:kernfs_vma_set_policy",
        "fs/kernfs/file.c:kernfs_vma_access",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/kernfs/file.c:kernfs_vma_fault",
        "fs/kernfs/file.c:kernfs_vma_open",
        "fs/kernfs/file.c:kernfs_fop_write",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582433776,
      "name": "kernfs_get_active",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct kernfs_node * kernfs_get_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582532728,
      "name": "kernfs_get_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:413",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rmdir",
        "fs/kernfs/dir.c:kernfs_iop_mkdir"
      ],
      "caller_func": [
        "fs/kernfs/file.c:kernfs_fop_poll",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_mmap",
        "fs/kernfs/file.c:kernfs_vma_get_policy",
        "fs/kernfs/file.c:kernfs_vma_set_policy",
        "fs/kernfs/file.c:kernfs_vma_access",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/kernfs/file.c:kernfs_vma_fault",
        "fs/kernfs/file.c:kernfs_vma_open",
        "fs/kernfs/file.c:kernfs_fop_write",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582532512,
      "name": "kernfs_get_active",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct kernfs_node * kernfs_get_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582838400,
      "name": "kernfs_get_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:413",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rmdir",
        "fs/kernfs/dir.c:kernfs_iop_mkdir",
        "fs/kernfs/file.c:kernfs_fop_poll",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_mmap",
        "fs/kernfs/file.c:kernfs_vma_get_policy",
        "fs/kernfs/file.c:kernfs_vma_set_policy",
        "fs/kernfs/file.c:kernfs_vma_access",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/kernfs/file.c:kernfs_vma_fault",
        "fs/kernfs/file.c:kernfs_vma_open",
        "fs/kernfs/file.c:kernfs_fop_write",
        "fs/kernfs/file.c:kernfs_file_direct_read",
        "fs/kernfs/file.c:kernfs_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582838400,
      "name": "kernfs_get_active",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct kernfs_node * kernfs_get_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582911152,
      "name": "kernfs_get_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:413",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rmdir",
        "fs/kernfs/dir.c:kernfs_iop_mkdir",
        "fs/kernfs/file.c:kernfs_fop_poll",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_mmap",
        "fs/kernfs/file.c:kernfs_vma_get_policy",
        "fs/kernfs/file.c:kernfs_vma_set_policy",
        "fs/kernfs/file.c:kernfs_vma_access",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/kernfs/file.c:kernfs_vma_fault",
        "fs/kernfs/file.c:kernfs_vma_open",
        "fs/kernfs/file.c:kernfs_fop_write_iter",
        "fs/kernfs/file.c:kernfs_file_read_iter",
        "fs/kernfs/file.c:kernfs_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582911152,
      "name": "kernfs_get_active",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct kernfs_node * kernfs_get_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582938592,
      "name": "kernfs_get_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:413",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rmdir",
        "fs/kernfs/dir.c:kernfs_iop_mkdir",
        "fs/kernfs/file.c:kernfs_fop_poll",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_mmap",
        "fs/kernfs/file.c:kernfs_vma_get_policy",
        "fs/kernfs/file.c:kernfs_vma_set_policy",
        "fs/kernfs/file.c:kernfs_vma_access",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/kernfs/file.c:kernfs_vma_fault",
        "fs/kernfs/file.c:kernfs_vma_open",
        "fs/kernfs/file.c:kernfs_fop_write_iter",
        "fs/kernfs/file.c:kernfs_file_read_iter",
        "fs/kernfs/file.c:kernfs_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582938592,
      "name": "kernfs_get_active",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct kernfs_node * kernfs_get_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583273712,
      "name": "kernfs_get_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:415",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rmdir",
        "fs/kernfs/dir.c:kernfs_iop_mkdir",
        "fs/kernfs/file.c:kernfs_fop_poll",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_mmap",
        "fs/kernfs/file.c:kernfs_vma_get_policy",
        "fs/kernfs/file.c:kernfs_vma_set_policy",
        "fs/kernfs/file.c:kernfs_vma_access",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/kernfs/file.c:kernfs_vma_fault",
        "fs/kernfs/file.c:kernfs_vma_open",
        "fs/kernfs/file.c:kernfs_fop_write_iter",
        "fs/kernfs/file.c:kernfs_file_read_iter",
        "fs/kernfs/file.c:kernfs_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583273712,
      "name": "kernfs_get_active",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct kernfs_node * kernfs_get_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583777568,
      "name": "kernfs_get_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:422",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rmdir",
        "fs/kernfs/dir.c:kernfs_iop_mkdir",
        "fs/kernfs/file.c:kernfs_fop_poll",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_mmap",
        "fs/kernfs/file.c:kernfs_vma_get_policy",
        "fs/kernfs/file.c:kernfs_vma_set_policy",
        "fs/kernfs/file.c:kernfs_vma_access",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/kernfs/file.c:kernfs_vma_fault",
        "fs/kernfs/file.c:kernfs_vma_open",
        "fs/kernfs/file.c:kernfs_fop_write_iter",
        "fs/kernfs/file.c:kernfs_file_read_iter",
        "fs/kernfs/file.c:kernfs_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583777568,
      "name": "kernfs_get_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct kernfs_node * kernfs_get_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584395696,
      "name": "kernfs_get_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:433",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rmdir",
        "fs/kernfs/dir.c:kernfs_iop_mkdir",
        "fs/kernfs/file.c:kernfs_fop_poll",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_mmap",
        "fs/kernfs/file.c:kernfs_vma_get_policy",
        "fs/kernfs/file.c:kernfs_vma_set_policy",
        "fs/kernfs/file.c:kernfs_vma_access",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/kernfs/file.c:kernfs_vma_fault",
        "fs/kernfs/file.c:kernfs_vma_open",
        "fs/kernfs/file.c:kernfs_fop_write_iter",
        "fs/kernfs/file.c:kernfs_file_read_iter",
        "fs/kernfs/file.c:kernfs_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584395696,
      "name": "kernfs_get_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct kernfs_node * kernfs_get_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584624128,
      "name": "kernfs_get_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:430",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rmdir",
        "fs/kernfs/dir.c:kernfs_iop_mkdir",
        "fs/kernfs/file.c:kernfs_fop_poll",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_mmap",
        "fs/kernfs/file.c:kernfs_vma_get_policy",
        "fs/kernfs/file.c:kernfs_vma_set_policy",
        "fs/kernfs/file.c:kernfs_vma_access",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/kernfs/file.c:kernfs_vma_fault",
        "fs/kernfs/file.c:kernfs_vma_open",
        "fs/kernfs/file.c:kernfs_fop_write_iter",
        "fs/kernfs/file.c:kernfs_file_read_iter",
        "fs/kernfs/file.c:kernfs_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584624128,
      "name": "kernfs_get_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct kernfs_node * kernfs_get_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584856624,
      "name": "kernfs_get_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:434",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rmdir",
        "fs/kernfs/dir.c:kernfs_iop_mkdir",
        "fs/kernfs/file.c:kernfs_fop_llseek",
        "fs/kernfs/file.c:kernfs_fop_poll",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_mmap",
        "fs/kernfs/file.c:kernfs_vma_access",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/kernfs/file.c:kernfs_vma_fault",
        "fs/kernfs/file.c:kernfs_vma_open",
        "fs/kernfs/file.c:kernfs_fop_write_iter",
        "fs/kernfs/file.c:kernfs_file_read_iter",
        "fs/kernfs/file.c:kernfs_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584856624,
      "name": "kernfs_get_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct kernfs_node * kernfs_get_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494166212,
      "name": "kernfs_get_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:413",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rmdir",
        "fs/kernfs/dir.c:kernfs_iop_mkdir"
      ],
      "caller_func": [
        "fs/kernfs/file.c:kernfs_fop_poll",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_mmap",
        "fs/kernfs/file.c:kernfs_vma_get_policy",
        "fs/kernfs/file.c:kernfs_vma_set_policy",
        "fs/kernfs/file.c:kernfs_vma_access",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/kernfs/file.c:kernfs_vma_fault",
        "fs/kernfs/file.c:kernfs_vma_open",
        "fs/kernfs/file.c:kernfs_fop_write",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494165840,
      "name": "kernfs_get_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
struct kernfs_node * kernfs_get_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227606232,
      "name": "kernfs_get_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:413",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rmdir",
        "fs/kernfs/dir.c:kernfs_iop_mkdir"
      ],
      "caller_func": [
        "fs/kernfs/file.c:kernfs_fop_poll",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_mmap",
        "fs/kernfs/file.c:kernfs_vma_access",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/kernfs/file.c:kernfs_vma_fault",
        "fs/kernfs/file.c:kernfs_vma_open",
        "fs/kernfs/file.c:kernfs_fop_write",
        "fs/kernfs/file.c:kernfs_fop_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227605920,
      "name": "kernfs_get_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct kernfs_node * kernfs_get_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287849808,
      "name": "kernfs_get_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:413",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rmdir",
        "fs/kernfs/dir.c:kernfs_iop_mkdir"
      ],
      "caller_func": [
        "fs/kernfs/file.c:kernfs_fop_poll",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_mmap",
        "fs/kernfs/file.c:kernfs_vma_get_policy",
        "fs/kernfs/file.c:kernfs_vma_set_policy",
        "fs/kernfs/file.c:kernfs_vma_access",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/kernfs/file.c:kernfs_vma_fault",
        "fs/kernfs/file.c:kernfs_vma_open",
        "fs/kernfs/file.c:kernfs_fop_write",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287849440,
      "name": "kernfs_get_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
struct kernfs_node * kernfs_get_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273635194,
      "name": "kernfs_get_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:413",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rmdir",
        "fs/kernfs/dir.c:kernfs_iop_mkdir",
        "fs/kernfs/file.c:kernfs_fop_poll",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_mmap",
        "fs/kernfs/file.c:kernfs_vma_access",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/kernfs/file.c:kernfs_vma_fault",
        "fs/kernfs/file.c:kernfs_vma_open",
        "fs/kernfs/file.c:kernfs_fop_write",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273635194,
      "name": "kernfs_get_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct kernfs_node * kernfs_get_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582501464,
      "name": "kernfs_get_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:413",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rmdir",
        "fs/kernfs/dir.c:kernfs_iop_mkdir"
      ],
      "caller_func": [
        "fs/kernfs/file.c:kernfs_fop_poll",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_mmap",
        "fs/kernfs/file.c:kernfs_vma_get_policy",
        "fs/kernfs/file.c:kernfs_vma_set_policy",
        "fs/kernfs/file.c:kernfs_vma_access",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/kernfs/file.c:kernfs_vma_fault",
        "fs/kernfs/file.c:kernfs_vma_open",
        "fs/kernfs/file.c:kernfs_fop_write",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582501248,
      "name": "kernfs_get_active",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct kernfs_node * kernfs_get_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582438696,
      "name": "kernfs_get_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:413",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rmdir",
        "fs/kernfs/dir.c:kernfs_iop_mkdir"
      ],
      "caller_func": [
        "fs/kernfs/file.c:kernfs_fop_poll",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_mmap",
        "fs/kernfs/file.c:kernfs_vma_get_policy",
        "fs/kernfs/file.c:kernfs_vma_set_policy",
        "fs/kernfs/file.c:kernfs_vma_access",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/kernfs/file.c:kernfs_vma_fault",
        "fs/kernfs/file.c:kernfs_vma_open",
        "fs/kernfs/file.c:kernfs_fop_write",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582438480,
      "name": "kernfs_get_active",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct kernfs_node * kernfs_get_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582491944,
      "name": "kernfs_get_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:413",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rmdir",
        "fs/kernfs/dir.c:kernfs_iop_mkdir"
      ],
      "caller_func": [
        "fs/kernfs/file.c:kernfs_fop_poll",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_mmap",
        "fs/kernfs/file.c:kernfs_vma_get_policy",
        "fs/kernfs/file.c:kernfs_vma_set_policy",
        "fs/kernfs/file.c:kernfs_vma_access",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/kernfs/file.c:kernfs_vma_fault",
        "fs/kernfs/file.c:kernfs_vma_open",
        "fs/kernfs/file.c:kernfs_fop_write",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582491728,
      "name": "kernfs_get_active",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct kernfs_node * kernfs_get_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582572568,
      "name": "kernfs_get_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:413",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rmdir",
        "fs/kernfs/dir.c:kernfs_iop_mkdir"
      ],
      "caller_func": [
        "fs/kernfs/file.c:kernfs_fop_poll",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_mmap",
        "fs/kernfs/file.c:kernfs_vma_get_policy",
        "fs/kernfs/file.c:kernfs_vma_set_policy",
        "fs/kernfs/file.c:kernfs_vma_access",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/kernfs/file.c:kernfs_vma_fault",
        "fs/kernfs/file.c:kernfs_vma_open",
        "fs/kernfs/file.c:kernfs_fop_write",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582572352,
      "name": "kernfs_get_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
