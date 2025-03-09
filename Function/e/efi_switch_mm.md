# Function: <code>efi_switch_mm</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void efi_switch_mm(struct mm_struct * mm)
```

```json
{
  "name": "efi_switch_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579395456,
      "name": "efi_switch_mm",
      "external": true,
      "loc": "arch/x86/platform/efi/efi_64.c:627",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_thunk_query_variable_info",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_query_variable_info",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579395456,
      "name": "efi_switch_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void efi_switch_mm(struct mm_struct * mm)
```

```json
{
  "name": "efi_switch_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579425363,
      "name": "efi_switch_mm",
      "external": true,
      "loc": "arch/x86/platform/efi/efi_64.c:627",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog"
      ],
      "caller_func": [
        "arch/x86/platform/efi/quirks.c:efi_recover_from_page_fault",
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
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579430560,
      "name": "efi_switch_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void efi_switch_mm(struct mm_struct * mm)
```

```json
{
  "name": "efi_switch_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579441408,
      "name": "efi_switch_mm",
      "external": true,
      "loc": "arch/x86/platform/efi/efi_64.c:630",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog"
      ],
      "caller_func": [
        "arch/x86/platform/efi/quirks.c:efi_recover_from_page_fault",
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
      "addr": 18446744071579446528,
      "name": "efi_switch_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void efi_switch_mm(struct mm_struct * mm)
```

```json
{
  "name": "efi_switch_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579444896,
      "name": "efi_switch_mm",
      "external": true,
      "loc": "arch/x86/platform/efi/efi_64.c:628",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog"
      ],
      "caller_func": [
        "arch/x86/platform/efi/quirks.c:efi_recover_from_page_fault",
        "arch/x86/platform/uv/bios_uv.c:__uv_bios_call",
        "arch/x86/platform/uv/bios_uv.c:__uv_bios_call",
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
      "addr": 18446744071579450736,
      "name": "efi_switch_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void efi_switch_mm(struct mm_struct * mm)
```

```json
{
  "name": "efi_switch_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579468755,
      "name": "efi_switch_mm",
      "external": true,
      "loc": "arch/x86/platform/efi/efi_64.c:493",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable"
      ],
      "caller_func": [
        "arch/x86/platform/efi/quirks.c:efi_recover_from_page_fault",
        "arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
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
      "addr": 18446744071579472672,
      "name": "efi_switch_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void efi_switch_mm(struct mm_struct * mm)
```

```json
{
  "name": "efi_switch_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579464824,
      "name": "efi_switch_mm",
      "external": true,
      "loc": "arch/x86/platform/efi/efi_64.c:465",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable"
      ],
      "caller_func": [
        "arch/x86/platform/efi/quirks.c:efi_recover_from_page_fault",
        "arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/uv/bios_uv.c:__uv_bios_call",
        "arch/x86/platform/uv/bios_uv.c:__uv_bios_call",
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
      "addr": 18446744071579468816,
      "name": "efi_switch_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void efi_switch_mm(struct mm_struct * mm)
```

```json
{
  "name": "efi_switch_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579440736,
      "name": "efi_switch_mm",
      "external": true,
      "loc": "arch/x86/platform/efi/efi_64.c:628",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog"
      ],
      "caller_func": [
        "arch/x86/platform/efi/quirks.c:efi_recover_from_page_fault",
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
      "addr": 18446744071579446576,
      "name": "efi_switch_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void efi_switch_mm(struct mm_struct * mm)
```

```json
{
  "name": "efi_switch_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579369760,
      "name": "efi_switch_mm",
      "external": true,
      "loc": "arch/x86/platform/efi/efi_64.c:628",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog"
      ],
      "caller_func": [
        "arch/x86/platform/efi/quirks.c:efi_recover_from_page_fault",
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
      "addr": 18446744071579375568,
      "name": "efi_switch_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void efi_switch_mm(struct mm_struct * mm)
```

```json
{
  "name": "efi_switch_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579440656,
      "name": "efi_switch_mm",
      "external": true,
      "loc": "arch/x86/platform/efi/efi_64.c:628",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog"
      ],
      "caller_func": [
        "arch/x86/platform/efi/quirks.c:efi_recover_from_page_fault",
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
      "addr": 18446744071579446496,
      "name": "efi_switch_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void efi_switch_mm(struct mm_struct * mm)
```

```json
{
  "name": "efi_switch_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579449895,
      "name": "efi_switch_mm",
      "external": true,
      "loc": "arch/x86/platform/efi/efi_64.c:628",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog"
      ],
      "caller_func": [
        "arch/x86/platform/efi/quirks.c:efi_recover_from_page_fault",
        "arch/x86/platform/uv/bios_uv.c:__uv_bios_call",
        "arch/x86/platform/uv/bios_uv.c:__uv_bios_call",
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
      "addr": 18446744071579456048,
      "name": "efi_switch_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void efi_switch_mm(struct mm_struct * mm)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void efi_switch_mm(struct mm_struct * mm)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void efi_switch_mm(struct mm_struct * mm)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void efi_switch_mm(struct mm_struct * mm)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void efi_switch_mm(struct mm_struct * mm)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void efi_switch_mm(struct mm_struct * mm)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
