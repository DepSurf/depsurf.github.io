# Function: <code>get_cpu_entry_area</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cpu_entry_area * get_cpu_entry_area(int cpu)
```

```json
{
  "name": "get_cpu_entry_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602715474,
      "name": "get_cpu_entry_area",
      "external": true,
      "loc": "arch/x86/mm/cpu_entry_area.c:18",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas"
      ],
      "caller_func": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/kernel/dumpstack.c:in_entry_stack",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:load_fixmap_gdt",
        "arch/x86/kernel/paravirt.c:native_load_tr_desc",
        "arch/x86/power/cpu.c:restore_processor_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579348896,
      "name": "get_cpu_entry_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
struct cpu_entry_area * get_cpu_entry_area(int cpu)
```

```json
{
  "name": "get_cpu_entry_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602888211,
      "name": "get_cpu_entry_area",
      "external": true,
      "loc": "arch/x86/mm/cpu_entry_area.c:18",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas"
      ],
      "caller_func": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/kernel/dumpstack.c:in_entry_stack",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:load_fixmap_gdt",
        "arch/x86/kernel/paravirt.c:native_load_tr_desc",
        "arch/x86/power/cpu.c:restore_processor_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579360560,
      "name": "get_cpu_entry_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
struct cpu_entry_area * get_cpu_entry_area(int cpu)
```

```json
{
  "name": "get_cpu_entry_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604685610,
      "name": "get_cpu_entry_area",
      "external": true,
      "loc": "arch/x86/mm/cpu_entry_area.c:20",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas"
      ],
      "caller_func": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/kernel/dumpstack.c:in_entry_stack",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:load_fixmap_gdt",
        "arch/x86/kernel/paravirt.c:native_load_tr_desc",
        "arch/x86/power/cpu.c:restore_processor_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579388080,
      "name": "get_cpu_entry_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
struct cpu_entry_area * get_cpu_entry_area(int cpu)
```

```json
{
  "name": "get_cpu_entry_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604785124,
      "name": "get_cpu_entry_area",
      "external": true,
      "loc": "arch/x86/mm/cpu_entry_area.c:20",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas"
      ],
      "caller_func": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/kernel/dumpstack.c:in_entry_stack",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:load_fixmap_gdt",
        "arch/x86/kernel/paravirt.c:native_load_tr_desc",
        "arch/x86/power/cpu.c:fix_processor_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579403584,
      "name": "get_cpu_entry_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
struct cpu_entry_area * get_cpu_entry_area(int cpu)
```

```json
{
  "name": "get_cpu_entry_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604810862,
      "name": "get_cpu_entry_area",
      "external": true,
      "loc": "arch/x86/mm/cpu_entry_area.c:20",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas"
      ],
      "caller_func": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/kernel/dumpstack.c:in_entry_stack",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:load_fixmap_gdt",
        "arch/x86/kernel/paravirt.c:native_load_tr_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579406768,
      "name": "get_cpu_entry_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
struct cpu_entry_area * get_cpu_entry_area(int cpu)
```

```json
{
  "name": "get_cpu_entry_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609149222,
      "name": "get_cpu_entry_area",
      "external": true,
      "loc": "arch/x86/mm/cpu_entry_area.c:24",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks"
      ],
      "caller_func": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:alloc_bts_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/events/intel/ds.c:alloc_pebs_buffer",
        "arch/x86/kernel/dumpstack.c:in_entry_stack",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:load_fixmap_gdt",
        "arch/x86/kernel/paravirt.c:native_load_tr_desc",
        "arch/x86/power/cpu.c:fix_processor_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579417360,
      "name": "get_cpu_entry_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
struct cpu_entry_area * get_cpu_entry_area(int cpu)
```

```json
{
  "name": "get_cpu_entry_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591658944,
      "name": "get_cpu_entry_area",
      "external": true,
      "loc": "arch/x86/mm/cpu_entry_area.c:25",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:alloc_bts_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/events/intel/ds.c:alloc_pebs_buffer",
        "arch/x86/kernel/dumpstack.c:in_entry_stack",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init_exception_handling",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:load_fixmap_gdt",
        "arch/x86/kernel/paravirt.c:native_load_tr_desc",
        "arch/x86/kernel/sev-es.c:setup_vc_stacks",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/power/cpu.c:fix_processor_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591658944,
      "name": "get_cpu_entry_area",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct cpu_entry_area * get_cpu_entry_area(int cpu)
```

```json
{
  "name": "get_cpu_entry_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591602640,
      "name": "get_cpu_entry_area",
      "external": true,
      "loc": "arch/x86/mm/cpu_entry_area.c:25",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/events/intel/ds.c:alloc_pebs_buffer",
        "arch/x86/kernel/dumpstack.c:in_entry_stack",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init_exception_handling",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:load_fixmap_gdt",
        "arch/x86/kernel/paravirt.c:native_load_tr_desc",
        "arch/x86/kernel/sev.c:sev_es_init_vc_handling",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area",
        "arch/x86/power/cpu.c:fix_processor_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591602640,
      "name": "get_cpu_entry_area",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct cpu_entry_area * get_cpu_entry_area(int cpu)
```

```json
{
  "name": "get_cpu_entry_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592775600,
      "name": "get_cpu_entry_area",
      "external": true,
      "loc": "arch/x86/mm/cpu_entry_area.c:25",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/events/intel/ds.c:alloc_pebs_buffer",
        "arch/x86/kernel/dumpstack.c:in_entry_stack",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init_exception_handling",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:load_fixmap_gdt",
        "arch/x86/kernel/paravirt.c:native_load_tr_desc",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/power/cpu.c:fix_processor_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592775600,
      "name": "get_cpu_entry_area",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct cpu_entry_area * get_cpu_entry_area(int cpu)
```

```json
{
  "name": "get_cpu_entry_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594673024,
      "name": "get_cpu_entry_area",
      "external": true,
      "loc": "arch/x86/mm/cpu_entry_area.c:25",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/events/intel/ds.c:alloc_pebs_buffer",
        "arch/x86/kernel/dumpstack.c:in_entry_stack",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init_exception_handling",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:load_fixmap_gdt",
        "arch/x86/kernel/paravirt.c:native_load_tr_desc",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/power/cpu.c:fix_processor_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594673024,
      "name": "get_cpu_entry_area",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct cpu_entry_area * get_cpu_entry_area(int cpu)
```

```json
{
  "name": "get_cpu_entry_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596407680,
      "name": "get_cpu_entry_area",
      "external": true,
      "loc": "arch/x86/mm/cpu_entry_area.c:63",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/events/intel/ds.c:alloc_pebs_buffer",
        "arch/x86/kernel/dumpstack.c:in_entry_stack",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init_exception_handling",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:load_fixmap_gdt",
        "arch/x86/kernel/paravirt.c:native_load_tr_desc",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/power/cpu.c:fix_processor_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596407680,
      "name": "get_cpu_entry_area",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct cpu_entry_area * get_cpu_entry_area(int cpu)
```

```json
{
  "name": "get_cpu_entry_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596939392,
      "name": "get_cpu_entry_area",
      "external": true,
      "loc": "arch/x86/mm/cpu_entry_area.c:70",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/events/intel/ds.c:alloc_pebs_buffer",
        "arch/x86/kernel/dumpstack.c:in_entry_stack",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init_exception_handling",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:load_fixmap_gdt",
        "arch/x86/kernel/paravirt.c:native_load_tr_desc",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/power/cpu.c:fix_processor_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596939392,
      "name": "get_cpu_entry_area",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct cpu_entry_area * get_cpu_entry_area(int cpu)
```

```json
{
  "name": "get_cpu_entry_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597864960,
      "name": "get_cpu_entry_area",
      "external": true,
      "loc": "arch/x86/mm/cpu_entry_area.c:70",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/events/intel/ds.c:alloc_pebs_buffer",
        "arch/x86/kernel/dumpstack.c:in_entry_stack",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init_exception_handling",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/paravirt.c:native_load_tr_desc",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/power/cpu.c:fix_processor_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597864960,
      "name": "get_cpu_entry_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct cpu_entry_area * get_cpu_entry_area(int cpu)
```

```json
{
  "name": "get_cpu_entry_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604724804,
      "name": "get_cpu_entry_area",
      "external": true,
      "loc": "arch/x86/mm/cpu_entry_area.c:20",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas"
      ],
      "caller_func": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/kernel/dumpstack.c:in_entry_stack",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:load_fixmap_gdt",
        "arch/x86/kernel/paravirt.c:native_load_tr_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579402608,
      "name": "get_cpu_entry_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
struct cpu_entry_area * get_cpu_entry_area(int cpu)
```

```json
{
  "name": "get_cpu_entry_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604692534,
      "name": "get_cpu_entry_area",
      "external": true,
      "loc": "arch/x86/mm/cpu_entry_area.c:20",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas"
      ],
      "caller_func": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "arch/x86/kernel/dumpstack.c:in_entry_stack",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579332048,
      "name": "get_cpu_entry_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
struct cpu_entry_area * get_cpu_entry_area(int cpu)
```

```json
{
  "name": "get_cpu_entry_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604802371,
      "name": "get_cpu_entry_area",
      "external": true,
      "loc": "arch/x86/mm/cpu_entry_area.c:20",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas"
      ],
      "caller_func": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/kernel/dumpstack.c:in_entry_stack",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:load_fixmap_gdt",
        "arch/x86/kernel/paravirt.c:native_load_tr_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579402528,
      "name": "get_cpu_entry_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
struct cpu_entry_area * get_cpu_entry_area(int cpu)
```

```json
{
  "name": "get_cpu_entry_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604814990,
      "name": "get_cpu_entry_area",
      "external": true,
      "loc": "arch/x86/mm/cpu_entry_area.c:20",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas"
      ],
      "caller_func": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/kernel/dumpstack.c:in_entry_stack",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:load_fixmap_gdt",
        "arch/x86/kernel/paravirt.c:native_load_tr_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579411392,
      "name": "get_cpu_entry_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct cpu_entry_area * get_cpu_entry_area(int cpu)
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct cpu_entry_area * get_cpu_entry_area(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct cpu_entry_area * get_cpu_entry_area(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct cpu_entry_area * get_cpu_entry_area(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct cpu_entry_area * get_cpu_entry_area(int cpu)
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
