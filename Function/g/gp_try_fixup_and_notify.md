# Function: <code>gp_try_fixup_and_notify</code>

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
bool gp_try_fixup_and_notify(struct pt_regs * regs, int trapnr, long unsigned int error_code, const char * str)
```

```json
{
  "name": "gp_try_fixup_and_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579116992,
      "name": "gp_try_fixup_and_notify",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:690",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_virtualization_exception",
        "arch/x86/kernel/traps.c:exc_general_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579116992,
      "name": "gp_try_fixup_and_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
bool gp_try_fixup_and_notify(struct pt_regs * regs, int trapnr, long unsigned int error_code, const char * str)
```

```json
{
  "name": "gp_try_fixup_and_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579156288,
      "name": "gp_try_fixup_and_notify",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:699",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_virtualization_exception",
        "arch/x86/kernel/traps.c:exc_general_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579156288,
      "name": "gp_try_fixup_and_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
bool gp_try_fixup_and_notify(struct pt_regs * regs, int trapnr, long unsigned int error_code, const char * str, long unsigned int address)
```

```json
{
  "name": "gp_try_fixup_and_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579158448,
      "name": "gp_try_fixup_and_notify",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:699",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_virtualization_exception",
        "arch/x86/kernel/traps.c:exc_general_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579158448,
      "name": "gp_try_fixup_and_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
bool gp_try_fixup_and_notify(struct pt_regs * regs, int trapnr, long unsigned int error_code, const char * str, long unsigned int address)
```

```json
{
  "name": "gp_try_fixup_and_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579187760,
      "name": "gp_try_fixup_and_notify",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:613",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_virtualization_exception",
        "arch/x86/kernel/traps.c:exc_general_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579187760,
      "name": "gp_try_fixup_and_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
bool gp_try_fixup_and_notify(struct pt_regs * regs, int trapnr, long unsigned int error_code, const char * str)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int address</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
