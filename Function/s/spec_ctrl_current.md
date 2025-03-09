# Function: <code>spec_ctrl_current</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 spec_ctrl_current()
```

```json
{
  "name": "spec_ctrl_current",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579239237,
      "name": "spec_ctrl_current",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:82",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:update_stibp_msr",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl"
      ],
      "caller_func": [
        "arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/uv/bios_uv.c:__uv_bios_call",
        "arch/x86/platform/uv/bios_uv.c:__uv_bios_call",
        "drivers/idle/intel_idle.c:intel_idle_ibrs",
        "drivers/idle/intel_idle.c:intel_idle_ibrs",
        "drivers/acpi/prmt.c:acpi_platformrt_space_handler",
        "drivers/acpi/prmt.c:acpi_platformrt_space_handler",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579235232,
      "name": "spec_ctrl_current",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 spec_ctrl_current()
```

```json
{
  "name": "spec_ctrl_current",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579297349,
      "name": "spec_ctrl_current",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:89",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:update_stibp_msr"
      ],
      "caller_func": [
        "arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/uv/bios_uv.c:__uv_bios_call",
        "arch/x86/platform/uv/bios_uv.c:__uv_bios_call",
        "drivers/idle/intel_idle.c:intel_idle_ibrs",
        "drivers/idle/intel_idle.c:intel_idle_ibrs",
        "drivers/acpi/prmt.c:acpi_platformrt_space_handler",
        "drivers/acpi/prmt.c:acpi_platformrt_space_handler",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579294528,
      "name": "spec_ctrl_current",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
u64 spec_ctrl_current()
```

```json
{
  "name": "spec_ctrl_current",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596926528,
      "name": "spec_ctrl_current",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:94",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:update_stibp_msr",
        "arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/uv/bios_uv.c:__uv_bios_call",
        "arch/x86/platform/uv/bios_uv.c:__uv_bios_call",
        "drivers/idle/intel_idle.c:intel_idle_ibrs",
        "drivers/idle/intel_idle.c:intel_idle_ibrs",
        "drivers/acpi/prmt.c:acpi_platformrt_space_handler",
        "drivers/acpi/prmt.c:acpi_platformrt_space_handler",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596926528,
      "name": "spec_ctrl_current",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
u64 spec_ctrl_current()
```

```json
{
  "name": "spec_ctrl_current",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597852208,
      "name": "spec_ctrl_current",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:94",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:update_stibp_msr",
        "arch/x86/platform/efi/efi_64.c:arch_efi_call_virt_teardown",
        "arch/x86/platform/efi/efi_64.c:arch_efi_call_virt_setup",
        "drivers/idle/intel_idle.c:intel_idle_ibrs",
        "drivers/idle/intel_idle.c:intel_idle_ibrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597852208,
      "name": "spec_ctrl_current",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
u64 spec_ctrl_current()
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
