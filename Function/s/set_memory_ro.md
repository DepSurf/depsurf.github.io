# Function: <code>set_memory_ro</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int set_memory_ro(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579300656,
      "name": "set_memory_ro",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1703",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:set_pages_ro"
      ],
      "caller_func": [
        "arch/x86/realmode/init.c:set_real_mode_permissions",
        "arch/x86/mm/init_64.c:set_kernel_text_ro",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "kernel/bpf/core.c:bpf_prog_select_runtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579300656,
      "name": "set_memory_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int set_memory_ro(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579300246,
      "name": "set_memory_ro",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1711",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:set_pages_ro"
      ],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "arch/x86/mm/init_64.c:set_kernel_text_ro",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "kernel/power/snapshot.c:snapshot_write_finalize",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/bpf/core.c:bpf_prog_select_runtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579299984,
      "name": "set_memory_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int set_memory_ro(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579315718,
      "name": "set_memory_ro",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1711",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:set_pages_ro"
      ],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "arch/x86/mm/init_64.c:set_kernel_text_ro",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "kernel/power/snapshot.c:snapshot_write_finalize",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/bpf/core.c:bpf_prog_select_runtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579315456,
      "name": "set_memory_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int set_memory_ro(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579313014,
      "name": "set_memory_ro",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1757",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:set_pages_ro"
      ],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/kprobes/core.c:arch_copy_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "arch/x86/mm/init_64.c:set_kernel_text_ro",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "kernel/power/snapshot.c:snapshot_write_finalize",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/bpf/core.c:bpf_prog_select_runtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579312816,
      "name": "set_memory_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int set_memory_ro(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579335654,
      "name": "set_memory_ro",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1757",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:set_pages_ro"
      ],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/kprobes/core.c:alloc_insn_page",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "arch/x86/mm/init_64.c:set_kernel_text_ro",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "kernel/power/snapshot.c:snapshot_write_finalize",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/bpf/core.c:bpf_prog_select_runtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579335456,
      "name": "set_memory_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int set_memory_ro(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579346677,
      "name": "set_memory_ro",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1787",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:set_pages_ro"
      ],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/kprobes/core.c:alloc_insn_page",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "arch/x86/mm/init_64.c:set_kernel_text_ro",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "kernel/power/snapshot.c:snapshot_write_finalize",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/bpf/core.c:bpf_prog_select_runtime",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579346272,
      "name": "set_memory_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int set_memory_ro(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579373221,
      "name": "set_memory_ro",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1980",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:set_pages_ro"
      ],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/kprobes/core.c:alloc_insn_page",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "arch/x86/mm/init_64.c:set_kernel_text_ro",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "kernel/power/snapshot.c:snapshot_write_finalize",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/bpf/core.c:bpf_prog_select_runtime",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579372816,
      "name": "set_memory_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int set_memory_ro(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579388293,
      "name": "set_memory_ro",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1991",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:set_pages_ro"
      ],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/kprobes/core.c:alloc_insn_page",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "arch/x86/mm/init_64.c:set_kernel_text_ro",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "kernel/power/snapshot.c:snapshot_write_finalize",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/bpf/core.c:bpf_prog_select_runtime",
        "kernel/bpf/verifier.c:jit_subprogs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579387888,
      "name": "set_memory_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int set_memory_ro(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579391621,
      "name": "set_memory_ro",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1897",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:set_pages_ro"
      ],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/kprobes/core.c:alloc_insn_page",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "arch/x86/mm/init_64.c:set_kernel_text_ro",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "kernel/power/snapshot.c:snapshot_write_finalize",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/bpf/core.c:bpf_prog_select_runtime",
        "kernel/bpf/verifier.c:jit_subprogs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579391216,
      "name": "set_memory_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int set_memory_ro(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579431845,
      "name": "set_memory_ro",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:1933",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:set_pages_ro"
      ],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/ftrace.c:set_ftrace_ops_ro",
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/kprobes/core.c:alloc_insn_page",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "kernel/power/snapshot.c:snapshot_write_finalize",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579431440,
      "name": "set_memory_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int set_memory_ro(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579431317,
      "name": "set_memory_ro",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:1933",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:set_pages_ro"
      ],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/ftrace.c:set_ftrace_ops_ro",
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/kprobes/core.c:alloc_insn_page",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "kernel/power/snapshot.c:snapshot_write_finalize",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579430912,
      "name": "set_memory_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int set_memory_ro(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579434277,
      "name": "set_memory_ro",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:1941",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:set_pages_ro"
      ],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/ftrace.c:set_ftrace_ops_ro",
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/kprobes/core.c:alloc_insn_page",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "kernel/power/snapshot.c:snapshot_write_finalize",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579433872,
      "name": "set_memory_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int set_memory_ro(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579498501,
      "name": "set_memory_ro",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:1941",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:set_pages_ro"
      ],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/ftrace.c:set_ftrace_ops_ro",
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/kprobes/core.c:alloc_insn_page",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "kernel/power/snapshot.c:snapshot_write_finalize",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579498096,
      "name": "set_memory_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int set_memory_ro(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579579891,
      "name": "set_memory_ro",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:1978",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:set_pages_ro"
      ],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/ftrace.c:set_ftrace_ops_ro",
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/kprobes/core.c:alloc_insn_page",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "kernel/power/snapshot.c:snapshot_write_finalize",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/module/strict_rwx.c:module_enable_ro",
        "kernel/module/strict_rwx.c:module_enable_ro",
        "kernel/module/strict_rwx.c:module_enable_ro",
        "kernel/module/strict_rwx.c:module_enable_ro",
        "kernel/module/strict_rwx.c:module_enable_ro",
        "kernel/bpf/core.c:bpf_prog_pack_alloc",
        "kernel/bpf/core.c:alloc_new_pack",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579579376,
      "name": "set_memory_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int set_memory_ro(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579689363,
      "name": "set_memory_ro",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:2074",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:set_pages_ro"
      ],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/ftrace.c:set_ftrace_ops_ro",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "kernel/power/snapshot.c:snapshot_write_finalize",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/module/strict_rwx.c:module_enable_ro",
        "kernel/module/strict_rwx.c:module_enable_ro",
        "kernel/module/strict_rwx.c:module_enable_ro",
        "kernel/module/strict_rwx.c:module_enable_ro",
        "kernel/module/strict_rwx.c:module_enable_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579688624,
      "name": "set_memory_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int set_memory_ro(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579703125,
      "name": "set_memory_ro",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:2075",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:set_pages_ro"
      ],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/ftrace.c:set_ftrace_ops_ro",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "kernel/power/snapshot.c:snapshot_write_finalize",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/module/strict_rwx.c:module_enable_ro",
        "kernel/module/strict_rwx.c:module_enable_ro",
        "kernel/module/strict_rwx.c:module_enable_ro",
        "kernel/module/strict_rwx.c:module_enable_ro",
        "kernel/module/strict_rwx.c:module_enable_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579702384,
      "name": "set_memory_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int set_memory_ro(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579737733,
      "name": "set_memory_ro",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:2074",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:set_pages_ro"
      ],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/ftrace.c:set_ftrace_ops_ro",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "kernel/power/snapshot.c:snapshot_write_finalize",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/module/strict_rwx.c:module_enable_ro",
        "kernel/module/strict_rwx.c:module_enable_ro",
        "kernel/module/strict_rwx.c:module_enable_ro",
        "kernel/module/strict_rwx.c:module_enable_ro",
        "kernel/module/strict_rwx.c:module_enable_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579736912,
      "name": "set_memory_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int set_memory_ro(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490353528,
      "name": "set_memory_ro",
      "external": true,
      "loc": "arch/arm64/mm/pageattr.c:111",
      "file": "arch/arm64/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/probes/kprobes.c:alloc_insn_page",
        "arch/arm64/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "kernel/bpf/core.c:bpf_prog_select_runtime",
        "kernel/bpf/verifier.c:jit_subprogs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490353528,
      "name": "set_memory_ro",
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
int set_memory_ro(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224501652,
      "name": "set_memory_ro",
      "external": true,
      "loc": "arch/arm/mm/pageattr.c:64",
      "file": "arch/arm/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/net/bpf_jit_32.c:bpf_int_jit_compile",
        "arch/arm/plat-omap/sram.c:omap_map_sram",
        "arch/arm/plat-omap/sram.c:omap_sram_push",
        "kernel/power/snapshot.c:snapshot_write_finalize",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/bpf/core.c:bpf_prog_select_runtime",
        "kernel/bpf/verifier.c:jit_subprogs",
        "drivers/misc/sram-exec.c:sram_exec_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224501652,
      "name": "set_memory_ro",
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "set_memory_ro",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "set_memory_ro",
      "external": false,
      "loc": "include/linux/set_memory.h:11",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_memory_ro",
      "external": false,
      "loc": "include/linux/set_memory.h:11",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "set_memory_ro",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "set_memory_ro",
      "external": false,
      "loc": "include/linux/set_memory.h:11",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_memory_ro",
      "external": false,
      "loc": "include/linux/set_memory.h:11",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
int set_memory_ro(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579387525,
      "name": "set_memory_ro",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1897",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:set_pages_ro"
      ],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/kprobes/core.c:alloc_insn_page",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "arch/x86/mm/init_64.c:set_kernel_text_ro",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "kernel/power/snapshot.c:snapshot_write_finalize",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/bpf/core.c:bpf_prog_select_runtime",
        "kernel/bpf/verifier.c:jit_subprogs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579387120,
      "name": "set_memory_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int set_memory_ro(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579316885,
      "name": "set_memory_ro",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1897",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:set_pages_ro"
      ],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/kprobes/core.c:alloc_insn_page",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "arch/x86/mm/init_64.c:set_kernel_text_ro",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "kernel/power/snapshot.c:snapshot_write_finalize",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/bpf/core.c:bpf_prog_select_runtime",
        "kernel/bpf/verifier.c:jit_subprogs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579316480,
      "name": "set_memory_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int set_memory_ro(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579387445,
      "name": "set_memory_ro",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1897",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:set_pages_ro"
      ],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/kprobes/core.c:alloc_insn_page",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "arch/x86/mm/init_64.c:set_kernel_text_ro",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "kernel/power/snapshot.c:snapshot_write_finalize",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/bpf/core.c:bpf_prog_select_runtime",
        "kernel/bpf/verifier.c:jit_subprogs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579387040,
      "name": "set_memory_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int set_memory_ro(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579395957,
      "name": "set_memory_ro",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1897",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:set_pages_ro"
      ],
      "caller_func": [
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/kprobes/core.c:alloc_insn_page",
        "arch/x86/mm/init_64.c:mark_rodata_ro",
        "arch/x86/mm/init_64.c:set_kernel_text_ro",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "kernel/power/snapshot.c:snapshot_write_finalize",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/bpf/core.c:bpf_prog_select_runtime",
        "kernel/bpf/verifier.c:jit_subprogs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579395552,
      "name": "set_memory_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int set_memory_ro(long unsigned int addr, int numpages)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int set_memory_ro(long unsigned int addr, int numpages)
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
