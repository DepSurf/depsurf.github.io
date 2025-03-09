# Function: <code>mprotect_fixup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int mprotect_fixup(struct vm_area_struct * vma, struct vm_area_struct * * pprev, long unsigned int start, long unsigned int end, long unsigned int newflags)
```

```json
{
  "name": "mprotect_fixup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580716192,
      "name": "mprotect_fixup",
      "external": true,
      "loc": "mm/mprotect.c:258",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:SyS_mprotect",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580716192,
      "name": "mprotect_fixup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 566
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
int mprotect_fixup(struct vm_area_struct * vma, struct vm_area_struct * * pprev, long unsigned int start, long unsigned int end, long unsigned int newflags)
```

```json
{
  "name": "mprotect_fixup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580831584,
      "name": "mprotect_fixup",
      "external": true,
      "loc": "mm/mprotect.c:262",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:SyS_mprotect",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580831584,
      "name": "mprotect_fixup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 619
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
int mprotect_fixup(struct vm_area_struct * vma, struct vm_area_struct * * pprev, long unsigned int start, long unsigned int end, long unsigned int newflags)
```

```json
{
  "name": "mprotect_fixup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580897200,
      "name": "mprotect_fixup",
      "external": true,
      "loc": "mm/mprotect.c:276",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:do_mprotect_pkey",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580897200,
      "name": "mprotect_fixup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 623
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
int mprotect_fixup(struct vm_area_struct * vma, struct vm_area_struct * * pprev, long unsigned int start, long unsigned int end, long unsigned int newflags)
```

```json
{
  "name": "mprotect_fixup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580941792,
      "name": "mprotect_fixup",
      "external": true,
      "loc": "mm/mprotect.c:279",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:do_mprotect_pkey",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580941792,
      "name": "mprotect_fixup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 610
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
int mprotect_fixup(struct vm_area_struct * vma, struct vm_area_struct * * pprev, long unsigned int start, long unsigned int end, long unsigned int newflags)
```

```json
{
  "name": "mprotect_fixup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581042048,
      "name": "mprotect_fixup",
      "external": true,
      "loc": "mm/mprotect.c:296",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:do_mprotect_pkey",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581042048,
      "name": "mprotect_fixup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 610
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
int mprotect_fixup(struct vm_area_struct * vma, struct vm_area_struct * * pprev, long unsigned int start, long unsigned int end, long unsigned int newflags)
```

```json
{
  "name": "mprotect_fixup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581179680,
      "name": "mprotect_fixup",
      "external": true,
      "loc": "mm/mprotect.c:346",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:do_mprotect_pkey",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581179680,
      "name": "mprotect_fixup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 838
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
int mprotect_fixup(struct vm_area_struct * vma, struct vm_area_struct * * pprev, long unsigned int start, long unsigned int end, long unsigned int newflags)
```

```json
{
  "name": "mprotect_fixup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581261968,
      "name": "mprotect_fixup",
      "external": true,
      "loc": "mm/mprotect.c:347",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:do_mprotect_pkey",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581261968,
      "name": "mprotect_fixup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 838
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
int mprotect_fixup(struct vm_area_struct * vma, struct vm_area_struct * * pprev, long unsigned int start, long unsigned int end, long unsigned int newflags)
```

```json
{
  "name": "mprotect_fixup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581336544,
      "name": "mprotect_fixup",
      "external": true,
      "loc": "mm/mprotect.c:348",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:do_mprotect_pkey",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581336544,
      "name": "mprotect_fixup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 822
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
int mprotect_fixup(struct vm_area_struct * vma, struct vm_area_struct * * pprev, long unsigned int start, long unsigned int end, long unsigned int newflags)
```

```json
{
  "name": "mprotect_fixup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581395968,
      "name": "mprotect_fixup",
      "external": true,
      "loc": "mm/mprotect.c:373",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:do_mprotect_pkey",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581395968,
      "name": "mprotect_fixup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 686
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
int mprotect_fixup(struct vm_area_struct * vma, struct vm_area_struct * * pprev, long unsigned int start, long unsigned int end, long unsigned int newflags)
```

```json
{
  "name": "mprotect_fixup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581594048,
      "name": "mprotect_fixup",
      "external": true,
      "loc": "mm/mprotect.c:399",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:do_mprotect_pkey",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581594048,
      "name": "mprotect_fixup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 733
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
int mprotect_fixup(struct vm_area_struct * vma, struct vm_area_struct * * pprev, long unsigned int start, long unsigned int end, long unsigned int newflags)
```

```json
{
  "name": "mprotect_fixup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581640064,
      "name": "mprotect_fixup",
      "external": true,
      "loc": "mm/mprotect.c:399",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:do_mprotect_pkey",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581640064,
      "name": "mprotect_fixup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 733
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
int mprotect_fixup(struct vm_area_struct * vma, struct vm_area_struct * * pprev, long unsigned int start, long unsigned int end, long unsigned int newflags)
```

```json
{
  "name": "mprotect_fixup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581661632,
      "name": "mprotect_fixup",
      "external": true,
      "loc": "mm/mprotect.c:399",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:do_mprotect_pkey",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581661632,
      "name": "mprotect_fixup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 735
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
int mprotect_fixup(struct vm_area_struct * vma, struct vm_area_struct * * pprev, long unsigned int start, long unsigned int end, long unsigned int newflags)
```

```json
{
  "name": "mprotect_fixup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581930000,
      "name": "mprotect_fixup",
      "external": true,
      "loc": "mm/mprotect.c:409",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:do_mprotect_pkey",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581930000,
      "name": "mprotect_fixup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 735
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
int mprotect_fixup(struct mmu_gather * tlb, struct vm_area_struct * vma, struct vm_area_struct * * pprev, long unsigned int start, long unsigned int end, long unsigned int newflags)
```

```json
{
  "name": "mprotect_fixup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582338672,
      "name": "mprotect_fixup",
      "external": true,
      "loc": "mm/mprotect.c:501",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:do_mprotect_pkey",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582338672,
      "name": "mprotect_fixup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 780
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
int mprotect_fixup(struct mmu_gather * tlb, struct vm_area_struct * vma, struct vm_area_struct * * pprev, long unsigned int start, long unsigned int end, long unsigned int newflags)
```

```json
{
  "name": "mprotect_fixup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582839696,
      "name": "mprotect_fixup",
      "external": true,
      "loc": "mm/mprotect.c:557",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:do_mprotect_pkey",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582839696,
      "name": "mprotect_fixup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 795
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
int mprotect_fixup(struct vma_iterator * vmi, struct mmu_gather * tlb, struct vm_area_struct * vma, struct vm_area_struct * * pprev, long unsigned int start, long unsigned int end, long unsigned int newflags)
```

```json
{
  "name": "mprotect_fixup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583055152,
      "name": "mprotect_fixup",
      "external": true,
      "loc": "mm/mprotect.c:575",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:do_mprotect_pkey",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583055152,
      "name": "mprotect_fixup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 792
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
int mprotect_fixup(struct vma_iterator * vmi, struct mmu_gather * tlb, struct vm_area_struct * vma, struct vm_area_struct * * pprev, long unsigned int start, long unsigned int end, long unsigned int newflags)
```

```json
{
  "name": "mprotect_fixup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583236736,
      "name": "mprotect_fixup",
      "external": true,
      "loc": "mm/mprotect.c:577",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:do_mprotect_pkey",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583236736,
      "name": "mprotect_fixup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 917
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
int mprotect_fixup(struct vm_area_struct * vma, struct vm_area_struct * * pprev, long unsigned int start, long unsigned int end, long unsigned int newflags)
```

```json
{
  "name": "mprotect_fixup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492799880,
      "name": "mprotect_fixup",
      "external": true,
      "loc": "mm/mprotect.c:373",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:__arm64_sys_mprotect",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492799880,
      "name": "mprotect_fixup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
int mprotect_fixup(struct vm_area_struct * vma, struct vm_area_struct * * pprev, long unsigned int start, long unsigned int end, long unsigned int newflags)
```

```json
{
  "name": "mprotect_fixup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226613448,
      "name": "mprotect_fixup",
      "external": true,
      "loc": "mm/mprotect.c:373",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:__se_sys_mprotect",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226613448,
      "name": "mprotect_fixup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 612
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
int mprotect_fixup(struct vm_area_struct * vma, struct vm_area_struct * * pprev, long unsigned int start, long unsigned int end, long unsigned int newflags)
```

```json
{
  "name": "mprotect_fixup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286172736,
      "name": "mprotect_fixup",
      "external": true,
      "loc": "mm/mprotect.c:373",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:__se_sys_mprotect",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286172736,
      "name": "mprotect_fixup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 848
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
int mprotect_fixup(struct vm_area_struct * vma, struct vm_area_struct * * pprev, long unsigned int start, long unsigned int end, long unsigned int newflags)
```

```json
{
  "name": "mprotect_fixup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272766318,
      "name": "mprotect_fixup",
      "external": true,
      "loc": "mm/mprotect.c:373",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:__se_sys_mprotect",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272766318,
      "name": "mprotect_fixup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 474
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
int mprotect_fixup(struct vm_area_struct * vma, struct vm_area_struct * * pprev, long unsigned int start, long unsigned int end, long unsigned int newflags)
```

```json
{
  "name": "mprotect_fixup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581364816,
      "name": "mprotect_fixup",
      "external": true,
      "loc": "mm/mprotect.c:373",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:do_mprotect_pkey",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581364816,
      "name": "mprotect_fixup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 686
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
int mprotect_fixup(struct vm_area_struct * vma, struct vm_area_struct * * pprev, long unsigned int start, long unsigned int end, long unsigned int newflags)
```

```json
{
  "name": "mprotect_fixup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581308320,
      "name": "mprotect_fixup",
      "external": true,
      "loc": "mm/mprotect.c:373",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:do_mprotect_pkey",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581308320,
      "name": "mprotect_fixup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 686
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
int mprotect_fixup(struct vm_area_struct * vma, struct vm_area_struct * * pprev, long unsigned int start, long unsigned int end, long unsigned int newflags)
```

```json
{
  "name": "mprotect_fixup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581356016,
      "name": "mprotect_fixup",
      "external": true,
      "loc": "mm/mprotect.c:373",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:do_mprotect_pkey",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581356016,
      "name": "mprotect_fixup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 686
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
int mprotect_fixup(struct vm_area_struct * vma, struct vm_area_struct * * pprev, long unsigned int start, long unsigned int end, long unsigned int newflags)
```

```json
{
  "name": "mprotect_fixup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581419936,
      "name": "mprotect_fixup",
      "external": true,
      "loc": "mm/mprotect.c:373",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:do_mprotect_pkey",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581419936,
      "name": "mprotect_fixup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 686
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mmu_gather * tlb</code>
</li>
<li>
<b>Param reordered. </b>
<code>vma, pprev, start, end, newflags</code> ➡️ <code>tlb, vma, pprev, start, end, newflags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vma_iterator * vmi</code>
</li>
<li>
<b>Param reordered. </b>
<code>tlb, vma, pprev, start, end, newflags</code> ➡️ <code>vmi, tlb, vma, pprev, start, end, newflags</code>
</li>
</ul>
</details>
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
