# Function: <code>vm_munmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int vm_munmap(long unsigned int start, size_t len)
```

```json
{
  "name": "vm_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580707024,
      "name": "vm_munmap",
      "external": true,
      "loc": "mm/mmap.c:2617",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "mm/mmap.c:SyS_munmap",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:SyS_io_setup",
        "fs/binfmt_elf.c:elf_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580707024,
      "name": "vm_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int vm_munmap(long unsigned int start, size_t len)
```

```json
{
  "name": "vm_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580820320,
      "name": "vm_munmap",
      "external": true,
      "loc": "mm/mmap.c:2514",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "fs/aio.c:SyS_io_setup",
        "fs/aio.c:kill_ioctx",
        "fs/binfmt_elf.c:elf_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580820320,
      "name": "vm_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int vm_munmap(long unsigned int start, size_t len)
```

```json
{
  "name": "vm_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580885808,
      "name": "vm_munmap",
      "external": true,
      "loc": "mm/mmap.c:2667",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:ioctx_alloc",
        "fs/binfmt_elf.c:elf_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580885808,
      "name": "vm_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int vm_munmap(long unsigned int start, size_t len)
```

```json
{
  "name": "vm_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580930800,
      "name": "vm_munmap",
      "external": true,
      "loc": "mm/mmap.c:2710",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "mm/mmap.c:SyS_munmap",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:ioctx_alloc",
        "fs/binfmt_elf.c:elf_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580930800,
      "name": "vm_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int vm_munmap(long unsigned int start, size_t len)
```

```json
{
  "name": "vm_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581030480,
      "name": "vm_munmap",
      "external": true,
      "loc": "mm/mmap.c:2736",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "mm/mmap.c:SyS_munmap",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:ioctx_alloc",
        "fs/binfmt_elf.c:elf_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581030480,
      "name": "vm_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int vm_munmap(long unsigned int start, size_t len)
```

```json
{
  "name": "vm_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581165152,
      "name": "vm_munmap",
      "external": true,
      "loc": "mm/mmap.c:2791",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "mm/mmap.c:__ia32_sys_munmap",
        "mm/mmap.c:__x64_sys_munmap",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:ioctx_alloc",
        "fs/binfmt_elf.c:elf_map",
        "fs/compat_binfmt_elf.c:elf_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581165152,
      "name": "vm_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int vm_munmap(long unsigned int start, size_t len)
```

```json
{
  "name": "vm_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581245312,
      "name": "vm_munmap",
      "external": true,
      "loc": "mm/mmap.c:2863",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:ioctx_alloc",
        "fs/binfmt_elf.c:elf_map",
        "fs/compat_binfmt_elf.c:elf_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581245312,
      "name": "vm_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int vm_munmap(long unsigned int start, size_t len)
```

```json
{
  "name": "vm_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581319808,
      "name": "vm_munmap",
      "external": true,
      "loc": "mm/mmap.c:2869",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:ioctx_alloc",
        "fs/binfmt_elf.c:elf_map",
        "fs/compat_binfmt_elf.c:elf_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581319808,
      "name": "vm_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int vm_munmap(long unsigned int start, size_t len)
```

```json
{
  "name": "vm_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581379040,
      "name": "vm_munmap",
      "external": true,
      "loc": "mm/mmap.c:2874",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:ioctx_alloc",
        "fs/binfmt_elf.c:elf_map",
        "fs/compat_binfmt_elf.c:elf_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581379040,
      "name": "vm_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int vm_munmap(long unsigned int start, size_t len)
```

```json
{
  "name": "vm_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581580304,
      "name": "vm_munmap",
      "external": true,
      "loc": "mm/mmap.c:2884",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:ioctx_alloc",
        "fs/binfmt_elf.c:elf_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581580304,
      "name": "vm_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int vm_munmap(long unsigned int start, size_t len)
```

```json
{
  "name": "vm_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581626048,
      "name": "vm_munmap",
      "external": true,
      "loc": "mm/mmap.c:2947",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:ioctx_alloc",
        "fs/binfmt_elf.c:elf_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581626048,
      "name": "vm_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int vm_munmap(long unsigned int start, size_t len)
```

```json
{
  "name": "vm_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581645264,
      "name": "vm_munmap",
      "external": true,
      "loc": "mm/mmap.c:2951",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:ioctx_alloc",
        "fs/binfmt_elf.c:elf_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581645264,
      "name": "vm_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int vm_munmap(long unsigned int start, size_t len)
```

```json
{
  "name": "vm_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581913280,
      "name": "vm_munmap",
      "external": true,
      "loc": "mm/mmap.c:2923",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:ioctx_alloc",
        "fs/binfmt_elf.c:elf_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581913280,
      "name": "vm_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int vm_munmap(long unsigned int start, size_t len)
```

```json
{
  "name": "vm_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582319696,
      "name": "vm_munmap",
      "external": true,
      "loc": "mm/mmap.c:2924",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:ioctx_alloc",
        "fs/binfmt_elf.c:elf_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582319696,
      "name": "vm_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int vm_munmap(long unsigned int start, size_t len)
```

```json
{
  "name": "vm_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582817536,
      "name": "vm_munmap",
      "external": true,
      "loc": "mm/mmap.c:2795",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:ioctx_alloc",
        "fs/binfmt_elf.c:elf_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582817536,
      "name": "vm_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int vm_munmap(long unsigned int start, size_t len)
```

```json
{
  "name": "vm_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583031696,
      "name": "vm_munmap",
      "external": true,
      "loc": "mm/mmap.c:2909",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:ioctx_alloc",
        "fs/binfmt_elf.c:elf_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583031696,
      "name": "vm_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int vm_munmap(long unsigned int start, size_t len)
```

```json
{
  "name": "vm_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583212912,
      "name": "vm_munmap",
      "external": true,
      "loc": "mm/mmap.c:2998",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/shstk.c:shstk_free",
        "arch/x86/kernel/shstk.c:alloc_shstk",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:ioctx_alloc",
        "fs/binfmt_elf.c:elf_load",
        "fs/compat_binfmt_elf.c:elf_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583212912,
      "name": "vm_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int vm_munmap(long unsigned int start, size_t len)
```

```json
{
  "name": "vm_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492785888,
      "name": "vm_munmap",
      "external": true,
      "loc": "mm/mmap.c:2874",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:ioctx_alloc",
        "fs/binfmt_elf.c:elf_map",
        "fs/compat_binfmt_elf.c:elf_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492785888,
      "name": "vm_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int vm_munmap(long unsigned int start, size_t len)
```

```json
{
  "name": "vm_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226601512,
      "name": "vm_munmap",
      "external": true,
      "loc": "mm/mmap.c:2874",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__se_sys_io_setup",
        "fs/aio.c:kill_ioctx",
        "fs/binfmt_elf.c:elf_map",
        "fs/binfmt_flat.c:load_flat_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226601512,
      "name": "vm_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int vm_munmap(long unsigned int start, size_t len)
```

```json
{
  "name": "vm_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286154496,
      "name": "vm_munmap",
      "external": true,
      "loc": "mm/mmap.c:2874",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:ioctx_alloc",
        "fs/binfmt_elf.c:elf_map",
        "fs/compat_binfmt_elf.c:elf_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286154496,
      "name": "vm_munmap",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int vm_munmap(long unsigned int start, size_t len)
```

```json
{
  "name": "vm_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272756996,
      "name": "vm_munmap",
      "external": true,
      "loc": "mm/mmap.c:2874",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__se_sys_io_setup",
        "fs/aio.c:kill_ioctx",
        "fs/binfmt_elf.c:elf_map",
        "fs/binfmt_flat.c:load_flat_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272756996,
      "name": "vm_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int vm_munmap(long unsigned int start, size_t len)
```

```json
{
  "name": "vm_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581347888,
      "name": "vm_munmap",
      "external": true,
      "loc": "mm/mmap.c:2874",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:ioctx_alloc",
        "fs/binfmt_elf.c:elf_map",
        "fs/compat_binfmt_elf.c:elf_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581347888,
      "name": "vm_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int vm_munmap(long unsigned int start, size_t len)
```

```json
{
  "name": "vm_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581291600,
      "name": "vm_munmap",
      "external": true,
      "loc": "mm/mmap.c:2874",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:ioctx_alloc",
        "fs/binfmt_elf.c:elf_map",
        "fs/compat_binfmt_elf.c:elf_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581291600,
      "name": "vm_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int vm_munmap(long unsigned int start, size_t len)
```

```json
{
  "name": "vm_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581339088,
      "name": "vm_munmap",
      "external": true,
      "loc": "mm/mmap.c:2874",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:ioctx_alloc",
        "fs/binfmt_elf.c:elf_map",
        "fs/compat_binfmt_elf.c:elf_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581339088,
      "name": "vm_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int vm_munmap(long unsigned int start, size_t len)
```

```json
{
  "name": "vm_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581403040,
      "name": "vm_munmap",
      "external": true,
      "loc": "mm/mmap.c:2874",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:ioctx_alloc",
        "fs/binfmt_elf.c:elf_map",
        "fs/compat_binfmt_elf.c:elf_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581403040,
      "name": "vm_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
