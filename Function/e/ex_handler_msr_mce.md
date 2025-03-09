# Function: <code>ex_handler_msr_mce</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void ex_handler_msr_mce(struct pt_regs * regs, bool wrmsr)
```

```json
{
  "name": "ex_handler_msr_mce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593831688,
      "name": "ex_handler_msr_mce",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:322",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/extable.c:fixup_exception",
        "arch/x86/mm/extable.c:fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593831688,
      "name": "ex_handler_msr_mce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void ex_handler_msr_mce(struct pt_regs * regs, bool wrmsr)
```

```json
{
  "name": "ex_handler_msr_mce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579339328,
      "name": "ex_handler_msr_mce",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:322",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/extable.c:fixup_exception",
        "arch/x86/mm/extable.c:fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579339328,
      "name": "ex_handler_msr_mce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void ex_handler_msr_mce(struct pt_regs * regs, bool wrmsr)
```

```json
{
  "name": "ex_handler_msr_mce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579348208,
      "name": "ex_handler_msr_mce",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:316",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/extable.c:fixup_exception",
        "arch/x86/mm/extable.c:fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579348208,
      "name": "ex_handler_msr_mce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void ex_handler_msr_mce(struct pt_regs * regs, bool wrmsr)
```

```json
{
  "name": "ex_handler_msr_mce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579378064,
      "name": "ex_handler_msr_mce",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:347",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/extable.c:fixup_exception",
        "arch/x86/mm/extable.c:fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579378064,
      "name": "ex_handler_msr_mce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void ex_handler_msr_mce(struct pt_regs * regs, bool wrmsr)
```
</details>
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
