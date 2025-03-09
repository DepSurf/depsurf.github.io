# Function: <code>__mm_populate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors)
```

```json
{
  "name": "__mm_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580661328,
      "name": "__mm_populate",
      "external": true,
      "loc": "mm/gup.c:930",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:do_mlock",
        "mm/mlock.c:SyS_mlockall",
        "mm/mmap.c:vm_brk",
        "mm/mmap.c:SyS_brk",
        "mm/mmap.c:SyS_remap_file_pages",
        "mm/mremap.c:SyS_mremap",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580661328,
      "name": "__mm_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors)
```

```json
{
  "name": "__mm_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580770480,
      "name": "__mm_populate",
      "external": true,
      "loc": "mm/gup.c:1053",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:SyS_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk",
        "mm/mmap.c:SyS_remap_file_pages",
        "mm/mmap.c:SyS_brk",
        "mm/mremap.c:SyS_mremap",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580770480,
      "name": "__mm_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors)
```

```json
{
  "name": "__mm_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580835856,
      "name": "__mm_populate",
      "external": true,
      "loc": "mm/gup.c:1057",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:SyS_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk",
        "mm/mmap.c:SyS_remap_file_pages",
        "mm/mmap.c:SyS_brk",
        "mm/mremap.c:SyS_mremap",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580835856,
      "name": "__mm_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors)
```

```json
{
  "name": "__mm_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580878416,
      "name": "__mm_populate",
      "external": true,
      "loc": "mm/gup.c:1138",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:SyS_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:SyS_remap_file_pages",
        "mm/mmap.c:SyS_remap_file_pages",
        "mm/mmap.c:SyS_remap_file_pages",
        "mm/mmap.c:SyS_brk",
        "mm/mremap.c:SyS_mremap",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580878416,
      "name": "__mm_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors)
```

```json
{
  "name": "__mm_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580974096,
      "name": "__mm_populate",
      "external": true,
      "loc": "mm/gup.c:1227",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:SyS_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:SyS_remap_file_pages",
        "mm/mmap.c:SyS_remap_file_pages",
        "mm/mmap.c:SyS_remap_file_pages",
        "mm/mmap.c:SyS_brk",
        "mm/mremap.c:SyS_mremap",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580974096,
      "name": "__mm_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors)
```

```json
{
  "name": "__mm_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581108624,
      "name": "__mm_populate",
      "external": true,
      "loc": "mm/gup.c:1233",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:__ia32_sys_mlockall",
        "mm/mlock.c:__x64_sys_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581108624,
      "name": "__mm_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors)
```

```json
{
  "name": "__mm_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581188656,
      "name": "__mm_populate",
      "external": true,
      "loc": "mm/gup.c:1258",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:__ia32_sys_mlockall",
        "mm/mlock.c:__x64_sys_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581188656,
      "name": "__mm_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors)
```

```json
{
  "name": "__mm_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581261200,
      "name": "__mm_populate",
      "external": true,
      "loc": "mm/gup.c:1241",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:__ia32_sys_mlockall",
        "mm/mlock.c:__x64_sys_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581261200,
      "name": "__mm_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors)
```

```json
{
  "name": "__mm_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581319872,
      "name": "__mm_populate",
      "external": true,
      "loc": "mm/gup.c:1244",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:__ia32_sys_mlockall",
        "mm/mlock.c:__x64_sys_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581319872,
      "name": "__mm_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors)
```

```json
{
  "name": "__mm_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581513472,
      "name": "__mm_populate",
      "external": true,
      "loc": "mm/gup.c:1463",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:__do_sys_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:__do_sys_brk",
        "mm/mremap.c:__do_sys_mremap",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581513472,
      "name": "__mm_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors)
```

```json
{
  "name": "__mm_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581554032,
      "name": "__mm_populate",
      "external": true,
      "loc": "mm/gup.c:1414",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:__do_sys_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:__do_sys_brk",
        "mm/mremap.c:__do_sys_mremap",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581554032,
      "name": "__mm_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
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
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors)
```

```json
{
  "name": "__mm_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581576912,
      "name": "__mm_populate",
      "external": true,
      "loc": "mm/gup.c:1499",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:__do_sys_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:__do_sys_brk",
        "mm/mremap.c:__do_sys_mremap",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581576912,
      "name": "__mm_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors)
```

```json
{
  "name": "__mm_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581841728,
      "name": "__mm_populate",
      "external": true,
      "loc": "mm/gup.c:1587",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:__do_sys_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:__do_sys_brk",
        "mm/mremap.c:__do_sys_mremap",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581841728,
      "name": "__mm_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 361
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
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors)
```

```json
{
  "name": "__mm_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582234384,
      "name": "__mm_populate",
      "external": true,
      "loc": "mm/gup.c:1621",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:__do_sys_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:__do_sys_brk",
        "mm/mremap.c:__do_sys_mremap",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582234384,
      "name": "__mm_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors)
```

```json
{
  "name": "__mm_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582724816,
      "name": "__mm_populate",
      "external": true,
      "loc": "mm/gup.c:1602",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:__do_sys_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:__do_sys_brk",
        "mm/mremap.c:__do_sys_mremap",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582724816,
      "name": "__mm_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors)
```

```json
{
  "name": "__mm_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582941376,
      "name": "__mm_populate",
      "external": true,
      "loc": "mm/gup.c:1724",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:__do_sys_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:__do_sys_brk",
        "mm/mremap.c:__do_sys_mremap",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582941376,
      "name": "__mm_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 395
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
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors)
```

```json
{
  "name": "__mm_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583116592,
      "name": "__mm_populate",
      "external": true,
      "loc": "mm/gup.c:1750",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:__do_sys_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:__do_sys_brk",
        "mm/mremap.c:__do_sys_mremap",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583116592,
      "name": "__mm_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 395
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
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors)
```

```json
{
  "name": "__mm_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492726112,
      "name": "__mm_populate",
      "external": true,
      "loc": "mm/gup.c:1244",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:__arm64_sys_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__arm64_sys_remap_file_pages",
        "mm/mmap.c:__arm64_sys_remap_file_pages",
        "mm/mmap.c:__arm64_sys_brk",
        "mm/mremap.c:__arm64_sys_mremap",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492726112,
      "name": "__mm_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors)
```

```json
{
  "name": "__mm_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226556884,
      "name": "__mm_populate",
      "external": true,
      "loc": "mm/gup.c:1244",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:__se_sys_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__se_sys_remap_file_pages",
        "mm/mmap.c:__se_sys_remap_file_pages",
        "mm/mmap.c:__se_sys_brk",
        "mm/mremap.c:__se_sys_mremap",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226556884,
      "name": "__mm_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors)
```

```json
{
  "name": "__mm_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286072064,
      "name": "__mm_populate",
      "external": true,
      "loc": "mm/gup.c:1244",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:__se_sys_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__se_sys_remap_file_pages",
        "mm/mmap.c:__se_sys_remap_file_pages",
        "mm/mmap.c:__se_sys_brk",
        "mm/mremap.c:__se_sys_mremap",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286072064,
      "name": "__mm_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors)
```

```json
{
  "name": "__mm_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272717960,
      "name": "__mm_populate",
      "external": true,
      "loc": "mm/gup.c:1244",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:__se_sys_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__se_sys_remap_file_pages",
        "mm/mmap.c:__se_sys_remap_file_pages",
        "mm/mmap.c:__se_sys_brk",
        "mm/mremap.c:__se_sys_mremap",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272717960,
      "name": "__mm_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors)
```

```json
{
  "name": "__mm_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581288720,
      "name": "__mm_populate",
      "external": true,
      "loc": "mm/gup.c:1244",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:__ia32_sys_mlockall",
        "mm/mlock.c:__x64_sys_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581288720,
      "name": "__mm_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors)
```

```json
{
  "name": "__mm_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581234528,
      "name": "__mm_populate",
      "external": true,
      "loc": "mm/gup.c:1244",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:__ia32_sys_mlockall",
        "mm/mlock.c:__x64_sys_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581234528,
      "name": "__mm_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors)
```

```json
{
  "name": "__mm_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581279920,
      "name": "__mm_populate",
      "external": true,
      "loc": "mm/gup.c:1244",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:__ia32_sys_mlockall",
        "mm/mlock.c:__x64_sys_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581279920,
      "name": "__mm_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors)
```

```json
{
  "name": "__mm_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581343872,
      "name": "__mm_populate",
      "external": true,
      "loc": "mm/gup.c:1244",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "mm/util.c:vm_mmap_pgoff",
        "mm/mlock.c:__ia32_sys_mlockall",
        "mm/mlock.c:__x64_sys_mlockall",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581343872,
      "name": "__mm_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
