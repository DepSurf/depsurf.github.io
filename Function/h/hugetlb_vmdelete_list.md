# Function: <code>hugetlb_vmdelete_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hugetlb_vmdelete_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581944588,
      "name": "hugetlb_vmdelete_list",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:456",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void hugetlb_vmdelete_list(struct rb_root * root, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "hugetlb_vmdelete_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582150432,
      "name": "hugetlb_vmdelete_list",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:328",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582150432,
      "name": "hugetlb_vmdelete_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
void hugetlb_vmdelete_list(struct rb_root * root, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "hugetlb_vmdelete_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582239888,
      "name": "hugetlb_vmdelete_list",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:328",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582239888,
      "name": "hugetlb_vmdelete_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
void hugetlb_vmdelete_list(struct rb_root * root, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "hugetlb_vmdelete_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582324720,
      "name": "hugetlb_vmdelete_list",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:337",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582324720,
      "name": "hugetlb_vmdelete_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
void hugetlb_vmdelete_list(struct rb_root_cached * root, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "hugetlb_vmdelete_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582475008,
      "name": "hugetlb_vmdelete_list",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:348",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582475008,
      "name": "hugetlb_vmdelete_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
void hugetlb_vmdelete_list(struct rb_root_cached * root, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "hugetlb_vmdelete_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582665744,
      "name": "hugetlb_vmdelete_list",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:342",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582665744,
      "name": "hugetlb_vmdelete_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
void hugetlb_vmdelete_list(struct rb_root_cached * root, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "hugetlb_vmdelete_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582767632,
      "name": "hugetlb_vmdelete_list",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:342",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582767632,
      "name": "hugetlb_vmdelete_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
void hugetlb_vmdelete_list(struct rb_root_cached * root, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "hugetlb_vmdelete_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582941936,
      "name": "hugetlb_vmdelete_list",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:356",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582941936,
      "name": "hugetlb_vmdelete_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
void hugetlb_vmdelete_list(struct rb_root_cached * root, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "hugetlb_vmdelete_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583048592,
      "name": "hugetlb_vmdelete_list",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:356",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583048592,
      "name": "hugetlb_vmdelete_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
void hugetlb_vmdelete_list(struct rb_root_cached * root, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "hugetlb_vmdelete_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583367056,
      "name": "hugetlb_vmdelete_list",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:402",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/hugetlbfs/inode.c:hugetlbfs_punch_hole",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583367056,
      "name": "hugetlb_vmdelete_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
void hugetlb_vmdelete_list(struct rb_root_cached * root, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "hugetlb_vmdelete_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583483040,
      "name": "hugetlb_vmdelete_list",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:402",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/hugetlbfs/inode.c:hugetlbfs_punch_hole",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583483040,
      "name": "hugetlb_vmdelete_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
void hugetlb_vmdelete_list(struct rb_root_cached * root, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "hugetlb_vmdelete_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583505232,
      "name": "hugetlb_vmdelete_list",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:407",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583505232,
      "name": "hugetlb_vmdelete_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
void hugetlb_vmdelete_list(struct rb_root_cached * root, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "hugetlb_vmdelete_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583860320,
      "name": "hugetlb_vmdelete_list",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:407",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583860320,
      "name": "hugetlb_vmdelete_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void hugetlb_vmdelete_list(struct rb_root_cached * root, long unsigned int start, long unsigned int end, zap_flags_t zap_flags)
```

```json
{
  "name": "hugetlb_vmdelete_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584431232,
      "name": "hugetlb_vmdelete_list",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:417",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584431232,
      "name": "hugetlb_vmdelete_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
void hugetlb_vmdelete_list(struct rb_root_cached * root, long unsigned int start, long unsigned int end, zap_flags_t zap_flags)
```

```json
{
  "name": "hugetlb_vmdelete_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585096128,
      "name": "hugetlb_vmdelete_list",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:523",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585096128,
      "name": "hugetlb_vmdelete_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
void hugetlb_vmdelete_list(struct rb_root_cached * root, long unsigned int start, long unsigned int end, zap_flags_t zap_flags)
```

```json
{
  "name": "hugetlb_vmdelete_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585325392,
      "name": "hugetlb_vmdelete_list",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:522",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585325392,
      "name": "hugetlb_vmdelete_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
void hugetlb_vmdelete_list(struct rb_root_cached * root, long unsigned int start, long unsigned int end, zap_flags_t zap_flags)
```

```json
{
  "name": "hugetlb_vmdelete_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585560080,
      "name": "hugetlb_vmdelete_list",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:555",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585560080,
      "name": "hugetlb_vmdelete_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
void hugetlb_vmdelete_list(struct rb_root_cached * root, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "hugetlb_vmdelete_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494745592,
      "name": "hugetlb_vmdelete_list",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:356",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494745592,
      "name": "hugetlb_vmdelete_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void hugetlb_vmdelete_list(struct rb_root_cached * root, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "hugetlb_vmdelete_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288574176,
      "name": "hugetlb_vmdelete_list",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:356",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288574176,
      "name": "hugetlb_vmdelete_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
void hugetlb_vmdelete_list(struct rb_root_cached * root, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "hugetlb_vmdelete_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274090456,
      "name": "hugetlb_vmdelete_list",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:356",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274090456,
      "name": "hugetlb_vmdelete_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void hugetlb_vmdelete_list(struct rb_root_cached * root, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "hugetlb_vmdelete_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583017328,
      "name": "hugetlb_vmdelete_list",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:356",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583017328,
      "name": "hugetlb_vmdelete_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
void hugetlb_vmdelete_list(struct rb_root_cached * root, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "hugetlb_vmdelete_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582954480,
      "name": "hugetlb_vmdelete_list",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:356",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582954480,
      "name": "hugetlb_vmdelete_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
void hugetlb_vmdelete_list(struct rb_root_cached * root, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "hugetlb_vmdelete_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583005936,
      "name": "hugetlb_vmdelete_list",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:356",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583005936,
      "name": "hugetlb_vmdelete_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
void hugetlb_vmdelete_list(struct rb_root_cached * root, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "hugetlb_vmdelete_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583095360,
      "name": "hugetlb_vmdelete_list",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:356",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:hugetlbfs_setattr",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583095360,
      "name": "hugetlb_vmdelete_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
void hugetlb_vmdelete_list(struct rb_root * root, long unsigned int start, long unsigned int end)
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct rb_root * root</code> ➡️ <code>struct rb_root_cached * root</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>zap_flags_t zap_flags</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void hugetlb_vmdelete_list(struct rb_root_cached * root, long unsigned int start, long unsigned int end)
```
</details>
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
