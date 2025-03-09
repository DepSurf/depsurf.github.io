# Function: <code>ppc_breakpoint_available</code>

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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
bool ppc_breakpoint_available()
```

```json
{
  "name": "ppc_breakpoint_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055282300276,
      "name": "ppc_breakpoint_available",
      "external": true,
      "loc": "arch/powerpc/kernel/process.c:799",
      "file": "arch/powerpc/kernel/process.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/process.c:do_break"
      ],
      "caller_func": [
        "arch/powerpc/kernel/ptrace.c:arch_ptrace",
        "arch/powerpc/kernel/process.c:do_break",
        "arch/powerpc/kernel/hw_breakpoint.c:hw_breakpoint_handler",
        "arch/powerpc/kernel/hw_breakpoint.c:hw_breakpoint_arch_parse",
        "arch/powerpc/kernel/hw_breakpoint.c:arch_uninstall_hw_breakpoint",
        "arch/powerpc/kernel/machine_kexec_64.c:kexec_prepare_cpus_wait",
        "arch/powerpc/kernel/machine_kexec_64.c:kexec_smp_down",
        "arch/powerpc/xmon/xmon.c:clear_all_bpt",
        "arch/powerpc/xmon/xmon.c:bpt_cmds",
        "arch/powerpc/xmon/xmon.c:xmon_core",
        "arch/powerpc/xmon/xmon.c:xmon_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282296096,
      "name": "ppc_breakpoint_available.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 13835058055282296144,
      "name": "ppc_breakpoint_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
bool ppc_breakpoint_available()
```
</details>
</li>
</ul>
