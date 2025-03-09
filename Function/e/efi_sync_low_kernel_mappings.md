# Function: <code>efi_sync_low_kernel_mappings</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void efi_sync_low_kernel_mappings()
```

```json
{
  "name": "efi_sync_low_kernel_mappings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579340848,
      "name": "efi_sync_low_kernel_mappings",
      "external": true,
      "loc": "arch/x86/platform/efi/efi_64.c:129",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi.c:efi_enter_virtual_mode",
        "arch/x86/platform/efi/efi.c:efi_enter_virtual_mode",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
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
      "addr": 18446744071579340848,
      "name": "efi_sync_low_kernel_mappings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void efi_sync_low_kernel_mappings()
```

```json
{
  "name": "efi_sync_low_kernel_mappings",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579346843,
      "name": "efi_sync_low_kernel_mappings",
      "external": true,
      "loc": "arch/x86/platform/efi/efi_64.c:164",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map"
      ],
      "caller_func": [
        "arch/x86/platform/efi/efi.c:efi_enter_virtual_mode",
        "arch/x86/platform/efi/efi.c:efi_enter_virtual_mode",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
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
      "addr": 18446744071579346144,
      "name": "efi_sync_low_kernel_mappings.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    },
    {
      "addr": 18446744071579350048,
      "name": "efi_sync_low_kernel_mappings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void efi_sync_low_kernel_mappings()
```

```json
{
  "name": "efi_sync_low_kernel_mappings",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579362806,
      "name": "efi_sync_low_kernel_mappings",
      "external": true,
      "loc": "arch/x86/platform/efi/efi_64.c:165",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map"
      ],
      "caller_func": [
        "arch/x86/platform/efi/efi.c:efi_enter_virtual_mode",
        "arch/x86/platform/efi/efi.c:efi_enter_virtual_mode",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579362000,
      "name": "efi_sync_low_kernel_mappings.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    },
    {
      "addr": 18446744071579367856,
      "name": "efi_sync_low_kernel_mappings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void efi_sync_low_kernel_mappings()
```

```json
{
  "name": "efi_sync_low_kernel_mappings",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579356166,
      "name": "efi_sync_low_kernel_mappings",
      "external": true,
      "loc": "arch/x86/platform/efi/efi_64.c:234",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map"
      ],
      "caller_func": [
        "arch/x86/platform/efi/efi.c:efi_enter_virtual_mode",
        "arch/x86/platform/efi/efi.c:efi_enter_virtual_mode",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579354752,
      "name": "efi_sync_low_kernel_mappings.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
    },
    {
      "addr": 18446744071579360336,
      "name": "efi_sync_low_kernel_mappings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void efi_sync_low_kernel_mappings()
```

```json
{
  "name": "efi_sync_low_kernel_mappings",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579384550,
      "name": "efi_sync_low_kernel_mappings",
      "external": true,
      "loc": "arch/x86/platform/efi/efi_64.c:241",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map"
      ],
      "caller_func": [
        "arch/x86/platform/efi/efi.c:efi_enter_virtual_mode",
        "arch/x86/platform/efi/efi.c:efi_enter_virtual_mode",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579381104,
      "name": "efi_sync_low_kernel_mappings.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
    },
    {
      "addr": 18446744071579387040,
      "name": "efi_sync_low_kernel_mappings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void efi_sync_low_kernel_mappings()
```

```json
{
  "name": "efi_sync_low_kernel_mappings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579395040,
      "name": "efi_sync_low_kernel_mappings",
      "external": true,
      "loc": "arch/x86/platform/efi/efi_64.c:244",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi.c:efi_enter_virtual_mode",
        "arch/x86/platform/efi/efi.c:efi_enter_virtual_mode",
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
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579395040,
      "name": "efi_sync_low_kernel_mappings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 401
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void efi_sync_low_kernel_mappings()
```

```json
{
  "name": "efi_sync_low_kernel_mappings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579423344,
      "name": "efi_sync_low_kernel_mappings",
      "external": true,
      "loc": "arch/x86/platform/efi/efi_64.c:244",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi.c:efi_enter_virtual_mode",
        "arch/x86/platform/efi/efi.c:efi_enter_virtual_mode",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
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
      "addr": 18446744071579423344,
      "name": "efi_sync_low_kernel_mappings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 401
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void efi_sync_low_kernel_mappings()
```

```json
{
  "name": "efi_sync_low_kernel_mappings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579439392,
      "name": "efi_sync_low_kernel_mappings",
      "external": true,
      "loc": "arch/x86/platform/efi/efi_64.c:247",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi.c:efi_enter_virtual_mode",
        "arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
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
      "addr": 18446744071579439392,
      "name": "efi_sync_low_kernel_mappings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 399
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void efi_sync_low_kernel_mappings()
```

```json
{
  "name": "efi_sync_low_kernel_mappings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579442784,
      "name": "efi_sync_low_kernel_mappings",
      "external": true,
      "loc": "arch/x86/platform/efi/efi_64.c:247",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi.c:efi_enter_virtual_mode",
        "arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
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
      "addr": 18446744071579442784,
      "name": "efi_sync_low_kernel_mappings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 399
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void efi_sync_low_kernel_mappings()
```

```json
{
  "name": "efi_sync_low_kernel_mappings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579466144,
      "name": "efi_sync_low_kernel_mappings",
      "external": true,
      "loc": "arch/x86/platform/efi/efi_64.c:110",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode",
        "arch/x86/platform/efi/efi.c:kexec_enter_virtual_mode",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
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
      "addr": 18446744071579466144,
      "name": "efi_sync_low_kernel_mappings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 677
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
void efi_sync_low_kernel_mappings()
```

```json
{
  "name": "efi_sync_low_kernel_mappings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579462560,
      "name": "efi_sync_low_kernel_mappings",
      "external": true,
      "loc": "arch/x86/platform/efi/efi_64.c:110",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode",
        "arch/x86/platform/efi/efi.c:kexec_enter_virtual_mode",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
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
      "addr": 18446744071579462560,
      "name": "efi_sync_low_kernel_mappings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 612
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
void efi_sync_low_kernel_mappings()
```

```json
{
  "name": "efi_sync_low_kernel_mappings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579464896,
      "name": "efi_sync_low_kernel_mappings",
      "external": true,
      "loc": "arch/x86/platform/efi/efi_64.c:107",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi.c:efi_enter_virtual_mode",
        "arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
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
      "addr": 18446744071579464896,
      "name": "efi_sync_low_kernel_mappings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 443
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void efi_sync_low_kernel_mappings()
```

```json
{
  "name": "efi_sync_low_kernel_mappings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_sync_low_kernel_mappings",
      "external": true,
      "loc": "arch/x86/platform/efi/efi_64.c:107",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi.c:efi_enter_virtual_mode",
        "arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
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
      "addr": 18446744071592093174,
      "name": "efi_sync_low_kernel_mappings.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
    },
    {
      "addr": 18446744071579530304,
      "name": "efi_sync_low_kernel_mappings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 515
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void efi_sync_low_kernel_mappings()
```

```json
{
  "name": "efi_sync_low_kernel_mappings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_sync_low_kernel_mappings",
      "external": true,
      "loc": "arch/x86/platform/efi/efi_64.c:107",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode",
        "arch/x86/platform/efi/efi.c:kexec_enter_virtual_mode",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
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
      "addr": 18446744071593860680,
      "name": "efi_sync_low_kernel_mappings.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 365
    },
    {
      "addr": 18446744071579617216,
      "name": "efi_sync_low_kernel_mappings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 523
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void efi_sync_low_kernel_mappings()
```

```json
{
  "name": "efi_sync_low_kernel_mappings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_sync_low_kernel_mappings",
      "external": true,
      "loc": "arch/x86/platform/efi/efi_64.c:107",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode",
        "arch/x86/platform/efi/efi.c:kexec_enter_virtual_mode",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
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
      "addr": 18446744071595971816,
      "name": "efi_sync_low_kernel_mappings.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
    },
    {
      "addr": 18446744071579729264,
      "name": "efi_sync_low_kernel_mappings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 538
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void efi_sync_low_kernel_mappings()
```

```json
{
  "name": "efi_sync_low_kernel_mappings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_sync_low_kernel_mappings",
      "external": true,
      "loc": "arch/x86/platform/efi/efi_64.c:107",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode",
        "arch/x86/platform/efi/efi.c:kexec_enter_virtual_mode",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
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
      "addr": 18446744071596489500,
      "name": "efi_sync_low_kernel_mappings.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
    },
    {
      "addr": 18446744071579775744,
      "name": "efi_sync_low_kernel_mappings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 539
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void efi_sync_low_kernel_mappings()
```

```json
{
  "name": "efi_sync_low_kernel_mappings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_sync_low_kernel_mappings",
      "external": true,
      "loc": "arch/x86/platform/efi/efi_64.c:107",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode",
        "arch/x86/platform/efi/efi.c:kexec_enter_virtual_mode",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "arch/x86/platform/efi/efi_64.c:arch_efi_call_virt_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597386122,
      "name": "efi_sync_low_kernel_mappings.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
    },
    {
      "addr": 18446744071579810640,
      "name": "efi_sync_low_kernel_mappings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 539
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void efi_sync_low_kernel_mappings()
```

```json
{
  "name": "efi_sync_low_kernel_mappings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579438624,
      "name": "efi_sync_low_kernel_mappings",
      "external": true,
      "loc": "arch/x86/platform/efi/efi_64.c:247",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi.c:efi_enter_virtual_mode",
        "arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
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
      "addr": 18446744071579438624,
      "name": "efi_sync_low_kernel_mappings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 399
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void efi_sync_low_kernel_mappings()
```

```json
{
  "name": "efi_sync_low_kernel_mappings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579367680,
      "name": "efi_sync_low_kernel_mappings",
      "external": true,
      "loc": "arch/x86/platform/efi/efi_64.c:247",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi.c:efi_enter_virtual_mode",
        "arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
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
      "addr": 18446744071579367680,
      "name": "efi_sync_low_kernel_mappings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 347
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void efi_sync_low_kernel_mappings()
```

```json
{
  "name": "efi_sync_low_kernel_mappings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579438544,
      "name": "efi_sync_low_kernel_mappings",
      "external": true,
      "loc": "arch/x86/platform/efi/efi_64.c:247",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi.c:efi_enter_virtual_mode",
        "arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
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
      "addr": 18446744071579438544,
      "name": "efi_sync_low_kernel_mappings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 399
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void efi_sync_low_kernel_mappings()
```

```json
{
  "name": "efi_sync_low_kernel_mappings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579447744,
      "name": "efi_sync_low_kernel_mappings",
      "external": true,
      "loc": "arch/x86/platform/efi/efi_64.c:247",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi.c:efi_enter_virtual_mode",
        "arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
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
      "addr": 18446744071579447744,
      "name": "efi_sync_low_kernel_mappings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 399
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void efi_sync_low_kernel_mappings()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void efi_sync_low_kernel_mappings()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void efi_sync_low_kernel_mappings()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void efi_sync_low_kernel_mappings()
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
