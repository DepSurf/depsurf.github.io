# Function: <code>kernfs_put_active</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void kernfs_put_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581509056,
      "name": "kernfs_put_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:472",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rmdir",
        "fs/kernfs/dir.c:kernfs_iop_mkdir",
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/file.c:kernfs_seq_stop_active",
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
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581509056,
      "name": "kernfs_put_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void kernfs_put_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581694464,
      "name": "kernfs_put_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:471",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_iop_rename",
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
        "fs/kernfs/file.c:kernfs_fop_write",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_seq_stop_active"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581694464,
      "name": "kernfs_put_active",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void kernfs_put_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581782416,
      "name": "kernfs_put_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:421",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_iop_rename",
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
        "fs/kernfs/file.c:kernfs_fop_write",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_seq_stop_active"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581782416,
      "name": "kernfs_put_active",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void kernfs_put_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581837168,
      "name": "kernfs_put_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:431",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_iop_rename",
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
        "fs/kernfs/file.c:kernfs_fop_write",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_seq_stop_active"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581837168,
      "name": "kernfs_put_active",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void kernfs_put_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581986768,
      "name": "kernfs_put_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:432",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_iop_rename",
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
        "fs/kernfs/file.c:kernfs_fop_write",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_seq_stop_active"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581986768,
      "name": "kernfs_put_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void kernfs_put_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582174304,
      "name": "kernfs_put_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:432",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_iop_rename",
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
        "fs/kernfs/file.c:kernfs_fop_write",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_seq_stop_active"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582174304,
      "name": "kernfs_put_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void kernfs_put_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582269392,
      "name": "kernfs_put_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:432",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_iop_rename",
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
        "fs/kernfs/file.c:kernfs_fop_write",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_seq_stop_active"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582269392,
      "name": "kernfs_put_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void kernfs_put_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582433824,
      "name": "kernfs_put_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:431",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_iop_rename",
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
        "fs/kernfs/file.c:kernfs_fop_write",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_seq_stop_active"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582433824,
      "name": "kernfs_put_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void kernfs_put_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582532560,
      "name": "kernfs_put_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:433",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_iop_rename",
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
        "fs/kernfs/file.c:kernfs_fop_write",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_seq_stop_active"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582532560,
      "name": "kernfs_put_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void kernfs_put_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582838448,
      "name": "kernfs_put_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:433",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_iop_rename",
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
        "fs/kernfs/file.c:kernfs_fop_write",
        "fs/kernfs/file.c:kernfs_file_direct_read",
        "fs/kernfs/file.c:kernfs_file_direct_read",
        "fs/kernfs/file.c:kernfs_seq_stop",
        "fs/kernfs/file.c:kernfs_seq_next",
        "fs/kernfs/file.c:kernfs_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582838448,
      "name": "kernfs_put_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void kernfs_put_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582911200,
      "name": "kernfs_put_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:433",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_iop_rename",
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
        "fs/kernfs/file.c:kernfs_fop_write_iter",
        "fs/kernfs/file.c:kernfs_file_read_iter",
        "fs/kernfs/file.c:kernfs_file_read_iter",
        "fs/kernfs/file.c:kernfs_seq_stop",
        "fs/kernfs/file.c:kernfs_seq_next",
        "fs/kernfs/file.c:kernfs_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582911200,
      "name": "kernfs_put_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void kernfs_put_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582938640,
      "name": "kernfs_put_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:433",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_iop_rename",
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
        "fs/kernfs/file.c:kernfs_fop_write_iter",
        "fs/kernfs/file.c:kernfs_file_read_iter",
        "fs/kernfs/file.c:kernfs_file_read_iter",
        "fs/kernfs/file.c:kernfs_seq_stop",
        "fs/kernfs/file.c:kernfs_seq_next",
        "fs/kernfs/file.c:kernfs_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582938640,
      "name": "kernfs_put_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void kernfs_put_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583273760,
      "name": "kernfs_put_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:435",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_iop_rename",
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
        "fs/kernfs/file.c:kernfs_fop_write_iter",
        "fs/kernfs/file.c:kernfs_file_read_iter",
        "fs/kernfs/file.c:kernfs_file_read_iter",
        "fs/kernfs/file.c:kernfs_seq_stop",
        "fs/kernfs/file.c:kernfs_seq_next",
        "fs/kernfs/file.c:kernfs_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583273760,
      "name": "kernfs_put_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void kernfs_put_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583777632,
      "name": "kernfs_put_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:442",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_iop_rename",
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
        "fs/kernfs/file.c:kernfs_fop_write_iter",
        "fs/kernfs/file.c:kernfs_file_read_iter",
        "fs/kernfs/file.c:kernfs_file_read_iter",
        "fs/kernfs/file.c:kernfs_seq_stop",
        "fs/kernfs/file.c:kernfs_seq_next",
        "fs/kernfs/file.c:kernfs_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583777632,
      "name": "kernfs_put_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void kernfs_put_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584395776,
      "name": "kernfs_put_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:453",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_iop_rename",
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
        "fs/kernfs/file.c:kernfs_fop_write_iter",
        "fs/kernfs/file.c:kernfs_file_read_iter",
        "fs/kernfs/file.c:kernfs_file_read_iter",
        "fs/kernfs/file.c:kernfs_seq_stop",
        "fs/kernfs/file.c:kernfs_seq_next",
        "fs/kernfs/file.c:kernfs_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584395776,
      "name": "kernfs_put_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void kernfs_put_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584624208,
      "name": "kernfs_put_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:450",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_iop_rename",
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
        "fs/kernfs/file.c:kernfs_fop_write_iter",
        "fs/kernfs/file.c:kernfs_file_read_iter",
        "fs/kernfs/file.c:kernfs_file_read_iter",
        "fs/kernfs/file.c:kernfs_seq_stop",
        "fs/kernfs/file.c:kernfs_seq_next",
        "fs/kernfs/file.c:kernfs_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584624208,
      "name": "kernfs_put_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void kernfs_put_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584856704,
      "name": "kernfs_put_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:454",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_iop_rename",
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
        "fs/kernfs/file.c:kernfs_fop_write_iter",
        "fs/kernfs/file.c:kernfs_file_read_iter",
        "fs/kernfs/file.c:kernfs_file_read_iter",
        "fs/kernfs/file.c:kernfs_seq_stop",
        "fs/kernfs/file.c:kernfs_seq_next",
        "fs/kernfs/file.c:kernfs_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584856704,
      "name": "kernfs_put_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void kernfs_put_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494165976,
      "name": "kernfs_put_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:433",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rmdir",
        "fs/kernfs/dir.c:kernfs_iop_mkdir",
        "fs/kernfs/file.c:kernfs_fop_poll",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_mmap",
        "fs/kernfs/file.c:kernfs_vma_get_policy",
        "fs/kernfs/file.c:kernfs_vma_set_policy",
        "fs/kernfs/file.c:kernfs_vma_access",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/kernfs/file.c:kernfs_vma_fault",
        "fs/kernfs/file.c:kernfs_vma_open",
        "fs/kernfs/file.c:kernfs_fop_write",
        "fs/kernfs/file.c:kernfs_fop_write",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_seq_stop_active"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494165976,
      "name": "kernfs_put_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void kernfs_put_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227606032,
      "name": "kernfs_put_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:433",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_iop_rename",
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
        "fs/kernfs/file.c:kernfs_fop_write",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_seq_stop_active"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227606032,
      "name": "kernfs_put_active",
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
void kernfs_put_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287849552,
      "name": "kernfs_put_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:433",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rmdir",
        "fs/kernfs/dir.c:kernfs_iop_mkdir",
        "fs/kernfs/file.c:kernfs_fop_poll",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_mmap",
        "fs/kernfs/file.c:kernfs_vma_get_policy",
        "fs/kernfs/file.c:kernfs_vma_set_policy",
        "fs/kernfs/file.c:kernfs_vma_access",
        "fs/kernfs/file.c:kernfs_vma_page_mkwrite",
        "fs/kernfs/file.c:kernfs_vma_fault",
        "fs/kernfs/file.c:kernfs_vma_open",
        "fs/kernfs/file.c:kernfs_fop_write",
        "fs/kernfs/file.c:kernfs_fop_write",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_seq_stop_active"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287849552,
      "name": "kernfs_put_active",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void kernfs_put_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273637864,
      "name": "kernfs_put_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:433",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rmdir",
        "fs/kernfs/dir.c:kernfs_iop_mkdir"
      ],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_iop_rename",
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
        "fs/kernfs/file.c:kernfs_fop_write",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_seq_stop_active"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273631790,
      "name": "kernfs_put_active.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446743936273635832,
      "name": "kernfs_put_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void kernfs_put_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582501296,
      "name": "kernfs_put_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:433",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_iop_rename",
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
        "fs/kernfs/file.c:kernfs_fop_write",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_seq_stop_active"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582501296,
      "name": "kernfs_put_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void kernfs_put_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582438528,
      "name": "kernfs_put_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:433",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_iop_rename",
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
        "fs/kernfs/file.c:kernfs_fop_write",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_seq_stop_active"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582438528,
      "name": "kernfs_put_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void kernfs_put_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582491776,
      "name": "kernfs_put_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:433",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_iop_rename",
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
        "fs/kernfs/file.c:kernfs_fop_write",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_seq_stop_active"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582491776,
      "name": "kernfs_put_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void kernfs_put_active(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582572400,
      "name": "kernfs_put_active",
      "external": true,
      "loc": "fs/kernfs/dir.c:433",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_iop_rename",
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
        "fs/kernfs/file.c:kernfs_fop_write",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_fop_read",
        "fs/kernfs/file.c:kernfs_seq_stop_active"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582572400,
      "name": "kernfs_put_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
