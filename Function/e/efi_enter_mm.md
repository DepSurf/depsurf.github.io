# Function: <code>efi_enter_mm</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void efi_enter_mm()
```

```json
{
  "name": "efi_enter_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579466984,
      "name": "efi_enter_mm",
      "external": true,
      "loc": "arch/x86/platform/efi/efi_64.c:462",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable"
      ],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/uv/bios_uv.c:__uv_bios_call",
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
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579470880,
      "name": "efi_enter_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void efi_enter_mm()
```

```json
{
  "name": "efi_enter_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579532472,
      "name": "efi_enter_mm",
      "external": true,
      "loc": "arch/x86/platform/efi/efi_64.c:462",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable"
      ],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/uv/bios_uv.c:__uv_bios_call",
        "drivers/acpi/prmt.c:acpi_platformrt_space_handler",
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
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579536368,
      "name": "efi_enter_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void efi_enter_mm()
```

```json
{
  "name": "efi_enter_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579619710,
      "name": "efi_enter_mm",
      "external": true,
      "loc": "arch/x86/platform/efi/efi_64.c:463",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable"
      ],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/uv/bios_uv.c:__uv_bios_call",
        "drivers/acpi/prmt.c:acpi_platformrt_space_handler",
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
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579624160,
      "name": "efi_enter_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void efi_enter_mm()
```

```json
{
  "name": "efi_enter_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627751005,
      "name": "efi_enter_mm",
      "external": true,
      "loc": "arch/x86/platform/efi/efi_64.c:471",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map"
      ],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:__uv_bios_call",
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
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579736384,
      "name": "efi_enter_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void efi_enter_mm()
```

```json
{
  "name": "efi_enter_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619510541,
      "name": "efi_enter_mm",
      "external": true,
      "loc": "arch/x86/platform/efi/efi_64.c:477",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map"
      ],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:__uv_bios_call",
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
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579782864,
      "name": "efi_enter_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "efi_enter_mm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621807373,
      "name": "efi_enter_mm",
      "external": false,
      "loc": "arch/x86/platform/efi/efi_64.c:477",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:arch_efi_call_virt_setup"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void efi_enter_mm()
```
</details>
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void efi_enter_mm()
```
</details>
</li>
</ul>
