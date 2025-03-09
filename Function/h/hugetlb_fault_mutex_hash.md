# Function: <code>hugetlb_fault_mutex_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
u32 hugetlb_fault_mutex_hash(struct hstate * h, struct mm_struct * mm, struct vm_area_struct * vma, struct address_space * mapping, long unsigned int idx, long unsigned int address)
```

```json
{
  "name": "hugetlb_fault_mutex_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580799360,
      "name": "hugetlb_fault_mutex_hash",
      "external": true,
      "loc": "mm/hugetlb.c:3650",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580799360,
      "name": "hugetlb_fault_mutex_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
u32 hugetlb_fault_mutex_hash(struct hstate * h, struct mm_struct * mm, struct vm_area_struct * vma, struct address_space * mapping, long unsigned int idx, long unsigned int address)
```

```json
{
  "name": "hugetlb_fault_mutex_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580922976,
      "name": "hugetlb_fault_mutex_hash",
      "external": true,
      "loc": "mm/hugetlb.c:3665",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580922976,
      "name": "hugetlb_fault_mutex_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
u32 hugetlb_fault_mutex_hash(struct hstate * h, struct mm_struct * mm, struct vm_area_struct * vma, struct address_space * mapping, long unsigned int idx, long unsigned int address)
```

```json
{
  "name": "hugetlb_fault_mutex_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580991328,
      "name": "hugetlb_fault_mutex_hash",
      "external": true,
      "loc": "mm/hugetlb.c:3779",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580991328,
      "name": "hugetlb_fault_mutex_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
u32 hugetlb_fault_mutex_hash(struct hstate * h, struct mm_struct * mm, struct vm_area_struct * vma, struct address_space * mapping, long unsigned int idx, long unsigned int address)
```

```json
{
  "name": "hugetlb_fault_mutex_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581038096,
      "name": "hugetlb_fault_mutex_hash",
      "external": true,
      "loc": "mm/hugetlb.c:3797",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581038096,
      "name": "hugetlb_fault_mutex_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
u32 hugetlb_fault_mutex_hash(struct hstate * h, struct mm_struct * mm, struct vm_area_struct * vma, struct address_space * mapping, long unsigned int idx, long unsigned int address)
```

```json
{
  "name": "hugetlb_fault_mutex_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581147840,
      "name": "hugetlb_fault_mutex_hash",
      "external": true,
      "loc": "mm/hugetlb.c:3818",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581147840,
      "name": "hugetlb_fault_mutex_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
u32 hugetlb_fault_mutex_hash(struct hstate * h, struct mm_struct * mm, struct vm_area_struct * vma, struct address_space * mapping, long unsigned int idx, long unsigned int address)
```

```json
{
  "name": "hugetlb_fault_mutex_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581291280,
      "name": "hugetlb_fault_mutex_hash",
      "external": true,
      "loc": "mm/hugetlb.c:3848",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581291280,
      "name": "hugetlb_fault_mutex_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
u32 hugetlb_fault_mutex_hash(struct hstate * h, struct mm_struct * mm, struct vm_area_struct * vma, struct address_space * mapping, long unsigned int idx, long unsigned int address)
```

```json
{
  "name": "hugetlb_fault_mutex_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581374192,
      "name": "hugetlb_fault_mutex_hash",
      "external": true,
      "loc": "mm/hugetlb.c:3888",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581374192,
      "name": "hugetlb_fault_mutex_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
u32 hugetlb_fault_mutex_hash(struct hstate * h, struct address_space * mapping, long unsigned int idx, long unsigned int address)
```

```json
{
  "name": "hugetlb_fault_mutex_hash",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581496270,
      "name": "hugetlb_fault_mutex_hash",
      "external": true,
      "loc": "mm/hugetlb.c:3977",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581485184,
      "name": "hugetlb_fault_mutex_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
u32 hugetlb_fault_mutex_hash(struct hstate * h, struct address_space * mapping, long unsigned int idx, long unsigned int address)
```

```json
{
  "name": "hugetlb_fault_mutex_hash",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581560798,
      "name": "hugetlb_fault_mutex_hash",
      "external": true,
      "loc": "mm/hugetlb.c:4094",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581549600,
      "name": "hugetlb_fault_mutex_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
u32 hugetlb_fault_mutex_hash(struct address_space * mapping, long unsigned int idx)
```

```json
{
  "name": "hugetlb_fault_mutex_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581759504,
      "name": "hugetlb_fault_mutex_hash",
      "external": true,
      "loc": "mm/hugetlb.c:4515",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581759504,
      "name": "hugetlb_fault_mutex_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
u32 hugetlb_fault_mutex_hash(struct address_space * mapping, long unsigned int idx)
```

```json
{
  "name": "hugetlb_fault_mutex_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581807488,
      "name": "hugetlb_fault_mutex_hash",
      "external": true,
      "loc": "mm/hugetlb.c:4505",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581807488,
      "name": "hugetlb_fault_mutex_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
u32 hugetlb_fault_mutex_hash(struct address_space * mapping, long unsigned int idx)
```

```json
{
  "name": "hugetlb_fault_mutex_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581835456,
      "name": "hugetlb_fault_mutex_hash",
      "external": true,
      "loc": "mm/hugetlb.c:4746",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_handle_userfault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581835456,
      "name": "hugetlb_fault_mutex_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
u32 hugetlb_fault_mutex_hash(struct address_space * mapping, long unsigned int idx)
```

```json
{
  "name": "hugetlb_fault_mutex_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582125696,
      "name": "hugetlb_fault_mutex_hash",
      "external": true,
      "loc": "mm/hugetlb.c:5051",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_handle_userfault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582125696,
      "name": "hugetlb_fault_mutex_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
u32 hugetlb_fault_mutex_hash(struct address_space * mapping, long unsigned int idx)
```

```json
{
  "name": "hugetlb_fault_mutex_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582571552,
      "name": "hugetlb_fault_mutex_hash",
      "external": true,
      "loc": "mm/hugetlb.c:5678",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_handle_userfault",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582571552,
      "name": "hugetlb_fault_mutex_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
u32 hugetlb_fault_mutex_hash(struct address_space * mapping, long unsigned int idx)
```

```json
{
  "name": "hugetlb_fault_mutex_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583091072,
      "name": "hugetlb_fault_mutex_hash",
      "external": true,
      "loc": "mm/hugetlb.c:5959",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_handle_userfault",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583091072,
      "name": "hugetlb_fault_mutex_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
u32 hugetlb_fault_mutex_hash(struct address_space * mapping, long unsigned int idx)
```

```json
{
  "name": "hugetlb_fault_mutex_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583301024,
      "name": "hugetlb_fault_mutex_hash",
      "external": true,
      "loc": "mm/hugetlb.c:6058",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_handle_userfault",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583301024,
      "name": "hugetlb_fault_mutex_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
u32 hugetlb_fault_mutex_hash(struct address_space * mapping, long unsigned int idx)
```

```json
{
  "name": "hugetlb_fault_mutex_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583538256,
      "name": "hugetlb_fault_mutex_hash",
      "external": true,
      "loc": "mm/hugetlb.c:6326",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_handle_userfault",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/userfaultfd.c:mfill_atomic_poison",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583538256,
      "name": "hugetlb_fault_mutex_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
u32 hugetlb_fault_mutex_hash(struct hstate * h, struct address_space * mapping, long unsigned int idx, long unsigned int address)
```

```json
{
  "name": "hugetlb_fault_mutex_hash",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492994048,
      "name": "hugetlb_fault_mutex_hash",
      "external": true,
      "loc": "mm/hugetlb.c:4094",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492985576,
      "name": "hugetlb_fault_mutex_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
u32 hugetlb_fault_mutex_hash(struct hstate * h, struct address_space * mapping, long unsigned int idx, long unsigned int address)
```

```json
{
  "name": "hugetlb_fault_mutex_hash",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286416612,
      "name": "hugetlb_fault_mutex_hash",
      "external": true,
      "loc": "mm/hugetlb.c:4094",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286416096,
      "name": "hugetlb_fault_mutex_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
u32 hugetlb_fault_mutex_hash(struct hstate * h, struct address_space * mapping, long unsigned int idx, long unsigned int address)
```

```json
{
  "name": "hugetlb_fault_mutex_hash",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272897508,
      "name": "hugetlb_fault_mutex_hash",
      "external": true,
      "loc": "mm/hugetlb.c:4094",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272888746,
      "name": "hugetlb_fault_mutex_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
u32 hugetlb_fault_mutex_hash(struct hstate * h, struct address_space * mapping, long unsigned int idx, long unsigned int address)
```

```json
{
  "name": "hugetlb_fault_mutex_hash",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581529534,
      "name": "hugetlb_fault_mutex_hash",
      "external": true,
      "loc": "mm/hugetlb.c:4094",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581518336,
      "name": "hugetlb_fault_mutex_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
u32 hugetlb_fault_mutex_hash(struct hstate * h, struct address_space * mapping, long unsigned int idx, long unsigned int address)
```

```json
{
  "name": "hugetlb_fault_mutex_hash",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581471374,
      "name": "hugetlb_fault_mutex_hash",
      "external": true,
      "loc": "mm/hugetlb.c:4094",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581460512,
      "name": "hugetlb_fault_mutex_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
u32 hugetlb_fault_mutex_hash(struct hstate * h, struct address_space * mapping, long unsigned int idx, long unsigned int address)
```

```json
{
  "name": "hugetlb_fault_mutex_hash",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581520846,
      "name": "hugetlb_fault_mutex_hash",
      "external": true,
      "loc": "mm/hugetlb.c:4094",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581509648,
      "name": "hugetlb_fault_mutex_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
u32 hugetlb_fault_mutex_hash(struct hstate * h, struct address_space * mapping, long unsigned int idx, long unsigned int address)
```

```json
{
  "name": "hugetlb_fault_mutex_hash",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581585814,
      "name": "hugetlb_fault_mutex_hash",
      "external": true,
      "loc": "mm/hugetlb.c:4094",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581574656,
      "name": "hugetlb_fault_mutex_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct mm_struct * mm</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct * vma</code>
</li>
<li>
<b>Param reordered. </b>
<code>h, mm, vma, mapping, idx, address</code> ➡️ <code>h, mapping, idx, address</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct hstate * h</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int address</code>
</li>
<li>
<b>Param reordered. </b>
<code>h, mapping, idx, address</code> ➡️ <code>mapping, idx</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
u32 hugetlb_fault_mutex_hash(struct hstate * h, struct address_space * mapping, long unsigned int idx, long unsigned int address)
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
