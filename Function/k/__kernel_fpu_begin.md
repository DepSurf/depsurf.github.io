# Function: <code>__kernel_fpu_begin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __kernel_fpu_begin()
```

```json
{
  "name": "__kernel_fpu_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579081952,
      "name": "__kernel_fpu_begin",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:108",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:kernel_fpu_begin",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable_nonblocking",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579081952,
      "name": "__kernel_fpu_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __kernel_fpu_begin()
```

```json
{
  "name": "__kernel_fpu_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579078352,
      "name": "__kernel_fpu_begin",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:112",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:kernel_fpu_begin",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579078352,
      "name": "__kernel_fpu_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void __kernel_fpu_begin()
```

```json
{
  "name": "__kernel_fpu_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579076256,
      "name": "__kernel_fpu_begin",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:96",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:kernel_fpu_begin",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579076256,
      "name": "__kernel_fpu_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void __kernel_fpu_begin()
```

```json
{
  "name": "__kernel_fpu_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579068416,
      "name": "__kernel_fpu_begin",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:95",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:kernel_fpu_begin",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579068416,
      "name": "__kernel_fpu_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void __kernel_fpu_begin()
```

```json
{
  "name": "__kernel_fpu_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579077584,
      "name": "__kernel_fpu_begin",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:95",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:kernel_fpu_begin",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579077584,
      "name": "__kernel_fpu_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void __kernel_fpu_begin()
```

```json
{
  "name": "__kernel_fpu_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579083648,
      "name": "__kernel_fpu_begin",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:96",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:kernel_fpu_begin",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_query_variable_info",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579083648,
      "name": "__kernel_fpu_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__kernel_fpu_begin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579089434,
      "name": "__kernel_fpu_begin",
      "external": false,
      "loc": "arch/x86/kernel/fpu/core.c:96",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:kernel_fpu_begin"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void __kernel_fpu_begin()
```
</details>
</li>
</ul>
