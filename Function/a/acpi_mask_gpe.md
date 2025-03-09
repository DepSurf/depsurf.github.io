# Function: <code>acpi_mask_gpe</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked)
```

```json
{
  "name": "acpi_mask_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584107822,
      "name": "acpi_mask_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:274",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes",
        "drivers/acpi/sysfs.c:counter_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584107822,
      "name": "acpi_mask_gpe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked)
```

```json
{
  "name": "acpi_mask_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584174754,
      "name": "acpi_mask_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:274",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes",
        "drivers/acpi/sysfs.c:counter_set",
        "drivers/acpi/sysfs.c:counter_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584174754,
      "name": "acpi_mask_gpe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked)
```

```json
{
  "name": "acpi_mask_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584479318,
      "name": "acpi_mask_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:274",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes",
        "drivers/acpi/sysfs.c:counter_set",
        "drivers/acpi/sysfs.c:counter_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584479318,
      "name": "acpi_mask_gpe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked)
```

```json
{
  "name": "acpi_mask_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584704072,
      "name": "acpi_mask_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:259",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes",
        "drivers/acpi/sysfs.c:counter_set",
        "drivers/acpi/sysfs.c:counter_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584704072,
      "name": "acpi_mask_gpe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked)
```

```json
{
  "name": "acpi_mask_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584804172,
      "name": "acpi_mask_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:259",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes",
        "drivers/acpi/sysfs.c:counter_set",
        "drivers/acpi/sysfs.c:counter_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584804172,
      "name": "acpi_mask_gpe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked)
```

```json
{
  "name": "acpi_mask_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585007017,
      "name": "acpi_mask_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:259",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes",
        "drivers/acpi/sysfs.c:counter_set",
        "drivers/acpi/sysfs.c:counter_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585007017,
      "name": "acpi_mask_gpe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked)
```

```json
{
  "name": "acpi_mask_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585143020,
      "name": "acpi_mask_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:259",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes",
        "drivers/acpi/sysfs.c:counter_set",
        "drivers/acpi/sysfs.c:counter_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585143020,
      "name": "acpi_mask_gpe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked)
```

```json
{
  "name": "acpi_mask_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585848113,
      "name": "acpi_mask_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:259",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes",
        "drivers/acpi/sysfs.c:counter_set",
        "drivers/acpi/sysfs.c:counter_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585848113,
      "name": "acpi_mask_gpe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked)
```

```json
{
  "name": "acpi_mask_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585969264,
      "name": "acpi_mask_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:259",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes",
        "drivers/acpi/sysfs.c:counter_set",
        "drivers/acpi/sysfs.c:counter_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585969264,
      "name": "acpi_mask_gpe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked)
```

```json
{
  "name": "acpi_mask_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585846332,
      "name": "acpi_mask_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:259",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes",
        "drivers/acpi/sysfs.c:counter_set",
        "drivers/acpi/sysfs.c:counter_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585846332,
      "name": "acpi_mask_gpe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked)
```

```json
{
  "name": "acpi_mask_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586333179,
      "name": "acpi_mask_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:259",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes",
        "drivers/acpi/sysfs.c:counter_set",
        "drivers/acpi/sysfs.c:counter_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586333179,
      "name": "acpi_mask_gpe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked)
```

```json
{
  "name": "acpi_mask_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587579833,
      "name": "acpi_mask_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:259",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes",
        "drivers/acpi/sysfs.c:counter_set",
        "drivers/acpi/sysfs.c:counter_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587579833,
      "name": "acpi_mask_gpe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked)
```

```json
{
  "name": "acpi_mask_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588868368,
      "name": "acpi_mask_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:259",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes",
        "drivers/acpi/sysfs.c:counter_set",
        "drivers/acpi/sysfs.c:counter_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588868368,
      "name": "acpi_mask_gpe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked)
```

```json
{
  "name": "acpi_mask_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589157808,
      "name": "acpi_mask_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:259",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes",
        "drivers/acpi/sysfs.c:counter_set",
        "drivers/acpi/sysfs.c:counter_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589157808,
      "name": "acpi_mask_gpe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked)
```

```json
{
  "name": "acpi_mask_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589464128,
      "name": "acpi_mask_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:259",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes",
        "drivers/acpi/sysfs.c:counter_set",
        "drivers/acpi/sysfs.c:counter_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589464128,
      "name": "acpi_mask_gpe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_mask_gpe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_mask_gpe",
      "external": false,
      "loc": "include/acpi/acpixf.h:725",
      "file": "drivers/acpi/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
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
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked)
```

```json
{
  "name": "acpi_mask_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585042738,
      "name": "acpi_mask_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:259",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes",
        "drivers/acpi/sysfs.c:counter_set",
        "drivers/acpi/sysfs.c:counter_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585042738,
      "name": "acpi_mask_gpe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked)
```

```json
{
  "name": "acpi_mask_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584958298,
      "name": "acpi_mask_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:259",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes",
        "drivers/acpi/sysfs.c:counter_set",
        "drivers/acpi/sysfs.c:counter_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584958298,
      "name": "acpi_mask_gpe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked)
```

```json
{
  "name": "acpi_mask_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585094604,
      "name": "acpi_mask_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:259",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes",
        "drivers/acpi/sysfs.c:counter_set",
        "drivers/acpi/sysfs.c:counter_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585094604,
      "name": "acpi_mask_gpe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked)
```

```json
{
  "name": "acpi_mask_gpe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585200764,
      "name": "acpi_mask_gpe",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:259",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes",
        "drivers/acpi/sysfs.c:counter_set",
        "drivers/acpi/sysfs.c:counter_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585200764,
      "name": "acpi_mask_gpe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked)
```
</details>
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
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_mask_gpe(acpi_handle gpe_device, u32 gpe_number, u8 is_masked)
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
