# Function: <code>do_trap_error</code>

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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void do_trap_error(struct pt_regs * regs, int signo, int code, long unsigned int addr, const char * str)
```

```json
{
  "name": "do_trap_error",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271347110,
      "name": "do_trap_error",
      "external": false,
      "loc": "arch/riscv/kernel/traps.c:75",
      "file": "arch/riscv/kernel/traps.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/kernel/traps.c:do_trap_ecall_m",
        "arch/riscv/kernel/traps.c:do_trap_ecall_s",
        "arch/riscv/kernel/traps.c:do_trap_ecall_u",
        "arch/riscv/kernel/traps.c:do_trap_store_fault",
        "arch/riscv/kernel/traps.c:do_trap_store_misaligned",
        "arch/riscv/kernel/traps.c:do_trap_load_fault",
        "arch/riscv/kernel/traps.c:do_trap_load_misaligned",
        "arch/riscv/kernel/traps.c:do_trap_insn_illegal",
        "arch/riscv/kernel/traps.c:do_trap_insn_fault",
        "arch/riscv/kernel/traps.c:do_trap_insn_misaligned",
        "arch/riscv/kernel/traps.c:do_trap_unknown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271347110,
      "name": "do_trap_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void do_trap_error(struct pt_regs * regs, int signo, int code, long unsigned int addr, const char * str)
```
</details>
</li>
</ul>
