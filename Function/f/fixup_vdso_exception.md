# Function: <code>fixup_vdso_exception</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool fixup_vdso_exception(struct pt_regs * regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr)
```

```json
{
  "name": "fixup_vdso_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578865328,
      "name": "fixup_vdso_exception",
      "external": true,
      "loc": "arch/x86/entry/vdso/extable.c:12",
      "file": "arch/x86/entry/vdso/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/mm/fault.c:mm_fault_error",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578865328,
      "name": "fixup_vdso_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
bool fixup_vdso_exception(struct pt_regs * regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr)
```

```json
{
  "name": "fixup_vdso_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578865232,
      "name": "fixup_vdso_exception",
      "external": true,
      "loc": "arch/x86/entry/vdso/extable.c:12",
      "file": "arch/x86/entry/vdso/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578865232,
      "name": "fixup_vdso_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
bool fixup_vdso_exception(struct pt_regs * regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr)
```

```json
{
  "name": "fixup_vdso_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578866784,
      "name": "fixup_vdso_exception",
      "external": true,
      "loc": "arch/x86/entry/vdso/extable.c:12",
      "file": "arch/x86/entry/vdso/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578866784,
      "name": "fixup_vdso_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
bool fixup_vdso_exception(struct pt_regs * regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr)
```

```json
{
  "name": "fixup_vdso_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578862976,
      "name": "fixup_vdso_exception",
      "external": true,
      "loc": "arch/x86/entry/vdso/extable.c:12",
      "file": "arch/x86/entry/vdso/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578862976,
      "name": "fixup_vdso_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
bool fixup_vdso_exception(struct pt_regs * regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr)
```

```json
{
  "name": "fixup_vdso_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578865424,
      "name": "fixup_vdso_exception",
      "external": true,
      "loc": "arch/x86/entry/vdso/extable.c:12",
      "file": "arch/x86/entry/vdso/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578865424,
      "name": "fixup_vdso_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
bool fixup_vdso_exception(struct pt_regs * regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr)
```

```json
{
  "name": "fixup_vdso_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578863376,
      "name": "fixup_vdso_exception",
      "external": true,
      "loc": "arch/x86/entry/vdso/extable.c:12",
      "file": "arch/x86/entry/vdso/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578863376,
      "name": "fixup_vdso_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
bool fixup_vdso_exception(struct pt_regs * regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr)
```

```json
{
  "name": "fixup_vdso_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578873888,
      "name": "fixup_vdso_exception",
      "external": true,
      "loc": "arch/x86/entry/vdso/extable.c:12",
      "file": "arch/x86/entry/vdso/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578873888,
      "name": "fixup_vdso_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
bool fixup_vdso_exception(struct pt_regs * regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr)
```
</details>
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
