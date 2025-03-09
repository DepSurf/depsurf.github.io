# Function: <code>shmem_getpage_gfp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int shmem_getpage_gfp(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, int * fault_type)
```

```json
{
  "name": "shmem_getpage_gfp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580586032,
      "name": "shmem_getpage_gfp",
      "external": false,
      "loc": "mm/shmem.c:1064",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580586032,
      "name": "shmem_getpage_gfp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2088
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
int shmem_getpage_gfp(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, struct mm_struct * fault_mm, int * fault_type)
```

```json
{
  "name": "shmem_getpage_gfp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580682000,
      "name": "shmem_getpage_gfp",
      "external": false,
      "loc": "mm/shmem.c:1544",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_splice_read",
        "mm/shmem.c:shmem_file_splice_read",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_fault",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580682000,
      "name": "shmem_getpage_gfp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3037
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
int shmem_getpage_gfp(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, struct mm_struct * fault_mm, int * fault_type)
```

```json
{
  "name": "shmem_getpage_gfp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580749040,
      "name": "shmem_getpage_gfp",
      "external": false,
      "loc": "mm/shmem.c:1571",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_fault",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580749040,
      "name": "shmem_getpage_gfp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3083
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
int shmem_getpage_gfp(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, struct vm_fault * vmf, int * fault_type)
```

```json
{
  "name": "shmem_getpage_gfp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580784528,
      "name": "shmem_getpage_gfp",
      "external": false,
      "loc": "mm/shmem.c:1596",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_fault",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580784528,
      "name": "shmem_getpage_gfp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2876
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
int shmem_getpage_gfp(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, struct vm_fault * vmf, int * fault_type)
```

```json
{
  "name": "shmem_getpage_gfp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580873824,
      "name": "shmem_getpage_gfp",
      "external": false,
      "loc": "mm/shmem.c:1611",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_fault",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580873824,
      "name": "shmem_getpage_gfp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3017
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
int shmem_getpage_gfp(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, struct vm_fault * vmf, int * fault_type)
```

```json
{
  "name": "shmem_getpage_gfp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581010624,
      "name": "shmem_getpage_gfp",
      "external": false,
      "loc": "mm/shmem.c:1630",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_fault",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581010624,
      "name": "shmem_getpage_gfp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3313
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
int shmem_getpage_gfp(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, struct vm_fault * vmf, vm_fault_t * fault_type)
```

```json
{
  "name": "shmem_getpage_gfp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581084400,
      "name": "shmem_getpage_gfp",
      "external": false,
      "loc": "mm/shmem.c:1596",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_fault",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581084400,
      "name": "shmem_getpage_gfp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3223
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
int shmem_getpage_gfp(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, struct vm_fault * vmf, vm_fault_t * fault_type)
```

```json
{
  "name": "shmem_getpage_gfp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581152992,
      "name": "shmem_getpage_gfp",
      "external": false,
      "loc": "mm/shmem.c:1733",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_fault",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581152992,
      "name": "shmem_getpage_gfp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2359
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
int shmem_getpage_gfp(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, struct vm_fault * vmf, vm_fault_t * fault_type)
```

```json
{
  "name": "shmem_getpage_gfp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581210848,
      "name": "shmem_getpage_gfp",
      "external": false,
      "loc": "mm/shmem.c:1748",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_fault",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581210848,
      "name": "shmem_getpage_gfp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2359
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
int shmem_getpage_gfp(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, struct vm_fault * vmf, vm_fault_t * fault_type)
```

```json
{
  "name": "shmem_getpage_gfp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581395472,
      "name": "shmem_getpage_gfp",
      "external": false,
      "loc": "mm/shmem.c:1732",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_read_mapping_page_gfp",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_fault",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581395472,
      "name": "shmem_getpage_gfp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2254
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
int shmem_getpage_gfp(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, struct vm_fault * vmf, vm_fault_t * fault_type)
```

```json
{
  "name": "shmem_getpage_gfp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581440880,
      "name": "shmem_getpage_gfp",
      "external": false,
      "loc": "mm/shmem.c:1793",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_read_mapping_page_gfp",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_fault",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581440880,
      "name": "shmem_getpage_gfp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2228
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
int shmem_getpage_gfp(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, struct vm_fault * vmf, vm_fault_t * fault_type)
```

```json
{
  "name": "shmem_getpage_gfp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581461680,
      "name": "shmem_getpage_gfp",
      "external": false,
      "loc": "mm/shmem.c:1791",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_read_mapping_page_gfp",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_fault",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581461680,
      "name": "shmem_getpage_gfp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2231
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
int shmem_getpage_gfp(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, struct vm_fault * vmf, vm_fault_t * fault_type)
```

```json
{
  "name": "shmem_getpage_gfp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shmem_getpage_gfp",
      "external": false,
      "loc": "mm/shmem.c:1814",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_read_mapping_page_gfp",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_fault",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581716576,
      "name": "shmem_getpage_gfp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2132
    },
    {
      "addr": 18446744071592192601,
      "name": "shmem_getpage_gfp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
int shmem_getpage_gfp(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, struct vm_fault * vmf, vm_fault_t * fault_type)
```

```json
{
  "name": "shmem_getpage_gfp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shmem_getpage_gfp",
      "external": false,
      "loc": "mm/shmem.c:1823",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_read_mapping_page_gfp",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582092560,
      "name": "shmem_getpage_gfp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2345
    },
    {
      "addr": 18446744071593968452,
      "name": "shmem_getpage_gfp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int shmem_getpage_gfp(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, struct vm_fault * vmf, vm_fault_t * fault_type)
```

```json
{
  "name": "shmem_getpage_gfp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492596664,
      "name": "shmem_getpage_gfp",
      "external": false,
      "loc": "mm/shmem.c:1748",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_fault",
        "mm/shmem.c:shmem_fault",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492596664,
      "name": "shmem_getpage_gfp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2380
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
int shmem_getpage_gfp(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, struct vm_fault * vmf, vm_fault_t * fault_type)
```

```json
{
  "name": "shmem_getpage_gfp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226451772,
      "name": "shmem_getpage_gfp",
      "external": false,
      "loc": "mm/shmem.c:1748",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_fault",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226451772,
      "name": "shmem_getpage_gfp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2220
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
int shmem_getpage_gfp(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, struct vm_fault * vmf, vm_fault_t * fault_type)
```

```json
{
  "name": "shmem_getpage_gfp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285911488,
      "name": "shmem_getpage_gfp",
      "external": false,
      "loc": "mm/shmem.c:1748",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_read_mapping_page_gfp",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_fault",
        "mm/shmem.c:shmem_fault",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285911488,
      "name": "shmem_getpage_gfp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3264
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
int shmem_getpage_gfp(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, struct vm_fault * vmf, vm_fault_t * fault_type)
```

```json
{
  "name": "shmem_getpage_gfp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272628976,
      "name": "shmem_getpage_gfp",
      "external": false,
      "loc": "mm/shmem.c:1748",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_fault",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272628976,
      "name": "shmem_getpage_gfp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1826
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
int shmem_getpage_gfp(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, struct vm_fault * vmf, vm_fault_t * fault_type)
```

```json
{
  "name": "shmem_getpage_gfp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581179696,
      "name": "shmem_getpage_gfp",
      "external": false,
      "loc": "mm/shmem.c:1748",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_fault",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581179696,
      "name": "shmem_getpage_gfp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2359
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
int shmem_getpage_gfp(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, struct vm_fault * vmf, vm_fault_t * fault_type)
```

```json
{
  "name": "shmem_getpage_gfp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581126464,
      "name": "shmem_getpage_gfp",
      "external": false,
      "loc": "mm/shmem.c:1748",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_fault",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581126464,
      "name": "shmem_getpage_gfp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2341
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
int shmem_getpage_gfp(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, struct vm_fault * vmf, vm_fault_t * fault_type)
```

```json
{
  "name": "shmem_getpage_gfp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581170896,
      "name": "shmem_getpage_gfp",
      "external": false,
      "loc": "mm/shmem.c:1748",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_fault",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581170896,
      "name": "shmem_getpage_gfp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2359
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
int shmem_getpage_gfp(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, struct vm_fault * vmf, vm_fault_t * fault_type)
```

```json
{
  "name": "shmem_getpage_gfp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581233936,
      "name": "shmem_getpage_gfp",
      "external": false,
      "loc": "mm/shmem.c:1748",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_fault",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581233936,
      "name": "shmem_getpage_gfp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2360
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mm_struct * fault_mm</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, index, pagep, sgp, gfp, fault_type</code> ➡️ <code>inode, index, pagep, sgp, gfp, fault_mm, fault_type</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vm_area_struct * vma</code>
</li>
<li>
<b>Param added. </b>
<code>struct vm_fault * vmf</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mm_struct * fault_mm</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, index, pagep, sgp, gfp, fault_mm, fault_type</code> ➡️ <code>inode, index, pagep, sgp, gfp, vma, vmf, fault_type</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int * fault_type</code> ➡️ <code>vm_fault_t * fault_type</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int shmem_getpage_gfp(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, struct vm_fault * vmf, vm_fault_t * fault_type)
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
