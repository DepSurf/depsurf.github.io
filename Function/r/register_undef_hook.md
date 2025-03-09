# Function: <code>register_undef_hook</code>

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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void register_undef_hook(struct undef_hook * hook)
```

```json
{
  "name": "register_undef_hook",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490241656,
      "name": "register_undef_hook",
      "external": true,
      "loc": "arch/arm64/kernel/traps.c:286",
      "file": "arch/arm64/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/cpufeature.c:enable_mrs_emulation",
        "arch/arm64/kernel/armv8_deprecated.c:update_insn_emulation_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490241656,
      "name": "register_undef_hook",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void register_undef_hook(struct undef_hook * hook)
```

```json
{
  "name": "register_undef_hook",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224434976,
      "name": "register_undef_hook",
      "external": true,
      "loc": "arch/arm/kernel/traps.c:401",
      "file": "arch/arm/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/ptrace.c:ptrace_break_init",
        "arch/arm/kernel/ptrace.c:ptrace_break_init",
        "arch/arm/kernel/ptrace.c:ptrace_break_init",
        "arch/arm/kernel/kgdb.c:kgdb_arch_init",
        "arch/arm/kernel/kgdb.c:kgdb_arch_init",
        "arch/arm/kernel/swp_emulate.c:swp_emulation_init",
        "arch/arm/kernel/hw_breakpoint.c:arch_hw_breakpoint_init",
        "arch/arm/probes/uprobes/core.c:arch_uprobes_init",
        "arch/arm/probes/uprobes/core.c:arch_uprobes_init",
        "arch/arm/probes/kprobes/core.c:arch_init_kprobes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224434976,
      "name": "register_undef_hook",
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void register_undef_hook(struct undef_hook * hook)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void register_undef_hook(struct undef_hook * hook)
```
</details>
</li>
</ul>
