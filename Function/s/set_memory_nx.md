# Function: <code>set_memory_nx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int set_memory_nx(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_nx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579297472,
      "name": "set_memory_nx",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1694",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:set_real_mode_permissions",
        "arch/x86/mm/init.c:free_init_pages",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "arch/x86/mm/pageattr.c:set_pages_nx",
        "arch/x86/platform/efi/efi.c:efi_set_executable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579297472,
      "name": "set_memory_nx",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int set_memory_nx(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_nx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579296928,
      "name": "set_memory_nx",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1702",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/mm/init.c:free_init_pages",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "arch/x86/mm/pageattr.c:set_pages_nx",
        "arch/x86/platform/efi/efi.c:efi_set_executable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579296928,
      "name": "set_memory_nx",
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
int set_memory_nx(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_nx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579312464,
      "name": "set_memory_nx",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1702",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/mm/init.c:free_init_pages",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "arch/x86/mm/pageattr.c:set_pages_nx",
        "arch/x86/platform/efi/efi.c:efi_set_executable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579312464,
      "name": "set_memory_nx",
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
int set_memory_nx(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_nx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579309984,
      "name": "set_memory_nx",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1748",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/kprobes/core.c:free_insn_page",
        "arch/x86/mm/init.c:free_init_pages",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "arch/x86/mm/pageattr.c:set_pages_nx",
        "arch/x86/platform/efi/efi.c:efi_set_executable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579309984,
      "name": "set_memory_nx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int set_memory_nx(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_nx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579332160,
      "name": "set_memory_nx",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1748",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/kprobes/core.c:free_insn_page",
        "arch/x86/mm/init.c:free_init_pages",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "arch/x86/mm/pageattr.c:set_pages_nx",
        "arch/x86/platform/efi/efi.c:efi_set_executable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579332160,
      "name": "set_memory_nx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int set_memory_nx(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_nx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579343024,
      "name": "set_memory_nx",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1778",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/kprobes/core.c:free_insn_page",
        "arch/x86/mm/init.c:free_init_pages",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "arch/x86/mm/pageattr.c:set_pages_nx",
        "arch/x86/platform/efi/efi.c:efi_set_executable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579343024,
      "name": "set_memory_nx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int set_memory_nx(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_nx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579369664,
      "name": "set_memory_nx",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1971",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/kprobes/core.c:free_insn_page",
        "arch/x86/mm/init.c:free_init_pages",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "arch/x86/mm/pageattr.c:set_pages_nx",
        "arch/x86/platform/efi/efi.c:efi_set_executable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579369664,
      "name": "set_memory_nx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int set_memory_nx(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_nx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579384672,
      "name": "set_memory_nx",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1982",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/mm/init.c:free_init_pages",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "arch/x86/mm/pageattr.c:set_pages_nx",
        "arch/x86/platform/efi/efi.c:efi_set_executable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579384672,
      "name": "set_memory_nx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int set_memory_nx(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_nx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579391152,
      "name": "set_memory_nx",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1889",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/mm/init.c:free_init_pages",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "arch/x86/platform/efi/efi.c:efi_set_executable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579391152,
      "name": "set_memory_nx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int set_memory_nx(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_nx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579431376,
      "name": "set_memory_nx",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:1925",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/mm/init.c:free_init_pages",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "arch/x86/platform/efi/efi.c:efi_set_executable",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579431376,
      "name": "set_memory_nx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int set_memory_nx(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_nx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579430848,
      "name": "set_memory_nx",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:1925",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/mm/init.c:free_init_pages",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579430848,
      "name": "set_memory_nx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int set_memory_nx(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_nx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579433808,
      "name": "set_memory_nx",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:1933",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/mm/init.c:free_init_pages",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579433808,
      "name": "set_memory_nx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int set_memory_nx(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_nx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579498032,
      "name": "set_memory_nx",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:1933",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/mm/init.c:free_init_pages",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579498032,
      "name": "set_memory_nx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int set_memory_nx(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_nx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579579264,
      "name": "set_memory_nx",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:1970",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/mm/init.c:free_init_pages",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "kernel/module/strict_rwx.c:module_enable_nx",
        "kernel/module/strict_rwx.c:module_enable_nx",
        "kernel/module/strict_rwx.c:module_enable_nx",
        "kernel/module/strict_rwx.c:module_enable_nx",
        "kernel/module/strict_rwx.c:module_enable_nx",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579579264,
      "name": "set_memory_nx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int set_memory_nx(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_nx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579688496,
      "name": "set_memory_nx",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:2066",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/mm/init.c:free_init_pages",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "kernel/module/strict_rwx.c:module_enable_nx",
        "kernel/module/strict_rwx.c:module_enable_nx",
        "kernel/module/strict_rwx.c:module_enable_nx",
        "kernel/module/strict_rwx.c:module_enable_nx",
        "kernel/module/strict_rwx.c:module_enable_nx",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579688496,
      "name": "set_memory_nx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int set_memory_nx(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_nx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579702256,
      "name": "set_memory_nx",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:2067",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/mm/init.c:free_initrd_mem",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "kernel/module/strict_rwx.c:module_enable_nx",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579702256,
      "name": "set_memory_nx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int set_memory_nx(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_nx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579736784,
      "name": "set_memory_nx",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:2066",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/mm/init.c:free_initrd_mem",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "kernel/module/strict_rwx.c:module_enable_nx",
        "kernel/bpf/trampoline.c:arch_unprotect_bpf_trampoline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579736784,
      "name": "set_memory_nx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int set_memory_nx(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_nx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490353656,
      "name": "set_memory_nx",
      "external": true,
      "loc": "arch/arm64/mm/pageattr.c:125",
      "file": "arch/arm64/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490353656,
      "name": "set_memory_nx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int set_memory_nx(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_nx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224501724,
      "name": "set_memory_nx",
      "external": true,
      "loc": "arch/arm/mm/pageattr.c:78",
      "file": "arch/arm/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/misc/sram-exec.c:sram_exec_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224501724,
      "name": "set_memory_nx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int set_memory_nx(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_nx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579387056,
      "name": "set_memory_nx",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1889",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/mm/init.c:free_init_pages",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "arch/x86/platform/efi/efi.c:efi_set_executable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579387056,
      "name": "set_memory_nx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int set_memory_nx(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_nx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579316416,
      "name": "set_memory_nx",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1889",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/mm/init.c:free_init_pages",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "arch/x86/platform/efi/efi.c:efi_set_executable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579316416,
      "name": "set_memory_nx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int set_memory_nx(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_nx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579386976,
      "name": "set_memory_nx",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1889",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/mm/init.c:free_init_pages",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "arch/x86/platform/efi/efi.c:efi_set_executable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579386976,
      "name": "set_memory_nx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int set_memory_nx(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_nx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579395488,
      "name": "set_memory_nx",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1889",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/mm/init.c:free_init_pages",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "arch/x86/platform/efi/efi.c:efi_set_executable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579395488,
      "name": "set_memory_nx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int set_memory_nx(long unsigned int addr, int numpages)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int set_memory_nx(long unsigned int addr, int numpages)
```
</details>
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
