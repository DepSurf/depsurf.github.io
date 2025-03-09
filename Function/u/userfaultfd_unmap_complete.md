# Function: <code>userfaultfd_unmap_complete</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void userfaultfd_unmap_complete(struct mm_struct * mm, struct list_head * uf)
```

```json
{
  "name": "userfaultfd_unmap_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581619728,
      "name": "userfaultfd_unmap_complete",
      "external": true,
      "loc": "fs/userfaultfd.c:780",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:vm_munmap",
        "mm/mmap.c:SyS_brk",
        "mm/mmap.c:SyS_brk",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:SyS_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581619728,
      "name": "userfaultfd_unmap_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void userfaultfd_unmap_complete(struct mm_struct * mm, struct list_head * uf)
```

```json
{
  "name": "userfaultfd_unmap_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581764384,
      "name": "userfaultfd_unmap_complete",
      "external": true,
      "loc": "fs/userfaultfd.c:824",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:vm_munmap",
        "mm/mmap.c:SyS_brk",
        "mm/mmap.c:SyS_brk",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:SyS_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581764384,
      "name": "userfaultfd_unmap_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void userfaultfd_unmap_complete(struct mm_struct * mm, struct list_head * uf)
```

```json
{
  "name": "userfaultfd_unmap_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581933120,
      "name": "userfaultfd_unmap_complete",
      "external": true,
      "loc": "fs/userfaultfd.c:839",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:vm_munmap",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581933120,
      "name": "userfaultfd_unmap_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void userfaultfd_unmap_complete(struct mm_struct * mm, struct list_head * uf)
```

```json
{
  "name": "userfaultfd_unmap_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582017536,
      "name": "userfaultfd_unmap_complete",
      "external": true,
      "loc": "fs/userfaultfd.c:844",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582017536,
      "name": "userfaultfd_unmap_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void userfaultfd_unmap_complete(struct mm_struct * mm, struct list_head * uf)
```

```json
{
  "name": "userfaultfd_unmap_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582154144,
      "name": "userfaultfd_unmap_complete",
      "external": true,
      "loc": "fs/userfaultfd.c:856",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582154144,
      "name": "userfaultfd_unmap_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
void userfaultfd_unmap_complete(struct mm_struct * mm, struct list_head * uf)
```

```json
{
  "name": "userfaultfd_unmap_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582231424,
      "name": "userfaultfd_unmap_complete",
      "external": true,
      "loc": "fs/userfaultfd.c:856",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582231424,
      "name": "userfaultfd_unmap_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
void userfaultfd_unmap_complete(struct mm_struct * mm, struct list_head * uf)
```

```json
{
  "name": "userfaultfd_unmap_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582469248,
      "name": "userfaultfd_unmap_complete",
      "external": true,
      "loc": "fs/userfaultfd.c:855",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__do_sys_brk",
        "mm/mmap.c:__do_sys_brk",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:__do_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582469248,
      "name": "userfaultfd_unmap_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void userfaultfd_unmap_complete(struct mm_struct * mm, struct list_head * uf)
```

```json
{
  "name": "userfaultfd_unmap_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582526288,
      "name": "userfaultfd_unmap_complete",
      "external": true,
      "loc": "fs/userfaultfd.c:823",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__do_sys_brk",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:__do_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582526288,
      "name": "userfaultfd_unmap_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void userfaultfd_unmap_complete(struct mm_struct * mm, struct list_head * uf)
```

```json
{
  "name": "userfaultfd_unmap_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582555072,
      "name": "userfaultfd_unmap_complete",
      "external": true,
      "loc": "fs/userfaultfd.c:823",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__do_sys_brk",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:__do_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582555072,
      "name": "userfaultfd_unmap_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void userfaultfd_unmap_complete(struct mm_struct * mm, struct list_head * uf)
```

```json
{
  "name": "userfaultfd_unmap_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582871200,
      "name": "userfaultfd_unmap_complete",
      "external": true,
      "loc": "fs/userfaultfd.c:824",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__do_sys_brk",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:__do_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582871200,
      "name": "userfaultfd_unmap_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void userfaultfd_unmap_complete(struct mm_struct * mm, struct list_head * uf)
```

```json
{
  "name": "userfaultfd_unmap_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583434800,
      "name": "userfaultfd_unmap_complete",
      "external": true,
      "loc": "fs/userfaultfd.c:833",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__do_sys_brk",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:__do_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583434800,
      "name": "userfaultfd_unmap_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
void userfaultfd_unmap_complete(struct mm_struct * mm, struct list_head * uf)
```

```json
{
  "name": "userfaultfd_unmap_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584024400,
      "name": "userfaultfd_unmap_complete",
      "external": true,
      "loc": "fs/userfaultfd.c:849",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__do_sys_brk",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:__do_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584024400,
      "name": "userfaultfd_unmap_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
void userfaultfd_unmap_complete(struct mm_struct * mm, struct list_head * uf)
```

```json
{
  "name": "userfaultfd_unmap_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584249136,
      "name": "userfaultfd_unmap_complete",
      "external": true,
      "loc": "fs/userfaultfd.c:879",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__do_sys_brk",
        "mm/mmap.c:__do_sys_brk",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:__do_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584249136,
      "name": "userfaultfd_unmap_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
void userfaultfd_unmap_complete(struct mm_struct * mm, struct list_head * uf)
```

```json
{
  "name": "userfaultfd_unmap_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584465712,
      "name": "userfaultfd_unmap_complete",
      "external": true,
      "loc": "fs/userfaultfd.c:876",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__do_sys_brk",
        "mm/mmap.c:__do_sys_brk",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:__do_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584465712,
      "name": "userfaultfd_unmap_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
void userfaultfd_unmap_complete(struct mm_struct * mm, struct list_head * uf)
```

```json
{
  "name": "userfaultfd_unmap_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493800544,
      "name": "userfaultfd_unmap_complete",
      "external": true,
      "loc": "fs/userfaultfd.c:856",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__arm64_sys_brk",
        "mm/mmap.c:__arm64_sys_brk",
        "mm/mremap.c:__arm64_sys_mremap",
        "mm/mremap.c:__arm64_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493800544,
      "name": "userfaultfd_unmap_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void userfaultfd_unmap_complete(struct mm_struct * mm, struct list_head * uf)
```

```json
{
  "name": "userfaultfd_unmap_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227310924,
      "name": "userfaultfd_unmap_complete",
      "external": true,
      "loc": "fs/userfaultfd.c:856",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__se_sys_brk",
        "mm/mmap.c:__se_sys_brk",
        "mm/mremap.c:__se_sys_mremap",
        "mm/mremap.c:__se_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227310924,
      "name": "userfaultfd_unmap_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void userfaultfd_unmap_complete(struct mm_struct * mm, struct list_head * uf)
```

```json
{
  "name": "userfaultfd_unmap_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287415936,
      "name": "userfaultfd_unmap_complete",
      "external": true,
      "loc": "fs/userfaultfd.c:856",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__se_sys_brk",
        "mm/mmap.c:__se_sys_brk",
        "mm/mremap.c:__se_sys_mremap",
        "mm/mremap.c:__se_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287415936,
      "name": "userfaultfd_unmap_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
void userfaultfd_unmap_complete(struct mm_struct * mm, struct list_head * uf)
```

```json
{
  "name": "userfaultfd_unmap_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273387082,
      "name": "userfaultfd_unmap_complete",
      "external": true,
      "loc": "fs/userfaultfd.c:856",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__se_sys_brk",
        "mm/mmap.c:__se_sys_brk",
        "mm/mremap.c:__se_sys_mremap",
        "mm/mremap.c:__se_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273387082,
      "name": "userfaultfd_unmap_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void userfaultfd_unmap_complete(struct mm_struct * mm, struct list_head * uf)
```

```json
{
  "name": "userfaultfd_unmap_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582200160,
      "name": "userfaultfd_unmap_complete",
      "external": true,
      "loc": "fs/userfaultfd.c:856",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582200160,
      "name": "userfaultfd_unmap_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
void userfaultfd_unmap_complete(struct mm_struct * mm, struct list_head * uf)
```

```json
{
  "name": "userfaultfd_unmap_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582137520,
      "name": "userfaultfd_unmap_complete",
      "external": true,
      "loc": "fs/userfaultfd.c:856",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582137520,
      "name": "userfaultfd_unmap_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
void userfaultfd_unmap_complete(struct mm_struct * mm, struct list_head * uf)
```

```json
{
  "name": "userfaultfd_unmap_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582190640,
      "name": "userfaultfd_unmap_complete",
      "external": true,
      "loc": "fs/userfaultfd.c:856",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582190640,
      "name": "userfaultfd_unmap_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
void userfaultfd_unmap_complete(struct mm_struct * mm, struct list_head * uf)
```

```json
{
  "name": "userfaultfd_unmap_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582266752,
      "name": "userfaultfd_unmap_complete",
      "external": true,
      "loc": "fs/userfaultfd.c:856",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582266752,
      "name": "userfaultfd_unmap_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void userfaultfd_unmap_complete(struct mm_struct * mm, struct list_head * uf)
```
</details>
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
