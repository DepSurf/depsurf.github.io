# Function: <code>set_memory_rox</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int set_memory_rox(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_rox",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579688704,
      "name": "set_memory_rox",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:2079",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/kprobes/core.c:alloc_insn_page",
        "kernel/bpf/core.c:bpf_prog_pack_alloc",
        "kernel/bpf/core.c:alloc_new_pack",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579688704,
      "name": "set_memory_rox",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int set_memory_rox(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_rox",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579702464,
      "name": "set_memory_rox",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:2080",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/kprobes/core.c:alloc_insn_page",
        "kernel/bpf/core.c:bpf_prog_pack_alloc",
        "kernel/bpf/core.c:alloc_new_pack",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579702464,
      "name": "set_memory_rox",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int set_memory_rox(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_rox",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579736992,
      "name": "set_memory_rox",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:2079",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/kprobes/core.c:alloc_insn_page",
        "kernel/bpf/core.c:bpf_prog_pack_alloc",
        "kernel/bpf/core.c:alloc_new_pack",
        "kernel/bpf/trampoline.c:arch_protect_bpf_trampoline",
        "kernel/bpf/trampoline.c:arch_protect_bpf_trampoline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579736992,
      "name": "set_memory_rox",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int set_memory_rox(long unsigned int addr, int numpages)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
