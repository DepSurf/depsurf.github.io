# Function: <code>arm64_skip_faulting_instruction</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void arm64_skip_faulting_instruction(struct pt_regs * regs, long unsigned int size)
```

```json
{
  "name": "arm64_skip_faulting_instruction",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490237720,
      "name": "arm64_skip_faulting_instruction",
      "external": true,
      "loc": "arch/arm64/kernel/traps.c:271",
      "file": "arch/arm64/kernel/traps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/traps.c:wfi_handler",
        "arch/arm64/kernel/traps.c:cntfrq_read_handler",
        "arch/arm64/kernel/traps.c:cntvct_read_handler",
        "arch/arm64/kernel/traps.c:ctr_read_handler",
        "arch/arm64/kernel/traps.c:user_cache_maint_handler"
      ],
      "caller_func": [
        "arch/arm64/kernel/traps.c:wfi_handler",
        "arch/arm64/kernel/traps.c:cntfrq_read_handler",
        "arch/arm64/kernel/traps.c:cntvct_read_handler",
        "arch/arm64/kernel/traps.c:ctr_read_handler",
        "arch/arm64/kernel/traps.c:user_cache_maint_handler",
        "arch/arm64/kernel/cpufeature.c:do_emulate_mrs",
        "arch/arm64/kernel/cpufeature.c:ssbs_emulation_handler",
        "arch/arm64/kernel/armv8_deprecated.c:t16_setend_handler",
        "arch/arm64/kernel/armv8_deprecated.c:a32_setend_handler",
        "arch/arm64/kernel/armv8_deprecated.c:cp15barrier_handler",
        "arch/arm64/kernel/armv8_deprecated.c:swp_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490237664,
      "name": "arm64_skip_faulting_instruction.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446603336490241576,
      "name": "arm64_skip_faulting_instruction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void arm64_skip_faulting_instruction(struct pt_regs * regs, long unsigned int size)
```
</details>
</li>
</ul>
