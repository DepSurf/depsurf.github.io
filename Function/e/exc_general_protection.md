# Function: <code>exc_general_protection</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void exc_general_protection(struct pt_regs * regs, long unsigned int error_code)
```

```json
{
  "name": "exc_general_protection",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591153984,
      "name": "exc_general_protection",
      "external": true,
      "loc": "arch/x86/kernel/traps.c:525",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591153984,
      "name": "exc_general_protection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 817
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
void exc_general_protection(struct pt_regs * regs, long unsigned int error_code)
```

```json
{
  "name": "exc_general_protection",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591647232,
      "name": "exc_general_protection",
      "external": true,
      "loc": "arch/x86/kernel/traps.c:530",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev-es.c:safe_stack_exc_vmm_communication"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591647232,
      "name": "exc_general_protection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 815
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
void exc_general_protection(struct pt_regs * regs, long unsigned int error_code)
```

```json
{
  "name": "exc_general_protection",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591591056,
      "name": "exc_general_protection",
      "external": true,
      "loc": "arch/x86/kernel/traps.c:531",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:vc_raw_handle_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591591056,
      "name": "exc_general_protection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 829
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
void exc_general_protection(struct pt_regs * regs, long unsigned int error_code)
```

```json
{
  "name": "exc_general_protection",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592762672,
      "name": "exc_general_protection",
      "external": true,
      "loc": "arch/x86/kernel/traps.c:562",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:vc_raw_handle_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592762672,
      "name": "exc_general_protection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1027
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
void exc_general_protection(struct pt_regs * regs, long unsigned int error_code)
```

```json
{
  "name": "exc_general_protection",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594655760,
      "name": "exc_general_protection",
      "external": true,
      "loc": "arch/x86/kernel/traps.c:719",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:vc_raw_handle_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594655760,
      "name": "exc_general_protection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 943
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
void exc_general_protection(struct pt_regs * regs, long unsigned int error_code)
```

```json
{
  "name": "exc_general_protection",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596389024,
      "name": "exc_general_protection",
      "external": true,
      "loc": "arch/x86/kernel/traps.c:728",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:vc_raw_handle_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596389024,
      "name": "exc_general_protection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1100
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
void exc_general_protection(struct pt_regs * regs, long unsigned int error_code)
```

```json
{
  "name": "exc_general_protection",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596919232,
      "name": "exc_general_protection",
      "external": true,
      "loc": "arch/x86/kernel/traps.c:729",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:vc_raw_handle_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596919232,
      "name": "exc_general_protection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1107
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
void exc_general_protection(struct pt_regs * regs, long unsigned int error_code)
```

```json
{
  "name": "exc_general_protection",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597844928,
      "name": "exc_general_protection",
      "external": true,
      "loc": "arch/x86/kernel/traps.c:643",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:vc_raw_handle_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597844928,
      "name": "exc_general_protection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1141
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void exc_general_protection(struct pt_regs * regs, long unsigned int error_code)
```
</details>
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
