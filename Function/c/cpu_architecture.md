# Function: <code>cpu_architecture</code>

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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
int cpu_architecture()
```

```json
{
  "name": "cpu_architecture",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224426400,
      "name": "cpu_architecture",
      "external": true,
      "loc": "arch/arm/kernel/setup.c:275",
      "file": "arch/arm/kernel/setup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/setup.c:c_show",
        "arch/arm/kernel/setup.c:setup_processor",
        "arch/arm/kernel/setup.c:setup_processor",
        "arch/arm/kernel/setup.c:setup_processor"
      ],
      "caller_func": [
        "arch/arm/vfp/vfpmodule.c:vfp_init",
        "arch/arm/kernel/setup.c:c_show",
        "arch/arm/kernel/setup.c:setup_processor",
        "arch/arm/kernel/thumbee.c:thumbee_init",
        "arch/arm/kernel/swp_emulate.c:swp_emulation_init",
        "arch/arm/mm/fault.c:exceptions_init",
        "arch/arm/mm/fault.c:exceptions_init",
        "arch/arm/mm/idmap.c:init_static_idmap",
        "arch/arm/mm/mmu.c:__create_mapping",
        "arch/arm/mm/mmu.c:build_mem_type_table",
        "arch/arm/mm/mmu.c:early_cachepolicy",
        "arch/arm/mm/alignment.c:alignment_init",
        "arch/arm/mm/alignment.c:alignment_init",
        "arch/arm/mm/alignment.c:do_alignment",
        "arch/arm/mm/alignment.c:alignment_proc_show",
        "arch/arm/net/bpf_jit_32.c:bpf_int_jit_compile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224425792,
      "name": "cpu_architecture.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 3224426676,
      "name": "cpu_architecture",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int cpu_architecture()
```
</details>
</li>
</ul>
